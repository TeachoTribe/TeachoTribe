<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>TeachoTribe Consulting</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#16281F;
    --bg-2:#1E3628;
    --chalk:#F3F1E7;
    --chalk-dim:#C7CFC5;
    --gold:#E3A23C;
    --gold-dim:#8A6A34;
    --rule:rgba(243,241,231,0.14);
    box-sizing:border-box;
    padding-top:env(safe-area-inset-top,0px);
    padding-bottom:env(safe-area-inset-bottom,0px);
  }
  html{scroll-padding-top:env(safe-area-inset-top,0px);}
  *{box-sizing:border-box;}
  html,body{height:100%;}
  body{
    margin:0;
    background:var(--bg);
    color:var(--chalk);
    font-family:'Inter',system-ui,sans-serif;
    line-height:1.6;
  }
  h1,h2,h3{
    font-family:'Fraunces',Georgia,serif;
    font-weight:600;
    margin:0;
    line-height:1.15;
  }
  a{color:inherit;}
  .wrap{max-width:960px;margin:0 auto;padding:0 24px;}
  header{
    padding:22px 0;
    display:flex;
    justify-content:space-between;
    align-items:center;
    border-bottom:1px solid var(--rule);
  }
  .mark{font-family:'Fraunces',serif;font-size:19px;font-weight:600;letter-spacing:0.2px;}
  .mark span{color:var(--gold);}
  nav a{
    text-decoration:none;
    color:var(--chalk-dim);
    font-size:14px;
    margin-left:26px;
  }
  nav a:hover{color:var(--chalk);}

  .hero{padding:88px 0 72px;}
  .hero .kicker{
    color:var(--gold);
    font-size:15px;
    margin-bottom:18px;
    max-width:520px;
  }
  .hero h1{
    font-size:clamp(34px,5.4vw,54px);
    max-width:14ch;
  }
  .hero p.lede{
    max-width:52ch;
    color:var(--chalk-dim);
    font-size:17px;
    margin-top:22px;
  }
  .hero-cta{margin-top:34px;display:flex;gap:14px;flex-wrap:wrap;}
  .btn{
    display:inline-block;
    padding:13px 22px;
    border-radius:2px;
    text-decoration:none;
    font-size:15px;
    font-weight:500;
    border:1px solid transparent;
  }
  .btn-gold{background:var(--gold);color:#1B1204;}
  .btn-gold:hover{background:#eeb257;}
  .btn-ghost{border-color:var(--rule);color:var(--chalk);}
  .btn-ghost:hover{border-color:var(--chalk-dim);}

  section{padding:64px 0;border-top:1px solid var(--rule);}
  .about p{max-width:62ch;color:var(--chalk-dim);font-size:16px;}
  .about h2{font-size:28px;margin-bottom:20px;}

  .split{display:grid;grid-template-columns:1fr 1fr;gap:36px;}
  @media(max-width:680px){.split{grid-template-columns:1fr;}}
  .split .col h3{font-size:22px;margin-bottom:14px;color:var(--gold);}
  .split .col p{color:var(--chalk-dim);font-size:15.5px;margin:0 0 10px;}

  .services h2{font-size:28px;margin-bottom:8px;}
  .services > p{color:var(--chalk-dim);max-width:56ch;margin:0 0 34px;}
  .svc-list{border-top:1px solid var(--rule);}
  .svc-row{
    display:grid;
    grid-template-columns:220px 1fr;
    gap:24px;
    padding:26px 0;
    border-bottom:1px solid var(--rule);
  }
  @media(max-width:640px){.svc-row{grid-template-columns:1fr;gap:8px;}}
  .svc-row h3{font-size:19px;font-weight:500;}
  .svc-row p{margin:0;color:var(--chalk-dim);font-size:15.5px;max-width:56ch;}

  footer{padding:56px 0 60px;border-top:1px solid var(--rule);}
  .contact h2{font-size:28px;margin-bottom:14px;}
  .contact p{color:var(--chalk-dim);max-width:52ch;margin-bottom:26px;}
  .foot-meta{
    margin-top:50px;
    display:flex;
    justify-content:space-between;
    flex-wrap:wrap;
    gap:12px;
    color:var(--chalk-dim);
    font-size:13.5px;
  }
</style>
</head>
<body>

<div class="wrap">
  <header>
    <div class="mark">Teacho<span>Tribe</span></div>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" style="border-top:none;">
    <div class="kicker">Education consultancy · Greater Noida West</div>
    <h1>Where schools find great teachers, and teachers find great schools.</h1>
    <p class="lede">TeachoTribe Consulting connects schools with verified, qualified teachers — and gives educators access to real opportunities, a supportive community, and room to grow.</p>
    <div class="hero-cta">
      <a class="btn btn-gold" href="#contact">Talk to us</a>
      <a class="btn btn-ghost" href="#services">See what we do</a>
    </div>
  </section>

  <section class="about" id="about">
    <h2>Built for how schools actually hire</h2>
    <p>Most schools in Greater Noida West have no dedicated HR desk — hiring happens through word of mouth, last-minute calls, and a lot of guesswork. TeachoTribe Consulting exists to fix that: a verified teacher community on one side, and schools who need reliable staffing on the other, with us in the middle making the match.</p>
  </section>

  <section class="split">
    <div class="col">
      <h3>For schools</h3>
      <p>Pre-screened candidates for permanent roles, matched to your board and subject needs.</p>
      <p>Reliable substitute cover when a teacher is absent, without the scramble.</p>
      <p>One point of contact instead of chasing multiple job portals.</p>
    </div>
    <div class="col">
      <h3>For teachers</h3>
      <p>Genuine openings from schools actively hiring — not recycled listings.</p>
      <p>A community built around teaching in Greater Noida West specifically.</p>
      <p>Workshops on classroom tools, curriculum updates, and career growth.</p>
    </div>
  </section>

  <section class="services" id="services">
    <h2>What we do</h2>
    <p>Four ways we work with schools and teachers — you can start with one and add more as you grow with us.</p>
    <div class="svc-list">
      <div class="svc-row">
        <h3>Teacher placement</h3>
        <p>We shortlist and share verified candidates for open teaching positions, so schools spend less time screening and more time deciding.</p>
      </div>
      <div class="svc-row">
        <h3>Substitute staffing</h3>
        <p>Short-notice cover for absent teachers, drawn from educators already known to us and available on short timelines.</p>
      </div>
      <div class="svc-row">
        <h3>Teacher upskilling</h3>
        <p>Workshops on curriculum updates, classroom technology, and exam-pattern changes — for individual teachers or full school staff.</p>
      </div>
      <div class="svc-row">
        <h3>Verified teacher access</h3>
        <p>Schools get direct access to our growing, verified teacher community instead of posting open job ads and sorting through the noise.</p>
      </div>
    </div>
  </section>

  <footer>
    <div class="contact" id="contact">
      <h2>Let's talk</h2>
      <p>Whether you're a school looking to hire or a teacher looking for your next opportunity, reach out — we're based in and focused on Greater Noida West.</p>
      <div class="hero-cta">
        <a class="btn btn-gold" href="https://wa.me/919599390505">Message on WhatsApp</a>
        <a class="btn btn-ghost" href="mailto:teachotribe@gmail.com">Email us</a>
      </div>
    </div>
    <div class="foot-meta">
      <span>TeachoTribe Consulting</span>
      <span>Greater Noida West, Uttar Pradesh</span>
    </div>
  </footer>
</div>

</body>
</html>
