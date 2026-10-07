<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cabinet Dentaire Trauboutin — Occlusodontie &amp; Micro-Dentisterie | Blida</title>
<meta name="description" content="Cabinet Dentaire Trauboutin à Oued El Alleug, Blida. Expertise en occlusodontie et soins dentaires au microscope opératoire : endodontie, esthétique dentaire, équilibration de l'occlusion.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --ink:#0b2239;
  --deep:#0e3a4c;
  --teal:#12708a;
  --teal-light:#2aa0bd;
  --gold:#c9a24b;
  --gold-light:#e6cd8f;
  --bg:#f7fafb;
  --white:#ffffff;
  --text:#3d4b57;
  --muted:#7b8a96;
  --radius:18px;
  --shadow:0 20px 60px rgba(11,34,57,.12);
  --shadow-soft:0 10px 30px rgba(11,34,57,.08);
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:'Inter',sans-serif;color:var(--text);background:var(--bg);line-height:1.65;overflow-x:hidden}
h1,h2,h3,.serif{font-family:'Playfair Display',serif;color:var(--ink)}
img{max-width:100%;display:block}
a{text-decoration:none;color:inherit}
.container{width:min(1180px,92%);margin:0 auto}
.eyebrow{display:inline-flex;align-items:center;gap:.6rem;font-size:.78rem;font-weight:600;letter-spacing:.22em;text-transform:uppercase;color:var(--teal)}
.eyebrow::before{content:"";width:34px;height:2px;background:var(--gold);display:inline-block}
.section-title{font-size:clamp(1.9rem,3.4vw,2.7rem);line-height:1.2;margin:.6rem 0 1rem;font-weight:600}
.section-sub{max-width:640px;color:var(--muted);font-size:1.02rem}
section{padding:6rem 0}
.reveal{opacity:0;transform:translateY(30px);transition:opacity .8s ease,transform .8s ease}
.reveal.visible{opacity:1;transform:none}

