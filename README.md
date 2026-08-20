<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>M&E Passagens — Comprando com milhas, a passagem sai mais barata.</title>
<meta name="description" content="M&E Passagens: compre passagens mais baratas usando milhas — mesmo sem ter nenhuma. Inteligência de mercado, planejamento de rota e garantia de ponta a ponta.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='20' fill='%230D1B2A'/%3E%3Cpath d='M25 72 L25 26 L50 54 L75 26 L75 72' fill='none' stroke='%23FFFFFF' stroke-width='9' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M62 40 L74 26 L84 30 L70 44 Z' fill='%23C9A227'/%3E%3C/svg%3E">
<style>
  :root{
    --navy:#0D1B2A;
    --navy-2:#132638;
    --teal:#0E5F6E;
    --gold:#C9A227;
    --gold-light:#E4C766;
    --gray-light:#E6E8EB;
    --graphite:#3A3F44;
    --off-white:#F6F5F1;
    --white:#FFFFFF;
    --text:#1B2430;
    --muted:#6B7280;
    --radius:18px;
    --shadow:0 20px 50px -20px rgba(13,27,42,.25);
    --ease:cubic-bezier(.19,1,.22,1);
  }
  *{box-sizing:border-box;margin:0;padding:0;}
  html{scroll-behavior:smooth;}
  body{
    font-family:'Inter',sans-serif;
    color:var(--text);
    background:var(--off-white);
    line-height:1.6;
    overflow-x:hidden;
  }
  h1,h2,h3,h4,.font-heading{
    font-family:'Poppins',sans-serif;
    font-weight:600;
    letter-spacing:-0.02em;
    color:var(--navy);
  }
  a{color:inherit;text-decoration:none;}
  img,svg{display:block;max-width:100%;}
  ul{list-style:none;}
  .container{
    width:100%;
    max-width:1180px;
    margin:0 auto;
    padding:0 24px;
  }
  .eyebrow{
    display:inline-flex;
    align-items:center;
    gap:8px;
    font-family:'Poppins',sans-serif;
    font-size:12.5px;
    font-weight:600;
    letter-spacing:.14em;
    text-transform:uppercase;
    color:var(--gold);
  }
  .eyebrow::before{
    content:"";
    width:22px;height:2px;
    background:var(--gold);
    border-radius:2px;
  }
  .btn{
    display:inline-flex;
    align-items:center;
    justify-content:center;
    gap:10px;
    font-family:'Poppins',sans-serif;
    font-weight:600;
    font-size:15px;
    padding:15px 30px;
    border-radius:100px;
    cursor:pointer;
    border:none;
    transition:transform .35s var(--ease), box-shadow .35s var(--ease), background .3s ease, color .3s ease;
    white-space:nowrap;
  }
  .btn-primary{
    background:linear-gradient(135deg,var(--gold-light),var(--gold));
    color:var(--navy);
    box-shadow:0 12px 30px -10px rgba(201,162,39,.55);
  }
  .btn-primary:hover{transform:translateY(-3px);box-shadow:0 18px 36px -12px rgba(201,162,39,.65);}
  .btn-outline{
    background:transparent;
    border:1.5px solid rgba(255,255,255,.35);
    color:#fff;
  }
  .btn-outline:hover{background:rgba(255,255,255,.08);transform:translateY(-3px);}
  .btn-outline-dark{
    background:transparent;
    border:1.5px solid rgba(13,27,42,.18);
    color:var(--navy);
  }
  .btn-outline-dark:hover{background:rgba(13,27,42,.05);transform:translateY(-3px);}
  .btn svg{width:17px;height:17px;}

  /* ---------- HEADER ---------- */
  header{
    position:fixed;
    top:0;left:0;right:0;
    z-index:1000;
    padding:22px 0;
    transition:padding .4s var(--ease), background .4s var(--ease), box-shadow .4s var(--ease);
  }
  header.scrolled{
    padding:12px 0;
    background:rgba(13,27,42,.85);
    backdrop-filter:blur(14px) saturate(160%);
    box-shadow:0 10px 30px -18px rgba(0,0,0,.5);
  }
  .nav-wrap{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:24px;
  }
  .logo{
    display:flex;
    align-items:center;
    gap:11px;
  }
  .logo svg{width:38px;height:38px;flex-shrink:0;}
  .logo-word{
    font-family:'Poppins',sans-serif;
    font-weight:600;
    font-size:16.5px;
    letter-spacing:.09em;
    color:#fff;
  }
  nav.main-nav{
    display:flex;
    align-items:center;
    gap:38px;
  }
  nav.main-nav a{
    font-family:'Poppins',sans-serif;
    font-size:14px;
    font-weight:500;
    color:rgba(255,255,255,.82);
    position:relative;
    padding:4px 0;
    transition:color .3s ease;
  }
  nav.main-nav a::after{
    content:"";
    position:absolute;
    left:0;bottom:-2px;
    width:0;height:2px;
    background:var(--gold);
    transition:width .35s var(--ease);
  }
  nav.main-nav a:hover{color:#fff;}
  nav.main-nav a:hover::after{width:100%;}
  .header-actions{display:flex;align-items:center;gap:18px;}
  .btn-nav-cta{padding:12px 24px;font-size:13.5px;}
  .burger{
    display:none;
    flex-direction:column;
    gap:5px;
    background:none;border:none;cursor:pointer;
    padding:6px;
  }
  .burger span{width:24px;height:2px;background:#fff;border-radius:2px;transition:transform .3s ease, opacity .3s ease;}
  .mobile-panel{
    position:fixed;
    inset:0 0 auto 0;
    top:0;
    background:var(--navy);
    padding:100px 28px 40px;
    display:flex;
    flex-direction:column;
    gap:26px;
    transform:translateY(-110%);
    transition:transform .45s var(--ease);
    z-index:999;
  }
  .mobile-panel.open{transform:translateY(0);}
  .mobile-panel a{
    font-family:'Poppins',sans-serif;
    font-size:20px;
    font-weight:500;
    color:#fff;
  }

  /* ---------- HERO ---------- */
  .hero{
    position:relative;
    background:radial-gradient(120% 100% at 15% 0%, #16324a 0%, var(--navy) 46%, #081119 100%);
    color:#fff;
    padding:190px 0 150px;
    overflow:hidden;
  }
  .hero::before{
    content:"";
    position:absolute;
    inset:0;
    background-image:radial-gradient(rgba(255,255,255,.06) 1px, transparent 1px);
    background-size:26px 26px;
    opacity:.5;
    mask-image:radial-gradient(ellipse 70% 60% at 60% 30%, black 10%, transparent 75%);
  }
  .hero-grid{
    position:relative;
    z-index:2;
    display:grid;
    grid-template-columns:1.05fr .95fr;
    gap:50px;
    align-items:center;
  }
  .hero h1{
    color:#fff;
    font-size:clamp(34px,4.6vw,58px);
    line-height:1.08;
    margin:18px 0 22px;
  }
  .hero h1 .accent{color:var(--gold);}
  .hero-sub{
    font-family:'Poppins',sans-serif;
    font-weight:500;
    font-size:clamp(16px,1.6vw,19px);
    color:var(--gold-light);
    margin-bottom:16px;
  }
  .hero p.lead{
    max-width:520px;
    font-size:16.5px;
    color:rgba(255,255,255,.72);
    margin-bottom:38px;
  }
  .hero-ctas{display:flex;gap:16px;flex-wrap:wrap;margin-bottom:52px;}
  .hero-tags{display:flex;flex-wrap:wrap;gap:12px;}
  .hero-tag{
    font-family:'Poppins',sans-serif;
    font-size:12.5px;
    font-weight:500;
    letter-spacing:.03em;
    color:rgba(255,255,255,.82);
    border:1px solid rgba(255,255,255,.18);
    padding:9px 16px;
    border-radius:100px;
    background:rgba(255,255,255,.04);
  }

  /* hero visual: animated route */
  .hero-visual{
    position:relative;
    height:460px;
  }
  .route-card{
    position:absolute;
    inset:0;
    border-radius:24px;
    background:linear-gradient(160deg, rgba(255,255,255,.06), rgba(255,255,255,.015));
    border:1px solid rgba(255,255,255,.1);
    backdrop-filter:blur(6px);
    overflow:hidden;
  }
  .route-svg{width:100%;height:100%;}
  .route-path{
    fill:none;
    stroke:url(#routeGradient);
    stroke-width:2.5;
    stroke-linecap:round;
    stroke-dasharray:6 10;
    animation:dashMove 3.2s linear infinite;
  }
  @keyframes dashMove{to{stroke-dashoffset:-160;}}
  .plane-on-path{
    offset-path:path("M40,380 C120,330 150,220 230,190 C300,165 340,120 380,70");
    animation:flyPath 6s var(--ease) infinite;
  }
  @keyframes flyPath{
    0%{offset-distance:0%;opacity:0;}
    8%{opacity:1;}
    92%{opacity:1;}
    100%{offset-distance:100%;opacity:0;}
  }
  .float-card{
    position:absolute;
    background:#fff;
    border-radius:14px;
    box-shadow:0 20px 45px -16px rgba(0,0,0,.35);
    padding:14px 18px;
    display:flex;
    align-items:center;
    gap:12px;
    animation:floatY 5s ease-in-out infinite;
  }
  .float-card .ic{
    width:34px;height:34px;
    border-radius:9px;
    display:flex;align-items:center;justify-content:center;
    flex-shrink:0;
  }
  .float-card .ic svg{width:18px;height:18px;}
  .float-card p{font-family:'Poppins',sans-serif;font-size:12.5px;font-weight:600;color:var(--navy);white-space:nowrap;}
  .float-card span{display:block;font-size:10.5px;color:var(--muted);font-weight:500;}
  .fc-1{top:14%;left:2%;animation-delay:.2s;}
  .fc-1 .ic{background:rgba(14,95,110,.12);color:var(--teal);}
  .fc-2{bottom:16%;right:0%;animation-delay:1.4s;}
  .fc-2 .ic{background:rgba(201,162,39,.15);color:var(--gold);}
  @keyframes floatY{0%,100%{transform:translateY(0);}50%{transform:translateY(-12px);}}

  /* section basics */
  section{position:relative;padding:120px 0;}
  .section-head{max-width:640px;margin-bottom:60px;}
  .section-head h2{font-size:clamp(28px,3.4vw,42px);line-height:1.16;margin-top:14px;}
  .section-head p{color:var(--muted);font-size:16px;margin-top:16px;max-width:560px;}
  .section-head.center{margin-left:auto;margin-right:auto;text-align:center;}

  .reveal{opacity:0;transform:translateY(36px);transition:opacity .9s var(--ease), transform .9s var(--ease);}
  .reveal.in{opacity:1;transform:translateY(0);}
  .reveal-delay-1{transition-delay:.1s;}
  .reveal-delay-2{transition-delay:.22s;}
  .reveal-delay-3{transition-delay:.34s;}
  .reveal-delay-4{transition-delay:.46s;}

  /* ---------- PROBLEMA ---------- */
  .problem{background:var(--off-white);}
  .problem-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:24px;
    margin-bottom:44px;
  }
  .problem-card{
    background:#fff;
    border:1px solid rgba(13,27,42,.07);
    border-radius:var(--radius);
    padding:32px 28px;
    transition:transform .4s var(--ease), box-shadow .4s var(--ease);
  }
  .problem-card:hover{transform:translateY(-6px);box-shadow:var(--shadow);}
  .problem-card .num{
    font-family:'Poppins',sans-serif;
    font-weight:600;
    font-size:13px;
    color:var(--gold);
    letter-spacing:.05em;
    margin-bottom:16px;
    display:block;
  }
  .problem-card h3{font-size:18.5px;margin-bottom:10px;}
  .problem-card p{color:var(--muted);font-size:14.8px;}
  .problem-close{
    text-align:center;
    font-family:'Poppins',sans-serif;
    font-size:clamp(19px,2.2vw,25px);
    font-weight:500;
    color:var(--navy);
    max-width:720px;
    margin:0 auto;
  }
  .problem-close .accent{color:var(--teal);font-weight:600;}

  /* ---------- SOLUÇÃO ---------- */
  .solution{background:var(--navy);color:#fff;}
  .solution .eyebrow{color:var(--gold);}
  .solution .section-head h2{color:#fff;}
  .solution .section-head p{color:rgba(255,255,255,.62);}
  .steps{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:0;
    position:relative;
    margin-bottom:56px;
  }
  .steps::before{
    content:"";
    position:absolute;
    top:34px;left:12%;right:12%;
    height:1px;
    background:repeating-linear-gradient(to right, rgba(201,162,39,.45) 0 8px, transparent 8px 16px);
    z-index:0;
  }
  .step{
    position:relative;
    z-index:1;
    padding:0 26px;
  }
  .step-index{
    width:68px;height:68px;
    border-radius:50%;
    background:linear-gradient(150deg, rgba(201,162,39,.18), rgba(201,162,39,.05));
    border:1px solid rgba(201,162,39,.4);
    color:var(--gold-light);
    font-family:'Poppins',sans-serif;
    font-weight:600;
    font-size:22px;
    display:flex;align-items:center;justify-content:center;
    margin-bottom:24px;
  }
  .step h3{color:#fff;font-size:19px;margin-bottom:10px;}
  .step p{color:rgba(255,255,255,.62);font-size:14.8px;}
  .solution-note{
    display:flex;
    gap:18px;
    align-items:flex-start;
    background:rgba(255,255,255,.05);
    border:1px solid rgba(255,255,255,.1);
    border-radius:var(--radius);
    padding:26px 30px;
    max-width:760px;
    margin:0 auto;
  }
  .solution-note .dot{
    width:10px;height:10px;border-radius:50%;
    background:var(--gold);
    margin-top:7px;flex-shrink:0;
    box-shadow:0 0 0 4px rgba(201,162,39,.18);
  }
  .solution-note p{font-size:14.8px;color:rgba(255,255,255,.75);}
  .solution-note strong{color:#fff;}

  /* ---------- ECONOMIA / COMPARATIVO ---------- */
  .economy{background:var(--off-white);}
  .economy-card{
    background:linear-gradient(150deg, var(--gold-light), var(--gold) 60%);
    border-radius:28px;
    padding:6px;
    box-shadow:0 30px 60px -24px rgba(201,162,39,.4);
  }
  .economy-head{
    display:flex;
    align-items:center;
    gap:14px;
    padding:26px 30px 20px;
  }
  .economy-head .pig{
    width:44px;height:44px;
    border-radius:12px;
    background:rgba(13,27,42,.12);
    display:flex;align-items:center;justify-content:center;
    flex-shrink:0;
  }
  .economy-head .pig svg{width:23px;height:23px;color:var(--navy);}
  .economy-head h3{
    font-size:14px;
    letter-spacing:.04em;
    text-transform:uppercase;
    color:var(--navy);
  }
  .economy-body{
    background:var(--navy);
    border-radius:22px;
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:2px;
    overflow:hidden;
  }
  .economy-col{
    background:var(--navy);
    padding:34px 30px;
    text-align:left;
  }
  .economy-col.highlight{background:var(--navy-2);}
  .economy-col .tag{
    display:inline-flex;
    align-items:center;
    gap:6px;
    font-family:'Poppins',sans-serif;
    font-size:11.5px;
    font-weight:600;
    letter-spacing:.08em;
    color:var(--gold-light);
    margin-bottom:14px;
  }
  .economy-col .price{
    font-family:'Poppins',sans-serif;
    font-weight:600;
    font-size:clamp(26px,3vw,34px);
    color:#fff;
    margin-bottom:10px;
    letter-spacing:-.01em;
  }
  .economy-col .route{font-size:13px;color:rgba(255,255,255,.6);margin-bottom:16px;}
  .economy-col .save-line{
    font-size:12.5px;
    color:rgba(255,255,255,.5);
    padding-top:14px;
    border-top:1px solid rgba(255,255,255,.1);
  }
  .economy-col .save-line strong{color:var(--gold-light);font-weight:600;}
  .economy-banner{
    display:flex;
    align-items:center;
    justify-content:space-between;
    flex-wrap:wrap;
    gap:14px;
    padding:20px 30px;
  }
  .economy-banner p{
    font-family:'Poppins',sans-serif;
    font-weight:600;
    font-size:15px;
    color:var(--navy);
  }
  .economy-banner p strong{font-size:17px;}
  .economy-banner span.disclaimer{
    font-size:11.5px;
    color:rgba(13,27,42,.6);
    font-family:'Inter',sans-serif;
    font-weight:500;
  }
  .economy-cta{text-align:center;margin-top:44px;}

  /* ---------- GARANTIA ---------- */
  .guarantee{background:var(--off-white);}
  .guarantee-inner{
    background:linear-gradient(120deg, var(--teal), #0a4753);
    border-radius:28px;
    padding:74px 60px;
    color:#fff;
    position:relative;
    overflow:hidden;
  }
  .guarantee-inner::after{
    content:"";
    position:absolute;
    width:520px;height:520px;
    right:-160px;top:-200px;
    background:radial-gradient(circle, rgba(201,162,39,.25), transparent 70%);
  }
  .guarantee-top{
    display:grid;
    grid-template-columns:1.1fr .9fr;
    gap:50px;
    align-items:end;
    margin-bottom:56px;
    position:relative;
    z-index:1;
  }
  .guarantee-top h2{color:#fff;font-size:clamp(26px,3.2vw,38px);line-height:1.2;}
  .guarantee-top p{color:rgba(255,255,255,.82);font-size:16px;margin-top:16px;}
  .guarantee-items{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:22px;
    position:relative;
    z-index:1;
  }
  .g-item{
    background:rgba(255,255,255,.08);
    border:1px solid rgba(255,255,255,.14);
    border-radius:14px;
    padding:22px 20px;
  }
  .g-item svg{width:22px;height:22px;color:var(--gold-light);margin-bottom:14px;}
  .g-item h4{font-family:'Poppins',sans-serif;font-weight:600;font-size:14.5px;color:#fff;margin-bottom:6px;}
  .g-item p{font-size:12.8px;color:rgba(255,255,255,.68);}

  /* ---------- DIFERENCIAIS ---------- */
  .diff-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:22px;
  }
  .diff-card{
    padding:34px 26px;
    border-radius:var(--radius);
    background:#fff;
    border:1px solid rgba(13,27,42,.07);
    transition:transform .4s var(--ease), box-shadow .4s var(--ease), border-color .4s ease;
  }
  .diff-card:hover{transform:translateY(-6px);box-shadow:var(--shadow);border-color:transparent;}
  .diff-icon{
    width:46px;height:46px;
    border-radius:12px;
    display:flex;align-items:center;justify-content:center;
    margin-bottom:22px;
    background:rgba(13,27,42,.06);
  }
  .diff-icon svg{width:22px;height:22px;color:var(--navy);}
  .diff-card:nth-child(2) .diff-icon{background:rgba(14,95,110,.1);}
  .diff-card:nth-child(2) .diff-icon svg{color:var(--teal);}
  .diff-card:nth-child(3) .diff-icon{background:rgba(201,162,39,.12);}
  .diff-card:nth-child(3) .diff-icon svg{color:var(--gold);}
  .diff-card:nth-child(4) .diff-icon{background:rgba(58,63,68,.09);}
  .diff-card:nth-child(4) .diff-icon svg{color:var(--graphite);}
  .diff-card h3{font-size:18px;margin-bottom:10px;}
  .diff-card p{color:var(--muted);font-size:14.5px;}

  /* ---------- SOBRE ---------- */
  .about{background:var(--gray-light);}
  .about-grid{
    display:grid;
    grid-template-columns:.85fr 1.15fr;
    gap:70px;
    align-items:center;
  }
  .about-visual{
    position:relative;
    display:flex;align-items:center;justify-content:center;
    padding:50px;
  }
  .about-visual .ring{
    position:absolute;
    border-radius:50%;
    border:1px dashed rgba(13,27,42,.18);
  }
  .ring-1{width:100%;height:100%;}
  .ring-2{width:78%;height:78%;animation:spin 40s linear infinite;}
  @keyframes spin{to{transform:rotate(360deg);}}
  .about-visual svg.symbol{width:150px;height:150px;position:relative;z-index:1;filter:drop-shadow(0 18px 30px rgba(13,27,42,.18));}
  .about-text p{font-size:16px;color:var(--graphite);margin-bottom:20px;}
  .about-text p strong{color:var(--navy);}
  .about-pillars{
    display:flex;
    gap:14px;
    flex-wrap:wrap;
    margin-top:28px;
  }
  .pillar{
    font-family:'Poppins',sans-serif;
    font-size:12.5px;
    font-weight:600;
    letter-spacing:.03em;
    padding:9px 18px;
    border-radius:100px;
    border:1px solid rgba(13,27,42,.15);
    color:var(--navy);
  }

  /* ---------- CTA FINAL ---------- */
  .final-cta{
    background:radial-gradient(120% 140% at 80% 0%, #123244 0%, var(--navy) 55%, #070d14 100%);
    color:#fff;
    text-align:center;
    padding:130px 0;
    position:relative;
    overflow:hidden;
  }
  .final-cta::before{
    content:"";
    position:absolute;inset:0;
    background-image:
      linear-gradient(rgba(201,162,39,.5) 1px, transparent 1px);
    background-size:100% 46px;
    opacity:.03;
  }
  .final-cta .eyebrow{justify-content:center;}
  .final-cta h2{
    color:#fff;
    font-size:clamp(30px,4.2vw,50px);
    max-width:760px;
    margin:18px auto 20px;
    line-height:1.15;
  }
  .final-cta p{
    color:rgba(255,255,255,.68);
    max-width:520px;
    margin:0 auto 40px;
    font-size:16px;
  }
  .final-cta .hero-ctas{justify-content:center;margin-bottom:0;}

  /* ---------- FOOTER ---------- */
  footer{background:#080f18;color:rgba(255,255,255,.6);padding:64px 0 30px;}
  .footer-top{
    display:grid;
    grid-template-columns:1.4fr .8fr .8fr 1fr;
    gap:40px;
    padding-bottom:46px;
    border-bottom:1px solid rgba(255,255,255,.08);
    margin-bottom:30px;
  }
  .footer-brand .logo-word{color:#fff;}

  /* ---------- LOGO PLACEHOLDER (substituir pela arte oficial) ---------- */
  .logo-placeholder{
    display:flex;
    align-items:center;
    justify-content:center;
    border:1.5px dashed rgba(255,255,255,.45);
    border-radius:8px;
    color:rgba(255,255,255,.55);
    background:rgba(255,255,255,.03);
    flex-shrink:0;
  }
  .logo-placeholder svg{width:55%;height:55%;}
  .logo-placeholder.dark{
    border-color:rgba(13,27,42,.35);
    color:rgba(13,27,42,.5);
    background:rgba(13,27,42,.04);
  }
  .logo-placeholder-label{
    margin-top:14px;
    font-family:'Poppins',sans-serif;
    font-size:11px;
    font-weight:600;
    letter-spacing:.08em;
    text-transform:uppercase;
    color:rgba(13,27,42,.4);
    text-align:center;
  }
  .footer-brand p{font-size:13.5px;margin-top:16px;max-width:280px;color:rgba(255,255,255,.5);}
  .footer-col h5{font-family:'Poppins',sans-serif;color:#fff;font-size:13px;letter-spacing:.05em;text-transform:uppercase;margin-bottom:18px;}
  .footer-col ul{display:flex;flex-direction:column;gap:12px;}
  .footer-col a{font-size:14px;transition:color .3s ease;}
  .footer-col a:hover{color:#fff;}
  .footer-bottom{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
    gap:12px;
    font-size:12.5px;
    color:rgba(255,255,255,.4);
  }

  /* ---------- RESPONSIVE ---------- */
  @media (max-width:980px){
    nav.main-nav{display:none;}
    .header-actions .btn-nav-cta{display:none;}
    .burger{display:flex;}
    .hero-grid{grid-template-columns:1fr;}
    .hero-visual{height:340px;order:-1;margin-bottom:20px;}
    .hero{padding-top:150px;}
    .problem-grid{grid-template-columns:1fr;}
    .steps{grid-template-columns:1fr;gap:40px;}
    .steps::before{display:none;}
    .economy-body{grid-template-columns:1fr;}
    .economy-banner{flex-direction:column;align-items:flex-start;}
    .guarantee-top{grid-template-columns:1fr;}
    .guarantee-items{grid-template-columns:repeat(2,1fr);}
    .guarantee-inner{padding:48px 28px;}
    .diff-grid{grid-template-columns:repeat(2,1fr);}
    .about-grid{grid-template-columns:1fr;}
    .about-visual{padding:10px 0 30px;}
    .footer-top{grid-template-columns:1fr 1fr;}
  }
  @media (max-width:560px){
    section{padding:80px 0;}
    .guarantee-items{grid-template-columns:1fr;}
    .diff-grid{grid-template-columns:1fr;}
    .footer-top{grid-template-columns:1fr;}
    .float-card{padding:10px 14px;}
    .float-card p{font-size:11.5px;}
  }
</style>
</head>
<body>

<!-- ===================== HEADER ===================== -->
<header id="siteHeader">
  <div class="container nav-wrap">
    <!-- ============================================================ -->
    <!-- SUBSTITUIR AQUI: logo oficial da M&E Passagens (SVG/PNG do cliente). -->
    <!-- Troque a <div class="logo-placeholder"> abaixo pela arte final,     -->
    <!-- mantendo a classe "logo" no <a> e a largura/altura de 38px.         -->
    <!-- ============================================================ -->
    <a href="#top" class="logo">
      <div class="logo-placeholder" style="width:38px;height:38px;" aria-hidden="true">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.4"/><path d="M21 15l-4.5-4.5L5 21"/></svg>
      </div>
      <span class="logo-word">M&amp;E PASSAGENS</span>
    </a>

    <nav class="main-nav">
      <a href="#como-funciona">Como funciona</a>
      <a href="#economia">Economia</a>
      <a href="#diferenciais">Diferenciais</a>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>

    <div class="header-actions">
      <a class="btn btn-primary btn-nav-cta" href="https://wa.link/anl0e4" target="_blank" rel="noopener">Peça sua cotação</a>
      <button class="burger" id="burgerBtn" aria-label="Abrir menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </div>
</header>

<div class="mobile-panel" id="mobilePanel">
  <a href="#como-funciona">Como funciona</a>
  <a href="#economia">Economia</a>
  <a href="#diferenciais">Diferenciais</a>
  <a href="#sobre">Sobre</a>
  <a href="#contato">Contato</a>
  <a class="btn btn-primary" href="https://wa.link/anl0e4" target="_blank" rel="noopener" style="margin-top:10px;">Peça sua cotação</a>
</div>

<!-- ===================== HERO ===================== -->
<section class="hero" id="top">
  <div class="container hero-grid">
    <div>
      <span class="eyebrow reveal in">Confiança para escolher. Inteligência para viajar.</span>
      <h1 class="reveal in">Comprando com milhas, <span class="accent">a passagem sai mais barata.</span></h1>
      <p class="hero-sub reveal in reveal-delay-1">E não, você não precisa ter milhas para isso.</p>
      <p class="lead reveal in reveal-delay-1">
        A M&amp;E usa Inteligência de Mercado para mapear milhas ociosas, transformá-las em milhas próprias e
        emitir sua passagem com esse saldo. Resultado: uma tarifa mais baixa que a tarifa cheia — com
        acompanhamento de ponta a ponta, do planejamento da rota ao embarque.
      </p>
      <div class="hero-ctas reveal in reveal-delay-2">
        <a class="btn btn-primary" href="https://wa.link/anl0e4" target="_blank" rel="noopener">
          Peça sua cotação
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
        </a>
        <a class="btn btn-outline" href="#economia">Ver economia real</a>
      </div>
      <div class="hero-tags reveal in reveal-delay-3">
        <span class="hero-tag">Passagem mais barata</span>
        <span class="hero-tag">Sem precisar ter milhas</span>
        <span class="hero-tag">Inteligência de mercado</span>
        <span class="hero-tag">Ponta a ponta</span>
      </div>
    </div>

    <div class="hero-visual reveal in reveal-delay-2">
      <div class="route-card">
        <svg class="route-svg" viewBox="0 0 420 460" preserveAspectRatio="xMidYMid meet">
          <defs>
            <linearGradient id="routeGradient" x1="40" y1="380" x2="380" y2="70" gradientUnits="userSpaceOnUse">
              <stop stop-color="#0E5F6E"/>
              <stop offset="1" stop-color="#C9A227"/>
            </linearGradient>
          </defs>
          <path class="route-path" d="M40,380 C120,330 150,220 230,190 C300,165 340,120 380,70"/>
          <circle cx="40" cy="380" r="5" fill="#0E5F6E"/>
          <circle cx="380" cy="70" r="5" fill="#C9A227"/>
          <g class="plane-on-path" transform="rotate(-40)">
            <path d="M0 -9 L11 -3 L13 1 L2 -1 L2 8 L6 12 L6 15 L0 12.5 L-6 15 L-6 12 L-2 8 L-2 -1 L-13 1 L-11 -3 Z" fill="#C9A227"/>
          </g>
        </svg>
      </div>
      <div class="float-card fc-1">
        <div class="ic">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2v20M2 12h20" stroke-linecap="round"/><circle cx="12" cy="12" r="9"/></svg>
        </div>
        <div><p>Passagem mais barata</p><span>Comprando com milhas</span></div>
      </div>
      <div class="float-card fc-2">
        <div class="ic">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg>
        </div>
        <div><p>Garantia ponta a ponta</p><span>Da rota ao embarque</span></div>
      </div>
    </div>
  </div>
</section>

<!-- ===================== PROBLEMA ===================== -->
<section class="problem">
  <div class="container">
    <div class="section-head center" style="margin-left:auto;margin-right:auto;">
      <span class="eyebrow reveal">O desafio</span>
      <h2 class="reveal">Acumular milhas dá certo. <br>O problema é o tempo.</h2>
      <p class="reveal" style="margin-left:auto;margin-right:auto;">Fazer esse trabalho sozinho consome tempo e atenção — e as regras mudam o tempo todo.</p>
    </div>

    <div class="problem-grid">
      <div class="problem-card reveal reveal-delay-1">
        <span class="num">01</span>
        <h3>Gastar todo mês</h3>
        <p>Concentrar despesas no cartão certo, no momento certo, só para manter o acúmulo em ritmo.</p>
      </div>
      <div class="problem-card reveal reveal-delay-2">
        <span class="num">02</span>
        <h3>Acompanhar promoções</h3>
        <p>Comparar bônus de transferência entre bancos e programas exige tempo — e atenção constante.</p>
      </div>
      <div class="problem-card reveal reveal-delay-3">
        <span class="num">03</span>
        <h3>Regras que mudam</h3>
        <p>Milhas têm validade e os programas alteram condições sem aviso. O trabalho nunca acaba.</p>
      </div>
    </div>

    <p class="problem-close reveal">
      Isso é, na prática, <span class="accent">um segundo trabalho</span> — e mesmo assim a maioria continua
      pagando tarifa cheia.
    </p>
  </div>
</section>

<!-- ===================== SOLUÇÃO / COMO FUNCIONA ===================== -->
<section class="solution" id="como-funciona">
  <div class="container">
    <div class="section-head center" style="margin-left:auto;margin-right:auto;">
      <span class="eyebrow reveal">Como funciona</span>
      <h2 class="reveal">A M&amp;E já faz esse trabalho todos os dias.</h2>
      <p class="reveal" style="margin-left:auto;margin-right:auto;">Nossa Inteligência de Mercado monitora, organiza e converte oportunidades em passagens mais baratas — para que sua única preocupação seja o destino.</p>
    </div>

    <div class="steps">
      <div class="step reveal reveal-delay-1">
        <div class="step-index">01</div>
        <h3>Mapeamos</h3>
        <p>Monitoramos continuamente a disponibilidade de milhas ociosas no mercado.</p>
      </div>
      <div class="step reveal reveal-delay-2">
        <div class="step-index">02</div>
        <h3>Convertemos</h3>
        <p>Transformamos essa disponibilidade em milhas próprias da M&amp;E, prontas para uso.</p>
      </div>
      <div class="step reveal reveal-delay-3">
        <div class="step-index">03</div>
        <h3>Emitimos mais barato</h3>
        <p>Usamos nosso saldo para emitir seu bilhete com milhas — uma tarifa mais baixa que a cheia, mesmo que você não tenha milhas.</p>
      </div>
    </div>

    <div class="solution-note reveal">
      <span class="dot"></span>
      <p><strong>Transparência em cada cotação:</strong> o preço de uma passagem muda conforme procura e disponibilidade — por isso toda cotação vale para o momento em que é feita, e a compra com milhas tende a sair mais barata que a tarifa cheia dos canais tradicionais.</p>
    </div>
  </div>
</section>

<!-- ===================== ECONOMIA / COMPARATIVO ===================== -->
<section class="economy" id="economia">
  <div class="container">
    <div class="section-head center" style="margin-left:auto;margin-right:auto;">
      <span class="eyebrow reveal">Economia real</span>
      <h2 class="reveal">Compare e veja quanto você economiza.</h2>
      <p class="reveal" style="margin-left:auto;margin-right:auto;">Exemplo real de cotação: mesma rota, mesma data — a diferença é comprar com milhas.</p>
    </div>

    <div class="economy-card reveal">
      <div class="economy-head">
        <div class="pig">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 9c0 1-1 2-1 2s1 1 1 2-1.5 3-5 3H8c-2.5 0-4-1-4-3 0-1 .5-2 1-2-1-1-1-2 0-3 .5-2 3-4 6-4 3.5 0 6 2 7 3 1 0 1.5.5 1 2z"/><circle cx="15" cy="10" r=".5" fill="currentColor"/><path d="M5 13v2M9 17v1.5M14 17v1.5"/></svg>
        </div>
        <h3>Economia — Melhor combo LATAM ida + volta</h3>
      </div>
      <div class="economy-body">
        <div class="economy-col">
          <span class="tag">Sem milhas</span>
          <div class="price">R$ 3.079,09</div>
          <div class="route">Melhor combo: LATAM ida + volta</div>
          <div class="save-line">Economia vs. opção mais cara: <strong>R$ 529,00</strong></div>
        </div>
        <div class="economy-col highlight">
          <span class="tag">Com milhas</span>
          <div class="price">R$ 2.685,29</div>
          <div class="route">Melhor combo: LATAM ida + volta</div>
          <div class="save-line">Economia vs. opção mais cara: <strong>R$ 1.808,25</strong></div>
        </div>
      </div>
      <div class="economy-banner">
        <p>Comprando com milhas, essa passagem sai <strong>R$ 393,80 mais barata.</strong></p>
        <span class="disclaimer">Valores sujeitos à disponibilidade. Consulte condições de milhas e tarifas.</span>
      </div>
    </div>

    <div class="economy-cta reveal">
      <a class="btn btn-primary" href="https://wa.link/anl0e4" target="_blank" rel="noopener">
        Peça sua cotação com milhas
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
      </a>
    </div>
  </div>
</section>

<!-- ===================== GARANTIA PONTA A PONTA ===================== -->
<section class="guarantee">
  <div class="container">
    <div class="guarantee-inner">
      <div class="guarantee-top">
        <div>
          <span class="eyebrow reveal" style="color:#F2D98A;">Garantia de ponta a ponta</span>
          <h2 class="reveal">Do planejamento da rota ao momento do embarque.</h2>
        </div>
        <p class="reveal reveal-delay-1">Sua única preocupação deve ser o destino. Cuidamos de cada etapa da sua viagem com acompanhamento próximo, do primeiro contato até o portão de embarque.</p>
      </div>

      <div class="guarantee-items">
        <div class="g-item reveal reveal-delay-1">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 11l18-5-5 18-4-8-8-4z"/></svg>
          <h4>Planejamento de rota</h4>
          <p>Estratégia pensada para a sua necessidade de viagem.</p>
        </div>
        <div class="g-item reveal reveal-delay-2">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 12l2 2 4-4M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <h4>Emissão estratégica</h4>
          <p>Uso inteligente do nosso saldo de milhas próprias.</p>
        </div>
        <div class="g-item reveal reveal-delay-3">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 01-2 2H7l-4 4V5a2 2 0 012-2h14a2 2 0 012 2z"/></svg>
          <h4>Acompanhamento contínuo</h4>
          <p>Suporte próximo em cada etapa, sem burocracia.</p>
        </div>
        <div class="g-item reveal reveal-delay-4">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 2L11 13M22 2l-7 20-4-9-9-4 20-7z"/></svg>
          <h4>Suporte até o embarque</h4>
          <p>Do check-in ao portão, sua viagem acompanhada.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===================== DIFERENCIAIS ===================== -->
<section id="diferenciais">
  <div class="container">
    <div class="section-head reveal">
      <span class="eyebrow">Tom da marca</span>
      <h2>Seguro. Claro. Presente do início ao fim.</h2>
      <p>Clareza para explicar. Credibilidade para vender valor. É assim que a M&amp;E se apresenta em cada ponto de contato.</p>
    </div>

    <div class="diff-grid">
      <div class="diff-card reveal reveal-delay-1">
        <div class="diff-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2l8 4v6c0 5-3.5 8.5-8 10-4.5-1.5-8-5-8-10V6l8-4z"/></svg>
        </div>
        <h3>Profissional</h3>
        <p>Objetivo e confiável em cada recomendação e cada etapa do processo.</p>
      </div>
      <div class="diff-card reveal reveal-delay-2">
        <div class="diff-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M13 2L3 14h8l-1 8 10-12h-8l1-8z"/></svg>
        </div>
        <h3>Inteligente</h3>
        <p>Estratégia e inovação por trás de cada cotação e cada rota planejada.</p>
      </div>
      <div class="diff-card reveal reveal-delay-3">
        <div class="diff-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20.8 4.6c-1.6-1.6-4.2-1.6-5.8 0L12 7.6l-3-3c-1.6-1.6-4.2-1.6-5.8 0-1.6 1.6-1.6 4.2 0 5.8l8.8 8.8 8.8-8.8c1.6-1.6 1.6-4.2 0-5.8z"/></svg>
        </div>
        <h3>Próximo</h3>
        <p>Acompanhamento de perto em cada etapa, do primeiro contato ao embarque.</p>
      </div>
      <div class="diff-card reveal reveal-delay-4">
        <div class="diff-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
        </div>
        <h3>Inspirador</h3>
        <p>Viagem com liberdade — planejada para chegar mais longe.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===================== SOBRE ===================== -->
<section class="about" id="sobre">
  <div class="container about-grid">
    <!-- ============================================================ -->
    <!-- SUBSTITUIR AQUI: símbolo/logo oficial da M&E (SVG/PNG do cliente). -->
    <!-- Troque a <div class="logo-placeholder"> abaixo pela arte final,    -->
    <!-- mantendo a largura/altura de 150px para caber nos anéis decorativos. -->
    <!-- ============================================================ -->
    <div class="about-visual reveal">
      <div class="ring ring-1"></div>
      <div class="ring ring-2"></div>
      <div class="logo-placeholder dark" style="width:150px;height:150px;border-radius:50%;position:relative;z-index:1;" aria-hidden="true">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.4"/><path d="M21 15l-4.5-4.5L5 21"/></svg>
      </div>
    </div>

    <div class="about-text reveal reveal-delay-1">
      <span class="eyebrow">Sobre a M&amp;E</span>
      <h2 style="margin:16px 0 22px;font-size:clamp(26px,3vw,36px);">O M que carrega uma rota.</h2>
      <p>O símbolo da M&amp;E representa o movimento ascendente de uma viagem: planejamento, aproveitamento de oportunidade e liberdade para chegar mais longe.</p>
      <p>Trabalhamos para que escolher uma passagem seja simples — e para que viajar seja sempre uma questão de <strong>estratégia</strong>, apoiada por inteligência de mercado e por um time que acompanha cada detalhe do início ao fim.</p>
      <div class="about-pillars">
        <span class="pillar">Estratégia</span>
        <span class="pillar">Confiança</span>
        <span class="pillar">Inteligência</span>
        <span class="pillar">Liberdade</span>
      </div>
    </div>
  </div>
</section>

<!-- ===================== CTA FINAL ===================== -->
<section class="final-cta" id="contato">
  <div class="container">
    <span class="eyebrow reveal">Vamos planejar sua próxima viagem</span>
    <h2 class="reveal reveal-delay-1">Descubra quanto você economiza comprando com milhas.</h2>
    <p class="reveal reveal-delay-2">Conte pra gente o destino e as datas. A cotação é sem compromisso, com acompanhamento do início ao embarque.</p>
    <div class="hero-ctas reveal reveal-delay-3">
      <a class="btn btn-primary" href="https://wa.link/anl0e4" target="_blank" rel="noopener">
        Peça sua cotação
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
      </a>
    </div>
  </div>
</section>

<!-- ===================== FOOTER ===================== -->
<footer>
  <div class="container">
    <div class="footer-top">
      <div class="footer-brand">
        <!-- ============================================================ -->
        <!-- SUBSTITUIR AQUI: logo oficial da M&E Passagens (SVG/PNG do cliente). -->
        <!-- Troque a <div class="logo-placeholder"> abaixo pela arte final,     -->
        <!-- mantendo a classe "logo" no <a> e a largura/altura de 34px.         -->
        <!-- ============================================================ -->
        <a href="#top" class="logo">
          <div class="logo-placeholder" style="width:34px;height:34px;" aria-hidden="true">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.4"/><path d="M21 15l-4.5-4.5L5 21"/></svg>
          </div>
          <span class="logo-word">M&amp;E PASSAGENS</span>
        </a>
        <p>Confiança para escolher. Inteligência para viajar. Inteligência que te leva mais longe.</p>
      </div>

      <div class="footer-col">
        <h5>Navegação</h5>
        <ul>
          <li><a href="#como-funciona">Como funciona</a></li>
          <li><a href="#economia">Economia</a></li>
          <li><a href="#diferenciais">Diferenciais</a></li>
          <li><a href="#sobre">Sobre</a></li>
        </ul>
      </div>

      <div class="footer-col">
        <h5>Marca</h5>
        <ul>
          <li><a href="#top">Estratégia</a></li>
          <li><a href="#top">Confiança</a></li>
          <li><a href="#top">Liberdade</a></li>
        </ul>
      </div>

      <div class="footer-col">
        <h5>Fale conosco</h5>
        <ul>
          <li><a href="https://wa.link/anl0e4" target="_blank" rel="noopener">WhatsApp — Peça sua cotação</a></li>
        </ul>
      </div>
    </div>

    <div class="footer-bottom">
      <span>© <span id="year"></span> M&amp;E Passagens. Todos os direitos reservados.</span>
      <span>Inteligência que te leva mais longe.</span>
    </div>
  </div>
</footer>

<script>
  // Header scroll state
  const header = document.getElementById('siteHeader');
  const onScroll = () => {
    if(window.scrollY > 40){ header.classList.add('scrolled'); }
    else{ header.classList.remove('scrolled'); }
  };
  document.addEventListener('scroll', onScroll, {passive:true});
  onScroll();

  // Mobile menu
  const burger = document.getElementById('burgerBtn');
  const panel = document.getElementById('mobilePanel');
  burger.addEventListener('click', () => panel.classList.toggle('open'));
  panel.querySelectorAll('a').forEach(a => a.addEventListener('click', () => panel.classList.remove('open')));

  // Scroll reveal
  const revealEls = document.querySelectorAll('.reveal');
  const io = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if(entry.isIntersecting){
        entry.target.classList.add('in');
        io.unobserve(entry.target);
      }
    });
  }, {threshold:.15, rootMargin:'0px 0px -60px 0px'});
  revealEls.forEach(el => io.observe(el));

  // Footer year
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
