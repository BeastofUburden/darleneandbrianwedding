<!DOCTYPE html>
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Brian &amp; Darlene — Forever Begins</title>
<link href="./Brian &amp; Darlene — Forever Begins_files/css2" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --blush: #f0d4dc;
    --rose: #d4849a;
    --dusty-lilac: #c9b8d4;
    --sage: #b5c9b8;
    --powder-blue: #b8cfd4;
    --cream: #faf6f0;
    --warm-white: #fdf9f4;
    --gold: #c9a96e;
    --deep-rose: #9a5c6e;
    --deep-lilac: #7a6488;
    --deep-sage: #5c7a60;
    --ink: #2a2030;
    --ink-light: #4a3c54;
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'EB Garamond', Georgia, serif;
    background-color: var(--warm-white);
    color: var(--ink);
    overflow-x: hidden;
  }

  /* ── Ornamental border overlay ── */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 100;
    border: 18px solid transparent;
    border-image: repeating-linear-gradient(
      90deg,
      var(--gold) 0px, var(--gold) 4px,
      transparent 4px, transparent 14px,
      var(--rose) 14px, var(--rose) 18px
    ) 18;
    opacity: 0.35;
  }

  /* ── Navigation ── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 50;
    background: rgba(250, 246, 240, 0.92);
    backdrop-filter: blur(8px);
    border-bottom: 1px solid rgba(201, 169, 110, 0.3);
    display: flex;
    justify-content: center;
    gap: 2.5rem;
    padding: 0.85rem 1rem;
  }
  nav a {
    font-family: 'Cormorant Garamond', serif;
    font-size: 0.85rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--ink-light);
    text-decoration: none;
    transition: color 0.2s;
  }
  nav a:hover { color: var(--deep-rose); }

  /* ── Hero ── */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 6rem 2rem 4rem;
    position: relative;
    background:
      radial-gradient(ellipse 80% 60% at 50% 0%, #f5dde5 0%, transparent 70%),
      radial-gradient(ellipse 60% 40% at 10% 80%, #ddd5e8 0%, transparent 60%),
      radial-gradient(ellipse 50% 40% at 90% 70%, #cde3e6 0%, transparent 60%),
      var(--warm-white);
  }

  .hero-ornament {
    font-size: 1.4rem;
    color: var(--gold);
    letter-spacing: 0.5em;
    margin-bottom: 1.5rem;
    opacity: 0.7;
  }

  .hero h1 {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(3.5rem, 10vw, 7rem);
    font-weight: 300;
    font-style: italic;
    line-height: 1.1;
    color: var(--ink);
    letter-spacing: -0.01em;
  }

  .hero h1 span {
    color: var(--deep-rose);
  }

  .ampersand {
    font-size: 0.65em;
    color: var(--gold);
    display: block;
    line-height: 1;
    font-style: normal;
  }

  .hero-date {
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.1rem;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--ink-light);
    margin-top: 2rem;
    padding: 0.6rem 2rem;
    border-top: 1px solid var(--gold);
    border-bottom: 1px solid var(--gold);
    opacity: 0.8;
  }

  .hero-sub {
    font-size: 1.15rem;
    font-style: italic;
    color: var(--deep-lilac);
    margin-top: 1.5rem;
    opacity: 0.9;
  }

  .scroll-cue {
    margin-top: 3rem;
    font-size: 0.75rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold);
    opacity: 0.6;
    animation: bounce 2s infinite;
  }

  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(6px); }
  }

  /* ── Sections ── */
  section {
    padding: 5rem 2rem;
    max-width: 860px;
    margin: 0 auto;
  }

  .section-label {
    font-family: 'Cormorant Garamond', serif;
    font-size: 0.8rem;
    letter-spacing: 0.35em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 0.75rem;
    display: flex;
    align-items: center;
    gap: 1rem;
  }
  .section-label::before, .section-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: linear-gradient(to right, transparent, var(--gold), transparent);
    opacity: 0.4;
  }

  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2rem, 5vw, 2.8rem);
    font-weight: 400;
    font-style: italic;
    color: var(--ink);
    text-align: center;
    margin-bottom: 2.5rem;
    line-height: 1.2;
  }

  /* ── Details cards ── */
  .details-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.5rem;
    margin-top: 1rem;
  }

  .detail-card {
    background: linear-gradient(145deg, var(--cream), #f5ede8);
    border: 1px solid rgba(201, 169, 110, 0.3);
    border-radius: 4px;
    padding: 2rem 1.5rem;
    text-align: center;
    position: relative;
    overflow: hidden;
  }

  .detail-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
    background: linear-gradient(to right, var(--blush), var(--dusty-lilac), var(--powder-blue));
  }

  .detail-card .icon {
    font-size: 1.8rem;
    margin-bottom: 0.75rem;
    display: block;
  }

  .detail-card h3 {
    font-family: 'Cormorant Garamond', serif;
    font-size: 0.75rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 0.6rem;
  }

  .detail-card p {
    font-size: 1.05rem;
    color: var(--ink);
    line-height: 1.6;
  }

  .detail-card a {
    color: var(--deep-rose);
    text-decoration: none;
    font-style: italic;
  }

  /* ── Dress code ── */
  .dress-code-box {
    background: linear-gradient(135deg, #f5e0e8, #ede0f0, #dceaec);
    border-radius: 4px;
    padding: 2.5rem;
    text-align: center;
    border: 1px solid rgba(201, 169, 110, 0.25);
  }

  .dress-code-box p {
    font-size: 1.15rem;
    line-height: 1.8;
    color: var(--ink);
  }

  .dress-code-box strong {
    font-weight: 500;
    color: var(--deep-rose);
  }

  .color-swatches {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 1rem;
    margin-top: 2rem;
  }

  .swatch {
    width: 52px;
    height: 52px;
    border-radius: 50%;
    border: 3px solid white;
    box-shadow: 0 2px 8px rgba(0,0,0,0.12);
    position: relative;
  }
  .swatch::after {
    content: attr(data-label);
    position: absolute;
    bottom: -1.4rem;
    left: 50%;
    transform: translateX(-50%);
    font-size: 0.6rem;
    letter-spacing: 0.05em;
    white-space: nowrap;
    color: var(--ink-light);
    font-family: 'Cormorant Garamond', serif;
  }
  .swatch-wrap { display: flex; flex-direction: column; align-items: center; gap: 0.5rem; }

  .no-white {
    margin-top: 2.5rem;
    display: inline-block;
    background: rgba(154, 92, 110, 0.1);
    border: 1px solid rgba(154, 92, 110, 0.3);
    border-radius: 100px;
    padding: 0.4rem 1.2rem;
    font-size: 0.85rem;
    color: var(--deep-rose);
    letter-spacing: 0.05em;
  }

  /* ── Divider ── */
  .floral-divider {
    text-align: center;
    font-size: 1.5rem;
    color: var(--gold);
    opacity: 0.5;
    margin: 0;
    letter-spacing: 0.6em;
    padding: 1rem 0;
  }

  /* ── RSVP Form ── */
  #rsvp { background: radial-gradient(ellipse 70% 50% at 50% 0%, #f0d8e4 0%, transparent 70%), radial-gradient(ellipse 50% 40% at 80% 100%, #d8d0e8 0%, transparent 60%), var(--warm-white); max-width: 100%; padding: 5rem 2rem; }
  .rsvp-inner { max-width: 640px; margin: 0 auto; }
  .form-group { margin-bottom: 1.5rem; }
  label { display: block; font-family: 'Cormorant Garamond', serif; font-size: 0.8rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--ink-light); margin-bottom: 0.5rem; }
  input[type="text"], input[type="email"], input[type="number"], select, textarea { width: 100%; padding: 0.75rem 1rem; font-family: 'EB Garamond', serif; font-size: 1rem; color: var(--ink); background: rgba(255,255,255,0.75); border: 1px solid rgba(201,169,110,0.4); border-radius: 2px; outline: none; transition: border-color 0.2s, box-shadow 0.2s; appearance: none; }
  input:focus, select:focus, textarea:focus { border-color: var(--rose); box-shadow: 0 0 0 3px rgba(212,132,154,0.15); }
  textarea { resize: vertical; min-height: 90px; }
  .radio-group { display: flex; gap: 1rem; flex-wrap: wrap; }
  .radio-label { display: flex; align-items: center; gap: 0.5rem; cursor: pointer; font-family: 'EB Garamond', serif; font-size: 1rem; color: var(--ink); text-transform: none; letter-spacing: 0; }
  .radio-label input[type="radio"] { width: auto; accent-color: var(--deep-rose); }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  .submit-btn { width: 100%; padding: 1rem; background: linear-gradient(135deg, var(--deep-rose), var(--deep-lilac)); color: white; border: none; border-radius: 2px; font-family: 'Cormorant Garamond', serif; font-size: 1.1rem; letter-spacing: 0.2em; text-transform: uppercase; cursor: pointer; margin-top: 0.5rem; transition: opacity 0.2s, transform 0.1s; }
  .submit-btn:hover { opacity: 0.9; }
  .submit-btn:active { transform: scale(0.99); }
  .success-msg { display: none; text-align: center; padding: 2rem; background: linear-gradient(135deg, #e8f5e4, #f0e8f4); border: 1px solid rgba(92,122,96,0.3); border-radius: 4px; }
  .success-msg h3 { font-family: 'Playfair Display', serif; font-size: 1.8rem; font-style: italic; color: var(--deep-sage); margin-bottom: 0.5rem; }
  .success-msg p { color: var(--ink-light); font-style: italic; }
 
  /* Gifts */
  #gifts { background: radial-gradient(ellipse 60% 40% at 30% 0%, #e8dff0 0%, transparent 60%), radial-gradient(ellipse 50% 40% at 80% 100%, #f5dde5 0%, transparent 60%), var(--warm-white); max-width: 100%; padding: 5rem 2rem; }
  .gifts-inner { max-width: 860px; margin: 0 auto; }
  .gifts-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(190px, 1fr)); gap: 1.5rem; margin-top: 1rem; }
  .gift-card { background: linear-gradient(145deg, var(--cream), #f0eaf5); border: 1px solid rgba(201,169,110,0.3); border-radius: 4px; padding: 1.75rem 1.25rem; text-align: center; position: relative; overflow: hidden; display: flex; flex-direction: column; align-items: center; gap: 0.75rem; }
  .gift-card::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 3px; }
  .gift-card.zelle::before { background: linear-gradient(to right, #6B3FA0, #9B5FC0); }
  .gift-card.cashapp::before { background: linear-gradient(to right, #00C244, #00A836); }
  .gift-card.ath::before { background: linear-gradient(to right, #E63946, #C1121F); }
  .gift-card.amazon::before { background: linear-gradient(to right, #FF9900, #e07b00); }
  .gift-card h3 { font-family: 'Cormorant Garamond', serif; font-size: 0.8rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--gold); }
  .gift-card .gift-handle { font-size: 1rem; color: var(--ink); font-style: italic; word-break: break-all; }
  .gift-card img { width: 120px; height: 120px; border-radius: 4px; border: 1px solid rgba(201,169,110,0.2); }
  .gift-btn { display: inline-block; margin-top: 0.25rem; padding: 0.5rem 1.25rem; border: 1px solid var(--gold); border-radius: 2px; font-family: 'Cormorant Garamond', serif; font-size: 0.8rem; letter-spacing: 0.15em; text-transform: uppercase; color: var(--ink-light); text-decoration: none; transition: background 0.2s; }
  .gift-btn:hover { background: var(--blush); }
  .placeholder-badge { background: rgba(201,169,110,0.15); border: 1px dashed var(--gold); border-radius: 100px; padding: 0.3rem 0.9rem; font-size: 0.75rem; color: var(--gold); letter-spacing: 0.1em; margin-top: 0.25rem; }

  /* Memories */
  .memories-btn { display: inline-block; padding: 1rem 2rem; background: linear-gradient(135deg, var(--deep-sage), var(--deep-lilac)); color: white; border: none; border-radius: 2px; font-family: 'Cormorant Garamond', serif; font-size: 1.1rem; letter-spacing: 0.2em; text-transform: uppercase; cursor: pointer; text-decoration: none; transition: opacity 0.2s; }
  .memories-btn:hover { opacity: 0.9; }

  /* ── Footer ── */
  footer {
    text-align: center;
    padding: 3rem 2rem;
    font-family: 'Cormorant Garamond', serif;
    font-size: 0.85rem;
    letter-spacing: 0.15em;
    color: var(--gold);
    opacity: 0.7;
    border-top: 1px solid rgba(201, 169, 110, 0.2);
  }

  /* ── Fade in on scroll ── */
  .reveal {
    opacity: 0;
    transform: translateY(24px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* Stagger children */
  .stagger > * {
    opacity: 0;
    transform: translateY(18px);
    transition: opacity 0.6s ease, transform 0.6s ease;
  }
  .stagger.visible > *:nth-child(1) { opacity:1; transform:none; transition-delay:0.05s; }
  .stagger.visible > *:nth-child(2) { opacity:1; transform:none; transition-delay:0.15s; }
  .stagger.visible > *:nth-child(3) { opacity:1; transform:none; transition-delay:0.25s; }
  .stagger.visible > *:nth-child(4) { opacity:1; transform:none; transition-delay:0.35s; }

   @media (max-width: 520px) {
    .form-row { grid-template-columns: 1fr; }
    nav { gap: 1rem; }
    nav a { font-size: 0.72rem; }
</style>
</head>
<body>

<!-- Navigation -->
<nav>
  <a href="#details">Details</a>
  <a href="#dress-code">Attire</a>
  <a href="#venue">Venue</a>
  <a href="#rsvp">RSVP</a>
  <a href="#gifts">Gifts</a>
  <a href="#memories">Memories</a>
</nav>

<!-- Hero -->
<div class="hero">
  <div class="hero-ornament">✦ ✦ ✦</div>
  <h1>
    Brian
    <span class="ampersand">&amp;</span>
    Darlene
  </h1>
  <div class="hero-date">Please join us to celebrate</div>
  
  <div class="scroll-cue">↓ Scroll to explore ↓</div>
</div>

<!-- Details Section -->
<section id="details">
  <div class="section-label">The Day</div>
  <h2 class="section-title">Celebration Details</h2>

  <div class="details-grid stagger visible">
    <div class="detail-card">
      <span class="icon">🌸</span>
      <h3>Date</h3>
      <p>October 10, 2026<br><em style="font-size:0.9rem; color:#888;"></em></p>
    </div>
    <div class="detail-card">
      <span class="icon">🕑</span>
      <h3>Time</h3>
      <p>2:00 PM – 8:00 PM</p>
    </div>
    <div class="detail-card">
      <span class="icon">📍</span>
      <h3>Venue</h3>
      <p>Hacienda el Amanecer<br>Camuy, Puerto Rico</p>
    </div>
    <div class="detail-card">
      <span class="icon">🌿</span>
      <h3>Schedule</h3>
      <p>Guest Welcoming 2pm to 2:30pm
<br>
Ceremony 2:30pm to 3pm
<br>
Cocktail Hour 3pm to 4pm<br>Dinner 4pm to 5:30pm 
<br>
Dancing 5:30pm to 8pm</p>
    </div>
  </div>
</section>

<div class="floral-divider">✾ ✾ ✾</div>

<!-- Dress Code -->
<section id="dress-code">
  <div class="section-label">Attire</div>
  <h2 class="section-title">Dress Code</h2>

  <div class="dress-code-box reveal visible">
    <p>
      We invite you to dress in <strong>Semi-Formal</strong> elegance.<br>
      Embrace the romance of the evening in<br>
      <strong>pastel &amp; powdered tones</strong> — soft, dreamy, and refined.
    </p>

    <div class="color-swatches">
      <div class="swatch-wrap">
        <div class="swatch" style="background:#f0d4dc;" data-label="Blush"></div>
        
      </div>
      <div class="swatch-wrap">
        <div class="swatch" style="background:#c9b8d4;" data-label="Lilac"></div>
        
      </div>
      <div class="swatch-wrap">
        <div class="swatch" style="background:#b8cfd4;" data-label="Sky"></div>
        
      </div>
      <div class="swatch-wrap">
        <div class="swatch" style="background:#b5c9b8;" data-label="Sage"></div>
        
      </div>
      <div class="swatch-wrap">
        <div class="swatch" style="background:#f7e4b8;" data-label="Butter"></div>
        
      </div>
      <div class="swatch-wrap">
        <div class="swatch" style="background:#d4b8c9;" data-label="Mauve"></div>
        
      </div>
    </div>

    <div>
      <span class="no-white">🚫 No white, ivory, or cream, please</span>
    </div>
  </div>
</section>

<div class="floral-divider">✾ ✾ ✾</div>

<!-- Venue Section -->
<section id="venue">
  <div class="section-label">Where to Find Us</div>
  <h2 class="section-title">Hacienda el Amanecer</h2>

  <div class="detail-card reveal visible" style="text-align:center; padding:2.5rem;">
    <p style="font-size:1.15rem; line-height:2; margin-bottom:1.5rem;">
      Camuy, Puerto Rico<br>
      <em style="color:var(--deep-lilac); font-size:1rem;">
        Nestled among the lush landscapes of Puerto Rico's north coast
      </em><br>  C4X6+QV, Piedra Gorda, Camuy 00627, Puerto Rico
<br>
    
    </p>
    <a href="https://maps.google.com/?q=Hacienda+el+Amanecer+Camuy+Puerto+Rico" target="_blank" style="display: inline-block; padding: 0.7rem 2rem; border: 1px solid var(--gold); color: var(--ink-light); font-family: &quot;Cormorant Garamond&quot;, serif; letter-spacing: 0.15em; text-transform: uppercase; font-size: 0.85rem; text-decoration: none; transition: background 0.2s, color 0.2s; background: transparent;" onmouseover="this.style.background='var(--blush)'" onmouseout="this.style.background='transparent'">
      Open in Maps ↗
    </a>
  </div>
</section>

<div class="floral-divider">✾ ✾ ✾</div>

<!-- RSVP — powered by Google Form -->
<section id="rsvp" style="max-width:100%; padding:5rem 2rem;">
  <div class="rsvp-inner">
    <div class="section-label">Your Response</div>
    <h2 class="section-title">Kindly RSVP</h2>
    <p style="text-align:center; font-style:italic; color:var(--ink-light); margin-bottom:2.5rem; font-size:1.05rem;">
      Please respond by <strong style="font-weight:500; color:var(--deep-rose);">[RSVP Deadline Date]</strong>
    </p>
    <p style="text-align:center; font-style:italic; color:var(--ink-light); margin-bottom:2rem; font-size:0.95rem;">
      Fill out our RSVP form below — your response goes directly to us.<br>
      Song requests are included so we can build the perfect playlist! 🎶
    </p>
    <div style="text-align:center;">
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSfpgKZ2HrZ7IH0vwQt2TpAxBVpM32OvKWtPDMOwxybZnBtayA/viewform" target="_blank" style="display:inline-block; padding:1rem 2.5rem; background:linear-gradient(135deg,var(--deep-rose),var(--deep-lilac)); color:white; font-family:'Cormorant Garamond',serif; font-size:1.1rem; letter-spacing:0.2em; text-transform:uppercase; text-decoration:none; border-radius:2px; transition:opacity 0.2s;" onmouseover="this.style.opacity='0.85'" onmouseout="this.style.opacity='1'">
        Open RSVP Form ✦
      </a>
      <p style="margin-top:1.25rem; font-size:0.85rem; color:var(--ink-light); font-style:italic; opacity:0.7;">
        Opens in a new tab — takes less than 2 minutes
      </p>
    </div>
  </div>
</section>

<div class="floral-divider">✾ ✾ ✾</div>

<!-- Gifts Section -->
<section id="gifts" style="max-width:100%; padding:5rem 2rem; background: radial-gradient(ellipse 60% 40% at 30% 0%, #e8dff0 0%, transparent 60%), radial-gradient(ellipse 50% 40% at 80% 100%, #f5dde5 0%, transparent 60%), var(--warm-white);">
  <div class="gifts-inner">
    <div class="section-label">With Gratitude</div>
    <h2 class="section-title">A Gift of Love</h2>
    <p style="text-align:center; font-style:italic; color:var(--ink-light); margin-bottom:3rem; font-size:1.05rem; max-width:520px; margin-left:auto; margin-right:auto;">
      Your presence is our greatest gift. If you wish to celebrate us further,
      we are grateful for any contribution through the options below.
    </p>

    <div class="gifts-grid stagger">

      <!-- Zelle -->
      <div class="gift-card zelle">
        <h3>💜 Zelle</h3>
        <p class="gift-handle">brian.rivers6981@gmail.com</p>
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALoAAAC6CAIAAACWbMCmAAADfUlEQVR4nO3dMa7cNhRAUdvIRlK78v4XkSp1ljJZgBpd4pHSt8+p52vGwgXhB85Q3z+fzze458fTH4CvRC4EciGQC4FcCORCIBcCuRDIhUAuBHIhkAuBXAjkQiAXArkQyIXgr7U/+/n3r9nPkfz73z8Lf7X2mafe63qdr3gPrS4EciGQC4FcCORCsDgZXa39T/uOfRPEnWnl5Dz1/ntodSGQC4FcCORCIBeCscno6tk9mqkrP7vXc/Ie3mF1IZALgVwI5EIgF4KNk9Hb3PmG252/+pNZXQjkQiAXArkQyIXgD5qM7uz+TL1mbQp7P6sLgVwI5EIgFwK5EGycjJ6dBe68+9prTu4ivW2esroQyIVALgRyIZALwdhk9P5vnU3tEF1NTU/vv4dWFwK5EMiFQC4EciFYnIzetpdx9ew5CVM7Vm9jdSGQC4FcCORCIBeC75/PZ+HPnn1ez9RM8ez34t5/f66sLgRyIZALgVwI5EKwOBndsXaS9tTM9RV3ZN7/b7e6EMiFQC4EciGQC8HYntGUk7PS1JRx8hNOnTS+Nj1ZXQjkQiAXArkQyIVgbM9o6pzqfeckTNk3hd25zrOsLgRyIZALgVwI5EKweALDvrPX9u0Zrb3Xyetc7fs89ozYTi4EciGQC4FcCMZO7T75jNRnf2szdY73s69ZY3UhkAuBXAjkQiAXgtc96XXfntGd60x9A/Dq2e/X2TPiAXIhkAuBXAjkQnD01O6Tp23v2zM6+e7P/qLqyupCIBcCuRDIhUAuBEf3jKZOWpvaf5n6NdDJZxWdPOPuyupCIBcCuRDIhUAuBBufZ3TSyRlnapq7420n9VldCORCIBcCuRDIheB1zzO64+Rssnblfa+ZYs+I7eRCIBcCuRDIhWDj2XRT1k5XWLvy1Llzd0zdsZO/PLK6EMiFQC4EciGQC8HG3xm97dmmUxPWvvPr1vg2HS8lFwK5EMiFQC4EGyejZz17tsOafc+EuvNed1hdCORCIBcCuRDIheC3nYxO7v7sm8KmnnI7Nd9ZXQjkQiAXArkQyIXgdU963fdeJ/dWTp7ScJLVhUAuBHIhkAuBXAjGJqNnT6ub+k3T2vS0duW10x6uTt55qwuBXAjkQiAXArkQ/CbPM+IMqwuBXAjkQiAXArkQyIVALgRyIZALgVwI5EIgFwK5EMiFQC4EciGQC8H/zvKQhJGoxxoAAAAASUVORK5CYII=" alt="Zelle QR Code">
        <span style="font-size:0.75rem; color:var(--ink-light); font-style:italic;">Scan or send to email above</span>
      </div>

      <!-- CashApp -->
      <div class="gift-card cashapp">
        <h3>💚 Cash App</h3>
        <p class="gift-handle">$YourCashTag</p>
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAANIAAADSCAIAAACw+wkVAAAEPElEQVR4nO3dMZIUORRAQSD2Imtjcf9DYK29R2kOUE4hvvSqm0yb6WpmXihCIZX09fV6fYGzvtVfgL+R7AjIjoDsCMiOgOwIyI6A7AjIjoDsCMiOgOwIyI6A7AjIjoDsCMiOwD9rP/b93x+z3+O3/Pf/z4WfuvOd73zy9XOmvs++/9c+a9/ZaEdAdgRkR0B2BGRHYHEme7U2o7njzkxtbTZ3ct565+lTz2r/FncY7QjIjoDsCMiOgOwIjM1kr/bNLtd+6vp9nrZKu++TT/4t7jDaEZAdAdkRkB0B2RHYOJN9R2vrpGs/1e4KbhntCMiOgOwIyI6A7Ah8yEx2alb4tNnlvlXRltGOgOwIyI6A7AjIjsDGmezJWdjJZ63NdtdWaZ//5uwaox0B2RGQHQHZEZAdgbGZbLuauTZPnDpzad+zpmbNT2O0IyA7ArIjIDsCsiOwOJN92hpfu/47NSd92rlM+xjtCMiOgOwIyI6A7AiM3Sd7cl3yaXO3tXlruyO6PZPZaEdAdgRkR0B2BGRH4A1OfDp5O2q7B3jf+cYnz2S+w2hHQHYEZEdAdgRkR+ANdhfve+tz6h3Yfabmkk+7FchoR0B2BGRHQHYEZEdg4+7iO562J3nqTdWTtwK167ZrjHYEZEdAdgRkR0B2BL6+Xq9jD1t7e3RqPfHkbPfkLuU7T7/a91u9w2hHQHYEZEdAdgRkR2BsTfbq5P01a55242274/dq3/cx2hGQHQHZEZAdAdkRGDvxad/e1KmV03YV8mrtzKU7n7PvNz/FaEdAdgRkR0B2BGRHYGwmO/Xu6r510qk3ea/ad3tPruR6T5Y3JjsCsiMgOwKyIzB2dvHU26NTT2/nd/vOSmr3G7uFhzcmOwKyIyA7ArIjcPTEp30+46Tiqae351bdYbQjIDsCsiMgOwKyIxDfwnPnk+/Yt1P3auob3rH2rKm3fb0ny0eRHQHZEZAdAdkRGFuTfdoNMlP27Zp+2l5r98ny4WRHQHYEZEdAdgQWZ7J/z3upV0+7u3bNyRuIrox2BGRHQHYEZEdAdgTGTnxa+zf7TM0cT/4v9t0BdOeTT+6aNtoRkB0B2RGQHQHZERhbkz2pPc3pHd8IPrlH+g6jHQHZEZAdAdkRkB2Bsftk2928a/adAfWOd7ye/GSjHQHZEZAdAdkRkB2BsZnsVXvG79pccurE432nB3/GyVpGOwKyIyA7ArIjIDsCG2eyJ51cEX7afbJXU3f3WJPlo8iOgOwIyI6A7Ah8yEx23/lOJ2epJ2/GaU/EMtoRkB0B2RGQHQHZEdh4C8+Up81S29tzrvbNQO0u5qPIjoDsCMiOgOwIjK3JtqcZ77tlZupzps4cftpdutZkeRuyIyA7ArIjIDsCi2uy8CeMdgRkR0B2BGRHQHYEZEdAdgRkR0B2BGRHQHYEZEdAdgRkR0B2BGRHQHYEfgHC5jtmd6/CTQAAAABJRU5ErkJggg==" alt="CashApp QR Code" style="opacity:0.4; filter:grayscale(1);">
        <span class="placeholder-badge">⏳ Coming Soon</span>
        <span style="font-size:0.75rem; color:var(--ink-light); font-style:italic;">Update with your $cashtag</span>
      </div>

      <!-- ATH Móvil -->
      <div class="gift-card ath">
        <h3>❤️ ATH Móvil</h3>
        <p class="gift-handle">787-217-9056</p>
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAKIAAACiCAIAAABNkIFMAAACr0lEQVR4nO3dQY7UMBRAQQZxEdasuP8hWLHmKM0BIkQwdpzOq1r3tBI9WfpjpZ2P1+v1iaf7vPsCuILMCTInyJwgc4LMCTInyJwgc4LMCTInyJwgc4LMCTInyJwgc8KXsT/79vX73Ov4Jz9//fjrZ85c4ZnvGfvmdcau2WpOkDlB5gSZE2ROGJy0j8YmwDP2TrZn3P/ereYEmRNkTpA5QeaEaZP20diU+I77zEdX3vsZVnOCzAkyJ8icIHPCwkl7r1kT+7rp90pWc4LMCTInyJwgc8JjJ+2jp07RZ1jNCTInyJwgc4LMCQsn7fvPsetm77vdu9WcIHOCzAkyJ8icMG3SvtuT0mcc5+Gx2fv+9241J8icIHOCzAkyJ3w84x2R5SdDzrCaE2ROkDlB5gSZEwYn7TOT7bqd3nXnk+zdwXb2CP9F5gSZE2ROkDlh2qS9zqwZft3/AleeTOjNNfyRzAkyJ8icIHPCY99cM/YM9thnZn3zOlZzgswJMifInCBzwrTntPfuD5+x96mPve+ysZoTZE6QOUHmBJkTFj49cuX8uW6/euwu7vZ7TKs5QeYEmRNkTpA5YfDpkXc8d3rv9Lt3z99qTpA5QeYEmRNkTniDX0QezdpnvnKX++jK3XKrOUHmBJkTZE6QOeEhv4gc+8yZa75yrl7Hak6QOUHmBJkTZE5Y+Db2vb8BvPLMkLHzA8e+eYzVnCBzgswJMifInLBw0r6bsdn7aNYOtlP+mEzmBJkTZE6QOeGxk/asvehZ77vZ+4SJ1Zwgc4LMCTInyJywcNLee67Iuqe711l3WqDVnCBzgswJMifInDBt0t57GskzThpZx2pOkDlB5gSZE2ROmPaOSO7Mak6QOUHmBJkTZE6QOUHmBJkTZE6QOUHmBJkTZE6QOUHmBJkTZE74DUZp9cx0YAglAAAAAElFTkSuQmCC" alt="ATH Movil QR Code">
        <span style="font-size:0.75rem; color:var(--ink-light); font-style:italic;">Scan or send to number above</span>
      </div>

      <!-- Amazon -->
      <div class="gift-card amazon">
        <h3>🛍️ Amazon Wishlist</h3>
        <p class="gift-handle" style="font-size:0.9rem;">Brian &amp; Darlene's Registry</p>
        <img src="data:image/png;base64,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" alt="Amazon Wishlist QR Code">
        <a href="https://www.amazon.com/hz/wishlist/ls/2VQ6P5DKHSJG2?ref_=wl_share" target="_blank" class="gift-btn">View Wishlist ↗</a>
      </div>

    </div>
  </div>
</section>

<div class="floral-divider">✾ ✾ ✾</div>

<!-- Share the Memories -->
<section id="memories" style="max-width:100%; padding:5rem 2rem;">
  <div style="max-width:640px; margin:0 auto; text-align:center;">
    <div class="section-label">After the Wedding</div>
    <h2 class="section-title">Making Memories</h2>
    <p style="text-align:center; font-style:italic; color:var(--ink-light); margin-bottom:2.5rem; font-size:1.05rem;">
      We'd love to see your photos and read your favorite moments from our special day.
      Upload your pictures, videos, and well-wishes — let's build our memory together.
    </p>
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSfpgKZ2HrZ7IH0vwQt2TpAxBVpM32OvKWtPDMOwxybZnBtayA/viewform?usp=publish-editor" target="_blank" class="memories-btn">
      Share Your Photos &amp; Memories ✦
    </a>
  </div>
</section>

<footer>
  ✦ &nbsp; Brian &amp; Darlene &nbsp; ✦ &nbsp; Hacienda el Amanecer, Camuy, Puerto Rico &nbsp; ✦
</footer>

<script>
  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal, .stagger');
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));
</script>


</body></html>