/* ---------- HEADER ---------- */
header{position:fixed;inset:0 0 auto;z-index:100;transition:background .35s,box-shadow .35s;padding:1.1rem 0}
header.scrolled{background:rgba(255,255,255,.92);backdrop-filter:blur(14px);box-shadow:0 6px 30px rgba(11,34,57,.08);padding:.7rem 0}
.nav{display:flex;align-items:center;justify-content:space-between}
.logo{display:flex;align-items:center;gap:.7rem;font-family:'Playfair Display',serif;font-weight:700;font-size:1.25rem;color:#fff;transition:color .35s}
header.scrolled .logo{color:var(--ink)}
.logo-mark{width:42px;height:42px;border-radius:12px;background:linear-gradient(135deg,var(--teal),var(--teal-light));display:grid;place-items:center;box-shadow:0 8px 20px rgba(18,112,138,.35);flex:none}
.logo-mark svg{width:24px;height:24px;stroke:#fff}
.logo small{display:block;font-family:'Inter',sans-serif;font-size:.62rem;font-weight:500;letter-spacing:.28em;text-transform:uppercase;opacity:.75}
.nav-links{display:flex;align-items:center;gap:2rem;list-style:none}
.nav-links a{font-size:.92rem;font-weight:500;color:rgba(255,255,255,.85);transition:color .3s;position:relative}
header.scrolled .nav-links a{color:var(--text)}
.nav-links a::after{content:"";position:absolute;left:0;bottom:-6px;width:0;height:2px;background:var(--gold);transition:width .3s}
.nav-links a:hover::after{width:100%}
.btn{display:inline-flex;align-items:center;gap:.55rem;padding:.85rem 1.7rem;border-radius:999px;font-weight:600;font-size:.92rem;cursor:pointer;border:none;transition:transform .25s,box-shadow .25s,background .25s}
.btn-gold{background:linear-gradient(135deg,var(--gold),#b8892e);color:#fff;box-shadow:0 10px 26px rgba(201,162,75,.4)}
.btn-gold:hover{transform:translateY(-2px);box-shadow:0 14px 34px rgba(201,162,75,.5)}
.btn-ghost{background:rgba(255,255,255,.12);color:#fff;border:1px solid rgba(255,255,255,.35);backdrop-filter:blur(6px)}
.btn-ghost:hover{background:rgba(255,255,255,.22)}
.btn-teal{background:var(--teal);color:#fff;box-shadow:0 10px 26px rgba(18,112,138,.35)}
.btn-teal:hover{transform:translateY(-2px)}
.burger{display:none;background:none;border:none;cursor:pointer;width:40px;height:40px}
.burger span{display:block;width:24px;height:2px;background:#fff;margin:5px auto;transition:.3s}
header.scrolled .burger span{background:var(--ink)}

/* ---------- HERO ---------- */
.hero{position:relative;min-height:100vh;display:flex;align-items:center;padding:9rem 0 5rem;color:#fff;overflow:hidden;
  background:radial-gradient(1200px 700px at 85% -10%,rgba(42,160,189,.35),transparent 60%),
             radial-gradient(900px 600px at -10% 110%,rgba(201,162,75,.22),transparent 55%),
             linear-gradient(150deg,#0b2239 0%,#0e3a4c 55%,#0f4a5c 100%)}
.hero-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:4rem;align-items:center}
.hero h1{font-size:clamp(2.4rem,4.6vw,3.9rem);line-height:1.12;color:#fff;font-weight:600}
.hero h1 em{font-style:normal;background:linear-gradient(120deg,var(--gold-light),var(--gold));-webkit-background-clip:text;background-clip:text;color:transparent}
.hero p.lead{margin:1.4rem 0 2.2rem;font-size:1.08rem;color:rgba(255,255,255,.78);max-width:540px;font-weight:300}
.hero-ctas{display:flex;gap:1rem;flex-wrap:wrap}
.hero-badges{display:flex;gap:2.2rem;margin-top:3rem;flex-wrap:wrap}
.hero-badges div strong{display:block;font-family:'Playfair Display',serif;font-size:1.6rem;color:var(--gold-light)}
.hero-badges div span{font-size:.82rem;color:rgba(255,255,255,.65);letter-spacing:.04em}

/* microscope visual */
.hero-visual{position:relative;display:grid;place-items:center}
.scope-frame{position:relative;width:min(420px,88%);aspect-ratio:1/1.15;border-radius:32px;overflow:hidden;
  background:linear-gradient(160deg,rgba(255,255,255,.14),rgba(255,255,255,.04));border:1px solid rgba(255,255,255,.22);backdrop-filter:blur(8px);box-shadow:0 40px 90px rgba(0,0,0,.35)}
.scope-frame svg{width:100%;height:100%}
.ring{position:absolute;border-radius:50%;border:1px dashed rgba(230,205,143,.5);animation:spin 26s linear infinite}
.ring.r1{width:120%;height:120%;top:-10%;left:-10%}
.ring.r2{width:135%;height:135%;top:-17.5%;left:-17.5%;animation-duration:40s;animation-direction:reverse}
@keyframes spin{to{transform:rotate(360deg)}}
.float-card{position:absolute;background:rgba(255,255,255,.96);color:var(--ink);border-radius:16px;padding:.85rem 1.15rem;box-shadow:var(--shadow);display:flex;align-items:center;gap:.7rem;font-size:.85rem;font-weight:600}
.float-card svg{width:26px;height:26px;flex:none}
.fc1{bottom:8%;left:-6%}
.fc2{top:12%;right:-5%}
.wave{position:absolute;bottom:-2px;left:0;width:100%;line-height:0}
.wave svg{width:100%;height:80px;display:block}

/* ---------- EXPERTISE (occlusion + microscope) ---------- */
.expertise{background:var(--white)}
.exp-grid{display:grid;grid-template-columns:1fr 1fr;gap:3.5rem;align-items:center;margin-top:3.5rem}
.exp-media{position:relative;border-radius:var(--radius);overflow:hidden;box-shadow:var(--shadow);min-height:420px;display:grid;place-items:center;padding:2.5rem}
.exp-media.occ{background:linear-gradient(150deg,#0e3a4c,#12708a)}
.exp-media.micro{background:linear-gradient(150deg,#0b2239,#0f4a5c)}
.exp-media svg{width:100%;max-width:380px;height:auto}
.exp-tag{position:absolute;top:1.2rem;left:1.2rem;background:rgba(255,255,255,.14);border:1px solid rgba(255,255,255,.3);color:#fff;font-size:.72rem;font-weight:600;letter-spacing:.2em;text-transform:uppercase;padding:.45rem 1rem;border-radius:999px;backdrop-filter:blur(6px)}
.exp-body h3{font-size:1.7rem;margin-bottom:1rem}
.exp-body p{color:var(--muted);margin-bottom:1.1rem}
.check-list{list-style:none;margin:1.4rem 0 1.8rem;display:grid;gap:.8rem}
.check-list li{display:flex;gap:.8rem;align-items:flex-start;font-size:.96rem}
.check-list li::before{content:"";flex:none;width:22px;height:22px;margin-top:2px;border-radius:50%;
  background:var(--teal) url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='white' stroke-width='3' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='M20 6L9 17l-5-5'/%3E%3C/svg%3E") center/12px no-repeat}
.exp-rev .exp-media{order:2}
.exp-rev .exp-body{order:1}
@media(max-width:900px){.exp-grid{grid-template-columns:1fr}.exp-rev .exp-media{order:0}}

/* ---------- SERVICES ---------- */
.services{background:linear-gradient(180deg,var(--bg),#eef5f7)}
.svc-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.6rem;margin-top:3rem}
.svc-card{background:#fff;border-radius:var(--radius);padding:2.1rem 1.8rem;box-shadow:var(--shadow-soft);border:1px solid #e6eef1;transition:transform .3s,box-shadow .3s;position:relative;overflow:hidden}
.svc-card::after{content:"";position:absolute;inset:auto -30% -60% auto;width:200px;height:200px;border-radius:50%;background:radial-gradient(circle,rgba(42,160,189,.12),transparent 70%)}
.svc-card:hover{transform:translateY(-8px);box-shadow:var(--shadow)}
.svc-icon{width:56px;height:56px;border-radius:16px;display:grid;place-items:center;background:linear-gradient(135deg,rgba(18,112,138,.12),rgba(42,160,189,.08));margin-bottom:1.3rem}
.svc-icon svg{width:28px;height:28px;stroke:var(--teal)}
.svc-card h3{font-size:1.18rem;margin-bottom:.55rem}
.svc-card p{font-size:.92rem;color:var(--muted)}

/* ---------- WHY ---------- */
.why{background:var(--deep);color:#fff;position:relative;overflow:hidden}
.why::before{content:"";position:absolute;width:600px;height:600px;border-radius:50%;background:radial-gradient(circle,rgba(42,160,189,.25),transparent 65%);top:-200px;right:-150px}
.why .section-title{color:#fff}
.why .section-sub{color:rgba(255,255,255,.65)}
.why-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:1.4rem;margin-top:3rem}
.why-card{background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.14);border-radius:var(--radius);padding:1.8rem 1.5rem;backdrop-filter:blur(8px);transition:background .3s,transform .3s}
.why-card:hover{background:rgba(255,255,255,.12);transform:translateY(-6px)}
.why-card .num{font-family:'Playfair Display',serif;font-size:2rem;color:var(--gold-light);margin-bottom:.7rem}
.why-card h3{font-size:1.05rem;color:#fff;margin-bottom:.5rem;font-family:'Inter',sans-serif;font-weight:600}
.why-card p{font-size:.88rem;color:rgba(255,255,255,.6)}

/* ---------- REVIEWS ---------- */
.reviews{background:#fff}
.rev-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.6rem;margin-top:3rem}
.rev-card{background:var(--bg);border-radius:var(--radius);padding:2rem;border:1px solid #e6eef1;position:relative}
.rev-card .stars{color:var(--gold);letter-spacing:.15em;margin-bottom:1rem}
.rev-card p{font-size:.95rem;font-style:italic;color:var(--text)}
.rev-card .who{display:flex;align-items:center;gap:.8rem;margin-top:1.4rem}
.rev-card .avatar{width:44px;height:44px;border-radius:50%;background:linear-gradient(135deg,var(--teal),var(--teal-light));color:#fff;display:grid;place-items:center;font-weight:600}
.rev-card .who strong{display:block;font-size:.92rem;color:var(--ink)}
.rev-card .who span{font-size:.8rem;color:var(--muted)}

/* ---------- CONTACT ---------- */
.contact{background:linear-gradient(180deg,#eef5f7,var(--bg))}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:3.5rem;margin-top:3rem;align-items:stretch}
.info-card{background:#fff;border-radius:var(--radius);box-shadow:var(--shadow-soft);padding:2.4rem;border:1px solid #e6eef1}
.info-row{display:flex;gap:1.1rem;align-items:flex-start;padding:1.05rem 0;border-bottom:1px solid #eef3f5}
.info-row:last-of-type{border-bottom:none}
.info-ico{width:46px;height:46px;flex:none;border-radius:14px;background:rgba(18,112,138,.1);display:grid;place-items:center}
.info-ico svg{width:22px;height:22px;stroke:var(--teal)}
.info-row h4{font-size:.82rem;text-transform:uppercase;letter-spacing:.12em;color:var(--muted);font-weight:600}
.info-row p{font-weight:600;color:var(--ink);margin-top:.15rem}
.info-row a{color:var(--teal)}
.socials{display:flex;gap:.8rem;margin-top:1.6rem}
.socials a{width:46px;height:46px;border-radius:14px;display:grid;place-items:center;background:var(--ink);transition:background .3s,transform .3s}
.socials a:hover{background:var(--teal);transform:translateY(-4px)}
.socials svg{width:22px;height:22px;fill:#fff}
.appt-card{background:linear-gradient(150deg,#0b2239,#0f4a5c);border-radius:var(--radius);padding:2.4rem;color:#fff;box-shadow:var(--shadow);display:flex;flex-direction:column;justify-content:center;position:relative;overflow:hidden}
.appt-card::after{content:"";position:absolute;width:300px;height:300px;border-radius:50%;background:radial-gradient(circle,rgba(201,162,75,.3),transparent 70%);bottom:-120px;right:-100px}
.appt-card h3{font-size:1.6rem;color:#fff;margin-bottom:.8rem}
.appt-card p{color:rgba(255,255,255,.7);font-size:.95rem;margin-bottom:1.8rem}
.hours{width:100%;border-collapse:collapse;margin-bottom:1.8rem;font-size:.92rem}
.hours td{padding:.6rem 0;border-bottom:1px dashed rgba(255,255,255,.18);color:rgba(255,255,255,.85)}
.hours td:last-child{text-align:right;font-weight:600;color:var(--gold-light)}
.hours tr.closed td{color:rgba(255,255,255,.45)}

/* ---------- FOOTER ---------- */
footer{background:var(--ink);color:rgba(255,255,255,.6);padding:3.5rem 0 2rem;font-size:.9rem}
.foot-grid{display:grid;grid-template-columns:2fr 1fr 1fr;gap:3rem;margin-bottom:2.5rem}
footer h4{color:#fff;font-family:'Inter',sans-serif;font-size:.85rem;text-transform:uppercase;letter-spacing:.15em;margin-bottom:1.1rem}
footer ul{list-style:none;display:grid;gap:.6rem}
footer a:hover{color:var(--gold-light)}
.foot-bottom{border-top:1px solid rgba(255,255,255,.1);padding-top:1.5rem;display:flex;justify-content:space-between;gap:1rem;flex-wrap:wrap;font-size:.82rem}

/* mobile */
@media(max-width:960px){
  .nav-links{position:fixed;inset:0;background:linear-gradient(150deg,#0b2239,#0f4a5c);flex-direction:column;justify-content:center;gap:2rem;transform:translateX(100%);transition:transform .4s;z-index:99}
  .nav-links.open{transform:none}
  .nav-links a{color:#fff !important;font-size:1.2rem}
  .burger{display:block;position:relative;z-index:100}
  .nav-links.open + .burger span{background:#fff}
  .hero-grid{grid-template-columns:1fr;gap:3rem}
  .hero-visual{display:none}
  .svc-grid,.rev-grid{grid-template-columns:1fr 1fr}
  .why-grid{grid-template-columns:1fr 1fr}
  .contact-grid,.foot-grid{grid-template-columns:1fr}
}
@media(max-width:600px){
  section{padding:4rem 0}
  .svc-grid,.rev-grid,.why-grid{grid-template-columns:1fr}
  .hero-badges{gap:1.4rem}
}
</style>
</head>
<body>

<!-- ======= HEADER ======= -->
<header id="header">
  <div class="container nav">
    <a href="#" class="logo">
      <span class="logo-mark">
        <svg viewBox="0 0 24 24" fill="none" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5.5c-1.6-1.4-4-1.7-5.6-.4C4.7 6.4 4.6 8.9 5.5 11c.8 2 .9 4.2 1.2 6.3.2 1.4.5 3.2 1.9 3.2 1.6 0 1.6-2.2 1.8-3.5.2-1.2.6-3 2.6-3s2.4 1.8 2.6 3c.2 1.3.2 3.5 1.8 3.5 1.4 0 1.7-1.8 1.9-3.2.3-2.1.4-4.3 1.2-6.3.9-2.1.8-4.6-.9-5.9-1.6-1.3-4-1-5.6.4z"/></svg>
      </span>
      <span>Cabinet Trauboutin<small>Dentaire · Blida</small></span>
    </a>
    <ul class="nav-links" id="navLinks">
      <li><a href="#expertises">Expertises</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#apropos">Le Cabinet</a></li>
      <li><a href="#avis">Avis</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="tel:+213783831225" class="btn btn-gold">Prendre rendez-vous</a></li>
    </ul>
    <button class="burger" id="burger" aria-label="Menu"><span></span><span></span><span></span></button>
  </div>
</header>

<!-- ======= HERO ======= -->
<section class="hero" style="padding-top:9rem">
  <div class="container hero-grid">
    <div>
      <span class="eyebrow" style="color:var(--gold-light)">Cabinet Dentaire · Oued El Alleug, Blida</span>
      <h1>La précision au <em>microscope</em>,<br>l'harmonie par <em>l'occlusion</em>.</h1>
      <p class="lead">Le Cabinet Dentaire Trauboutin allie haute technologie et expertise clinique : micro-dentisterie, endodontie au microscope opératoire et occlusodontie pour des sourires durablement sains.</p>
      <div class="hero-ctas">
        <a href="tel:+213783831225" class="btn btn-gold">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.12.96.37 1.9.72 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.91.35 1.85.6 2.81.72A2 2 0 0 1 22 16.92z"/></svg>
          0783 83 12 25
        </a>
        <a href="#expertises" class="btn btn-ghost">Découvrir nos expertises</a>
      </div>
      <div class="hero-badges">
        <div><strong>Microscope</strong><span>opératoire haute définition</span></div>
        <div><strong>Occlusodontie</strong><span>analyse de l'articulé</span></div>
        <div><strong>Sterilisation</strong><span>protocole strict</span></div>
      </div>
    </div>
    <div class="hero-visual">
      <div class="ring r1"></div>
      <div class="ring r2"></div>
      <div class="scope-frame">
        <!-- Illustration microscope -->
        <svg viewBox="0 0 400 460" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="metal" x1="0" y1="0" x2="1" y2="1">
              <stop offset="0" stop-color="#dfe9ee"/><stop offset=".5" stop-color="#9fb6c0"/><stop offset="1" stop-color="#5f7f8c"/>
            </linearGradient>
            <linearGradient id="metal2" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0" stop-color="#b8ccd4"/><stop offset="1" stop-color="#6e8b96"/>
            </linearGradient>
            <radialGradient id="lensGlow" cx=".5" cy=".5" r=".5">
              <stop offset="0" stop-color="#7fd8ee" stop-opacity=".9"/><stop offset="1" stop-color="#7fd8ee" stop-opacity="0"/>
            </radialGradient>
          </defs>
          <circle cx="200" cy="230" r="150" fill="url(#lensGlow)" opacity=".35"/>
          <!-- base -->
          <rect x="120" y="386" width="160" height="18" rx="9" fill="url(#metal2)"/>
          <path d="M182 386 h36 v-16 a18 18 0 0 0 -36 0 z" fill="url(#metal)"/>
          <!-- arm -->
          <path d="M200 370 C 150 340, 138 260, 158 190" stroke="url(#metal)" stroke-width="26" stroke-linecap="round" fill="none"/>
          <!-- body tube angled -->
          <g transform="rotate(28 200 200)">
            <rect x="168" y="88" width="64" height="150" rx="18" fill="url(#metal)"/>
            <rect x="176" y="72" width="48" height="34" rx="10" fill="url(#metal2)"/>
            <rect x="176" y="216" width="48" height="44" rx="10" fill="url(#metal2)"/>
          </g>
          <!-- binocular head -->
          <g transform="rotate(28 200 200)">
            <rect x="182" y="252" width="36" height="34" rx="8" fill="url(#metal)"/>
            <circle cx="182" cy="300" r="12" fill="#2b3f49"/><circle cx="182" cy="300" r="6" fill="#7fd8ee"/>
            <circle cx="218" cy="300" r="12" fill="#2b3f49"/><circle cx="218" cy="300" r="6" fill="#7fd8ee"/>
          </g>
          <!-- objective -->
          <circle cx="248" cy="330" r="26" fill="url(#metal2)"/>
          <circle cx="248" cy="330" r="14" fill="#12303e"/>
          <circle cx="248" cy="330" r="7" fill="#9fe8f8"/>
          <!-- light beam -->
          <path d="M248 356 L214 430 h68 z" fill="url(#lensGlow)"/>
          <!-- tooth on stage -->
          <ellipse cx="248" cy="436" rx="52" ry="8" fill="#0a2a35" opacity=".6"/>
          <g transform="translate(224 388) scale(1.15)">
            <path d="M21 4c-3-2.6-7.5-3.2-10.5-.8C7 5.6 6.8 9.2 8.9 12.3c1.6 2.4 1.8 5 2.3 7.5.3 1.7.9 3.9 3.5 3.9 3 0 3-3.6 3.4-5.7.4-1.9 1.2-4.8 5-4.8s4.6 2.9 5 4.8c.4 2.1.4 5.7 3.4 5
