<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CT Flooring Services | Premium Flooring & Remodeling in Redondo Beach, CA</title>
<meta name="description" content="CT Flooring Services - 4.8★ rated flooring contractor in Redondo Beach, CA. Hardwood, laminate, floor repair, remodeling & drywall. Call (424) 500-7345 for a free estimate.">
<style>
  :root{
    --wood-dark:#3d2817;
    --wood:#6b4423;
    --wood-light:#a47148;
    --amber:#e8a33d;
    --amber-light:#f5c477;
    --cream:#faf6f0;
    --ink:#221a12;
    --card:#fffdf9;
  }
  *{margin:0;padding:0;box-sizing:border-box}
  html{scroll-behavior:smooth}
  body{font-family:'Segoe UI',system-ui,-apple-system,sans-serif;background:var(--cream);color:var(--ink);overflow-x:hidden}
  h1,h2,h3{line-height:1.15}
  img{max-width:100%}

  /* ===== NAV ===== */
  nav{position:fixed;top:0;left:0;right:0;z-index:100;display:flex;justify-content:space-between;align-items:center;
      padding:14px 6vw;background:rgba(34,26,18,.85);backdrop-filter:blur(12px);transform-style:preserve-3d}
  .logo{color:var(--cream);font-weight:800;font-size:1.3rem;letter-spacing:.5px;display:flex;align-items:center;gap:10px}
  .logo-badge{width:38px;height:38px;border-radius:10px;background:linear-gradient(135deg,var(--amber),var(--wood-light));
      display:grid;place-items:center;font-size:1.1rem;transform:rotate(-6deg);box-shadow:0 4px 14px rgba(232,163,61,.5)}
  .nav-links{display:flex;gap:28px;align-items:center}
  .nav-links a{color:#e9ddcb;text-decoration:none;font-size:.95rem;font-weight:600;transition:.25s}
  .nav-links a:hover{color:var(--amber-light)}
  .nav-call{background:var(--amber);color:var(--ink)!important;padding:10px 20px;border-radius:30px;font-weight:700!important}
  .nav-call:hover{background:var(--amber-light);transform:translateY(-2px)}
  @media(max-width:820px){.nav-links a:not(.nav-call){display:none}}

  /* ===== HERO with 3D ===== */
  .hero{min-height:100vh;display:flex;align-items:center;justify-content:center;text-align:center;position:relative;
      background:radial-gradient(ellipse at 30% 20%,#7a5230 0%,var(--wood-dark) 55%,#241608 100%);
      perspective:1200px;overflow:hidden;padding:120px 6vw 80px}
  .hero::before{content:"";position:absolute;inset:0;
      background:repeating-linear-gradient(90deg,rgba(255,255,255,.03) 0 2px,transparent 2px 120px);pointer-events:none}
  .hero-inner{position:relative;z-index:2;max-width:860px;transform-style:preserve-3d;animation:heroFloat 7s ease-in-out infinite}
  @keyframes heroFloat{0%,100%{transform:translateY(0) rotateX(0)}50%{transform:translateY(-10px) rotateX(1.5deg)}}
  .hero-tag{display:inline-block;background:rgba(232,163,61,.15);border:1px solid rgba(232,163,61,.5);color:var(--amber-light);
      padding:8px 20px;border-radius:30px;font-size:.85rem;font-weight:700;letter-spacing:2px;text-transform:uppercase;margin-bottom:24px}
  .hero h1{color:var(--cream);font-size:clamp(2.2rem,6vw,4rem);font-weight:800;margin-bottom:18px;
      text-shadow:0 10px 40px rgba(0,0,0,.5)}
  .hero h1 span{color:var(--amber)}
  .hero p{color:#d9c8b2;font-size:clamp(1rem,2.2vw,1.25rem);max-width:620px;margin:0 auto 30px}
  .stars-big{color:var(--amber);font-size:1.4rem;letter-spacing:4px;margin-bottom:6px}
  .rating-note{color:var(--amber-light);font-weight:700;margin-bottom:32px}
  .btn-row{display:flex;gap:18px;justify-content:center;flex-wrap:wrap}
  .btn{display:inline-block;padding:16px 36px;border-radius:40px;font-weight:800;text-decoration:none;font-size:1.05rem;transition:.3s}
  .btn-amber{background:linear-gradient(135deg,var(--amber),#d18a1f);color:var(--ink);box-shadow:0 10px 30px rgba(232,163,61,.45)}
  .btn-amber:hover{transform:translateY(-4px) scale(1.03);box-shadow:0 16px 40px rgba(232,163,61,.6)}
  .btn-ghost{border:2px solid rgba(250,246,240,.5);color:var(--cream)}
  .btn-ghost:hover{border-color:var(--amber);color:var(--amber-light);transform:translateY(-4px)}

  /* 3D floating planks */
  .plank{position:absolute;border-radius:8px;background:linear-gradient(135deg,var(--wood-light),var(--wood));
      box-shadow:0 20px 50px rgba(0,0,0,.5);opacity:.9;transform-style:preserve-3d}
  .plank::after{content:"";position:absolute;inset:0;border-radius:8px;
      background:repeating-linear-gradient(0deg,rgba(0,0,0,.12) 0 3px,transparent 3px 9px)}
  .p1{width:220px;height:44px;top:16%;left:6%;transform:rotateY(35deg) rotateZ(-8deg);animation:drift1 9s ease-in-out infinite}
  .p2{width:170px;height:36px;bottom:22%;right:8%;transform:rotateY(-30deg) rotateZ(6deg);animation:drift2 11s ease-in-out infinite}
  .p3{width:140px;height:32px;top:58%;left:10%;transform:rotateY(25deg) rotateZ(4deg);animation:drift1 13s ease-in-out infinite reverse}
  @keyframes drift1{0%,100%{transform:rotateY(35deg) rotateZ(-8deg) translateY(0)}50%{transform:rotateY(50deg) rotateZ(-8deg) translateY(-24px)}}
  @keyframes drift2{0%,100%{transform:rotateY(-30deg) rotateZ(6deg) translateY(0)}50%{transform:rotateY(-45deg) rotateZ(6deg) translateY(20px)}}

  /* ===== SECTIONS ===== */
  section{padding:90px 6vw}
  .section-title{text-align:center;font-size:clamp(1.8rem,4vw,2.6rem);font-weight:800;margin-bottom:12px}
  .section-sub{text-align:center;color:#7a6a58;max-width:560px;margin:0 auto 56px;font-size:1.05rem}

  /* Services 3D cards */
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:26px;max-width:1100px;margin:0 auto;perspective:1500px}
  .card{background:var(--card);border-radius:20px;padding:36px 28px;text-align:center;border:1px solid #eee2d2;
      transform-style:preserve-3d;transition:transform .35s ease, box-shadow .35s ease;cursor:default;
      box-shadow:0 6px 20px rgba(61,40,23,.08)}
  .card:hover{transform:rotateX(6deg) rotateY(-6deg) translateY(-8px);box-shadow:0 26px 50px rgba(61,40,23,.22)}
  .card .icon{width:70px;height:70px;margin:0 auto 20px;border-radius:18px;display:grid;place-items:center;font-size:2rem;
      background:linear-gradient(135deg,var(--wood),var(--wood-light));transform:translateZ(40px);
      box-shadow:0 10px 22px rgba(107,68,35,.35)}
  .card h3{font-size:1.2rem;margin-bottom:10px;transform:translateZ(30px)}
  .card p{color:#6d5f4e;font-size:.93rem;line-height:1.55;transform:translateZ(20px)}

  /* Why us band */
  .band{background:linear-gradient(120deg,var(--wood-dark),var(--wood));color:var(--cream)}
  .band .section-sub{color:#cbb79d}
  .stats{display:flex;flex-wrap:wrap;justify-content:center;gap:50px;max-width:900px;margin:0 auto}
  .stat{text-align:center}
  .stat b{display:block;font-size:2.6rem;color:var(--amber)}
  .stat span{color:#d9c8b2;font-size:.95rem}

  /* Reviews */
  .reviews-wrap{max-width:1100px;margin:0 auto}
  .review{background:var(--card);border-radius:18px;padding:28px;border:1px solid #eee2d2;
      box-shadow:0 6px 18px rgba(61,40,23,.07);transform-style:preserve-3d;transition:.3s}
  .review:hover{transform:translateY(-6px) rotateX(3deg);box-shadow:0 20px 40px rgba(61,40,23,.16)}
  .review .r-stars{color:var(--amber);font-size:1.1rem;letter-spacing:2px;margin-bottom:10px}
  .review .r-tag{display:inline-block;background:#f3e8d8;color:var(--wood);font-size:.75rem;font-weight:700;
      padding:4px 12px;border-radius:20px;margin-bottom:12px}
  .review p{font-size:.95rem;line-height:1.6;color:#55483a;margin-bottom:16px}
  .review .r-name{font-weight:700;color:var(--wood-dark)}
  .review .r-time{color:#a08d76;font-size:.82rem}
  .reviews-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:24px}

  /* CTA */
  .cta{background:radial-gradient(ellipse at 50% 0%,#7a5230,var(--wood-dark) 70%);text-align:center;color:var(--cream)}
  .cta h2{font-size:clamp(1.8rem,4.5vw,2.8rem);margin-bottom:14px}
  .cta p{color:#d9c8b2;margin-bottom:34px;font-size:1.1rem}
  .cta .btn-amber{font-size:1.2rem;padding:20px 46px}

  footer{background:#1c1207;color:#9c8a72;text-align:center;padding:34px 6vw;font-size:.88rem}
  footer b{color:var(--cream)}

  /* fade-in on scroll */
  .fade{opacity:0;transform:translateY(30px);transition:opacity .7s ease,transform .7s ease}
  .fade.show{opacity:1;transform:none}

  /* floating call button mobile */
  .fab{position:fixed;bottom:22px;right:22px;z-index:99;width:62px;height:62px;border-radius:50%;
      background:linear-gradient(135deg,var(--amber),#d18a1f);display:grid;place-items:center;font-size:1.6rem;
      box-shadow:0 10px 30px rgba(232,163,61,.6);animation:pulse 2.2s infinite;text-decoration:none}
  @keyframes pulse{0%,100%{transform:scale(1)}50%{transform:scale(1.08)}}
  @media(min-width:821px){.fab{display:none}}
</style>
</head>
<body>

<nav>
  <div class="logo"><span class="logo-badge">🪵</span> CT Flooring Services</div>
  <div class="nav-links">
    <a href="#services">Services</a>
    <a href="#why">Why Us</a>
    <a href="#reviews">Reviews</a>
    <a class="nav-call" href="tel:+14245007345">📞 (424) 500-7345</a>
  </div>
</nav>

<!-- HERO -->
<header class="hero">
  <div class="plank p1"></div><div class="plank p2"></div><div class="plank p3"></div>
  <div class="hero-inner">
    <div class="hero-tag">Redondo Beach · California</div>
    <h1>Floors That Transform <span>Your Home</span></h1>
    <p>Hardwood, laminate & luxury vinyl installation, floor repair, and full home remodeling — done right, on time, and at a great price.</p>
    <div class="stars-big">★★★★★</div>
    <div class="rating-note">4.8 out of 5 · 131 Google Reviews</div>
    <div class="btn-row">
      <a class="btn btn-amber" href="tel:+14245007345">📞 Call for Free Estimate</a>
      <a class="btn btn-ghost" href="#services">View Our Services</a>
    </div>
  </div>
</header>

<!-- SERVICES -->
<section id="services">
  <h2 class="section-title fade">What We Do</h2>
  <p class="section-sub fade">From a single room to a full remodel — one trusted crew for your entire project.</p>
  <div class="grid">
    <div class="card fade"><div class="icon">🪵</div><h3>Hardwood & Laminate</h3><p>Precision installation of hardwood, laminate and luxury vinyl plank with flawless finishes.</p></div>
    <div class="card fade"><div class="icon">🔧</div><h3>Floor Repair & Sanding</h3><p>Water damage, scratches, warped boards — we restore your floors to like-new condition.</p></div>
    <div class="card fade"><div class="icon">🏠</div><h3>Home Remodeling</h3><p>Kitchens, bathrooms, additions and whole-home remodels handled start to finish.</p></div>
    <div class="card fade"><div class="icon">🧱</div><h3>Drywall & Framing</h3><p>Professional drywall repair, wall finishing, and structural framing by experienced pros.</p></div>
    <div class="card fade"><div class="icon">🛡️</div><h3>Roof Repair</h3><p>Reliable roofing repairs that protect your home — trusted by your neighbors.</p></div>
    <div class="card fade"><div class="icon">✨</div><h3>Floor Polishing</h3><p>Deep cleaning and polishing that brings out the natural beauty of your floors.</p></div>
  </div>
</section>

<!-- WHY US -->
<section id="why" class="band">
  <h2 class="section-title fade">Why Homeowners Choose Us</h2>
  <p class="section-sub fade">Rated 4.8★ by 131+ customers across the South Bay for a reason.</p>
  <div class="stats fade">
    <div class="stat"><b>4.8★</b><span>Google Rating</span></div>
    <div class="stat"><b>131+</b><span>Happy Reviews</span></div>
    <div class="stat"><b>100%</b><span>Licensed & Insured</span></div>
    <div class="stat"><b>Free</b><span>Estimates</span></div>
  </div>
</section>

<!-- REVIEWS -->
<section id="reviews">
  <h2 class="section-title fade">What Our Customers Say</h2>
  <p class="section-sub fade">Real reviews from real homeowners in Redondo Beach and the South Bay.</p>
  <div class="reviews-wrap reviews-grid">
    <div class="review fade"><div class="r-stars">★★★★★</div><span class="r-tag">Great price</span>
      <p>"I had rain damage in my bathroom that affected the walls. I planned to replace the shower surround and damaged drywall — once the walls were done, the work was excellent."</p>
      <div class="r-name">Brendan Cohen</div><div class="r-time">18 hours ago</div></div>
    <div class="review fade"><div class="r-stars">★★★★★</div><span class="r-tag">Great price</span>
      <p>"I have had many average and frustrating experiences with past home remodeling projects over the years. This project was a refreshing change and set a new standard."</p>
      <div class="r-name">M Todd</div><div class="r-time">5 days ago</div></div>
    <div class="review fade"><div class="r-stars">★★★★★</div><span class="r-tag">Reasonable price</span>
      <p>"I spent a long time searching for ideas to remodel my backyard and got a few estimates before contacting CT Flooring Services. I really liked the way they handled everything."</p>
      <div class="r-name">Ryker Foley</div><div class="r-time">a week ago</div></div>
    <div class="review fade"><div class="r-stars">★★★★★</div><span class="r-tag">Great price</span>
      <p>"The remodeling team has been updating our homes, and from the start the whole process has been helpful, clear, and easy to follow. Whenever I had questions they answered right away."</p>
      <div class="r-name">Julian Ochoa</div><div class="r-time">a week ago</div></div>
    <div class="review fade"><div class="r-stars">★★★★★</div><span class="r-tag">Great price</span>
      <p>"Wow, just wow. This home remodeling team was professional from start to finish. I am a very picky homeowner and I expect a lot — they exceeded every expectation."</p>
      <div class="r-name">caitlin douglas · Local Guide</div><div class="r-time">a week ago</div></div>
    <div class="review fade"><div class="r-stars">★★★★★</div><span class="r-tag">Great price</span>
      <p>"The team did an excellent job on our second-story home addition and remodeling project. We had a tough time finding a contractor we could really trust — until we found CT."</p>
      <div class="r-name">Abel Jefferson</div><div class="r-time">a week ago</div></div>
    <div class="review fade"><div class="r-stars">★★★★★</div><span class="r-tag">Great price</span>
      <p>"CT Flooring Services handled a large remodel of our home. The crew protects floors by laying down protective coverings before starting work and always arrives on time."</p>
      <div class="r-name">Kylee Wilcox</div><div class="r-time">2 weeks ago</div></div>
  </div>
</section>

<!-- CTA -->
<section class="cta">
  <h2 class="fade">Ready to Upgrade Your Floors?</h2>
  <p class="fade">Call now for a free, no-obligation estimate. Open today until 10 PM.</p>
  <a class="btn btn-amber fade" href="tel:+14245007345">📞 Call (424) 500-7345</a>
</section>

<footer>
  <b>CT Flooring Services</b> · Redondo Beach, California<br>
  Flooring · Remodeling · Drywall · Framing · Roofing<br>
  📞 <a href="tel:+14245007345" style="color:var(--amber-light);text-decoration:none">(424) 500-7345</a>
</footer>

<a class="fab" href="tel:+14245007345" aria-label="Call now">📞</a>

<script>
  // Scroll fade-in
  const obs = new IntersectionObserver(entries=>{
    entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('show')});
  },{threshold:.12});
  document.querySelectorAll('.fade').forEach(el=>obs.observe(el));

  // 3D tilt on cards
  document.querySelectorAll('.card').forEach(card=>{
    card.addEventListener('mousemove',e=>{
      const r=card.getBoundingClientRect();
      const x=(e.clientX-r.left)/r.width-.5, y=(e.clientY-r.top)/r.height-.5;
      card.style.transform=`rotateX(${-y*10}deg) rotateY(${x*10}deg) translateY(-8px)`;
    });
    card.addEventListener('mouseleave',()=>card.style.transform='');
  });
</script>
</body>
</html>
