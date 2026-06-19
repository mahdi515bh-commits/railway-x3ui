<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>railway_x3-ui — پنل X-UI روی Railway</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;700;900&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --blue-900: #042C53;
    --blue-800: #0C447C;
    --blue-600: #185FA5;
    --blue-400: #378ADD;
    --blue-200: #85B7EB;
    --blue-100: #B5D4F4;
    --blue-50:  #E6F1FB;
    --teal-600: #0F6E56;
    --teal-400: #1D9E75;
    --teal-50:  #E1F5EE;
    --amber-600: #854F0B;
    --amber-400: #BA7517;
    --amber-50: #FAEEDA;
    --red-600: #A32D2D;
    --red-50: #FCEBEB;
    --gray-900: #2C2C2A;
    --gray-600: #5F5E5A;
    --gray-200: #B4B2A9;
    --gray-100: #D3D1C7;
    --gray-50: #F1EFE8;
  }

  body {
    font-family: 'Vazirmatn', sans-serif;
    background: #0a0e1a;
    color: #e8eaf6;
    direction: rtl;
    line-height: 1.8;
    overflow-x: hidden;
  }

  /* ── HERO ── */
  .hero {
    position: relative;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 4rem 2rem;
    overflow: hidden;
  }

  .hero-bg {
    position: absolute; inset: 0;
    background: radial-gradient(ellipse at 50% 0%, #1a2a6c22 0%, transparent 70%),
                radial-gradient(ellipse at 80% 80%, #185FA511 0%, transparent 60%),
                radial-gradient(ellipse at 20% 60%, #0C447C11 0%, transparent 50%);
  }

  /* grid lines */
  .grid-lines {
    position: absolute; inset: 0;
    background-image:
      linear-gradient(rgba(55,138,221,.04) 1px, transparent 1px),
      linear-gradient(90deg, rgba(55,138,221,.04) 1px, transparent 1px);
    background-size: 60px 60px;
    animation: gridPulse 8s ease-in-out infinite;
  }
  @keyframes gridPulse {
    0%,100% { opacity: .6; }
    50%      { opacity: 1; }
  }

  /* floating particles */
  .particles { position: absolute; inset: 0; pointer-events: none; }
  .particle {
    position: absolute;
    width: 3px; height: 3px;
    border-radius: 50%;
    background: var(--blue-400);
    animation: float linear infinite;
    opacity: 0;
  }
  @keyframes float {
    0%   { transform: translateY(100vh) translateX(0) scale(0); opacity: 0; }
    10%  { opacity: .7; }
    90%  { opacity: .7; }
    100% { transform: translateY(-20vh) translateX(var(--dx)) scale(1); opacity: 0; }
  }

  /* logo ring */
  .logo-wrap {
    position: relative;
    margin-bottom: 2rem;
    animation: logoEntrance .8s cubic-bezier(.22,1,.36,1) both;
  }
  @keyframes logoEntrance {
    from { transform: scale(.4) rotate(-20deg); opacity: 0; }
    to   { transform: scale(1) rotate(0deg);    opacity: 1; }
  }
  .logo-ring {
    width: 120px; height: 120px;
    border-radius: 50%;
    background: linear-gradient(135deg, #185FA5, #0C447C);
    display: flex; align-items: center; justify-content: center;
    font-size: 3rem; font-weight: 900; color: #fff;
    position: relative;
    box-shadow: 0 0 60px rgba(55,138,221,.35);
    animation: ringPulse 3s ease-in-out infinite;
  }
  @keyframes ringPulse {
    0%,100% { box-shadow: 0 0 40px rgba(55,138,221,.3); }
    50%      { box-shadow: 0 0 80px rgba(55,138,221,.6); }
  }
  .logo-ring::before {
    content: '';
    position: absolute; inset: -8px;
    border-radius: 50%;
    border: 2px solid rgba(55,138,221,.3);
    animation: spin 8s linear infinite;
  }
  .logo-ring::after {
    content: '';
    position: absolute; inset: -16px;
    border-radius: 50%;
    border: 1px dashed rgba(55,138,221,.15);
    animation: spin 16s linear infinite reverse;
  }
  @keyframes spin { to { transform: rotate(360deg); } }

  .hero-title {
    font-size: clamp(2.2rem, 6vw, 4rem);
    font-weight: 900;
    background: linear-gradient(135deg, #fff 0%, var(--blue-200) 50%, var(--blue-400) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: .75rem;
    animation: titleSlide .9s cubic-bezier(.22,1,.36,1) .2s both;
  }
  @keyframes titleSlide {
    from { transform: translateY(30px); opacity: 0; }
    to   { transform: translateY(0);    opacity: 1; }
  }

  .hero-sub {
    font-size: 1.15rem;
    color: var(--blue-200);
    max-width: 600px;
    margin: 0 auto 2.5rem;
    animation: titleSlide .9s cubic-bezier(.22,1,.36,1) .35s both;
  }

  /* badges */
  .badges {
    display: flex; flex-wrap: wrap; gap: .6rem;
    justify-content: center;
    margin-bottom: 2.5rem;
    animation: titleSlide .9s cubic-bezier(.22,1,.36,1) .5s both;
  }
  .badge {
    padding: .35rem .9rem;
    border-radius: 100px;
    font-size: .8rem;
    font-weight: 500;
    border: 1px solid;
    transition: transform .2s, box-shadow .2s;
  }
  .badge:hover { transform: translateY(-2px); }
  .badge-blue   { background: rgba(55,138,221,.1); border-color: rgba(55,138,221,.4); color: var(--blue-200); }
  .badge-teal   { background: rgba(29,158,117,.1); border-color: rgba(29,158,117,.4); color: #5DCAA5; }
  .badge-amber  { background: rgba(186,117,23,.1);  border-color: rgba(186,117,23,.4);  color: #FAC775; }
  .badge-gray   { background: rgba(180,178,169,.08);border-color: rgba(180,178,169,.3); color: var(--gray-200); }

  /* scroll indicator */
  .scroll-cue {
    position: absolute; bottom: 2rem; left: 50%; transform: translateX(-50%);
    display: flex; flex-direction: column; align-items: center; gap: .4rem;
    color: rgba(255,255,255,.3); font-size: .75rem;
    animation: bounceY 2s ease-in-out infinite;
  }
  .scroll-cue svg { width: 20px; height: 20px; }
  @keyframes bounceY {
    0%,100% { transform: translateX(-50%) translateY(0); }
    50%      { transform: translateX(-50%) translateY(8px); }
  }

  /* ── SECTIONS ── */
  section { max-width: 900px; margin: 0 auto; padding: 5rem 2rem; }

  .section-label {
    font-size: .75rem; font-weight: 700; letter-spacing: .15em;
    text-transform: uppercase; color: var(--blue-400);
    margin-bottom: .5rem;
  }
  .section-title {
    font-size: 2rem; font-weight: 700;
    background: linear-gradient(135deg, #fff, var(--blue-200));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
    margin-bottom: 1rem;
  }
  .section-desc { color: rgba(255,255,255,.55); font-size: 1rem; max-width: 560px; }

  /* divider */
  .divider {
    width: 100%; height: 1px;
    background: linear-gradient(90deg, transparent, rgba(55,138,221,.3), transparent);
    margin: 0 auto;
  }

  /* ── ABOUT CARD ── */
  .about-card {
    margin-top: 3rem;
    background: linear-gradient(135deg, rgba(24,95,165,.12), rgba(12,68,124,.06));
    border: 1px solid rgba(55,138,221,.18);
    border-radius: 20px;
    padding: 2.5rem;
    position: relative;
    overflow: hidden;
    animation: fadeUp .6s ease both;
  }
  @keyframes fadeUp {
    from { transform: translateY(24px); opacity: 0; }
    to   { transform: translateY(0);    opacity: 1; }
  }
  .about-card::before {
    content: '';
    position: absolute; top: 0; right: 0;
    width: 200px; height: 200px;
    background: radial-gradient(circle, rgba(55,138,221,.12), transparent 70%);
    pointer-events: none;
  }
  .about-card p { color: rgba(255,255,255,.7); line-height: 2; margin-bottom: .75rem; }
  .about-card p:last-child { margin-bottom: 0; }
  .highlight { color: var(--blue-200); font-weight: 600; }

  /* ── FILE TREE ── */
  .file-tree {
    background: rgba(10,14,26,.9);
    border: 1px solid rgba(55,138,221,.15);
    border-radius: 16px;
    overflow: hidden;
    margin-top: 2rem;
  }
  .file-tree-header {
    background: rgba(55,138,221,.08);
    padding: .75rem 1.25rem;
    display: flex; align-items: center; gap: .5rem;
    border-bottom: 1px solid rgba(55,138,221,.12);
  }
  .dot { width: 12px; height: 12px; border-radius: 50%; }
  .dot-r { background: #ff5f57; }
  .dot-y { background: #febc2e; }
  .dot-g { background: #28c840; }
  .file-tree-body { padding: 1.25rem 1.5rem; font-family: monospace; font-size: .9rem; line-height: 2.2; }
  .tree-dir  { color: var(--blue-300, #6fa8dc); font-weight: 600; }
  .tree-file { color: rgba(255,255,255,.65); }
  .tree-line { color: rgba(55,138,221,.3); }
  .tree-comment { color: rgba(255,255,255,.3); font-style: italic; }

  /* ── STEPS ── */
  .steps-grid { display: flex; flex-direction: column; gap: 2rem; margin-top: 3rem; }

  .step-card {
    background: rgba(255,255,255,.03);
    border: 1px solid rgba(55,138,221,.12);
    border-radius: 20px;
    padding: 2rem;
    position: relative;
    overflow: hidden;
    transition: border-color .3s, background .3s, transform .3s;
    animation: fadeUp .6s ease both;
  }
  .step-card:hover {
    border-color: rgba(55,138,221,.4);
    background: rgba(55,138,221,.05);
    transform: translateY(-3px);
  }
  .step-card::before {
    content: '';
    position: absolute; top: 0; right: 0; bottom: 0; width: 3px;
    background: linear-gradient(180deg, var(--blue-400), var(--teal-400));
    border-radius: 0 20px 20px 0;
  }

  .step-num {
    display: inline-flex; align-items: center; justify-content: center;
    width: 44px; height: 44px; border-radius: 12px;
    background: linear-gradient(135deg, var(--blue-600), var(--blue-800));
    color: #fff; font-weight: 700; font-size: 1.1rem;
    margin-bottom: 1rem;
    box-shadow: 0 4px 20px rgba(24,95,165,.4);
    animation: numBounce .5s cubic-bezier(.34,1.56,.64,1) both;
  }
  @keyframes numBounce {
    from { transform: scale(0) rotate(-20deg); opacity: 0; }
    to   { transform: scale(1) rotate(0);      opacity: 1; }
  }

  .step-title { font-size: 1.15rem; font-weight: 700; color: #fff; margin-bottom: .5rem; }
  .step-desc  { color: rgba(255,255,255,.55); font-size: .95rem; line-height: 1.9; }

  /* tip box inside step */
  .tip-box {
    margin-top: 1rem;
    background: rgba(29,158,117,.08);
    border: 1px solid rgba(29,158,117,.25);
    border-radius: 10px;
    padding: .75rem 1rem;
    font-size: .88rem;
    color: #5DCAA5;
    display: flex; align-items: flex-start; gap: .6rem;
  }
  .tip-icon { flex-shrink: 0; margin-top: 2px; }

  /* warn box */
  .warn-box {
    margin-top: 1rem;
    background: rgba(186,117,23,.08);
    border: 1px solid rgba(186,117,23,.25);
    border-radius: 10px;
    padding: .75rem 1rem;
    font-size: .88rem;
    color: #FAC775;
    display: flex; align-items: flex-start; gap: .6rem;
  }

  /* step connector line */
  .step-connector {
    display: flex; justify-content: center;
    height: 2.5rem; position: relative;
  }
  .step-connector::before {
    content: '';
    position: absolute; top: 0; left: 50%;
    width: 2px; height: 100%;
    background: linear-gradient(180deg, rgba(55,138,221,.4), rgba(55,138,221,.1));
  }
  .step-connector-dot {
    width: 8px; height: 8px; border-radius: 50%;
    background: var(--blue-400);
    align-self: center;
    position: relative; z-index: 1;
    animation: dotPulse 1.5s ease-in-out infinite;
  }
  @keyframes dotPulse {
    0%,100% { box-shadow: 0 0 0 0 rgba(55,138,221,.5); }
    50%      { box-shadow: 0 0 0 6px rgba(55,138,221,0); }
  }

  /* code block */
  .code-block {
    background: rgba(0,0,0,.6);
    border: 1px solid rgba(55,138,221,.15);
    border-radius: 10px;
    padding: 1rem 1.25rem;
    font-family: monospace;
    font-size: .88rem;
    color: #85B7EB;
    margin-top: .75rem;
    overflow-x: auto;
    direction: ltr; text-align: left;
    position: relative;
  }
  .code-block .key   { color: #FAC775; }
  .code-block .val   { color: #5DCAA5; }
  .code-block .cmt   { color: rgba(255,255,255,.3); }

  /* copy btn */
  .copy-btn {
    position: absolute; top: .6rem; left: .6rem;
    background: rgba(55,138,221,.15);
    border: 1px solid rgba(55,138,221,.3);
    border-radius: 6px;
    color: var(--blue-200);
    font-size: .75rem; padding: .25rem .6rem;
    cursor: pointer;
    transition: background .2s;
  }
  .copy-btn:hover { background: rgba(55,138,221,.3); }

  /* ── TECH TABLE ── */
  .tech-table-wrap {
    margin-top: 2.5rem;
    border: 1px solid rgba(55,138,221,.15);
    border-radius: 16px;
    overflow: hidden;
  }
  .tech-table { width: 100%; border-collapse: collapse; }
  .tech-table th {
    background: rgba(55,138,221,.1);
    padding: .85rem 1.25rem;
    text-align: right;
    font-size: .8rem; font-weight: 600;
    color: var(--blue-200);
    letter-spacing: .08em;
    border-bottom: 1px solid rgba(55,138,221,.15);
  }
  .tech-table td {
    padding: .85rem 1.25rem;
    font-size: .9rem;
    color: rgba(255,255,255,.7);
    border-bottom: 1px solid rgba(255,255,255,.04);
  }
  .tech-table tr:last-child td { border-bottom: none; }
  .tech-table tr:hover td { background: rgba(55,138,221,.05); }
  .tech-pill {
    display: inline-flex; align-items: center; gap: .4rem;
    background: rgba(55,138,221,.12);
    border: 1px solid rgba(55,138,221,.25);
    border-radius: 100px;
    padding: .2rem .75rem;
    font-size: .8rem; color: var(--blue-200);
  }

  /* ── CLIENTS ── */
  .clients-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.25rem;
    margin-top: 2.5rem;
  }
  .client-card {
    background: rgba(255,255,255,.03);
    border: 1px solid rgba(255,255,255,.08);
    border-radius: 16px;
    padding: 1.5rem;
    text-align: center;
    transition: all .3s;
    cursor: pointer;
    text-decoration: none;
  }
  .client-card:hover {
    background: rgba(55,138,221,.08);
    border-color: rgba(55,138,221,.35);
    transform: translateY(-4px);
    box-shadow: 0 12px 40px rgba(24,95,165,.2);
  }
  .client-icon {
    font-size: 2.2rem; margin-bottom: .75rem;
    display: block;
    animation: iconFloat 3s ease-in-out infinite;
  }
  @keyframes iconFloat {
    0%,100% { transform: translateY(0); }
    50%      { transform: translateY(-6px); }
  }
  .client-name  { font-weight: 600; color: #fff; font-size: .95rem; margin-bottom: .25rem; }
  .client-plat  { font-size: .78rem; color: rgba(255,255,255,.4); }

  /* ── FAQ ── */
  .faq-list { margin-top: 2.5rem; display: flex; flex-direction: column; gap: 1rem; }
  .faq-item {
    background: rgba(255,255,255,.03);
    border: 1px solid rgba(255,255,255,.07);
    border-radius: 14px;
    overflow: hidden;
    transition: border-color .3s;
  }
  .faq-item:hover { border-color: rgba(55,138,221,.3); }
  .faq-q {
    padding: 1.1rem 1.5rem;
    font-weight: 600; font-size: .95rem; color: #fff;
    cursor: pointer;
    display: flex; justify-content: space-between; align-items: center;
    gap: 1rem;
    user-select: none;
  }
  .faq-arrow {
    flex-shrink: 0;
    width: 20px; height: 20px;
    border-radius: 50%;
    background: rgba(55,138,221,.15);
    display: flex; align-items: center; justify-content: center;
    transition: transform .3s, background .3s;
    color: var(--blue-200);
    font-size: .7rem;
  }
  .faq-item.open .faq-arrow { transform: rotate(180deg); background: rgba(55,138,221,.3); }
  .faq-a {
    max-height: 0; overflow: hidden;
    transition: max-height .4s ease, padding .3s;
    padding: 0 1.5rem;
    color: rgba(255,255,255,.55); font-size: .9rem; line-height: 1.9;
  }
  .faq-item.open .faq-a { max-height: 200px; padding: 0 1.5rem 1.1rem; }

  /* ── SECURITY ── */
  .security-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.25rem;
    margin-top: 2.5rem;
  }
  .sec-card {
    background: rgba(163,45,45,.04);
    border: 1px solid rgba(163,45,45,.15);
    border-radius: 16px;
    padding: 1.5rem;
    transition: all .3s;
  }
  .sec-card:hover {
    background: rgba(163,45,45,.08);
    border-color: rgba(163,45,45,.35);
    transform: translateY(-3px);
  }
  .sec-icon { font-size: 1.8rem; margin-bottom: .75rem; }
  .sec-title { font-weight: 700; color: #f09595; margin-bottom: .4rem; font-size: .95rem; }
  .sec-desc  { color: rgba(255,255,255,.5); font-size: .85rem; line-height: 1.8; }

  /* ── FOOTER ── */
  .footer {
    border-top: 1px solid rgba(55,138,221,.1);
    padding: 4rem 2rem;
    text-align: center;
  }
  .footer-star {
    display: inline-flex; align-items: center; gap: .5rem;
    background: linear-gradient(135deg, rgba(55,138,221,.15), rgba(29,158,117,.1));
    border: 1px solid rgba(55,138,221,.25);
    border-radius: 100px;
    padding: .6rem 1.5rem;
    color: #fff; font-size: .9rem; font-weight: 500;
    margin-bottom: 2rem;
    animation: starPulse 2s ease-in-out infinite;
    cursor: pointer;
    text-decoration: none;
  }
  @keyframes starPulse {
    0%,100% { box-shadow: 0 0 0 0 rgba(55,138,221,.3); }
    50%      { box-shadow: 0 0 20px 4px rgba(55,138,221,.2); }
  }
  .footer-text { color: rgba(255,255,255,.3); font-size: .85rem; }
  .footer-links { display: flex; justify-content: center; gap: 2rem; margin-top: 1.5rem; }
  .footer-link { color: rgba(255,255,255,.4); text-decoration: none; font-size: .85rem; transition: color .2s; }
  .footer-link:hover { color: var(--blue-200); }

  /* ── SCROLL REVEAL ── */
  .reveal { opacity: 0; transform: translateY(30px); transition: opacity .7s ease, transform .7s ease; }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* ── PROGRESS BAR ── */
  .progress-bar {
    position: fixed; top: 0; right: 0; left: 0; height: 3px;
    background: linear-gradient(90deg, var(--blue-600), var(--teal-400));
    transform-origin: right;
    transform: scaleX(0);
    z-index: 1000;
    transition: transform .1s;
  }
</style>
</head>
<body>

<div class="progress-bar" id="prog"></div>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg"></div>
  <div class="grid-lines"></div>
  <div class="particles" id="parts"></div>

  <div class="logo-wrap">
    <div class="logo-ring">X</div>
  </div>

  <h1 class="hero-title">railway_x3-ui</h1>
  <p class="hero-sub">اجرای پنل X-UI روی Railway — بدون VPS، بدون نصب دستی، در چند دقیقه آنلاین باش</p>

  <div class="badges">
    <span class="badge badge-blue">🐳 Docker Ready</span>
    <span class="badge badge-teal">⚡ 3X-UI v3.0.2</span>
    <span class="badge badge-amber">🏔️ Alpine 3.19</span>
    <span class="badge badge-gray">🚂 Railway</span>
    <span class="badge badge-blue">🔒 VLESS / XRay</span>
  </div>

  <div class="scroll-cue">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 9l6 6 6-6"/></svg>
    اسکرول کن
  </div>
</section>

<div class="divider"></div>

<!-- ABOUT -->
<section>
  <div class="reveal">
    <p class="section-label">درباره پروژه</p>
    <h2 class="section-title">این پروژه چیه؟</h2>
    <p class="section-desc">سریع‌ترین راه برای داشتن پنل پروکسی شخصی</p>

    <div class="about-card">
      <p>
        <span class="highlight">railway_x3-ui</span> به تو این امکان رو میده که پنل محبوب
        <span class="highlight">3X-UI</span> رو مستقیماً روی زیرساخت رایگان Railway اجرا کنی.
        نه VPS لازم داری، نه SSH، نه کانفیگ دستی.
      </p>
      <p>
        فقط یه <span class="highlight">Dockerfile</span> هوشمند، یه اسکریپت استارت، و یه فایل
        <span class="highlight">railway.toml</span> — همین‌قدر ساده.
        در کمتر از ۵ دقیقه پنلت آنلاینه و میتونی کانفیگ VLESS، VMess و... بسازی.
      </p>
    </div>

    <div class="file-tree reveal">
      <div class="file-tree-header">
        <div class="dot dot-r"></div><div class="dot dot-y"></div><div class="dot dot-g"></div>
        <span style="margin-right:.75rem; font-size:.85rem; color:rgba(255,255,255,.4);">ساختار پروژه</span>
      </div>
      <div class="file-tree-body">
        <div><span class="tree-dir">📁 railway_x3-ui/</span></div>
        <div><span class="tree-line">├── </span><span class="tree-file">🐳 Dockerfile</span> <span class="tree-comment">— ایمیج Alpine + X-UI</span></div>
        <div><span class="tree-line">├── </span><span class="tree-file">🚀 start.sh</span> <span class="tree-comment">— اسکریپت راه‌اندازی</span></div>
        <div><span class="tree-line">└── </span><span class="tree-file">⚙️ railway.toml</span> <span class="tree-comment">— تنظیمات دیپلوی</span></div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- STEPS -->
<section>
  <div class="reveal">
    <p class="section-label">راهنمای نصب</p>
    <h2 class="section-title">مراحل دیپلوی</h2>
    <p class="section-desc">از صفر تا آنلاین — گام به گام</p>
  </div>

  <div class="steps-grid">

    <!-- step 1 -->
    <div class="step-card reveal" style="animation-delay:.1s">
      <div class="step-num">۱</div>
      <div class="step-title">ساخت اکانت Railway</div>
      <div class="step-desc">
        به سایت <strong style="color:var(--blue-200)">railway.com</strong> برو.
        روی دکمه <em>Login</em> کلیک کن و گزینه <em>Login with GitHub</em> رو انتخاب کن.
        دسترسی رو تأیید کن — اکانتت آماده‌ست.
      </div>
      <div class="tip-box">
        <span class="tip-icon">✅</span>
        اگه هنوز اکانت گیت‌هاب نداری، اول روی github.com ثبت‌نام کن.
      </div>
    </div>

    <div class="step-connector"><div class="step-connector-dot"></div></div>

    <!-- step 2 -->
    <div class="step-card reveal" style="animation-delay:.15s">
      <div class="step-num">۲</div>
      <div class="step-title">فورک کردن و اضافه کردن به Railway</div>
      <div class="step-desc">
        این ریپو رو <strong style="color:var(--blue-200)">Fork</strong> کن تا یه کپی توی اکانت گیت‌هاب خودت داشته باشی.
        بعد توی Railway داشبورد، روی <em>+ New Project</em> کلیک کن،
        گزینه <em>Deploy from GitHub repo</em> رو بزن و ریپوی فورک‌شده رو انتخاب کن.
        Railway خودش Dockerfile رو شناسایی میکنه و بیلد رو شروع میکنه.
      </div>
      <div class="tip-box">
        <span class="tip-icon">⏳</span>
        صبر کن تا بیلد تموم بشه — معمولاً ۱ تا ۲ دقیقه طول میکشه.
      </div>
    </div>

    <div class="step-connector"><div class="step-connector-dot"></div></div>

    <!-- step 3 -->
    <div class="step-card reveal" style="animation-delay:.2s">
      <div class="step-num">۳</div>
      <div class="step-title">اضافه کردن دامنه پنل (پورت ۲۰۵۳)</div>
      <div class="step-desc">
        روی پروژه کلیک کن. از منوی بالا <em>Settings</em> رو انتخاب کن.
        در منوی سمت راست به بخش <em>Networking</em> برو.
        در قسمت <em>Public Networking</em> یه دامنه جنریت کن و پورت رو <strong style="color:var(--blue-200)">2053</strong> بذار.
        چند ثانیه صبر کن تا دامنه فعال بشه.
      </div>
      <div class="code-block">
        <button class="copy-btn" onclick="copyCode(this)">کپی</button>
        http://<span class="val">YOUR-DOMAIN</span>.up.railway.app:<span class="key">2053</span>
        <span class="cmt">  ← آدرس پنل شما</span>
      </div>
      <div class="tip-box">
        <span class="tip-icon">💡</span>
        این دامنه فقط برای پنل مدیریتیه — نه برای ترافیک پروکسی.
      </div>
    </div>

    <div class="step-connector"><div class="step-connector-dot"></div></div>

    <!-- step 4 -->
    <div class="step-card reveal" style="animation-delay:.25s">
      <div class="step-num">۴</div>
      <div class="step-title">ورود به پنل و ساخت کانفیگ</div>
      <div class="step-desc">
        آدرس پنلت رو توی مرورگر باز کن.
        با اطلاعات پیش‌فرض زیر وارد شو، بعد فوری پسوردت رو عوض کن!
        به قسمت <em>Inbounds</em> برو و یه اینباند جدید با پروتکل مورد نظرت اضافه کن.
      </div>
      <div class="code-block">
        <button class="copy-btn" onclick="copyCode(this)">کپی</button>
        <span class="key">Username:</span> <span class="val">admin</span>
        <span class="key">Password:</span> <span class="val">admin</span>
      </div>
      <div class="warn-box">
        <span>⚠️</span>
        بعد از اولین ورود، حتماً پسورد رو از Panel Settings عوض کن!
      </div>
    </div>

    <div class="step-connector"><div class="step-connector-dot"></div></div>

    <!-- step 5 -->
    <div class="step-card reveal" style="animation-delay:.3s">
      <div class="step-num">۵</div>
      <div class="step-title">اضافه کردن TCP Proxy برای ترافیک</div>
      <div class="step-desc">
        دوباره برو به Railway → <em>Settings</em> → <em>Networking</em>.
        این بار در بخش <em>TCP Proxy</em> روی <em>Add TCP Proxy</em> کلیک کن.
        پورت رو <strong style="color:var(--blue-200)">دقیقاً همون پورتی</strong> که برای اینباند تنظیم کردی بذار.
        Railway یه دامنه + پورت جدید بهت میده — این <strong style="color:#5DCAA5">دامنه ترافیکیه</strong>.
      </div>
      <div class="tip-box">
        <span class="tip-icon">🎯</span>
        حالا ۲ دامنه داری: یکی برای پنل، یکی برای عبور ترافیک.
      </div>
    </div>

    <div class="step-connector"><div class="step-connector-dot"></div></div>

    <!-- step 6 -->
    <div class="step-card reveal" style="animation-delay:.35s">
      <div class="step-num">۶</div>
      <div class="step-title">ویرایش کانفیگ با دامنه ترافیکی</div>
      <div class="step-desc">
        توی پنل، اینباند مورد نظرت رو ویرایش کن.
        در فیلد <em>Address</em> دامنه TCP Proxy رو وارد کن.
        در فیلد <em>Port</em> پورت TCP Proxy رو بذار.
        ذخیره کن و با دکمه QR Code یا Copy Link لینک نهاییت رو بگیر.
      </div>
      <div class="tip-box">
        <span class="tip-icon">🔗</span>
        کانفیگ نهایی رو کپی کن و توی کلاینتت وارد کن.
      </div>
    </div>

  </div>
</section>

<div class="divider"></div>

<!-- SPECS -->
<section>
  <div class="reveal">
    <p class="section-label">مشخصات فنی</p>
    <h2 class="section-title">جزئیات تکنیکال</h2>

    <div class="tech-table-wrap">
      <table class="tech-table">
        <thead>
          <tr>
            <th>کامپوننت</th>
            <th>مقدار</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>ایمیج پایه</td><td><span class="tech-pill">🏔️ alpine:3.19</span></td></tr>
          <tr><td>نسخه X-UI</td><td><span class="tech-pill">⚡ v3.0.2</span></td></tr>
          <tr><td>پورت پنل</td><td><span class="tech-pill">🖥️ 2053</span></td></tr>
          <tr><td>پورت ترافیک</td><td><span class="tech-pill">🌐 دلخواه (در اینباند)</span></td></tr>
          <tr><td>روش بیلد</td><td><span class="tech-pill">🐳 Dockerfile</span></td></tr>
          <tr><td>سیاست ری‌استارت</td><td><span class="tech-pill">🔄 always</span></td></tr>
          <tr><td>تایم‌زون</td><td><span class="tech-pill">🕐 Asia/Tehran</span></td></tr>
          <tr><td>دیتابیس</td><td><span class="tech-pill">🗄️ SQLite</span></td></tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- CLIENTS -->
<section>
  <div class="reveal">
    <p class="section-label">کلاینت‌ها</p>
    <h2 class="section-title">با چه نرم‌افزارهایی وصل بشیم؟</h2>

    <div class="clients-grid">
      <a class="client-card" href="https://github.com/2dust/v2rayNG" target="_blank">
        <span class="client-icon">📱</span>
        <div class="client-name">v2rayNG</div>
        <div class="client-plat">Android</div>
      </a>
      <a class="client-card" href="https://github.com/MatsuriDayo/nekoray" target="_blank">
        <span class="client-icon">🐱</span>
        <div class="client-name">Nekoray</div>
        <div class="client-plat">Windows / Linux</div>
      </a>
      <a class="client-card" href="https://github.com/hiddify/hiddify-next" target="_blank">
        <span class="client-icon">🌐</span>
        <div class="client-name">Hiddify</div>
        <div class="client-plat">همه پلتفرم‌ها</div>
      </a>
      <a class="client-card" href="https://apps.apple.com/app/foxray/id6448898396" target="_blank">
        <span class="client-icon">🦊</span>
        <div class="client-name">FoXray</div>
        <div class="client-plat">iOS / macOS</div>
      </a>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- SECURITY -->
<section>
  <div class="reveal">
    <p class="section-label">امنیت</p>
    <h2 class="section-title">نکات امنیتی مهم</h2>

    <div class="security-grid">
      <div class="sec-card reveal">
        <div class="sec-icon">🔐</div>
        <div class="sec-title">پسورد پیش‌فرض رو عوض کن</div>
        <div class="sec-desc">بعد از اولین ورود، فوری از Panel Settings پسورد و یوزرنیم رو تغییر بده.</div>
      </div>
      <div class="sec-card reveal" style="animation-delay:.1s">
        <div class="sec-icon">🎲</div>
        <div class="sec-title">UUID قوی استفاده کن</div>
        <div class="sec-desc">برای کانفیگ‌هات از UUID تصادفی استفاده کن — پنل خودش میتونه تولید کنه.</div>
      </div>
      <div class="sec-card reveal" style="animation-delay:.2s">
        <div class="sec-icon">👁️</div>
        <div class="sec-title">اتصالات رو چک کن</div>
        <div class="sec-desc">از داشبورد پنل مرتب اتصالات فعال رو بررسی کن و موارد ناشناس رو حذف کن.</div>
      </div>
      <div class="sec-card reveal" style="animation-delay:.3s">
        <div class="sec-icon">🚫</div>
        <div class="sec-title">اشتراک‌گذاری نکن</div>
        <div class="sec-desc">آدرس پنلت رو به کسی ندی — دسترسی به پنل = کنترل کامل.</div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- FAQ -->
<section>
  <div class="reveal">
    <p class="section-label">سوالات متداول</p>
    <h2 class="section-title">FAQ</h2>

    <div class="faq-list">
      <div class="faq-item">
        <div class="faq-q" onclick="toggleFaq(this)">
          آیا پلن رایگان Railway کافیه؟
          <span class="faq-arrow">▼</span>
        </div>
        <div class="faq-a">پلن رایگان Railway ساعت محدودی در ماه داره. برای استفاده پایدار و ۲۴/۷، پلن پولی ($5 در ماه) پیشنهاد میشه.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q" onclick="toggleFaq(this)">
          چرا به دو دامنه نیاز دارم؟
          <span class="faq-arrow">▼</span>
        </div>
        <div class="faq-a">یه دامنه برای پنل مدیریتیه (HTTP) و یه دامنه برای عبور ترافیک پروکسی (TCP). جداسازی این دو، پایداری و امنیت رو بالا میبره.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q" onclick="toggleFaq(this)">
          آیا میتونم دامنه شخصی اضافه کنم؟
          <span class="faq-arrow">▼</span>
        </div>
        <div class="faq-a">بله! در بخش Networking می‌تونی دامنه دلخواه خودت رو به جای دامنه پیش‌فرض railway.app اضافه کنی.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q" onclick="toggleFaq(this)">
          پنل لود نمیشه — چیکار کنم؟
          <span class="faq-arrow">▼</span>
        </div>
        <div class="faq-a">تب Logs در Railway رو چک کن. مطمئن شو پورت 2053 درست در بخش Networking مپ شده. اگه بیلد ارور داشته، لاگ بیلد رو هم ببین.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q" onclick="toggleFaq(this)">
          آیا پروتکل‌های دیگه‌ای هم پشتیبانی میشه؟
          <span class="faq-arrow">▼</span>
        </div>
        <div class="faq-a">بله! 3X-UI از VLESS، VMess، Trojan، Shadowsocks و سایر پروتکل‌های XRay پشتیبانی میکنه.</div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- FOOTER -->
<footer class="footer">
  <a class="footer-star" href="#" onclick="return false">
    ⭐ اگه این پروژه مفید بود، ستاره بده!
  </a>
  <div class="footer-text">
    ساخته‌شده با ❤️ — با <a href="https://github.com/mhsanaei/3x-ui" style="color:var(--blue-200); text-decoration:none;">3X-UI</a> توسط MHSanaei و <a href="https://railway.com" style="color:var(--blue-200); text-decoration:none;">Railway</a>
  </div>
  <div class="footer-links">
    <a class="footer-link" href="https://github.com/mhsanaei/3x-ui">3X-UI</a>
    <a class="footer-link" href="https://railway.com">Railway</a>
    <a class="footer-link" href="https://github.com/XTLS/Xray-core">XRay Core</a>
  </div>
</footer>

<script>
/* particles */
const parts = document.getElementById('parts');
for(let i=0;i<35;i++){
  const p = document.createElement('div');
  p.className = 'particle';
  const size = Math.random()*3+2;
  p.style.cssText = `
    left:${Math.random()*100}%;
    width:${size}px; height:${size}px;
    animation-duration:${6+Math.random()*10}s;
    animation-delay:${Math.random()*12}s;
    --dx:${(Math.random()-0.5)*120}px;
    opacity:${0.3+Math.random()*0.5};
  `;
  parts.appendChild(p);
}

/* progress bar */
window.addEventListener('scroll', () => {
  const d = document.documentElement;
  const prog = (d.scrollTop / (d.scrollHeight - d.clientHeight));
  document.getElementById('prog').style.transform = `scaleX(${prog})`;
});

/* scroll reveal */
const obs = new IntersectionObserver((entries)=>{
  entries.forEach(e=>{ if(e.isIntersecting) e.target.classList.add('visible'); });
},{threshold:.12});
document.querySelectorAll('.reveal').forEach(el=>obs.observe(el));

/* faq */
function toggleFaq(btn){
  const item = btn.closest('.faq-item');
  item.classList.toggle('open');
}

/* copy */
function copyCode(btn){
  const block = btn.closest('.code-block');
  const text = block.innerText.replace('کپی','').trim();
  navigator.clipboard.writeText(text).then(()=>{
    btn.textContent = '✅'; setTimeout(()=>btn.textContent='کپی',1500);
  });
}

/* staggered step reveal */
document.querySelectorAll('.step-card').forEach((el,i)=>{
  el.style.animationDelay = (i*0.1)+'s';
});
</script>
</body>
</html>
