<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Acme Consulting — Professional Services</title>
  <meta name="description" content="Acme Consulting — Fast, reliable business services that get results. Digital marketing, growth strategy, and operations support." />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <meta name="theme-color" content="#0b74de">

  <!-- Open Graph -->
  <meta property="og:title" content="Acme Consulting — Professional Services" />
  <meta property="og:description" content="Fast, reliable business services that get results. Digital marketing, growth strategy, and operations support." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="placeholder-image.png" />

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "Acme Consulting",
    "url": "https://yourdomain.com",
    "logo": "https://yourdomain.com/logo.png",
    "sameAs": [],
    "description": "Fast, reliable business services that get results.",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "City",
      "addressRegion": "Region",
      "postalCode": "00000",
      "streetAddress": "Street 123"
    },
    "telephone": "+1-555-555-5555"
  }
  </script>

  <style>
    :root{
      --accent:#0b74de;
      --accent-2:#0e63b6;
      --bg:#ffffff;
      --muted:#6b7280;
      --radius:12px;
      --max-width:1100px;
      --glass: rgba(255,255,255,0.6);
      --shadow: 0 8px 24px rgba(16,24,40,0.08);
      font-family: 'Inter', system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      color:#0f1724;
      background: linear-gradient(180deg,#f7fbff 0%, #ffffff 60%);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
      padding-bottom:60px;
    }
    .container{
      width:90%;
      max-width:var(--max-width);
      margin:0 auto;
    }

    /* NAV */
    header{
      position:sticky;
      top:0;
      z-index:50;
      backdrop-filter: blur(6px);
      background: linear-gradient(180deg, rgba(255,255,255,0.6), rgba(255,255,255,0.35));
      border-bottom: 1px solid rgba(15,23,36,0.04);
    }
    .nav{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      padding:14px 0;
    }
    .brand{display:flex;gap:12px;align-items:center}
    .logo{
      width:44px;height:44px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));
      display:inline-flex;align-items:center;justify-content:center;color:#fff;font-weight:700;
      box-shadow: var(--shadow);
      font-size:18px;
    }
    nav ul{display:flex;gap:18px;list-style:none;margin:0;padding:0;align-items:center}
    nav a{color:inherit;text-decoration:none;font-weight:600;font-size:15px}
    .btn{
      background:var(--accent);
      color:#fff;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600;
      box-shadow: 0 6px 18px rgba(11,116,222,0.18);
      display:inline-flex;gap:8px;align-items:center;
    }
    .mobile-toggle{display:none;background:transparent;border:0;font-size:20px}

    /* HERO */
    .hero{
      display:grid;
      grid-template-columns:1fr 420px;
      gap:32px;
      align-items:center;
      padding:48px 0 36px;
    }
    .hero-left h1{font-size:34px;margin:0 0 12px;line-height:1.05}
    .hero-left p{color:var(--muted);margin:0 0 22px}
    .cards{display:flex;gap:12px;flex-wrap:wrap}
    .card{background:#fff;padding:14px;border-radius:14px;box-shadow:var(--shadow);min-width:160px}
    .hero-right{
      background:linear-gradient(180deg,rgba(255,255,255,0.9),#fff);
      padding:22px;border-radius:14px;box-shadow:var(--shadow);
    }

    /* FEATURES */
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin:26px 0}
    .feature{background:#fff;padding:20px;border-radius:12px;box-shadow:var(--shadow)}
    .feature h4{margin:0 0 8px;font-size:16px}

    /* SERVICES */
    .services{display:grid;grid-template-columns:repeat(2,1fr);gap:18px;margin:28px 0}
    .service{background:linear-gradient(180deg,#fff,#fbfdff);padding:18px;border-radius:12px;box-shadow:var(--shadow)}

    /* TESTIMONIALS */
    .testimonials{display:flex;gap:12px;overflow:auto;padding-bottom:6px}
    .testimonial{min-width:260px;background:#fff;padding:16px;border-radius:12px;box-shadow:var(--shadow)}

    /* PRICING */
    .pricing{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:30px 0}
    .price{background:#fff;padding:20px;border-radius:12px;box-shadow:var(--shadow);display:flex;flex-direction:column;gap:10px}
    .price .price-amt{font-size:22px;font-weight:700;color:var(--accent)}

    /* ABOUT / CONTACT */
    footer{margin-top:36px;border-top:1px solid rgba(15,23,36,0.04);padding-top:26px;color:var(--muted)}
    form{display:flex;flex-direction:column;gap:10px}
    input,textarea,select{padding:12px;border-radius:10px;border:1px solid rgba(15,23,36,0.06);font-size:15px}
    textarea{min-height:120px;resize:vertical}
    .muted{color:var(--muted);font-size:13px}

    /* Responsive */
    @media (max-width:980px){
      .hero{grid-template-columns:1fr; padding:28px 0}
      .features{grid-template-columns:repeat(2,1fr)}
      .services{grid-template-columns:1fr}
      .pricing{grid-template-columns:1fr}
      nav ul{display:none}
      .mobile-toggle{display:block}
    }
    @media (max-width:520px){
      .features{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <header>
    <div class="container nav" aria-label="Top navigation">
      <div class="brand">
        <div class="logo" aria-hidden="true">AC</div>
        <div>
          <div style="font-weight:700">Acme Consulting</div>
          <div class="muted" style="font-size:13px">Growth • Marketing • Ops</div>
        </div>
      </div>

      <nav aria-label="Primary">
        <button class="mobile-toggle" id="navToggle" aria-label="Toggle menu">☰</button>
        <ul id="navList">
          <li><a href="#services">Services</a></li>
          <li><a href="#pricing">Pricing</a></li>
          <li><a href="#testimonials">Proof</a></li>
          <li><a href="#contact" class="btn">Get a Quote</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container" id="top">
    <!-- HERO -->
    <section class="hero" aria-labelledby="hero-heading">
      <div class="hero-left">
        <h1 id="hero-heading">Results-driven marketing & operations for growing businesses</h1>
        <p>We design plug-and-play campaigns, convertible content, and growth systems that bring more leads and higher lifetime value — without hiring a giant team.</p>
        <div style="display:flex;gap:12px;align-items:center">
          <a href="#contact" class="btn">Request a Quote</a>
          <a href="#services" style="padding:10px 14px;border-radius:10px;border:1px solid rgba(15,23,36,0.06);text-decoration:none;font-weight:600">See Services</a>
        </div>

        <div style="margin-top:22px" class="cards" aria-hidden="true">
          <div class="card"><strong>Average ROI</strong><div class="muted" style="font-size:13px">5–12x within 90 days</div></div>
          <div class="card"><strong>Avg. Client LTV</strong><div class="muted" style="font-size:13px">$6,200</div></div>
          <div class="card"><strong>Fast setup</strong><div class="muted" style="font-size:13px">Launch in 7 days</div></div>
        </div>
      </div>

      <aside class="hero-right" aria-label="Quick Quote">
        <h3 style="margin-top:0">Quick Quote</h3>
        <p class="muted" style="margin-bottom:8px">Tell us the service you need — we’ll reply within 24 hours.</p>
        <form id="quoteForm" action="https://formspree.io/f/{your-id}" method="POST" onsubmit="submitQuote(event)">
          <input name="name" type="text" placeholder="Your full name" required>
          <input name="email" type="email" placeholder="Email address" required>
          <select name="service" aria-label="Service">
            <option value="social">Social Media Ads</option>
            <option value="content">Content & Creatives</option>
            <option value="growth">Growth Ops</option>
            <option value="consult">Consultation</option>
          </select>
          <textarea name="message" placeholder="Brief project details (optional)"></textarea>
          <div style="display:flex;gap:8px">
            <button type="submit" class="btn">Send Request</button>
            <button type="button" onclick="copyEmail()" style="padding:10px;border-radius:10px;border:1px solid rgba(15,23,36,0.06);background:#fff">Email</button>
          </div>
          <div class="muted" style="margin-top:8px;font-size:13px">Or email us at <span id="emailText">hello@yourdomain.com</span></div>
        </form>
      </aside>
    </section>

    <!-- FEATURES -->
    <section id="services" aria-labelledby="services-heading">
      <h2 id="services-heading">What we do</h2>
      <div class="features" role="list">
        <div class="feature" role="listitem">
          <h4>Paid Media That Scales</h4>
          <p class="muted">Performance-first ad campaigns on Facebook, TikTok & Google — creative + optimization in one package.</p>
        </div>
        <div class="feature" role="listitem">
          <h4>Content Systems</h4>
          <p class="muted">Repurpose pillars: 1 long-form idea → 12 short posts, reels, and emails.</p>
        </div>
        <div class="feature" role="listitem">
          <h4>Conversion Ops</h4>
          <p class="muted">Landing pages, funnels, and automations that turn clicks into customers.</p>
        </div>
      </div>
    </section>

    <!-- SERVICES / OFFERINGS -->
    <section aria-labelledby="offer-heading">
      <h2 id="offer-heading">Core packages</h2>
      <div class="services">
        <div class="service">
          <h3>Starter</h3>
          <p class="muted">Perfect for early-stage teams. Setup + 30 days of creatives.</p>
          <ul class="muted">
            <li>Ad creative + 1 campaign</li>
            <li>Landing page template</li>
            <li>Weekly reporting</li>
          </ul>
          <div style="margin-top:auto"><strong class="price-amt">$2,500</strong></div>
        </div>

        <div class="service">
          <h3>Growth</h3>
          <p class="muted">For businesses ready to scale customer acquisition.</p>
          <ul class="muted">
            <li>Multi-channel ads</li>
            <li>Content pipeline (8 posts/week)</li>
            <li>Conversion rate optimization</li>
          </ul>
          <div style="margin-top:auto"><strong class="price-amt">$6,000</strong></div>
        </div>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section id="testimonials" aria-labelledby="testi-heading">
      <h2 id="testi-heading">Proof</h2>
      <div class="testimonials" role="list">
        <div class="testimonial" role="listitem">
          <p>“We doubled lead flow in 45 days — the team handled creative and scaling.”</p>
          <div class="muted">— J. Miller, CEO</div>
        </div>
        <div class="testimonial" role="listitem">
          <p>“Best onboarding experience. Clear ROI and steady improvement.”</p>
          <div class="muted">— S. Roy, Founder</div>
        </div>
        <div class="testimonial" role="listitem">
          <p>“Hands-on, expert guidance. Worth every penny.”</p>
          <div class="muted">— D. Chen, CMO</div>
        </div>
      </div>
    </section>

    <!-- PRICING -->
    <section id="pricing" aria-labelledby="pricing-heading">
      <h2 id="pricing-heading">Transparent pricing</h2>
      <div class="pricing">
        <div class="price">
          <h4>Consult</h4>
          <div class="price-amt">$350</div>
          <p class="muted">One-time 60-minute strategy call and action plan.</p>
          <a class="btn" href="#contact">Book Call</a>
        </div>
        <div class="price">
          <h4>Execution</h4>
          <div class="price-amt">$2,500</div>
          <p class="muted">Launch + 30 days management. Ideal for proof-of-concept.</p>
          <a class="btn" href="#contact">Start Project</a>
        </div>
        <div class="price">
          <h4>Retainer</h4>
          <div class="price-amt">$6,000/mo</div>
          <p class="muted">Full-funnel management and unlimited creative revisions.</p>
          <a class="btn" href="#contact">Apply</a>
        </div>
      </div>
    </section>

    <!-- ABOUT & CONTACT -->
    <section aria-labelledby="about-heading" style="margin-top:18px;display:grid;grid-template-columns:1fr 420px;gap:24px;align-items:start">
      <div>
        <h2 id="about-heading">About Acme</h2>
        <p class="muted">We’re a compact team of marketers, designers, and operators who build high-converting campaigns for ambitious companies. We prioritize measurable outcomes, clarity, and speed.</p>

        <h3>How we work</h3>
        <ul class="muted">
          <li>Week 0: Strategy & setup</li>
          <li>Week 1–2: Launch creatives & test</li>
          <li>Ongoing: Optimize, scale, and report</li>
        </ul>
      </div>

      <aside id="contact" style="background:linear-gradient(180deg, #fff, #fbfdff);padding:18px;border-radius:12px;box-shadow:var(--shadow)">
        <h3>Contact</h3>
        <form action="https://formspree.io/f/{your-id}" method="POST">
          <input name="name" type="text" placeholder="Name" required>
          <input name="email" type="email" placeholder="Email" required>
          <input name="company" placeholder="Company (optional)">
          <textarea name="message" placeholder="Tell us what you need" required></textarea>
          <button type="submit" class="btn">Send message</button>
        </form>
        <div class="muted" style="margin-top:12px;font-size:13px">
          Or email: <a href="mailto:hello@yourdomain.com">hello@yourdomain.com</a><br>
          Phone: +1 (555) 555‑5555
        </div>
      </aside>
    </section>

    <footer class="container">
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
        <div class="muted">© <span id="year"></span> Acme Consulting — Built for results</div>
        <div style="display:flex;gap:12px">
          <a href="#" class="muted">Privacy</a>
          <a href="#" class="muted">Terms</a>
          <a href="#" class="muted">Careers</a>
        </div>
      </div>
    </footer>
  </main>

  <script>
    // Small JS utilities: nav toggle, form feedback, copy email
    document.getElementById('year').textContent = new Date().getFullYear();

    const navToggle = document.getElementById('navToggle');
    const navList = document.getElementById('navList');
    navToggle && navToggle.addEventListener('click', () => {
      const shown = navList.style.display === 'flex';
      navList.style.display = shown ? 'none' : 'flex';
      navList.style.flexDirection = 'column';
      navList.style.gap = '12px';
      navList.style.position = 'absolute';
      navList.style.right = '20px';
      navList.style.top = '64px';
      navList.style.background = 'rgba(255,255,255,0.98)';
      navList.style.padding = '12px';
      navList.style.borderRadius = '10px';
      navList.style.boxShadow = '0 10px 30px rgba(16,24,40,0.08)';
    });

    function copyEmail(){
      const email = document.getElementById('emailText').textContent;
      navigator.clipboard?.writeText(email).then(()=>alert('Email copied to clipboard'));
    }

    // Quick UX: intercept form to show quick feedback (replace action with your endpoint)
    function submitQuote(e){
      // let the form submit (if using Formspree) — but show a quick friendly alert
      e.preventDefault();
      const form = e.target;
      const data = new FormData(form);
      fetch(form.action, {
        method: 'POST',
        body: data,
        headers:{'Accept':'application/json'}
      }).then(r => {
        if(r.ok){
          alert('Request sent — we will reply within 24 hours.');
          form.reset();
        } else {
          alert('There was an issue sending your request. You can email hello@yourdomain.com');
        }
      }).catch(()=>alert('Network error — try emailing hello@yourdomain.com'));
    }
  </script>
</body>
</html>
