<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ShowInsight — Premier Entertainment Experiences</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;0,700;1,300;1,400&family=Bebas+Neue&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --black: #000000;
    --white: #FFFFFF;
    --gold: #D4AF37;
    --gold-light: #E8C84A;
    --gold-dim: rgba(212,175,55,0.15);
    --dark: #0A0A0A;
    --charcoal: #161616;
    --gray: #1E1E1E;
    --mid-gray: #2A2A2A;
    --text-dim: rgba(255,255,255,0.55);
    --text-muted: rgba(255,255,255,0.3);
    --border: rgba(212,175,55,0.2);
    --font-display: 'Bebas Neue', sans-serif;
    --font-serif: 'Cormorant Garamond', serif;
    --font-body: 'DM Sans', sans-serif;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--black);
    color: var(--white);
    font-family: var(--font-body);
    font-weight: 300;
    overflow-x: hidden;
    cursor: none;
  }

  /* CUSTOM CURSOR */
  .cursor {
    position: fixed;
    width: 8px; height: 8px;
    background: var(--gold);
    border-radius: 50%;
    pointer-events: none;
    z-index: 99999;
    transform: translate(-50%,-50%);
    transition: transform 0.1s;
  }
  .cursor-ring {
    position: fixed;
    width: 32px; height: 32px;
    border: 1px solid rgba(212,175,55,0.5);
    border-radius: 50%;
    pointer-events: none;
    z-index: 99998;
    transform: translate(-50%,-50%);
    transition: all 0.18s ease;
  }
  body:hover .cursor { opacity: 1; }

  /* SCROLLBAR */
  ::-webkit-scrollbar { width: 3px; }
  ::-webkit-scrollbar-track { background: var(--black); }
  ::-webkit-scrollbar-thumb { background: var(--gold); }

  /* PAGE SECTIONS */
  .page { display: none; }
  .page.active { display: block; }

  /* ── NAVIGATION ── */
  nav {
    position: fixed; top: 0; left: 0; right: 0;
    z-index: 1000;
    padding: 24px 48px;
    display: flex; align-items: center; justify-content: space-between;
    transition: all 0.4s ease;
  }
  nav.scrolled {
    background: rgba(0,0,0,0.95);
    backdrop-filter: blur(20px);
    padding: 16px 48px;
    border-bottom: 1px solid var(--border);
  }
  .nav-logo {
    font-family: var(--font-display);
    font-size: 28px;
    letter-spacing: 4px;
    color: var(--white);
    cursor: pointer;
    position: relative;
  }
  .nav-logo span { color: var(--gold); }
  .nav-links {
    display: flex; gap: 40px; list-style: none;
    align-items: center;
  }
  .nav-links a {
    font-family: var(--font-body);
    font-size: 11px;
    letter-spacing: 2.5px;
    text-transform: uppercase;
    color: var(--text-dim);
    text-decoration: none;
    cursor: pointer;
    transition: color 0.3s;
    position: relative;
  }
  .nav-links a::after {
    content: '';
    position: absolute;
    bottom: -4px; left: 0;
    width: 0; height: 1px;
    background: var(--gold);
    transition: width 0.3s;
  }
  .nav-links a:hover, .nav-links a.active { color: var(--white); }
  .nav-links a:hover::after, .nav-links a.active::after { width: 100%; }
  .nav-cta {
    background: var(--gold);
    color: var(--black) !important;
    padding: 10px 24px;
    font-weight: 500 !important;
    border-radius: 1px;
  }
  .nav-cta::after { display: none !important; }
  .nav-cta:hover { background: var(--gold-light) !important; color: var(--black) !important; }
  .nav-admin-btn {
    background: none;
    border: 1px solid var(--border);
    color: var(--text-dim);
    padding: 8px 16px;
    font-family: var(--font-body);
    font-size: 10px;
    letter-spacing: 2px;
    text-transform: uppercase;
    cursor: pointer;
    transition: all 0.3s;
    border-radius: 1px;
  }
  .nav-admin-btn:hover { border-color: var(--gold); color: var(--gold); }

  /* ── HERO ── */
  #hero {
    height: 100vh; min-height: 700px;
    position: relative;
    display: flex; align-items: center;
    overflow: hidden;
  }
  .hero-bg {
    position: absolute; inset: 0;
    background:
      linear-gradient(160deg, rgba(0,0,0,0.3) 0%, rgba(0,0,0,0.7) 50%, rgba(0,0,0,0.95) 100%),
      radial-gradient(ellipse at 70% 40%, rgba(212,175,55,0.12) 0%, transparent 60%),
      repeating-linear-gradient(45deg, rgba(212,175,55,0.02) 0px, rgba(212,175,55,0.02) 1px, transparent 1px, transparent 40px);
    background-color: #080808;
  }
  .hero-lines {
    position: absolute; inset: 0;
    background-image:
      linear-gradient(rgba(212,175,55,0.06) 1px, transparent 1px),
      linear-gradient(90deg, rgba(212,175,55,0.06) 1px, transparent 1px);
    background-size: 80px 80px;
    mask-image: radial-gradient(ellipse at center, black 20%, transparent 80%);
  }
  .hero-content {
    position: relative; z-index: 2;
    padding: 0 8vw;
    max-width: 900px;
  }
  .hero-eyebrow {
    font-family: var(--font-body);
    font-size: 10px;
    letter-spacing: 5px;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 24px;
    display: flex; align-items: center; gap: 16px;
    opacity: 0; animation: fadeUp 0.8s 0.3s forwards;
  }
  .hero-eyebrow::before {
    content: '';
    display: block; width: 40px; height: 1px;
    background: var(--gold);
  }
  .hero-title {
    font-family: var(--font-display);
    font-size: clamp(72px, 11vw, 160px);
    line-height: 0.88;
    letter-spacing: 2px;
    margin-bottom: 32px;
    opacity: 0; animation: fadeUp 0.9s 0.5s forwards;
  }
  .hero-title em {
    font-family: var(--font-serif);
    font-style: italic;
    color: var(--gold);
    font-size: 0.7em;
    letter-spacing: 0;
    display: block;
  }
  .hero-sub {
    font-size: 16px;
    line-height: 1.7;
    color: var(--text-dim);
    max-width: 480px;
    margin-bottom: 48px;
    opacity: 0; animation: fadeUp 0.9s 0.7s forwards;
  }
  .hero-actions {
    display: flex; gap: 16px; align-items: center;
    opacity: 0; animation: fadeUp 0.9s 0.9s forwards;
  }
  .btn-primary {
    background: var(--gold);
    color: var(--black);
    padding: 16px 40px;
    font-family: var(--font-body);
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 3px;
    text-transform: uppercase;
    border: none; cursor: pointer;
    border-radius: 1px;
    transition: all 0.3s;
    position: relative; overflow: hidden;
  }
  .btn-primary::before {
    content: '';
    position: absolute; inset: 0;
    background: rgba(255,255,255,0.15);
    transform: translateX(-100%);
    transition: transform 0.4s ease;
  }
  .btn-primary:hover::before { transform: translateX(0); }
  .btn-secondary {
    background: none;
    color: var(--white);
    padding: 16px 40px;
    font-family: var(--font-body);
    font-size: 11px;
    font-weight: 400;
    letter-spacing: 3px;
    text-transform: uppercase;
    border: 1px solid rgba(255,255,255,0.25);
    cursor: pointer;
    border-radius: 1px;
    transition: all 0.3s;
  }
  .btn-secondary:hover { border-color: var(--gold); color: var(--gold); }

  .hero-scroll {
    position: absolute; bottom: 40px; left: 8vw;
    display: flex; align-items: center; gap: 12px;
    font-size: 10px; letter-spacing: 3px; text-transform: uppercase;
    color: var(--text-muted);
    opacity: 0; animation: fadeUp 1s 1.2s forwards;
  }
  .scroll-line {
    width: 40px; height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold));
    animation: scrollPulse 2s infinite;
  }
  @keyframes scrollPulse {
    0%,100% { opacity: 0.3; width: 40px; }
    50% { opacity: 1; width: 60px; }
  }
  .hero-stats {
    position: absolute; right: 8vw; bottom: 40px;
    display: flex; gap: 48px;
    opacity: 0; animation: fadeUp 1s 1.1s forwards;
  }
  .hero-stat { text-align: center; }
  .hero-stat-num {
    font-family: var(--font-display);
    font-size: 42px;
    color: var(--gold);
    line-height: 1;
    display: block;
  }
  .hero-stat-label {
    font-size: 10px; letter-spacing: 2px;
    text-transform: uppercase; color: var(--text-muted);
    margin-top: 6px; display: block;
  }

  /* ── SECTION STYLES ── */
  section {
    padding: 120px 8vw;
  }
  .section-eyebrow {
    font-size: 10px; letter-spacing: 4px;
    text-transform: uppercase; color: var(--gold);
    display: flex; align-items: center; gap: 16px;
    margin-bottom: 20px;
  }
  .section-eyebrow::before {
    content: ''; display: block;
    width: 30px; height: 1px; background: var(--gold);
  }
  .section-title {
    font-family: var(--font-display);
    font-size: clamp(48px, 7vw, 96px);
    line-height: 0.9;
    letter-spacing: 2px;
    margin-bottom: 16px;
  }
  .section-title em {
    font-family: var(--font-serif);
    font-style: italic;
    color: var(--gold);
    font-size: 0.75em;
  }
  .section-desc {
    color: var(--text-dim);
    font-size: 15px; line-height: 1.7;
    max-width: 520px;
  }

  /* ── FEATURED SHOWS ── */
  #featured {
    background: var(--charcoal);
    position: relative;
    overflow: hidden;
  }
  #featured::before {
    content: '';
    position: absolute; top: 0; left: 0; right: 0;
    height: 1px; background: linear-gradient(90deg, transparent, var(--gold), transparent);
  }
  .shows-grid {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr;
    gap: 2px;
    margin-top: 64px;
  }
  .show-card {
    position: relative; overflow: hidden;
    background: var(--gray);
    cursor: pointer;
    aspect-ratio: unset;
  }
  .show-card:first-child { grid-row: span 2; min-height: 600px; }
  .show-card:not(:first-child) { min-height: 296px; }
  .show-card-bg {
    position: absolute; inset: 0;
    transition: transform 0.6s ease;
  }
  .show-card:hover .show-card-bg { transform: scale(1.05); }
  .show-bg-1 { background: linear-gradient(135deg, #1a0a00, #3d1f00, #2a1000), radial-gradient(circle at 50% 80%, rgba(212,175,55,0.3), transparent 60%); }
  .show-bg-2 { background: linear-gradient(135deg, #000d1a, #001a33, #000a14); }
  .show-bg-3 { background: linear-gradient(135deg, #0d0010, #1a0020, #0a000d); }
  .show-bg-4 { background: linear-gradient(135deg, #001a0d, #003320, #000d07); }
  .show-card-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(to top, rgba(0,0,0,0.9) 0%, rgba(0,0,0,0.2) 50%, transparent 100%);
  }
  .show-card-body {
    position: absolute; bottom: 0; left: 0; right: 0;
    padding: 32px;
  }
  .show-type {
    font-size: 9px; letter-spacing: 3px;
    text-transform: uppercase; color: var(--gold);
    margin-bottom: 10px;
  }
  .show-card-title {
    font-family: var(--font-display);
    font-size: 32px; letter-spacing: 1px;
    line-height: 1;
    margin-bottom: 8px;
  }
  .show-card:first-child .show-card-title { font-size: 52px; }
  .show-card-date {
    font-size: 12px; color: var(--text-dim);
    display: flex; align-items: center; gap: 8px;
  }
  .show-tag {
    display: inline-block;
    padding: 4px 12px;
    border: 1px solid var(--gold);
    font-size: 9px; letter-spacing: 2px;
    text-transform: uppercase; color: var(--gold);
    margin-bottom: 12px;
  }
  .show-card-icons {
    position: absolute; top: 24px; right: 24px;
    display: flex; flex-direction: column; gap: 8px;
    align-items: flex-end;
  }

  /* ── PERFORMERS ── */
  #performers { background: var(--black); }
  .performers-header {
    display: flex; justify-content: space-between;
    align-items: flex-end; margin-bottom: 56px;
  }
  .performer-filters {
    display: flex; gap: 8px;
  }
  .filter-btn {
    background: none;
    border: 1px solid var(--border);
    color: var(--text-dim);
    padding: 8px 20px;
    font-family: var(--font-body);
    font-size: 10px; letter-spacing: 2px;
    text-transform: uppercase;
    cursor: pointer;
    border-radius: 1px;
    transition: all 0.3s;
  }
  .filter-btn.active, .filter-btn:hover {
    border-color: var(--gold); color: var(--gold);
    background: var(--gold-dim);
  }
  .performers-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 2px;
  }
  .performer-card {
    position: relative;
    overflow: hidden;
    aspect-ratio: 3/4;
    cursor: pointer;
    background: var(--charcoal);
    transition: all 0.4s;
  }
  .performer-card:nth-child(2) { margin-top: 48px; }
  .performer-card:nth-child(4) { margin-top: -48px; }
  .performer-portrait {
    position: absolute; inset: 0;
    display: flex; align-items: center; justify-content: center;
    font-size: 80px;
    transition: transform 0.6s ease;
  }
  .performer-card:hover .performer-portrait { transform: scale(1.08); }
  .p1 { background: linear-gradient(160deg, #1a0a00 0%, #3d1500 50%, #1a0800 100%); }
  .p2 { background: linear-gradient(160deg, #000a1a 0%, #001535 50%, #00080d 100%); }
  .p3 { background: linear-gradient(160deg, #0d0a00 0%, #2a2000 50%, #0d0800 100%); }
  .p4 { background: linear-gradient(160deg, #0a001a 0%, #1a0035 50%, #060010 100%); }
  .performer-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(to top, rgba(0,0,0,0.95) 0%, rgba(0,0,0,0.4) 50%, transparent 100%);
    opacity: 0.7;
    transition: opacity 0.4s;
  }
  .performer-card:hover .performer-overlay { opacity: 0.9; }
  .performer-info {
    position: absolute; bottom: 0; left: 0; right: 0;
    padding: 28px;
    transform: translateY(0);
    transition: transform 0.4s;
  }
  .performer-type {
    font-size: 9px; letter-spacing: 3px;
    text-transform: uppercase; color: var(--gold);
    margin-bottom: 6px;
  }
  .performer-name {
    font-family: var(--font-display);
    font-size: 26px; letter-spacing: 1px;
    margin-bottom: 4px;
  }
  .performer-rating {
    font-size: 11px; color: var(--text-dim);
    display: flex; align-items: center; gap: 6px;
  }
  .stars { color: var(--gold); letter-spacing: 2px; }
  .performer-cta {
    display: none;
    margin-top: 16px;
    font-size: 10px; letter-spacing: 2px;
    text-transform: uppercase; color: var(--gold);
    text-decoration: none;
  }
  .performer-card:hover .performer-cta { display: block; }
  .performer-price {
    position: absolute; top: 20px; right: 20px;
    background: rgba(0,0,0,0.7);
    border: 1px solid var(--border);
    padding: 6px 14px;
    font-size: 12px; color: var(--gold);
    font-family: var(--font-serif);
    font-style: italic;
  }

  /* ── PACKAGES ── */
  #packages {
    background: var(--charcoal);
    position: relative;
    overflow: hidden;
  }
  #packages::after {
    content: 'PACKAGES';
    position: absolute; bottom: -40px; right: -20px;
    font-family: var(--font-display);
    font-size: 180px; color: rgba(212,175,55,0.04);
    letter-spacing: 10px;
    pointer-events: none;
  }
  .packages-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2px;
    margin-top: 64px;
  }
  .package-card {
    background: var(--gray);
    padding: 48px 40px;
    position: relative;
    overflow: hidden;
    cursor: pointer;
    transition: all 0.4s;
    border: 1px solid transparent;
  }
  .package-card:hover { border-color: var(--border); }
  .package-card.featured {
    background: var(--mid-gray);
    border-color: var(--gold) !important;
  }
  .package-card.featured::before {
    content: 'MOST POPULAR';
    position: absolute; top: 0; right: 32px;
    background: var(--gold);
    color: var(--black);
    font-size: 8px; letter-spacing: 2px;
    padding: 6px 14px;
    font-weight: 500;
  }
  .package-tier {
    font-size: 10px; letter-spacing: 4px;
    text-transform: uppercase; color: var(--text-muted);
    margin-bottom: 8px;
  }
  .package-name {
    font-family: var(--font-display);
    font-size: 48px; letter-spacing: 2px;
    margin-bottom: 24px;
  }
  .package-card.featured .package-name { color: var(--gold); }
  .package-price {
    margin-bottom: 36px;
  }
  .price-amount {
    font-family: var(--font-serif);
    font-size: 56px; font-style: italic;
    line-height: 1; color: var(--white);
  }
  .price-suffix {
    font-size: 12px; color: var(--text-dim); margin-left: 8px;
  }
  .package-divider {
    width: 40px; height: 1px;
    background: var(--gold);
    margin-bottom: 32px;
  }
  .package-includes {
    list-style: none; margin-bottom: 40px;
  }
  .package-includes li {
    font-size: 14px; color: var(--text-dim);
    padding: 10px 0;
    border-bottom: 1px solid rgba(255,255,255,0.06);
    display: flex; align-items: center; gap: 12px;
  }
  .package-includes li::before {
    content: '✦';
    color: var(--gold); font-size: 8px;
    flex-shrink: 0;
  }
  .package-includes li.highlight { color: var(--white); }
  .package-btn {
    width: 100%;
    background: none;
    border: 1px solid var(--border);
    color: var(--white);
    padding: 16px;
    font-family: var(--font-body);
    font-size: 10px; letter-spacing: 3px;
    text-transform: uppercase;
    cursor: pointer;
    transition: all 0.3s;
  }
  .package-card.featured .package-btn {
    background: var(--gold);
    border-color: var(--gold);
    color: var(--black);
    font-weight: 500;
  }
  .package-btn:hover { background: var(--gold); border-color: var(--gold); color: var(--black); }

  /* ── TESTIMONIALS ── */
  #testimonials {
    background: var(--black);
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  .testimonials-container {
    max-width: 800px; margin: 64px auto 0;
    position: relative;
  }
  .testimonial {
    display: none;
  }
  .testimonial.active { display: block; }
  .testimonial-quote {
    font-family: var(--font-serif);
    font-size: clamp(22px, 3vw, 32px);
    font-style: italic; line-height: 1.5;
    color: var(--white); margin-bottom: 32px;
  }
  .testimonial-quote::before {
    content: '"';
    font-size: 3em; line-height: 0;
    color: var(--gold); opacity: 0.4;
    display: block; margin-bottom: 16px;
  }
  .testimonial-author {
    font-size: 11px; letter-spacing: 3px;
    text-transform: uppercase; color: var(--gold);
    margin-bottom: 4px;
  }
  .testimonial-role { font-size: 12px; color: var(--text-muted); }
  .testimonial-dots {
    display: flex; justify-content: center; gap: 8px; margin-top: 48px;
  }
  .dot {
    width: 6px; height: 6px; border-radius: 50%;
    background: var(--mid-gray); cursor: pointer;
    transition: all 0.3s;
  }
  .dot.active { background: var(--gold); width: 24px; border-radius: 3px; }

  /* ── BOOKING ── */
  #booking { background: var(--charcoal); }
  .booking-grid {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 80px; margin-top: 64px;
    align-items: start;
  }
  .booking-info h3 {
    font-family: var(--font-serif);
    font-size: 28px; font-style: italic;
    color: var(--gold); margin-bottom: 24px;
  }
  .booking-info p {
    color: var(--text-dim); font-size: 15px;
    line-height: 1.7; margin-bottom: 32px;
  }
  .booking-features {
    list-style: none;
  }
  .booking-features li {
    padding: 16px 0;
    border-bottom: 1px solid rgba(255,255,255,0.06);
    display: flex; align-items: center; gap: 16px;
    font-size: 14px; color: var(--text-dim);
  }
  .booking-features li::before {
    content: ''; display: block;
    width: 4px; height: 4px; border-radius: 50%;
    background: var(--gold); flex-shrink: 0;
  }
  .booking-form {
    display: flex; flex-direction: column; gap: 16px;
  }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .form-group { display: flex; flex-direction: column; gap: 8px; }
  .form-label {
    font-size: 9px; letter-spacing: 2.5px;
    text-transform: uppercase; color: var(--text-dim);
  }
  .form-input, .form-select, .form-textarea {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(255,255,255,0.1);
    color: var(--white);
    padding: 14px 18px;
    font-family: var(--font-body);
    font-size: 14px;
    border-radius: 1px;
    transition: border-color 0.3s;
    outline: none;
    width: 100%;
  }
  .form-input:focus, .form-select:focus, .form-textarea:focus {
    border-color: var(--gold);
    background: rgba(212,175,55,0.04);
  }
  .form-select { appearance: none; cursor: pointer; }
  .form-textarea { resize: vertical; min-height: 100px; }
  .price-preview {
    background: var(--gold-dim);
    border: 1px solid var(--border);
    padding: 20px 24px;
    display: flex; justify-content: space-between; align-items: center;
    border-radius: 1px;
  }
  .price-preview-label { font-size: 11px; letter-spacing: 2px; text-transform: uppercase; color: var(--text-dim); }
  .price-preview-amount {
    font-family: var(--font-serif);
    font-size: 32px; font-style: italic; color: var(--gold);
  }

  /* ── ABOUT ── */
  #about { background: var(--black); }
  .about-grid {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 80px; align-items: center; margin-top: 64px;
  }
  .about-visual {
    position: relative;
  }
  .about-image-main {
    width: 100%; aspect-ratio: 4/5;
    background: linear-gradient(160deg, #1a0800, #3d1500, #1a0400);
    display: flex; align-items: center; justify-content: center;
    font-size: 120px;
    position: relative; overflow: hidden;
  }
  .about-image-main::after {
    content: '';
    position: absolute; inset: 0;
    background: linear-gradient(to bottom, transparent 40%, rgba(0,0,0,0.6) 100%);
  }
  .about-image-accent {
    position: absolute; bottom: -32px; right: -32px;
    width: 55%;
    background: var(--charcoal);
    border: 2px solid var(--gold);
    aspect-ratio: 1;
    display: flex; align-items: center; justify-content: center;
    flex-direction: column; padding: 24px; text-align: center;
  }
  .about-accent-num {
    font-family: var(--font-display);
    font-size: 64px; color: var(--gold); line-height: 1;
  }
  .about-accent-text {
    font-size: 10px; letter-spacing: 2px;
    text-transform: uppercase; color: var(--text-dim);
  }
  .about-content h2 {
    font-family: var(--font-display);
    font-size: 56px; line-height: 0.9;
    margin-bottom: 8px;
  }
  .about-content h2 em {
    font-family: var(--font-serif);
    font-style: italic; color: var(--gold);
    font-size: 0.85em;
  }
  .about-content p {
    color: var(--text-dim); font-size: 15px;
    line-height: 1.8; margin-bottom: 20px;
  }
  .about-pillars {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 16px; margin-top: 32px;
  }
  .pillar {
    border-left: 1px solid var(--border);
    padding-left: 20px;
  }
  .pillar-title {
    font-family: var(--font-display);
    font-size: 18px; color: var(--gold); letter-spacing: 1px;
    margin-bottom: 6px;
  }
  .pillar-text { font-size: 13px; color: var(--text-muted); line-height: 1.6; }

  /* ── FOOTER ── */
  footer {
    background: var(--charcoal);
    border-top: 1px solid var(--border);
    padding: 64px 8vw 32px;
  }
  .footer-top {
    display: grid; grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 48px; margin-bottom: 48px;
  }
  .footer-brand-logo {
    font-family: var(--font-display);
    font-size: 32px; letter-spacing: 4px;
    margin-bottom: 16px;
  }
  .footer-brand-logo span { color: var(--gold); }
  .footer-tagline { font-size: 13px; color: var(--text-muted); line-height: 1.7; max-width: 280px; }
  .footer-col-title {
    font-size: 10px; letter-spacing: 3px;
    text-transform: uppercase; color: var(--gold);
    margin-bottom: 20px;
  }
  .footer-links { list-style: none; }
  .footer-links li { margin-bottom: 12px; }
  .footer-links a {
    font-size: 13px; color: var(--text-dim);
    text-decoration: none; cursor: pointer;
    transition: color 0.3s;
  }
  .footer-links a:hover { color: var(--white); }
  .footer-bottom {
    display: flex; justify-content: space-between; align-items: center;
    padding-top: 32px; border-top: 1px solid rgba(255,255,255,0.06);
    font-size: 11px; color: var(--text-muted);
  }
  .footer-social { display: flex; gap: 16px; }
  .social-link {
    width: 36px; height: 36px;
    border: 1px solid var(--border);
    display: flex; align-items: center; justify-content: center;
    font-size: 14px; cursor: pointer;
    transition: all 0.3s; border-radius: 50%;
  }
  .social-link:hover { border-color: var(--gold); color: var(--gold); }

  /* ── NEWSLETTER ── */
  #newsletter {
    background: var(--gold);
    padding: 80px 8vw;
    display: flex; align-items: center; justify-content: space-between;
    gap: 40px;
  }
  .newsletter-text h2 {
    font-family: var(--font-display);
    font-size: 48px; color: var(--black);
    letter-spacing: 2px; line-height: 0.9;
    margin-bottom: 8px;
  }
  .newsletter-text p { font-size: 14px; color: rgba(0,0,0,0.6); }
  .newsletter-form {
    display: flex; gap: 0; flex-shrink: 0; width: 420px;
  }
  .newsletter-input {
    flex: 1;
    background: rgba(0,0,0,0.15);
    border: 1px solid rgba(0,0,0,0.2);
    border-right: none;
    color: var(--black);
    padding: 16px 20px;
    font-family: var(--font-body);
    font-size: 14px; outline: none;
  }
  .newsletter-input::placeholder { color: rgba(0,0,0,0.4); }
  .newsletter-btn {
    background: var(--black);
    color: var(--gold);
    border: none;
    padding: 16px 28px;
    font-family: var(--font-body);
    font-size: 10px; letter-spacing: 2px;
    text-transform: uppercase; cursor: pointer;
    font-weight: 500;
    transition: background 0.3s;
  }
  .newsletter-btn:hover { background: #111; }

  /* ── ADMIN DASHBOARD ── */
  #admin-panel {
    display: none;
    position: fixed; inset: 0;
    z-index: 9000;
    background: var(--dark);
  }
  #admin-panel.open { display: flex; }
  .admin-sidebar {
    width: 240px;
    background: var(--charcoal);
    border-right: 1px solid var(--border);
    display: flex; flex-direction: column;
    padding: 0;
    flex-shrink: 0;
  }
  .admin-logo {
    padding: 24px;
    border-bottom: 1px solid var(--border);
    font-family: var(--font-display);
    font-size: 20px; letter-spacing: 3px;
  }
  .admin-logo span { color: var(--gold); }
  .admin-logo small {
    display: block;
    font-family: var(--font-body);
    font-size: 9px; letter-spacing: 2px;
    text-transform: uppercase; color: var(--text-muted);
    margin-top: 4px;
  }
  .admin-nav { padding: 16px 0; flex: 1; }
  .admin-nav-item {
    display: flex; align-items: center; gap: 12px;
    padding: 12px 24px;
    font-size: 12px; letter-spacing: 1px;
    color: var(--text-dim);
    cursor: pointer; transition: all 0.2s;
    border-left: 2px solid transparent;
  }
  .admin-nav-item:hover { color: var(--white); background: rgba(255,255,255,0.03); }
  .admin-nav-item.active {
    color: var(--gold);
    border-left-color: var(--gold);
    background: var(--gold-dim);
  }
  .admin-nav-icon { font-size: 16px; width: 20px; text-align: center; }
  .admin-nav-section {
    padding: 16px 24px 8px;
    font-size: 8px; letter-spacing: 3px;
    text-transform: uppercase; color: var(--text-muted);
  }
  .admin-close {
    padding: 20px 24px;
    border-top: 1px solid var(--border);
    display: flex; align-items: center; gap: 10px;
    font-size: 11px; color: var(--text-muted);
    cursor: pointer; transition: color 0.2s;
  }
  .admin-close:hover { color: var(--white); }
  .admin-main {
    flex: 1; overflow-y: auto;
    display: flex; flex-direction: column;
  }
  .admin-topbar {
    background: var(--charcoal);
    border-bottom: 1px solid var(--border);
    padding: 16px 32px;
    display: flex; justify-content: space-between; align-items: center;
    position: sticky; top: 0; z-index: 10;
  }
  .admin-topbar h1 {
    font-family: var(--font-display);
    font-size: 24px; letter-spacing: 2px;
  }
  .admin-topbar-actions { display: flex; gap: 12px; }
  .admin-btn {
    background: var(--gold);
    color: var(--black);
    border: none;
    padding: 10px 20px;
    font-family: var(--font-body);
    font-size: 10px; letter-spacing: 2px;
    text-transform: uppercase;
    cursor: pointer; font-weight: 500;
    border-radius: 1px;
    transition: background 0.2s;
  }
  .admin-btn:hover { background: var(--gold-light); }
  .admin-btn-secondary {
    background: none;
    border: 1px solid var(--border);
    color: var(--text-dim);
    padding: 10px 20px;
    font-family: var(--font-body);
    font-size: 10px; letter-spacing: 2px;
    text-transform: uppercase;
    cursor: pointer;
    border-radius: 1px;
    transition: all 0.2s;
  }
  .admin-btn-secondary:hover { border-color: var(--gold); color: var(--gold); }
  .admin-content { padding: 32px; flex: 1; }
  .admin-panel-section { display: none; }
  .admin-panel-section.active { display: block; }

  /* Admin stats */
  .stats-grid {
    display: grid; grid-template-columns: repeat(4, 1fr);
    gap: 16px; margin-bottom: 32px;
  }
  .stat-card {
    background: var(--charcoal);
    border: 1px solid var(--border);
    padding: 24px;
    border-radius: 2px;
  }
  .stat-card-label {
    font-size: 9px; letter-spacing: 2px;
    text-transform: uppercase; color: var(--text-muted);
    margin-bottom: 12px;
  }
  .stat-card-value {
    font-family: var(--font-display);
    font-size: 40px; letter-spacing: 1px;
    color: var(--white); line-height: 1;
    margin-bottom: 8px;
  }
  .stat-card-change {
    font-size: 11px; color: #4CAF50;
  }
  .stat-card-change.down { color: #f44336; }
  .stat-card:first-child { border-top: 2px solid var(--gold); }

  /* Admin table */
  .admin-table-wrap {
    background: var(--charcoal);
    border: 1px solid var(--border);
    border-radius: 2px; overflow: hidden;
    margin-top: 24px;
  }
  .admin-table-header {
    padding: 16px 24px;
    border-bottom: 1px solid var(--border);
    display: flex; justify-content: space-between; align-items: center;
  }
  .admin-table-title {
    font-size: 12px; letter-spacing: 2px;
    text-transform: uppercase; color: var(--text-dim);
  }
  .admin-search {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(255,255,255,0.1);
    color: var(--white);
    padding: 8px 16px;
    font-size: 12px;
    border-radius: 1px; outline: none;
    width: 220px;
  }
  .admin-search:focus { border-color: var(--gold); }
  table { width: 100%; border-collapse: collapse; }
  th {
    padding: 12px 24px;
    font-size: 9px; letter-spacing: 2.5px;
    text-transform: uppercase; color: var(--text-muted);
    text-align: left;
    background: rgba(255,255,255,0.02);
    border-bottom: 1px solid var(--border);
  }
  td {
    padding: 16px 24px;
    font-size: 13px; color: var(--text-dim);
    border-bottom: 1px solid rgba(255,255,255,0.04);
  }
  tr:last-child td { border-bottom: none; }
  tr:hover td { background: rgba(255,255,255,0.02); color: var(--white); }
  .status-badge {
    display: inline-block;
    padding: 4px 12px;
    font-size: 9px; letter-spacing: 1.5px;
    text-transform: uppercase; border-radius: 20px;
  }
  .badge-pending { background: rgba(255,193,7,0.15); color: #FFC107; }
  .badge-confirmed { background: rgba(76,175,80,0.15); color: #4CAF50; }
  .badge-completed { background: rgba(33,150,243,0.15); color: #2196F3; }
  .badge-cancelled { background: rgba(244,67,54,0.15); color: #f44336; }
  .table-action {
    background: none; border: 1px solid var(--border);
    color: var(--text-dim); padding: 5px 12px;
    font-size: 10px; cursor: pointer; border-radius: 1px;
    transition: all 0.2s;
  }
  .table-action:hover { border-color: var(--gold); color: var(--gold); }
  .table-action.danger:hover { border-color: #f44336; color: #f44336; }

  /* Admin forms */
  .admin-form-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 20px;
    background: var(--charcoal);
    border: 1px solid var(--border);
    padding: 32px; border-radius: 2px;
  }
  .admin-form-group { display: flex; flex-direction: column; gap: 8px; }
  .admin-form-group.full { grid-column: span 2; }
  .admin-form-label {
    font-size: 9px; letter-spacing: 2.5px;
    text-transform: uppercase; color: var(--text-muted);
  }
  .admin-form-input, .admin-form-select, .admin-form-textarea {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(255,255,255,0.1);
    color: var(--white);
    padding: 12px 16px;
    font-family: var(--font-body);
    font-size: 13px; border-radius: 1px; outline: none;
    transition: border-color 0.2s;
  }
  .admin-form-input:focus, .admin-form-select:focus, .admin-form-textarea:focus {
    border-color: var(--gold);
  }
  .admin-form-textarea { resize: vertical; min-height: 100px; }
  .admin-form-actions {
    grid-column: span 2;
    display: flex; gap: 12px; justify-content: flex-end;
    padding-top: 8px;
  }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }
  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  .reveal {
    opacity: 0; transform: translateY(40px);
    transition: opacity 0.8s ease, transform 0.8s ease;
  }
  .reveal.visible {
    opacity: 1; transform: translateY(0);
  }

  /* Modal */
  .modal-overlay {
    display: none;
    position: fixed; inset: 0;
    background: rgba(0,0,0,0.85);
    z-index: 8000;
    align-items: center; justify-content: center;
  }
  .modal-overlay.open { display: flex; }
  .modal {
    background: var(--charcoal);
    border: 1px solid var(--border);
    padding: 48px;
    width: 90%; max-width: 560px;
    position: relative;
    animation: fadeUp 0.4s ease;
  }
  .modal-title {
    font-family: var(--font-display);
    font-size: 36px; letter-spacing: 2px;
    margin-bottom: 8px;
  }
  .modal-sub { color: var(--text-dim); font-size: 14px; margin-bottom: 32px; }
  .modal-close {
    position: absolute; top: 24px; right: 24px;
    background: none; border: none; color: var(--text-dim);
    font-size: 20px; cursor: pointer; line-height: 1;
    transition: color 0.2s;
  }
  .modal-close:hover { color: var(--white); }

  /* Login */
  #login-modal .modal { max-width: 440px; }
  .login-form { display: flex; flex-direction: column; gap: 16px; }

  /* Toast */
  .toast {
    position: fixed; bottom: 32px; right: 32px;
    background: var(--gold);
    color: var(--black);
    padding: 16px 24px;
    font-size: 13px; font-weight: 500;
    z-index: 99999;
    animation: fadeUp 0.4s ease;
    border-radius: 1px;
  }

  /* Responsive */
  @media (max-width: 1024px) {
    nav { padding: 20px 32px; }
    .nav-links { gap: 24px; }
    .shows-grid { grid-template-columns: 1fr 1fr; }
    .show-card:first-child { grid-column: span 2; min-height: 400px; }
    .performers-grid { grid-template-columns: repeat(2, 1fr); }
    .packages-grid { grid-template-columns: 1fr; }
    .booking-grid, .about-grid { grid-template-columns: 1fr; }
    .footer-top { grid-template-columns: 1fr 1fr; }
    .stats-grid { grid-template-columns: repeat(2, 1fr); }
  }
  @media (max-width: 768px) {
    nav { padding: 16px 20px; }
    .nav-links { display: none; }
    section { padding: 80px 20px; }
    .shows-grid { grid-template-columns: 1fr; }
    .show-card:first-child { grid-column: auto; }
    .performers-grid { grid-template-columns: 1fr 1fr; }
    .performer-card:nth-child(2), .performer-card:nth-child(4) { margin-top: 0; }
    #newsletter { flex-direction: column; }
    .newsletter-form { width: 100%; }
    .hero-stats { display: none; }
    .form-row { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- CURSOR -->
<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAVIGATION -->
<nav id="mainNav">
  <div class="nav-logo" onclick="navigate('home')">SHOW<span>INSIGHT</span></div>
  <ul class="nav-links">
    <li><a onclick="navigate('home')" class="active" id="nav-home">Home</a></li>
    <li><a onclick="navigate('performers')" id="nav-performers">Performers</a></li>
    <li><a onclick="navigate('shows')" id="nav-shows">Shows</a></li>
    <li><a onclick="navigate('packages')" id="nav-packages">Packages</a></li>
    <li><a onclick="navigate('about')" id="nav-about">About</a></li>
    <li><a onclick="navigate('booking')" class="nav-cta" id="nav-booking">Book Now</a></li>
  </ul>
  <button class="nav-admin-btn" onclick="openAdmin()">Admin ↗</button>
</nav>

<!-- ══════════ HOME PAGE ══════════ -->
<div class="page active" id="page-home">

  <!-- HERO -->
  <section id="hero">
    <div class="hero-bg"></div>
    <div class="hero-lines"></div>
    <div class="hero-content">
      <div class="hero-eyebrow">Premier Entertainment Experiences</div>
      <h1 class="hero-title">
        WHERE THE
        <em>Stage Comes</em>
        ALIVE
      </h1>
      <p class="hero-sub">
        Curating extraordinary entertainment for unforgettable events. From electrifying DJs to breathtaking cabaret — we orchestrate the extraordinary.
      </p>
      <div class="hero-actions">
        <button class="btn-primary" onclick="navigate('booking')">Book an Experience</button>
        <button class="btn-secondary" onclick="navigate('shows')">Explore Shows</button>
      </div>
    </div>
    <div class="hero-scroll">
      <span class="scroll-line"></span>
      Scroll to discover
    </div>
    <div class="hero-stats">
      <div class="hero-stat">
        <span class="hero-stat-num">200+</span>
        <span class="hero-stat-label">Performances</span>
      </div>
      <div class="hero-stat">
        <span class="hero-stat-num">48</span>
        <span class="hero-stat-label">Elite Performers</span>
      </div>
      <div class="hero-stat">
        <span class="hero-stat-num">99%</span>
        <span class="hero-stat-label">Satisfaction</span>
      </div>
    </div>
  </section>

  <!-- FEATURED SHOWS -->
  <section id="featured">
    <div class="section-eyebrow">On Stage This Season</div>
    <div class="section-title">FEATURED<br><em>Shows</em></div>
    <div class="shows-grid reveal">
      <div class="show-card" onclick="navigate('shows')">
        <div class="show-card-bg show-bg-1"></div>
        <div class="show-card-overlay"></div>
        <div class="show-card-body">
          <div class="show-type">★ Headline Show</div>
          <div class="show-tag">Cabaret Night</div>
          <div class="show-card-title">THE GOLDEN<br>HOUR</div>
          <div class="show-card-date">🗓 Every Friday — 9PM onwards</div>
        </div>
      </div>
      <div class="show-card" onclick="navigate('shows')">
        <div class="show-card-bg show-bg-2"></div>
        <div class="show-card-overlay"></div>
        <div class="show-card-body">
          <div class="show-type">Live Music</div>
          <div class="show-card-title">ELECTRIC<br>SESSIONS</div>
          <div class="show-card-date">🗓 Saturdays — 8PM</div>
        </div>
      </div>
      <div class="show-card" onclick="navigate('shows')">
        <div class="show-card-bg show-bg-3"></div>
        <div class="show-card-overlay"></div>
        <div class="show-card-body">
          <div class="show-type">DJ Set</div>
          <div class="show-card-title">MIDNIGHT<br>PULSE</div>
          <div class="show-card-date">🗓 Thursdays — 10PM</div>
        </div>
      </div>
      <div class="show-card" onclick="navigate('shows')">
        <div class="show-card-bg show-bg-4"></div>
        <div class="show-card-overlay"></div>
        <div class="show-card-body">
          <div class="show-type">Special Event</div>
          <div class="show-card-title">GALA<br>NIGHT</div>
          <div class="show-card-date">🗓 Monthly — Check calendar</div>
        </div>
      </div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section id="testimonials">
    <div class="section-eyebrow" style="justify-content:center">What Clients Say</div>
    <div class="section-title" style="font-size:clamp(40px,6vw,80px)">BEYOND<br><em>Expectations</em></div>
    <div class="testimonials-container reveal">
      <div class="testimonial active">
        <p class="testimonial-quote">ShowInsight transformed our corporate gala into an absolutely unforgettable evening. The cabaret performers were world-class and our guests are still talking about it months later.</p>
        <div class="testimonial-author">Fatima Al-Rashid</div>
        <div class="testimonial-role">Director of Events, Prestige Group — Riyadh</div>
      </div>
      <div class="testimonial">
        <p class="testimonial-quote">The attention to detail is extraordinary. Every performer arrived prepared, professional, and completely in sync with our vision. This is the only entertainment partner we trust.</p>
        <div class="testimonial-author">James Harrington</div>
        <div class="testimonial-role">Event Director, The Grand Hyatt</div>
      </div>
      <div class="testimonial">
        <p class="testimonial-quote">I've worked with entertainment companies all over the world. ShowInsight stands in a category of their own — the talent roster is genuinely elite.</p>
        <div class="testimonial-author">Sofia Andreou</div>
        <div class="testimonial-role">Private Events Coordinator, Monaco</div>
      </div>
      <div class="testimonial-dots">
        <div class="dot active" onclick="goTestimonial(0)"></div>
        <div class="dot" onclick="goTestimonial(1)"></div>
        <div class="dot" onclick="goTestimonial(2)"></div>
      </div>
    </div>
  </section>

  <!-- NEWSLETTER -->
  <div id="newsletter">
    <div class="newsletter-text">
      <h2>STAY IN<br>THE LOOP</h2>
      <p>Get first access to upcoming shows & exclusive offers</p>
    </div>
    <form class="newsletter-form" onsubmit="handleNewsletter(event)">
      <input type="email" class="newsletter-input" placeholder="Your email address">
      <button type="submit" class="newsletter-btn">Subscribe</button>
    </form>
  </div>

  <!-- FOOTER -->
  <footer>
    <div class="footer-top">
      <div>
        <div class="footer-brand-logo">SHOW<span>INSIGHT</span></div>
        <p class="footer-tagline">Curating extraordinary entertainment experiences across Saudi Arabia and the wider Middle East region.</p>
      </div>
      <div>
        <div class="footer-col-title">Navigate</div>
        <ul class="footer-links">
          <li><a onclick="navigate('home')">Home</a></li>
          <li><a onclick="navigate('performers')">Performers</a></li>
          <li><a onclick="navigate('shows')">Shows</a></li>
          <li><a onclick="navigate('packages')">Packages</a></li>
        </ul>
      </div>
      <div>
        <div class="footer-col-title">Company</div>
        <ul class="footer-links">
          <li><a onclick="navigate('about')">About Us</a></li>
          <li><a onclick="navigate('booking')">Book Now</a></li>
          <li><a>Press</a></li>
          <li><a>Careers</a></li>
        </ul>
      </div>
      <div>
        <div class="footer-col-title">Contact</div>
        <ul class="footer-links">
          <li><a>hello@showinsight.com</a></li>
          <li><a>+966 11 234 5678</a></li>
          <li><a>Riyadh, Saudi Arabia</a></li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 2026 ShowInsight. All rights reserved.</span>
      <div class="footer-social">
        <div class="social-link">𝕏</div>
        <div class="social-link">in</div>
        <div class="social-link">◎</div>
      </div>
    </div>
  </footer>
</div>

<!-- ══════════ PERFORMERS PAGE ══════════ -->
<div class="page" id="page-performers">
  <div style="height:100px; background:var(--black)"></div>
  <section style="padding-top:60px; background:var(--black)">
    <div class="performers-header">
      <div>
        <div class="section-eyebrow">Elite Roster</div>
        <div class="section-title">OUR<br><em>Performers</em></div>
      </div>
      <div class="performer-filters">
        <button class="filter-btn active" onclick="filterPerformers(this,'all')">All</button>
        <button class="filter-btn" onclick="filterPerformers(this,'dj')">DJs</button>
        <button class="filter-btn" onclick="filterPerformers(this,'dancer')">Dancers</button>
        <button class="filter-btn" onclick="filterPerformers(this,'musician')">Musicians</button>
        <button class="filter-btn" onclick="filterPerformers(this,'vocalist')">Vocalists</button>
      </div>
    </div>
    <div class="performers-grid" id="performersGrid">
      <div class="performer-card" data-type="dj">
        <div class="performer-portrait p1">🎧</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $1,200</div>
        <div class="performer-info">
          <div class="performer-type">DJ / Producer</div>
          <div class="performer-name">DJ NOIR</div>
          <div class="performer-rating"><span class="stars">★★★★★</span> 5.0 (48 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
      <div class="performer-card" data-type="dancer">
        <div class="performer-portrait p2">💃</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $800</div>
        <div class="performer-info">
          <div class="performer-type">Contemporary Dancer</div>
          <div class="performer-name">ARIA CHEN</div>
          <div class="performer-rating"><span class="stars">★★★★★</span> 4.9 (32 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
      <div class="performer-card" data-type="musician">
        <div class="performer-portrait p3">🎻</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $950</div>
        <div class="performer-info">
          <div class="performer-type">Violinist</div>
          <div class="performer-name">LEO STRAVE</div>
          <div class="performer-rating"><span class="stars">★★★★★</span> 5.0 (27 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
      <div class="performer-card" data-type="vocalist">
        <div class="performer-portrait p4">🎤</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $1,500</div>
        <div class="performer-info">
          <div class="performer-type">Jazz Vocalist</div>
          <div class="performer-name">MAYA SOLIS</div>
          <div class="performer-rating"><span class="stars">★★★★☆</span> 4.8 (61 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
      <div class="performer-card" data-type="dj">
        <div class="performer-portrait" style="background:linear-gradient(160deg,#001a10,#003520,#001a0d)">🎛️</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $1,400</div>
        <div class="performer-info">
          <div class="performer-type">DJ / Live Sets</div>
          <div class="performer-name">ECHO MAX</div>
          <div class="performer-rating"><span class="stars">★★★★★</span> 5.0 (39 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
      <div class="performer-card" data-type="dancer">
        <div class="performer-portrait" style="background:linear-gradient(160deg,#1a1000,#352000,#1a1000)">🕺</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $700</div>
        <div class="performer-info">
          <div class="performer-type">Latin Dancer</div>
          <div class="performer-name">CARLOS VEGA</div>
          <div class="performer-rating"><span class="stars">★★★★★</span> 4.9 (55 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
      <div class="performer-card" data-type="musician">
        <div class="performer-portrait" style="background:linear-gradient(160deg,#001515,#002a2a,#001515)">🎷</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $880</div>
        <div class="performer-info">
          <div class="performer-type">Saxophonist</div>
          <div class="performer-name">JADE MONROE</div>
          <div class="performer-rating"><span class="stars">★★★★★</span> 5.0 (22 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
      <div class="performer-card" data-type="vocalist">
        <div class="performer-portrait" style="background:linear-gradient(160deg,#150010,#2a0020,#150010)">🎵</div>
        <div class="performer-overlay"></div>
        <div class="performer-price">From $1,800</div>
        <div class="performer-info">
          <div class="performer-type">Opera Vocalist</div>
          <div class="performer-name">ELENA VOSS</div>
          <div class="performer-rating"><span class="stars">★★★★★</span> 5.0 (18 events)</div>
          <div class="performer-cta">→ View Profile & Book</div>
        </div>
      </div>
    </div>
    <div style="text-align:center; margin-top:56px">
      <button class="btn-secondary" onclick="navigate('booking')">Book a Performer →</button>
    </div>
  </section>
  <footer style="background:var(--charcoal);border-top:1px solid var(--border);padding:32px 8vw;text-align:center;font-size:12px;color:var(--text-muted)">© 2026 ShowInsight</footer>
</div>

<!-- ══════════ SHOWS PAGE ══════════ -->
<div class="page" id="page-shows">
  <div style="height:100px; background:var(--black)"></div>
  <section style="padding-top:60px; background:var(--black)">
    <div class="section-eyebrow">Current & Upcoming</div>
    <div class="section-title">SHOWS &<br><em>Events</em></div>
    <p class="section-desc" style="margin-top:16px">Experience world-class performances curated for discerning audiences. Each show is a masterclass in artistry and atmosphere.</p>
    <div style="margin-top:64px; display:grid; gap:2px;">
      <div style="display:grid;grid-template-columns:3fr 1fr;gap:2px;">
        <div style="background:var(--charcoal);border:1px solid var(--border);padding:48px;display:grid;grid-template-columns:1fr 2fr;gap:48px;align-items:center">
          <div style="aspect-ratio:1;background:linear-gradient(135deg,#1a0a00,#3d1f00);display:flex;align-items:center;justify-content:center;font-size:80px;border-radius:2px">🎭</div>
          <div>
            <div class="show-type" style="margin-bottom:8px">★ Headline — Every Friday</div>
            <h2 style="font-family:var(--font-display);font-size:52px;letter-spacing:2px;margin-bottom:16px;line-height:0.9">THE GOLDEN HOUR</h2>
            <p style="color:var(--text-dim);font-size:14px;line-height:1.7;margin-bottom:24px">Our signature cabaret evening featuring world-class dancers, stunning acrobatics, and live vocals in an atmosphere of pure gold. Doors open at 8PM, show begins 9PM.</p>
            <div style="display:flex;gap:16px;flex-wrap:wrap;margin-bottom:24px">
              <span style="font-size:12px;color:var(--text-dim)">🕘 9:00 PM – 12:00 AM</span>
              <span style="font-size:12px;color:var(--text-dim)">📍 Main Stage</span>
              <span style="font-size:12px;color:var(--gold)">From $150/person</span>
            </div>
            <button class="btn-primary" onclick="navigate('booking')">Reserve Your Seats</button>
          </div>
        </div>
        <div style="background:var(--charcoal);border:1px solid var(--border);padding:32px;display:flex;flex-direction:column;justify-content:space-between">
          <div>
            <div style="font-size:9px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:12px">Upcoming Dates</div>
            <div id="show-calendar" style="display:flex;flex-direction:column;gap:8px"></div>
          </div>
          <div style="margin-top:24px;padding-top:24px;border-top:1px solid var(--border)">
            <div style="font-size:24px;font-family:var(--font-display);color:var(--gold)">$150+</div>
            <div style="font-size:10px;letter-spacing:1px;color:var(--text-muted)">Per person, table service included</div>
          </div>
        </div>
      </div>
      <!-- More shows -->
      <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:2px;margin-top:2px">
        <div style="background:var(--charcoal);border:1px solid var(--border);padding:36px">
          <div style="font-size:48px;margin-bottom:16px">🎸</div>
          <div class="show-type">Live Music — Saturdays</div>
          <h3 style="font-family:var(--font-display);font-size:36px;letter-spacing:1px;margin:8px 0;line-height:0.9">ELECTRIC SESSIONS</h3>
          <p style="font-size:13px;color:var(--text-dim);line-height:1.7;margin:12px 0">Live band performances spanning jazz, soul, and contemporary. Featuring rotating headline acts each week.</p>
          <div style="font-size:12px;color:var(--gold);margin-bottom:20px">From $80/person</div>
          <button class="btn-secondary" onclick="navigate('booking')" style="font-size:10px;padding:10px 24px">Book →</button>
        </div>
        <div style="background:var(--charcoal);border:1px solid var(--border);padding:36px">
          <div style="font-size:48px;margin-bottom:16px">🎧</div>
          <div class="show-type">DJ Set — Thursdays</div>
          <h3 style="font-family:var(--font-display);font-size:36px;letter-spacing:1px;margin:8px 0;line-height:0.9">MIDNIGHT PULSE</h3>
          <p style="font-size:13px;color:var(--text-dim);line-height:1.7;margin:12px 0">Curated electronic sets from our resident DJs and exclusive guest appearances. The night starts at midnight.</p>
          <div style="font-size:12px;color:var(--gold);margin-bottom:20px">From $60/person</div>
          <button class="btn-secondary" onclick="navigate('booking')" style="font-size:10px;padding:10px 24px">Book →</button>
        </div>
        <div style="background:var(--charcoal);border:1px solid var(--border);padding:36px">
          <div style="font-size:48px;margin-bottom:16px">🥂</div>
          <div class="show-type">Special Event — Monthly</div>
          <h3 style="font-family:var(--font-display);font-size:36px;letter-spacing:1px;margin:8px 0;line-height:0.9">GALA NIGHTS</h3>
          <p style="font-size:13px;color:var(--text-dim);line-height:1.7;margin:12px 0">Our exclusive monthly gala features multiple performers, fine dining pairings, and an atmosphere of pure theatre.</p>
          <div style="font-size:12px;color:var(--gold);margin-bottom:20px">From $250/person</div>
          <button class="btn-secondary" onclick="navigate('booking')" style="font-size:10px;padding:10px 24px">Book →</button>
        </div>
      </div>
    </div>
  </section>
  <footer style="background:var(--charcoal);border-top:1px solid var(--border);padding:32px 8vw;text-align:center;font-size:12px;color:var(--text-muted)">© 2026 ShowInsight</footer>
</div>

<!-- ══════════ PACKAGES PAGE ══════════ -->
<div class="page" id="page-packages">
  <div style="height:100px; background:var(--charcoal)"></div>
  <section id="packages" style="padding-top:60px">
    <div class="section-eyebrow">Pricing & Packages</div>
    <div class="section-title">CHOOSE YOUR<br><em>Experience</em></div>
    <p class="section-desc" style="margin-top:16px">Every package is fully customizable. All prices are starting from — our team will work with your specific requirements and budget.</p>
    <div class="packages-grid reveal">
      <div class="package-card">
        <div class="package-tier">Package 01</div>
        <div class="package-name">BRONZE</div>
        <div class="package-price">
          <span class="price-amount">$2,500</span>
          <span class="price-suffix">/ event</span>
        </div>
        <div class="package-divider"></div>
        <ul class="package-includes">
          <li>1 Solo Artist (2-hour set)</li>
          <li>Basic sound system</li>
          <li>Pre-event consultation</li>
          <li>Standard lighting rig</li>
          <li>Dedicated event manager</li>
          <li class="highlight" style="opacity:0.3;text-decoration:line-through">Multi-performer lineup</li>
          <li class="highlight" style="opacity:0.3;text-decoration:line-through">Custom theming</li>
        </ul>
        <button class="package-btn" onclick="navigate('booking')">Get Started</button>
      </div>
      <div class="package-card featured">
        <div class="package-tier">Package 02</div>
        <div class="package-name">SILVER</div>
        <div class="package-price">
          <span class="price-amount">$6,500</span>
          <span class="price-suffix">/ event</span>
        </div>
        <div class="package-divider"></div>
        <ul class="package-includes">
          <li class="highlight">3 Performers (DJ + Dancers + Vocalist)</li>
          <li class="highlight">Professional sound & lighting</li>
          <li class="highlight">Full event coordination</li>
          <li class="highlight">Custom set design elements</li>
          <li class="highlight">Choreography consultation</li>
          <li class="highlight">Post-event photography</li>
          <li style="opacity:0.3;text-decoration:line-through">Full production crew</li>
        </ul>
        <button class="package-btn" onclick="navigate('booking')">Book Silver</button>
      </div>
      <div class="package-card">
        <div class="package-tier">Package 03</div>
        <div class="package-name">GOLD</div>
        <div class="package-price">
          <span class="price-amount">$15,000</span>
          <span class="price-suffix">/ event</span>
        </div>
        <div class="package-divider"></div>
        <ul class="package-includes">
          <li class="highlight">Full performer ensemble (6+ artists)</li>
          <li class="highlight">Complete production crew</li>
          <li class="highlight">Custom stage design & theming</li>
          <li class="highlight">Pyrotechnics & special effects</li>
          <li class="highlight">Live streaming setup</li>
          <li class="highlight">Professional photography & video</li>
          <li class="highlight">Celebrity guest performer option</li>
        </ul>
        <button class="package-btn" onclick="navigate('booking')">Go Full Gold</button>
      </div>
    </div>
    <div style="text-align:center;margin-top:48px;padding:32px;background:var(--gray);border:1px solid var(--border)">
      <p style="font-family:var(--font-serif);font-size:22px;font-style:italic;color:var(--text-dim);margin-bottom:16px">Need something bespoke? Every great event starts with a conversation.</p>
      <button class="btn-primary" onclick="navigate('booking')">Request Custom Quote</button>
    </div>
  </section>
  <footer style="background:var(--charcoal);border-top:1px solid var(--border);padding:32px 8vw;text-align:center;font-size:12px;color:var(--text-muted)">© 2026 ShowInsight</footer>
</div>

<!-- ══════════ ABOUT PAGE ══════════ -->
<div class="page" id="page-about">
  <div style="height:100px; background:var(--black)"></div>
  <section id="about" style="padding-top:60px">
    <div class="about-grid reveal">
      <div class="about-visual">
        <div class="about-image-main">🎪</div>
        <div class="about-image-accent">
          <div class="about-accent-num">10+</div>
          <div class="about-accent-text">Years of Excellence</div>
        </div>
      </div>
      <div class="about-content">
        <div class="section-eyebrow" style="margin-bottom:16px">Our Story</div>
        <h2>SPOTLIGHT<br><em>on Craft</em></h2>
        <p style="margin-top:20px">ShowInsight was born from a singular conviction: that live entertainment, when done right, transcends the moment and becomes a memory that lasts a lifetime.</p>
        <p>Founded in Riyadh, we've spent over a decade assembling the finest roster of performers across the Middle East and beyond — DJs, dancers, musicians, vocalists, and full production crews who share our obsession with excellence.</p>
        <p>Whether you're planning an intimate private gathering or a large-scale corporate spectacular, our team brings the same relentless attention to detail to every brief.</p>
        <div class="about-pillars">
          <div class="pillar">
            <div class="pillar-title">VISION</div>
            <div class="pillar-text">Redefining what entertainment means in the modern era</div>
          </div>
          <div class="pillar">
            <div class="pillar-title">TALENT</div>
            <div class="pillar-text">Only the top 5% of auditioned performers join our roster</div>
          </div>
          <div class="pillar">
            <div class="pillar-title">CRAFT</div>
            <div class="pillar-text">Every performance is choreographed, rehearsed, and perfected</div>
          </div>
          <div class="pillar">
            <div class="pillar-title">SERVICE</div>
            <div class="pillar-text">Dedicated account management from brief to curtain call</div>
          </div>
        </div>
        <div style="margin-top:40px">
          <button class="btn-primary" onclick="navigate('booking')">Start Planning Your Event</button>
        </div>
      </div>
    </div>
  </section>
  <footer style="background:var(--charcoal);border-top:1px solid var(--border);padding:32px 8vw;text-align:center;font-size:12px;color:var(--text-muted)">© 2026 ShowInsight</footer>
</div>

<!-- ══════════ BOOKING PAGE ══════════ -->
<div class="page" id="page-booking">
  <div style="height:100px; background:var(--charcoal)"></div>
  <section id="booking" style="padding-top:60px">
    <div class="booking-grid">
      <div class="booking-info">
        <div class="section-eyebrow">Reserve Your Experience</div>
        <div class="section-title" style="font-size:clamp(40px,6vw,80px)">BOOK AN<br><em>Event</em></div>
        <h3>Your vision, our execution.</h3>
        <p>Fill in the form and our team will reach out within 24 hours with a tailored proposal. There's no commitment until you're completely happy with the plan.</p>
        <ul class="booking-features">
          <li>Free initial consultation & custom quote</li>
          <li>Dedicated event manager assigned</li>
          <li>Flexible date changes (72h notice)</li>
          <li>Full transparency on pricing — no hidden fees</li>
          <li>Post-event follow-up & feedback session</li>
        </ul>
        <div style="margin-top:40px;padding:24px;background:var(--gold-dim);border:1px solid var(--border)">
          <div style="font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:8px">Contact Directly</div>
          <div style="font-size:15px;color:var(--text-dim)">hello@showinsight.com<br>+966 11 234 5678</div>
        </div>
      </div>
      <div>
        <form class="booking-form" onsubmit="handleBooking(event)">
          <div class="form-row">
            <div class="form-group">
              <label class="form-label">First Name</label>
              <input type="text" class="form-input" placeholder="Ahmad">
            </div>
            <div class="form-group">
              <label class="form-label">Last Name</label>
              <input type="text" class="form-input" placeholder="Al-Khalid">
            </div>
          </div>
          <div class="form-group">
            <label class="form-label">Email Address</label>
            <input type="email" class="form-input" placeholder="ahmad@company.com">
          </div>
          <div class="form-group">
            <label class="form-label">Phone Number</label>
            <input type="tel" class="form-input" placeholder="+966 5X XXX XXXX">
          </div>
          <div class="form-row">
            <div class="form-group">
              <label class="form-label">Event Date</label>
              <input type="date" class="form-input" id="eventDate" onchange="calcPrice()">
            </div>
            <div class="form-group">
              <label class="form-label">Event Type</label>
              <select class="form-select" onchange="calcPrice()">
                <option value="">Select type...</option>
                <option value="corporate">Corporate Event</option>
                <option value="private">Private Party</option>
                <option value="wedding">Wedding</option>
                <option value="gala">Gala / Charity</option>
                <option value="launch">Product Launch</option>
              </select>
            </div>
          </div>
          <div class="form-group">
            <label class="form-label">Package</label>
            <select class="form-select" id="packageSelect" onchange="calcPrice()">
              <option value="">Select package...</option>
              <option value="2500">Bronze — from $2,500</option>
              <option value="6500">Silver — from $6,500</option>
              <option value="15000">Gold — from $15,000</option>
              <option value="0">Custom — Request quote</option>
            </select>
          </div>
          <div class="form-group">
            <label class="form-label">Performer Type(s)</label>
            <select class="form-select">
              <option>DJ + Dancers (most popular)</option>
              <option>Live Band</option>
              <option>Vocalist + Band</option>
              <option>Full Cabaret Production</option>
              <option>Custom mix — discuss with team</option>
            </select>
          </div>
          <div class="form-group">
            <label class="form-label">Event Location / Venue</label>
            <input type="text" class="form-input" placeholder="Venue name, city">
          </div>
          <div class="form-group">
            <label class="form-label">Additional Notes</label>
            <textarea class="form-textarea" placeholder="Tell us about your vision, expected guest count, theme, special requirements..."></textarea>
          </div>
          <div class="price-preview">
            <div>
              <div class="price-preview-label">Estimated Starting From</div>
              <div style="font-size:11px;color:var(--text-muted)">Final quote provided by our team</div>
            </div>
            <div class="price-preview-amount" id="pricePreview">$—</div>
          </div>
          <button type="submit" class="btn-primary" style="width:100%;padding:18px">Submit Booking Request →</button>
        </form>
      </div>
    </div>
  </section>
  <footer style="background:var(--charcoal);border-top:1px solid var(--border);padding:32px 8vw;text-align:center;font-size:12px;color:var(--text-muted)">© 2026 ShowInsight</footer>
</div>

<!-- ══════════ ADMIN DASHBOARD ══════════ -->
<div id="admin-panel">
  <div class="admin-sidebar">
    <div class="admin-logo">SHOW<span>INSIGHT</span><small>Admin Dashboard</small></div>
    <nav class="admin-nav">
      <div class="admin-nav-section">Overview</div>
      <div class="admin-nav-item active" onclick="adminNav(this,'overview')">
        <span class="admin-nav-icon">◈</span> Dashboard
      </div>
      <div class="admin-nav-section">Content</div>
      <div class="admin-nav-item" onclick="adminNav(this,'performers')">
        <span class="admin-nav-icon">★</span> Performers
      </div>
      <div class="admin-nav-item" onclick="adminNav(this,'shows')">
        <span class="admin-nav-icon">🎭</span> Shows
      </div>
      <div class="admin-nav-item" onclick="adminNav(this,'packages-admin')">
        <span class="admin-nav-icon">◇</span> Packages
      </div>
      <div class="admin-nav-section">Operations</div>
      <div class="admin-nav-item" onclick="adminNav(this,'bookings')">
        <span class="admin-nav-icon">📋</span> Bookings
      </div>
      <div class="admin-nav-item" onclick="adminNav(this,'content')">
        <span class="admin-nav-icon">✎</span> Content / CMS
      </div>
      <div class="admin-nav-item" onclick="adminNav(this,'newsletter')">
        <span class="admin-nav-icon">✉</span> Newsletter
      </div>
    </nav>
    <div class="admin-close" onclick="closeAdmin()">← Return to Website</div>
  </div>
  <div class="admin-main">
    <!-- Topbar -->
    <div class="admin-topbar">
      <h1 id="adminTitle">DASHBOARD</h1>
      <div class="admin-topbar-actions">
        <button class="admin-btn-secondary" id="adminSecBtn" style="display:none">Export CSV</button>
        <button class="admin-btn" id="adminPrimaryBtn" onclick="adminPrimaryAction()">+ Add New</button>
      </div>
    </div>
    <div class="admin-content">

      <!-- OVERVIEW -->
      <div class="admin-panel-section active" id="admin-overview">
        <div class="stats-grid">
          <div class="stat-card">
            <div class="stat-card-label">Total Bookings</div>
            <div class="stat-card-value">87</div>
            <div class="stat-card-change">↑ 12% this month</div>
          </div>
          <div class="stat-card">
            <div class="stat-card-label">Active Performers</div>
            <div class="stat-card-value">48</div>
            <div class="stat-card-change">↑ 3 new this week</div>
          </div>
          <div class="stat-card">
            <div class="stat-card-label">Upcoming Shows</div>
            <div class="stat-card-value">12</div>
            <div class="stat-card-change">Next: Friday 9PM</div>
          </div>
          <div class="stat-card">
            <div class="stat-card-label">Revenue (Month)</div>
            <div class="stat-card-value">$142K</div>
            <div class="stat-card-change">↑ 24% vs last month</div>
          </div>
        </div>
        <div class="admin-table-wrap">
          <div class="admin-table-header">
            <div class="admin-table-title">Recent Bookings</div>
            <input class="admin-search" placeholder="Search bookings...">
          </div>
          <table>
            <thead><tr>
              <th>Client</th><th>Event Type</th><th>Date</th><th>Package</th><th>Value</th><th>Status</th><th>Action</th>
            </tr></thead>
            <tbody>
              <tr><td>Ahmad Al-Khalid</td><td>Corporate Gala</td><td>Jun 15, 2026</td><td>Gold</td><td>$15,000</td><td><span class="status-badge badge-confirmed">Confirmed</span></td><td><button class="table-action">View</button></td></tr>
              <tr><td>Sarah Mitchell</td><td>Private Party</td><td>Jun 18, 2026</td><td>Silver</td><td>$8,200</td><td><span class="status-badge badge-pending">Pending</span></td><td><button class="table-action">View</button></td></tr>
              <tr><td>Mohammed Al-Faisal</td><td>Wedding</td><td>Jun 22, 2026</td><td>Gold</td><td>$22,000</td><td><span class="status-badge badge-confirmed">Confirmed</span></td><td><button class="table-action">View</button></td></tr>
              <tr><td>Jennifer Clarke</td><td>Product Launch</td><td>Jun 28, 2026</td><td>Bronze</td><td>$2,800</td><td><span class="status-badge badge-pending">Pending</span></td><td><button class="table-action">View</button></td></tr>
              <tr><td>Abdullah Al-Rashid</td><td>Charity Gala</td><td>Jul 3, 2026</td><td>Silver</td><td>$7,500</td><td><span class="status-badge badge-confirmed">Confirmed</span></td><td><button class="table-action">View</button></td></tr>
              <tr><td>Diana Petrova</td><td>Private Party</td><td>May 10, 2026</td><td>Bronze</td><td>$3,100</td><td><span class="status-badge badge-completed">Completed</span></td><td><button class="table-action">View</button></td></tr>
            </tbody>
          </table>
        </div>
      </div>

      <!-- PERFORMERS ADMIN -->
      <div class="admin-panel-section" id="admin-performers">
        <div class="admin-table-wrap">
          <div class="admin-table-header">
            <div class="admin-table-title">All Performers (48)</div>
            <input class="admin-search" placeholder="Search performers...">
          </div>
          <table>
            <thead><tr>
              <th>Name</th><th>Type</th><th>Base Rate</th><th>Rating</th><th>Events</th><th>Status</th><th>Actions</th>
            </tr></thead>
            <tbody>
              <tr><td>DJ Noir</td><td>DJ / Producer</td><td>$1,200</td><td>★★★★★ 5.0</td><td>48</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Remove</button></td></tr>
              <tr><td>Aria Chen</td><td>Contemporary Dancer</td><td>$800</td><td>★★★★★ 4.9</td><td>32</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Remove</button></td></tr>
              <tr><td>Leo Strave</td><td>Violinist</td><td>$950</td><td>★★★★★ 5.0</td><td>27</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Remove</button></td></tr>
              <tr><td>Maya Solis</td><td>Jazz Vocalist</td><td>$1,500</td><td>★★★★☆ 4.8</td><td>61</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Remove</button></td></tr>
              <tr><td>Echo Max</td><td>DJ / Live Sets</td><td>$1,400</td><td>★★★★★ 5.0</td><td>39</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Remove</button></td></tr>
              <tr><td>Elena Voss</td><td>Opera Vocalist</td><td>$1,800</td><td>★★★★★ 5.0</td><td>18</td><td><span class="status-badge badge-pending">On Leave</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Remove</button></td></tr>
            </tbody>
          </table>
        </div>
        <div style="margin-top:24px">
          <div style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:16px">Add New Performer</div>
          <div class="admin-form-grid">
            <div class="admin-form-group"><label class="admin-form-label">Full Name</label><input type="text" class="admin-form-input" placeholder="Performer name"></div>
            <div class="admin-form-group"><label class="admin-form-label">Performer Type</label><select class="admin-form-select"><option>DJ / Producer</option><option>Dancer</option><option>Vocalist</option><option>Musician</option><option>Other</option></select></div>
            <div class="admin-form-group"><label class="admin-form-label">Base Rate (USD)</label><input type="number" class="admin-form-input" placeholder="1200"></div>
            <div class="admin-form-group"><label class="admin-form-label">Contact Email</label><input type="email" class="admin-form-input" placeholder="performer@email.com"></div>
            <div class="admin-form-group full"><label class="admin-form-label">Bio / Description</label><textarea class="admin-form-textarea" placeholder="Brief bio for public profile..."></textarea></div>
            <div class="admin-form-group"><label class="admin-form-label">Photo URL</label><input type="text" class="admin-form-input" placeholder="https://..."></div>
            <div class="admin-form-group"><label class="admin-form-label">Tags (comma separated)</label><input type="text" class="admin-form-input" placeholder="house, techno, latin"></div>
            <div class="admin-form-actions">
              <button class="admin-btn-secondary">Clear</button>
              <button class="admin-btn" onclick="showToast('Performer added successfully!')">Save Performer</button>
            </div>
          </div>
        </div>
      </div>

      <!-- SHOWS ADMIN -->
      <div class="admin-panel-section" id="admin-shows">
        <div class="admin-table-wrap">
          <div class="admin-table-header">
            <div class="admin-table-title">All Shows</div>
            <input class="admin-search" placeholder="Search shows...">
          </div>
          <table>
            <thead><tr>
              <th>Show Name</th><th>Date</th><th>Performers</th><th>Capacity</th><th>Bookings</th><th>Status</th><th>Actions</th>
            </tr></thead>
            <tbody>
              <tr><td>The Golden Hour</td><td>Every Friday</td><td>5 performers</td><td>120</td><td>98/120</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Delete</button></td></tr>
              <tr><td>Electric Sessions</td><td>Every Saturday</td><td>4 performers</td><td>80</td><td>65/80</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Delete</button></td></tr>
              <tr><td>Midnight Pulse</td><td>Every Thursday</td><td>2 DJs</td><td>200</td><td>140/200</td><td><span class="status-badge badge-confirmed">Active</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Delete</button></td></tr>
              <tr><td>June Gala Night</td><td>Jun 30, 2026</td><td>8 performers</td><td>250</td><td>180/250</td><td><span class="status-badge badge-pending">Upcoming</span></td><td><button class="table-action">Edit</button> <button class="table-action danger">Delete</button></td></tr>
            </tbody>
          </table>
        </div>
        <div style="margin-top:24px">
          <div style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:16px">Create New Show</div>
          <div class="admin-form-grid">
            <div class="admin-form-group"><label class="admin-form-label">Show Name</label><input type="text" class="admin-form-input" placeholder="The Golden Hour"></div>
            <div class="admin-form-group"><label class="admin-form-label">Show Type</label><select class="admin-form-select"><option>Cabaret</option><option>Live Music</option><option>DJ Set</option><option>Gala</option><option>Special Event</option></select></div>
            <div class="admin-form-group"><label class="admin-form-label">Date / Schedule</label><input type="text" class="admin-form-input" placeholder="e.g. Every Friday or Jun 30, 2026"></div>
            <div class="admin-form-group"><label class="admin-form-label">Capacity</label><input type="number" class="admin-form-input" placeholder="120"></div>
            <div class="admin-form-group"><label class="admin-form-label">Ticket Price</label><input type="number" class="admin-form-input" placeholder="150"></div>
            <div class="admin-form-group"><label class="admin-form-label">Status</label><select class="admin-form-select"><option>upcoming</option><option>active</option><option>past</option></select></div>
            <div class="admin-form-group full"><label class="admin-form-label">Description</label><textarea class="admin-form-textarea" placeholder="Show description for public listing..."></textarea></div>
            <div class="admin-form-actions">
              <button class="admin-btn-secondary">Clear</button>
              <button class="admin-btn" onclick="showToast('Show created!')">Create Show</button>
            </div>
          </div>
        </div>
      </div>

      <!-- PACKAGES ADMIN -->
      <div class="admin-panel-section" id="admin-packages-admin">
        <div class="admin-table-wrap">
          <div class="admin-table-header">
            <div class="admin-table-title">Pricing Packages</div>
          </div>
          <table>
            <thead><tr>
              <th>Package</th><th>Base Price</th><th>Inclusions</th><th>Active Bookings</th><th>Actions</th>
            </tr></thead>
            <tbody>
              <tr><td><strong>Bronze</strong></td><td>$2,500</td><td>1 performer, 2h set, basic AV</td><td>14</td><td><button class="table-action">Edit Pricing</button></td></tr>
              <tr><td><strong>Silver</strong> ⭐</td><td>$6,500</td><td>3 performers, full AV, coordination</td><td>38</td><td><button class="table-action">Edit Pricing</button></td></tr>
              <tr><td><strong>Gold</strong></td><td>$15,000</td><td>6+ performers, full production</td><td>22</td><td><button class="table-action">Edit Pricing</button></td></tr>
              <tr><td><strong>Custom</strong></td><td>On request</td><td>Fully bespoke</td><td>13</td><td><button class="table-action">Edit</button></td></tr>
            </tbody>
          </table>
        </div>
        <div style="margin-top:24px;background:var(--charcoal);border:1px solid var(--border);padding:32px">
          <div style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:20px">Edit Package Pricing</div>
          <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:20px">
            <div class="admin-form-group"><label class="admin-form-label">Bronze Base Price</label><input type="number" class="admin-form-input" value="2500"></div>
            <div class="admin-form-group"><label class="admin-form-label">Silver Base Price</label><input type="number" class="admin-form-input" value="6500"></div>
            <div class="admin-form-group"><label class="admin-form-label">Gold Base Price</label><input type="number" class="admin-form-input" value="15000"></div>
          </div>
          <div style="margin-top:16px;display:flex;justify-content:flex-end">
            <button class="admin-btn" onclick="showToast('Pricing updated!')">Update Pricing</button>
          </div>
        </div>
      </div>

      <!-- BOOKINGS ADMIN -->
      <div class="admin-panel-section" id="admin-bookings">
        <div style="display:flex;gap:8px;margin-bottom:16px">
          <button class="filter-btn active" onclick="filterBookings(this,'all')">All</button>
          <button class="filter-btn" onclick="filterBookings(this,'pending')">Pending</button>
          <button class="filter-btn" onclick="filterBookings(this,'confirmed')">Confirmed</button>
          <button class="filter-btn" onclick="filterBookings(this,'completed')">Completed</button>
        </div>
        <div class="admin-table-wrap">
          <div class="admin-table-header">
            <div class="admin-table-title">All Bookings (87)</div>
            <div style="display:flex;gap:8px">
              <input class="admin-search" placeholder="Search...">
              <button class="admin-btn-secondary">Export CSV</button>
            </div>
          </div>
          <table>
            <thead><tr>
              <th>Client</th><th>Event</th><th>Date</th><th>Package</th><th>Total</th><th>Status</th><th>Actions</th>
            </tr></thead>
            <tbody id="bookingsTable">
              <tr data-status="confirmed"><td>Ahmad Al-Khalid</td><td>Corporate Gala</td><td>Jun 15</td><td>Gold</td><td>$15,000</td><td><span class="status-badge badge-confirmed">Confirmed</span></td><td><button class="table-action">View</button> <button class="table-action" onclick="showToast('Email sent!')">Email</button></td></tr>
              <tr data-status="pending"><td>Sarah Mitchell</td><td>Private Party</td><td>Jun 18</td><td>Silver</td><td>$8,200</td><td><span class="status-badge badge-pending">Pending</span></td><td><button class="table-action" onclick="showToast('Booking confirmed!')">Confirm</button> <button class="table-action danger" onclick="showToast('Booking rejected')">Reject</button></td></tr>
              <tr data-status="confirmed"><td>Mohammed Al-Faisal</td><td>Wedding</td><td>Jun 22</td><td>Gold</td><td>$22,000</td><td><span class="status-badge badge-confirmed">Confirmed</span></td><td><button class="table-action">View</button> <button class="table-action" onclick="showToast('Email sent!')">Email</button></td></tr>
              <tr data-status="pending"><td>Jennifer Clarke</td><td>Product Launch</td><td>Jun 28</td><td>Bronze</td><td>$2,800</td><td><span class="status-badge badge-pending">Pending</span></td><td><button class="table-action" onclick="showToast('Booking confirmed!')">Confirm</button> <button class="table-action danger">Reject</button></td></tr>
              <tr data-status="completed"><td>Diana Petrova</td><td>Private Party</td><td>May 10</td><td>Bronze</td><td>$3,100</td><td><span class="status-badge badge-completed">Completed</span></td><td><button class="table-action">View</button></td></tr>
              <tr data-status="cancelled"><td>Mark Johnson</td><td>Birthday</td><td>Apr 28</td><td>Silver</td><td>$6,500</td><td><span class="status-badge badge-cancelled">Cancelled</span></td><td><button class="table-action">Archive</button></td></tr>
            </tbody>
          </table>
        </div>
      </div>

      <!-- CONTENT ADMIN -->
      <div class="admin-panel-section" id="admin-content">
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px">
          <div class="admin-form-grid" style="height:fit-content">
            <div class="admin-form-group full"><div style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:4px">Hero Section</div></div>
            <div class="admin-form-group"><label class="admin-form-label">Hero Headline</label><input type="text" class="admin-form-input" value="WHERE THE STAGE COMES ALIVE"></div>
            <div class="admin-form-group"><label class="admin-form-label">Hero Subheadline</label><input type="text" class="admin-form-input" value="em: Stage Comes"></div>
            <div class="admin-form-group full"><label class="admin-form-label">Hero Description</label><textarea class="admin-form-textarea" style="min-height:80px">Curating extraordinary entertainment for unforgettable events.</textarea></div>
            <div class="admin-form-actions">
              <button class="admin-btn" onclick="showToast('Hero section updated!')">Save Changes</button>
            </div>
          </div>
          <div class="admin-form-grid" style="height:fit-content">
            <div class="admin-form-group full"><div style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:4px">FAQ Management</div></div>
            <div class="admin-form-group full"><label class="admin-form-label">FAQ Question</label><input type="text" class="admin-form-input" placeholder="Enter question..."></div>
            <div class="admin-form-group full"><label class="admin-form-label">FAQ Answer</label><textarea class="admin-form-textarea" placeholder="Enter answer..." style="min-height:80px"></textarea></div>
            <div class="admin-form-actions">
              <button class="admin-btn" onclick="showToast('FAQ added!')">Add FAQ Item</button>
            </div>
          </div>
          <div class="admin-form-grid" style="grid-column:span 2; height:fit-content">
            <div class="admin-form-group full"><div style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:4px">Testimonials</div></div>
            <div class="admin-form-group"><label class="admin-form-label">Client Name</label><input type="text" class="admin-form-input" placeholder="Client name"></div>
            <div class="admin-form-group"><label class="admin-form-label">Client Role / Company</label><input type="text" class="admin-form-input" placeholder="Director, Company Name"></div>
            <div class="admin-form-group full"><label class="admin-form-label">Testimonial Quote</label><textarea class="admin-form-textarea" placeholder="What did they say..." style="min-height:80px"></textarea></div>
            <div class="admin-form-actions">
              <button class="admin-btn" onclick="showToast('Testimonial added!')">Add Testimonial</button>
            </div>
          </div>
        </div>
      </div>

      <!-- NEWSLETTER ADMIN -->
      <div class="admin-panel-section" id="admin-newsletter">
        <div class="stats-grid" style="grid-template-columns:repeat(3,1fr)">
          <div class="stat-card"><div class="stat-card-label">Total Subscribers</div><div class="stat-card-value">1,284</div><div class="stat-card-change">↑ 47 this week</div></div>
          <div class="stat-card"><div class="stat-card-label">Open Rate</div><div class="stat-card-value">68%</div><div class="stat-card-change">↑ Above industry avg</div></div>
          <div class="stat-card"><div class="stat-card-label">Last Campaign</div><div class="stat-card-value">May 1</div><div class="stat-card-change">342 opens, 128 clicks</div></div>
        </div>
        <div class="admin-table-wrap">
          <div class="admin-table-header">
            <div class="admin-table-title">Recent Subscribers</div>
            <div style="display:flex;gap:8px">
              <input class="admin-search" placeholder="Search subscribers...">
              <button class="admin-btn-secondary">Export List</button>
            </div>
          </div>
          <table>
            <thead><tr><th>Email</th><th>Subscribed</th><th>Source</th><th>Action</th></tr></thead>
            <tbody>
              <tr><td>a.khalid@gmail.com</td><td>May 14, 2026</td><td>Homepage</td><td><button class="table-action danger">Unsubscribe</button></td></tr>
              <tr><td>sarah.m@company.com</td><td>May 13, 2026</td><td>Homepage</td><td><button class="table-action danger">Unsubscribe</button></td></tr>
              <tr><td>m.faisal@business.sa</td><td>May 12, 2026</td><td>Booking form</td><td><button class="table-action danger">Unsubscribe</button></td></tr>
              <tr><td>jenny.c@events.com</td><td>May 10, 2026</td><td>Homepage</td><td><button class="table-action danger">Unsubscribe</button></td></tr>
            </tbody>
          </table>
        </div>
        <div style="margin-top:24px;background:var(--charcoal);border:1px solid var(--border);padding:32px">
          <div style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:16px">Send Newsletter Campaign</div>
          <div class="admin-form-grid">
            <div class="admin-form-group"><label class="admin-form-label">Subject Line</label><input type="text" class="admin-form-input" placeholder="Email subject..."></div>
            <div class="admin-form-group"><label class="admin-form-label">Send To</label><select class="admin-form-select"><option>All Subscribers (1,284)</option><option>Recent (last 30 days)</option><option>Custom segment</option></select></div>
            <div class="admin-form-group full"><label class="admin-form-label">Message Body</label><textarea class="admin-form-textarea" placeholder="Email content..." style="min-height:120px"></textarea></div>
            <div class="admin-form-actions">
              <button class="admin-btn-secondary">Preview</button>
              <button class="admin-btn" onclick="showToast('Campaign sent to 1,284 subscribers!')">Send Campaign</button>
            </div>
          </div>
        </div>
      </div>

    </div><!-- /admin-content -->
  </div><!-- /admin-main -->
</div>

<!-- LOGIN MODAL -->
<div class="modal-overlay" id="login-modal">
  <div class="modal" id="loginModal">
    <button class="modal-close" onclick="closeModal('login-modal')">✕</button>
    <div class="modal-title">ADMIN<br>ACCESS</div>
    <p class="modal-sub">Enter your credentials to access the dashboard</p>
    <form class="login-form" onsubmit="handleLogin(event)">
      <div class="form-group">
        <label class="form-label">Email</label>
        <input type="email" class="form-input" placeholder="admin@showinsight.com" id="loginEmail">
      </div>
      <div class="form-group">
        <label class="form-label">Password</label>
        <input type="password" class="form-input" placeholder="••••••••" id="loginPass">
      </div>
      <button type="submit" class="btn-primary" style="width:100%;margin-top:8px">Access Dashboard</button>
    </form>
    <p style="text-align:center;margin-top:16px;font-size:11px;color:var(--text-muted)">Demo: any email + password</p>
  </div>
</div>

<script>
// ── CURSOR ──
const cursor = document.getElementById('cursor');
const cursorRing = document.getElementById('cursorRing');
let mx=0,my=0,rx=0,ry=0;
document.addEventListener('mousemove', e => { mx=e.clientX; my=e.clientY; cursor.style.left=mx+'px'; cursor.style.top=my+'px'; });
function animateRing(){rx+=(mx-rx)*0.12; ry+=(my-ry)*0.12; cursorRing.style.left=rx+'px'; cursorRing.style.top=ry+'px'; requestAnimationFrame(animateRing); }
animateRing();
document.querySelectorAll('a,button,.performer-card,.show-card,.package-card,.admin-nav-item').forEach(el=>{
  el.addEventListener('mouseenter',()=>{ cursorRing.style.transform='translate(-50%,-50%) scale(1.8)'; cursorRing.style.background=cursorRing.style.background='rgba(212,175,55,0.08)'; });
  el.addEventListener('mouseleave',()=>{ cursorRing.style.transform='translate(-50%,-50%) scale(1)'; cursorRing.style.background=''; });
});

// ── NAV SCROLL ──
window.addEventListener('scroll', ()=>{
  document.getElementById('mainNav').classList.toggle('scrolled', window.scrollY>60);
});

// ── NAVIGATION ──
function navigate(page){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-'+page).classList.add('active');
  document.querySelectorAll('.nav-links a').forEach(a=>a.classList.remove('active'));
  const navEl = document.getElementById('nav-'+page);
  if(navEl) navEl.classList.add('active');
  window.scrollTo(0,0);
  triggerReveal();
}

// ── SCROLL REVEAL ──
function triggerReveal(){
  setTimeout(()=>{
    document.querySelectorAll('.reveal').forEach(el=>{
      const rect=el.getBoundingClientRect();
      if(rect.top < window.innerHeight*0.9) el.classList.add('visible');
    });
  },100);
}
window.addEventListener('scroll', ()=>{
  document.querySelectorAll('.reveal:not(.visible)').forEach(el=>{
    const rect=el.getBoundingClientRect();
    if(rect.top < window.innerHeight*0.85) el.classList.add('visible');
  });
});
triggerReveal();

// ── TESTIMONIAL SLIDER ──
let tIdx=0;
function goTestimonial(i){
  document.querySelectorAll('.testimonial').forEach(t=>t.classList.remove('active'));
  document.querySelectorAll('.dot').forEach(d=>d.classList.remove('active'));
  tIdx=i;
  document.querySelectorAll('.testimonial')[i].classList.add('active');
  document.querySelectorAll('.dot')[i].classList.add('active');
}
setInterval(()=>{ goTestimonial((tIdx+1)%3); },5000);

// ── PERFORMER FILTER ──
function filterPerformers(btn, type){
  document.querySelectorAll('.filter-btn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  document.querySelectorAll('.performer-card').forEach(c=>{
    c.style.display = (type==='all'||c.dataset.type===type) ? 'block' : 'none';
  });
}

// ── SHOW CALENDAR ──
(function(){
  const cal = document.getElementById('show-calendar');
  if(!cal) return;
  const dates = ['May 16', 'May 23', 'May 30', 'Jun 6', 'Jun 13', 'Jun 20'];
  dates.forEach(d=>{
    cal.innerHTML += `<div style="display:flex;justify-content:space-between;align-items:center;padding:10px 0;border-bottom:1px solid rgba(255,255,255,0.05);font-size:13px">
      <span style="color:var(--text-dim)">${d}, 2026</span>
      <span style="font-size:9px;letter-spacing:1px;text-transform:uppercase;color:var(--gold);background:var(--gold-dim);padding:3px 10px;border-radius:20px">
        ${Math.random()>0.3?'Available':'Few seats'}
      </span>
    </div>`;
  });
})();

// ── PRICE CALCULATOR ──
function calcPrice(){
  const pkg = document.getElementById('packageSelect').value;
  const el = document.getElementById('pricePreview');
  if(!pkg || pkg==='0') { el.textContent='Custom'; return; }
  el.textContent = '$' + parseInt(pkg).toLocaleString();
}

// ── BOOKING FORM ──
function handleBooking(e){
  e.preventDefault();
  showToast('Booking request submitted! We\'ll be in touch within 24 hours.');
  e.target.reset();
  document.getElementById('pricePreview').textContent='$—';
}

// ── NEWSLETTER ──
function handleNewsletter(e){
  e.preventDefault();
  showToast('Welcome! You\'re now on the exclusive list.');
  e.target.reset();
}

// ── ADMIN ──
function openAdmin(){
  document.getElementById('login-modal').classList.add('open');
}
function handleLogin(e){
  e.preventDefault();
  closeModal('login-modal');
  document.getElementById('admin-panel').classList.add('open');
  document.body.style.overflow='hidden';
}
function closeAdmin(){
  document.getElementById('admin-panel').classList.remove('open');
  document.body.style.overflow='';
}
function adminNav(el, section){
  document.querySelectorAll('.admin-nav-item').forEach(i=>i.classList.remove('active'));
  el.classList.add('active');
  document.querySelectorAll('.admin-panel-section').forEach(s=>s.classList.remove('active'));
  const sec = document.getElementById('admin-'+section);
  if(sec) sec.classList.add('active');
  document.getElementById('adminTitle').textContent = el.textContent.trim().toUpperCase();
}
function adminPrimaryAction(){ showToast('Feature coming soon!'); }
function filterBookings(btn, status){
  document.querySelectorAll('#admin-bookings .filter-btn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  document.querySelectorAll('#bookingsTable tr').forEach(r=>{
    r.style.display=(status==='all'||r.dataset.status===status)?'':'none';
  });
}

// ── MODAL ──
function closeModal(id){
  document.getElementById(id).classList.remove('open');
}
document.querySelectorAll('.modal-overlay').forEach(m=>{
  m.addEventListener('click',e=>{ if(e.target===m) m.classList.remove('open'); });
});

// ── TOAST ──
function showToast(msg){
  const t = document.createElement('div');
  t.className='toast'; t.textContent=msg;
  document.body.appendChild(t);
  setTimeout(()=>t.remove(), 3500);
}
</script>
</body>
</html>
