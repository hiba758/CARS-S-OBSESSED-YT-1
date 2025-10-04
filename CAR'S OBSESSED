<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CAR's_obsessed — Ad</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent1:#ff4d4d;
      --accent2:#ffbf00;
      --glass: rgba(255,255,255,0.04);
      --text:#e6eef8;
      --muted:#9fb0c8;
      --radius:16px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      background:
        radial-gradient(circle at 10% 10%, rgba(255,200,0,0.06), transparent 10%),
        linear-gradient(180deg, rgba(8,10,12,1) 0%, rgba(14,19,29,1) 100%);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:24px;
    }

    .card {
      width:100%;
      max-width:760px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);
      padding:28px;
      box-shadow: 0 10px 30px rgba(2,6,23,0.6), inset 0 1px 0 rgba(255,255,255,0.02);
      border: 1px solid rgba(255,255,255,0.03);
      backdrop-filter: blur(6px);
    }

    .header-row{
      display:flex;
      align-items:center;
      gap:14px;
      margin-bottom:12px;
    }
    .logo {
      display:inline-grid;
      place-items:center;
      width:64px;
      height:64px;
      border-radius:12px;
      background: linear-gradient(135deg, rgba(255,77,77,0.14), rgba(255,191,0,0.08));
      border: 1px solid rgba(255,255,255,0.03);
      font-weight:700;
      font-size:20px;
      color:var(--text);
      box-shadow: 0 6px 18px rgba(0,0,0,0.5);
    }

    h1{
      font-size:20px;
      margin:0;
      line-height:1.05;
      letter-spacing: -0.2px;
      display:flex;
      align-items:center;
      gap:8px;
    }
    .subtitle{
      color:var(--muted);
      font-size:14px;
      margin-top:6px;
    }

    .content{
      margin-top:18px;
      line-height:1.6;
      font-size:16px;
    }

    .features{
      margin-top:12px;
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:10px 14px;
    }
    .feature{
      display:flex;
      gap:10px;
      align-items:flex-start;
      background: var(--glass);
      padding:10px;
      border-radius:10px;
      border:1px solid rgba(255,255,255,0.02);
    }
    .feature .emoji{
      font-size:20px;
      margin-top:2px;
      width:30px;
      text-align:center;
    }
    .feature .text{
      font-size:15px;
      color:var(--text);
    }
    .cta-row{
      margin-top:18px;
      display:flex;
      gap:12px;
      align-items:center;
      flex-wrap:wrap;
    }

    .subscribe-btn{
      display:inline-flex;
      align-items:center;
      gap:10px;
      padding:10px 16px;
      background: linear-gradient(90deg,var(--accent1),var(--accent2));
      color:#081018;
      font-weight:700;
      border-radius:12px;
      border:none;
      cursor:pointer;
      box-shadow: 0 8px 20px rgba(255,120,60,0.12);
      transition: transform .14s ease, box-shadow .14s ease;
      text-decoration:none;
    }
    .subscribe-btn:active{ transform: translateY(1px) scale(.998); }
    .subscribe-btn:hover{ transform: translateY(-2px); box-shadow: 0 12px 30px rgba(255,120,60,0.16); }

    .bell{
      width:36px;
      height:36px;
      display:inline-grid;
      place-items:center;
      border-radius:10px;
      background: rgba(255,255,255,0.03);
      border:1px solid rgba(255,255,255,0.02);
      cursor:pointer;
    }
    .meta{
      color:var(--muted);
      font-size:14px;
    }

    .small{
      font-size:13px;
      color:var(--muted);
      margin-top:10px;
    }

    /* BMW section */
    .car-showcase {
      margin-top: 32px;
      background: var(--glass);
      border-radius: var(--radius);
      padding: 16px;
      border: 1px solid rgba(255,255,255,0.05);
      overflow: hidden;
    }
    .car-showcase h2 {
      font-size: 18px;
      margin-top: 0;
      display:flex;
      align-items:center;
      gap:8px;
      color: var(--accent2);
    }
    .car-image {
      width: 100%;
      border-radius: 12px;
      margin-top: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .car-image:hover {
      transform: scale(1.03);
      box-shadow: 0 8px 20px rgba(0,0,0,0.4);
    }
    .car-desc {
      margin-top: 10px;
      color: var(--muted);
      font-size: 15px;
      line-height: 1.5;
    }

    @media (max-width:560px){
      .features{ grid-template-columns: 1fr; }
      .card{ padding:18px; }
    }

    .pulse { animation: pulse 2.2s infinite; }
    @keyframes pulse{
      0%{ transform: scale(1); opacity:1; }
      50%{ transform: scale(1.04); opacity:0.92; }
      100%{ transform: scale(1); opacity:1; }
    }
    .ring {
      transform-origin: center bottom;
      animation: ring 1s ease-in-out;
    }
    @keyframes ring {
      0% { transform: rotate(0deg); }
      15% { transform: rotate(-18deg); }
      30% { transform: rotate(12deg); }
      45% { transform: rotate(-8deg); }
      60% { transform: rotate(6deg); }
      75% { transform: rotate(-4deg); }
      100% { transform: rotate(0deg); }
    }
  </style>
</head>
<body>
  <main class="card" role="main" aria-labelledby="ad-title">
    <div class="header-row">
      <div class="logo">🔥</div>
      <div>
        <h1 id="ad-title">🚗 Welcome to <span style="color:var(--accent2);">🔥CAR's_obsessed🔥</span>! 🏎️</h1>
        <div class="subtitle">@Hibzz.M — Auto passion, reimagined</div>
      </div>
    </div>

    <div class="content">
      <p>Are you ready for <strong>thrilling rides, roaring engines,</strong> and <strong>non-stop car passion</strong>?  
      Join the <strong>#CarFam</strong> today for:</p>

      <div class="features">
        <div class="feature"><div class="emoji">🏁</div><div class="text"><strong>Epic car reviews</strong> &amp; test drives</div></div>
        <div class="feature"><div class="emoji">😎</div><div class="text"><strong>Luxury, vintage</strong> &amp; supercar features</div></div>
        <div class="feature"><div class="emoji">🎥</div><div class="text"><strong>Cinematic edits, engine sounds</strong> &amp; auto vibes</div></div>
        <div class="feature"><div class="emoji">💨</div><div class="text"><strong>Tips, facts</strong> &amp; behind-the-wheel moments</div></div>
      </div>

      <div class="cta-row">
        <a class="subscribe-btn" id="subscribeBtn" href="https://www.youtube.com/@Hibzz.M" target="_blank" rel="noopener noreferrer">
          Subscribe
        </a>
        <div class="bell" id="bellBtn">🔔</div>
        <div class="meta">✨ Hit the bell — don’t miss the next rev!</div>
      </div>

      <div class="small">🔥 Let’s ride together — only on <strong>@Hibzz.M</strong> | <em>CAR's_obsessed</em> 🚘💪</div>
    </div>

    <!-- BMW showcase section -->
    <section class="car-showcase">
      <h2>🚘 Sample Car Feature: BMW M4 Competition</h2>
      <img class="car-image" src="https://cdn.bmwblog.com/wp-content/uploads/2021/03/BMW-M4-Competition-F82-Exterior-18.jpg" alt="BMW M4 Competition">
      <p class="car-desc">
        The BMW M4 Competition — where elegance meets aggression. With a 3.0L Twin-Turbo inline-six engine delivering 503 horsepower, 
        it’s a perfect blend of performance and luxury. Watch its detailed review and hear that *signature BMW roar* on our channel! 🔥
      </p>
    </section>

  </main>

  <script>
    const bellBtn = document.getElementById('bellBtn');
    bellBtn.addEventListener('click', () => {
      bellBtn.classList.remove('ring');
      void bellBtn.offsetWidth;
      bellBtn.classList.add('ring');
    });

    const subscribeBtn = document.getElementById('subscribeBtn');
    subscribeBtn.classList.add('pulse');
    setTimeout(() => subscribeBtn.classList.remove('pulse'), 3200);
  </script>
</body>
</html>
