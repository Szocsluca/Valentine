<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Be My Valentine? 💖</title>

  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg1:#ff9a9e;
      --bg2:#fad0c4;
      --bg3:#fbc2eb;
      --ink:#3b2b2f;
      --card: rgba(255,255,255,.72);
      --card2: rgba(255,255,255,.58);
      --shadow: 0 20px 60px rgba(0,0,0,.18);
      --pink:#ff3b7a;
      --pink2:#ff6aa2;
      --yes:#27c281;
      --no:#ff4d5e;
      --dark:#12060c;
      --cream: rgba(255,255,255,.9);
    }

    *{ box-sizing:border-box; }
    html,body{ height:100%; }
    body{
      margin:0;
      font-family: 'Montserrat', ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Apple Color Emoji","Segoe UI Emoji";
      color:var(--ink);
      overflow-x:hidden;
      background: linear-gradient(270deg, var(--bg1), var(--bg2), var(--bg3), var(--bg1));
      background-size: 400% 400%;
      animation: bgMove 18s ease-in-out infinite;
    }
    @keyframes bgMove {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    /* floating hearts background */
    .hearts {
      position: fixed;
      inset: 0;
      pointer-events: none;
      overflow: hidden;
      z-index: 0;
    }
    .heart {
      position: absolute;
      width: 18px; height: 18px;
      transform: rotate(45deg);
      background: rgba(255,255,255,.55);
      border-radius: 4px;
      filter: blur(.2px);
      animation: floatUp linear infinite;
    }
    .heart::before, .heart::after{
      content:"";
      position:absolute;
      width: 18px; height: 18px;
      background: inherit;
      border-radius: 50%;
    }
    .heart::before{ left: -9px; top:0; }
    .heart::after{ left:0; top:-9px; }
    @keyframes floatUp {
      from { transform: translateY(20vh) rotate(45deg); opacity: 0; }
      10% { opacity: .9; }
      to { transform: translateY(-120vh) rotate(45deg); opacity: 0; }
    }

    /* layout */
    .wrap{
      min-height: 100%;
      display:grid;
      place-items:center;
      padding: 32px 18px;
      position: relative;
      z-index: 1;
    }

    .card{
      width: min(980px, 100%);
      display:grid;
      grid-template-columns: 1.15fr .85fr;
      gap: 18px;
      padding: 22px;
      background: linear-gradient(180deg, var(--card), var(--card2));
      border: 1px solid rgba(255,255,255,.55);
      border-radius: 26px;
      box-shadow: 0 0 60px 0 #ffb6d5, 0 20px 60px rgba(0,0,0,.18);
      backdrop-filter: blur(10px);
      transform: translateY(6px);
      animation: popIn .75s cubic-bezier(.2,1,.25,1) both;
      position: relative;
    }
    @keyframes popIn{
      from{ opacity:0; transform: translateY(26px) scale(.98); }
      to{ opacity:1; transform: translateY(6px) scale(1); }
    }
    @media (max-width: 860px){
      .card{ grid-template-columns: 1fr; }
    }

    .title{
      display:flex;
      align-items:flex-start;
      justify-content:space-between;
      gap: 14px;
      margin-bottom: 10px;
    }
    h1{
      margin:0;
      font-size: clamp(32px, 5vw, 54px);
      line-height: 1.05;
      letter-spacing: -0.02em;
      font-family: 'Great Vibes', cursive;
      color: #ff3b7a;
      text-shadow: 0 2px 18px #fff6, 0 4px 32px #ffb6d5;
      opacity: 0;
      transform: translateY(30px);
      animation: fadeInUp 1.2s .2s cubic-bezier(.2,1,.25,1) forwards;
    }
    @keyframes fadeInUp { to { opacity: 1; transform: none; } }

    .badge{
      font-weight: 700;
      padding: 10px 14px;
      border-radius: 999px;
      background: rgba(255,255,255,.55);
      border: 1px solid rgba(255,255,255,.7);
      box-shadow: 0 10px 30px rgba(0,0,0,.08);
      white-space: nowrap;
    }

    .subtitle{
      margin: 6px 0 0;
      font-size: 18px;
      opacity: 0;
      line-height: 1.5;
      font-family: 'Montserrat', sans-serif;
      animation: fadeInUp 1.2s .7s cubic-bezier(.2,1,.25,1) forwards;
    }

    .note{
      margin-top: 14px;
      padding: 14px 16px;
      border-radius: 16px;
      background: rgba(255,255,255,.55);
      border: 1px solid rgba(255,255,255,.7);
    }
    .note strong{ color: var(--pink); }

    /* polaroid */
    .polaroid{
      position: relative;
      border-radius: 20px;
      padding: 14px;
      background: rgba(255,255,255,.76);
      border: 1px solid rgba(255,255,255,.75);
      box-shadow: 0 18px 45px rgba(0,0,0,.12);
      transform: rotate(-1.2deg);
      overflow: hidden;
    }
    .polaroid::after{
      content:"";
      position:absolute;
      inset:-2px;
      background: radial-gradient(600px 240px at 30% 0%, rgba(255,59,122,.22), transparent 60%),
                  radial-gradient(500px 260px at 70% 20%, rgba(255,106,162,.18), transparent 60%);
      pointer-events:none;
      mix-blend-mode: multiply;
    }
    .photo{
      width: 100%;
      aspect-ratio: 4/3;
      border-radius: 16px;
      object-fit: cover;
      display:block;
      box-shadow: 0 8px 18px rgba(0,0,0,.12);
      background: #f2f2f2;
      transform: translateZ(0);
    }
    .caption{
      text-align:center;
      margin: 12px 0 2px;
      font-family: ui-rounded, system-ui, sans-serif;
      font-weight: 700;
      letter-spacing: .02em;
    }
    .dots{
      display:flex;
      justify-content:center;
      gap: 8px;
      margin-top: 10px;
    }
    .dot{
      width: 8px; height: 8px;
      border-radius: 999px;
      background: rgba(0,0,0,.18);
      border: 1px solid rgba(255,255,255,.7);
      cursor:pointer;
      transition: transform .2s ease, background .2s ease;
    }
    .dot.active{ background: rgba(255,59,122,.8); transform: scale(1.25); }

    /* buttons */
    .actions{
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
      margin-top: 16px;
      align-items:center;
    }
    button{
      border:0;
      padding: 14px 18px;
      border-radius: 999px;
      font-weight: 800;
      font-size: 16px;
      cursor:pointer;
      transition: transform .12s ease, box-shadow .2s ease, filter .2s ease;
      user-select:none;
    }
    .yes{
      background: linear-gradient(135deg, var(--yes), #7ef0c1);
      color: #083b28;
      box-shadow: 0 0 18px #7ef0c1, 0 14px 35px rgba(39,194,129,.25);
      text-shadow: 0 2px 8px #fff8;
    }
    .yes:hover{ transform: translateY(-1px) scale(1.06); filter: saturate(1.08); box-shadow: 0 0 32px #7ef0c1, 0 18px 45px rgba(39,194,129,.28); }
    .no{
      background: linear-gradient(135deg, var(--no), #ff91a0);
      color: #4b0c15;
      box-shadow: 0 0 18px #ff91a0, 0 14px 35px rgba(255,77,94,.22);
      position: relative;
      text-shadow: 0 2px 8px #fff8;
    }
    .no:hover{ transform: translateY(-1px) scale(1.04); }

    .tiny{
      font-size: 13px;
      opacity:.85;
      margin: 10px 0 0;
    }

    /* success overlay */
    .overlay{
      position: fixed;
      inset: 0;
      display:none;
      place-items:center;
      background: rgba(10, 5, 8, .42);
      backdrop-filter: blur(10px);
      z-index: 5;
      padding: 18px;
    }
    .overlay.show{ display:grid; }

    .modal{
      width: min(760px, 100%);
      background: rgba(255,255,255,.88);
      border: 1px solid rgba(255,255,255,.65);
      border-radius: 26px;
      box-shadow: 0 30px 90px rgba(0,0,0,.35);
      padding: 22px;
      position: relative;
      overflow:hidden;
      animation: modalIn .5s cubic-bezier(.2,1,.25,1) both;
    }
    @keyframes modalIn{
      from{ transform: translateY(18px) scale(.98); opacity:0;}
      to{ transform: translateY(0) scale(1); opacity:1;}
    }
    .modal h2{
      margin: 0;
      font-size: clamp(26px, 3.6vw, 38px);
      letter-spacing:-.02em;
    }
    .modal p{ margin: 10px 0 0; font-size: 16px; line-height: 1.55; }
    .close{
      position:absolute;
      right: 14px;
      top: 14px;
      width: 42px;
      height: 42px;
      border-radius: 999px;
      background: rgba(0,0,0,.06);
      font-weight: 900;
    }
    .close:hover{ transform: rotate(6deg); }

    /* celebratory heart confetti */
    .burst{
      position:absolute;
      inset: 0;
      pointer-events:none;
      overflow:hidden;
      opacity: .95;
    }
    .burst i{
      position:absolute;
      width: 14px; height: 14px;
      transform: rotate(45deg);
      background: rgba(255,59,122,.75);
      border-radius: 4px;
      animation: burst 1.35s ease-in-out infinite;
    }
    .burst i::before,.burst i::after{
      content:"";
      position:absolute;
      width: 14px; height: 14px;
      background: inherit;
      border-radius: 50%;
    }
    .burst i::before{ left:-7px; top:0; }
    .burst i::after{ left:0; top:-7px; }
    @keyframes burst{
      0%{ transform: translateY(70%) rotate(45deg) scale(.8); opacity:0; }
      20%{ opacity:1; }
      100%{ transform: translateY(-40%) rotate(45deg) scale(1.2); opacity:0; }
    }

    .footer{ margin-top: 14px; font-size: 12px; opacity: .75; }
    a{ color: inherit; }

    /* Sparkle overlay */
    .sparkles {
      pointer-events: none;
      position: fixed;
      inset: 0;
      z-index: 2;
      overflow: hidden;
    }
    .sparkle {
      position: absolute;
      width: 8px; height: 8px;
      background: radial-gradient(circle, #fff 60%, #ffb6d5 100%);
      border-radius: 50%;
      opacity: 0.7;
      filter: blur(0.5px);
      animation: sparkleAnim 2.2s linear infinite;
    }
    @keyframes sparkleAnim {
      0% { opacity: 0; transform: scale(0.7) translateY(0); }
      10% { opacity: 1; }
      90% { opacity: 1; }
      100% { opacity: 0; transform: scale(1.2) translateY(-40px); }
    }

    /* =========================
       MOVIE TRAILER INTRO
       ========================= */
    #introOverlay{
      position:fixed;
      inset:0;
      z-index:100;
      overflow:hidden;
      display:grid;
      place-items:center;
      background: var(--dark);
      opacity: 1;
      transition: opacity .9s ease, transform .9s ease;
    }
    #introOverlay.hide{
      opacity:0;
      transform: scale(1.02);
      pointer-events:none;
    }

    .introLayers{
      position:absolute;
      inset:-12%;
      will-change: transform;
      transform: translate3d(0,0,0);
      filter:saturate(1.05);
    }
    .introLayer{ position:absolute; inset:0; background-size: 140% 140%; will-change: transform; }
    .introLayer.layerA{
      background:
        radial-gradient(1200px 800px at 22% 35%, rgba(255,59,122,.38), transparent 58%),
        radial-gradient(900px 700px at 78% 28%, rgba(255,230,200,.22), transparent 60%),
        linear-gradient(120deg, #2a0b1a 0%, #14060c 60%, #2b0a14 100%);
      opacity:.96;
    }
    .introLayer.layerB{
      background:
        radial-gradient(1000px 720px at 40% 65%, rgba(255,106,162,.22), transparent 62%),
        radial-gradient(760px 540px at 72% 30%, rgba(255,255,255,.12), transparent 55%),
        linear-gradient(180deg, rgba(255,255,255,.06), transparent 60%);
      opacity:.85;
      mix-blend-mode: screen;
      filter: blur(0.6px);
    }
    .introLayer.layerC{
      background:
        radial-gradient(600px 420px at 52% 55%, rgba(255,255,255,.08), transparent 62%),
        radial-gradient(560px 420px at 45% 35%, rgba(255,59,122,.13), transparent 62%);
      opacity:.75;
      filter: blur(0.9px);
    }

    .filmGrain{
      position:absolute; inset:-20%;
      background:
        repeating-linear-gradient(0deg,
          rgba(255,255,255,.035) 0px,
          rgba(255,255,255,.035) 1px,
          transparent 2px,
          transparent 6px);
      mix-blend-mode: overlay;
      opacity:.22;
      animation: grainFlicker 3.4s infinite linear;
      pointer-events:none;
    }
    @keyframes grainFlicker{
      0%,100%{ opacity:.18; transform: translate3d(0,0,0) rotate(0.001deg); }
      50%{ opacity:.28; transform: translate3d(-1.2%, .6%, 0) rotate(0.001deg); }
    }

    .vignette{
      position:absolute; inset:-2px;
      background: radial-gradient(75% 65% at 50% 45%, transparent 55%, rgba(0,0,0,.72) 100%);
      pointer-events:none;
    }

    .spotlight{
      position:absolute;
      inset:-30%;
      background: radial-gradient(35% 35% at 0% 40%, rgba(255,255,255,.18), rgba(255,255,255,0) 70%);
      transform: translateX(-35%) rotate(-8deg);
      opacity: .0;
      filter: blur(1px);
      mix-blend-mode: screen;
      animation: spotlightSweep 5.3s 0.9s cubic-bezier(.2,1,.25,1) forwards;
      pointer-events:none;
    }
    @keyframes spotlightSweep{
      0%{ opacity:0; transform: translateX(-45%) rotate(-10deg); }
      20%{ opacity:.9; }
      65%{ opacity:.55; }
      100%{ opacity:0; transform: translateX(55%) rotate(8deg); }
    }

    .introStage{
      position: relative;
      z-index: 5;
      width: min(920px, 92vw);
      padding: 28px 18px;
      text-align: center;
      transform: translateY(8px);
      opacity: 1;
    }

    /* Title cards (trailer beats) */
    .titleCards{
      position: relative;
      display:grid;
      place-items:center;
      height: min(340px, 40vh);
      margin: 0 auto;
    }

    .cardBeat{
      position:absolute;
      inset:0;
      display:grid;
      place-items:center;
      opacity:0;
      transform: translateY(10px) scale(.99);
      filter: drop-shadow(0 24px 80px rgba(0,0,0,.55));
    }

    .beatText{
      font-family: 'Montserrat', sans-serif;
      letter-spacing: .26em;
      text-transform: uppercase;
      font-weight: 700;
      font-size: clamp(12px, 2.0vw, 14px);
      color: rgba(255,255,255,.86);
      margin-bottom: 14px;
    }

    .beatBig{
      font-family: 'Great Vibes', cursive;
      font-size: clamp(44px, 6.2vw, 76px);
      line-height: 1.02;
      color: rgba(255,255,255,.94);
      text-shadow: 0 2px 18px rgba(255,255,255,.22),
                   0 14px 90px rgba(255,59,122,.20);
      letter-spacing: .01em;
      margin: 0;
    }

    .beatBig .pink{
      color: #ffd6e6;
      text-shadow: 0 2px 18px rgba(255,255,255,.18),
                   0 16px 110px rgba(255,59,122,.26);
    }

    .beatSmall{
      margin-top: 12px;
      font-size: clamp(14px, 2.2vw, 18px);
      color: rgba(255,255,255,.78);
      max-width: 700px;
      line-height: 1.55;
    }

    /* Beat animations */
    .cardBeat.show{
      animation: beatIn 0.9s cubic-bezier(.2,1,.25,1) forwards;
    }
    .cardBeat.hide{
      animation: beatOut 0.55s ease forwards;
    }
    @keyframes beatIn{
      from{ opacity:0; transform: translateY(14px) scale(.99); }
      to{ opacity:1; transform: none; }
    }
    @keyframes beatOut{
      from{ opacity:1; transform: none; }
      to{ opacity:0; transform: translateY(-10px) scale(1.01); }
    }

    /* Glowing divider */
    .trailerDivider{
      width: min(520px, 84vw);
      height: 1px;
      margin: 18px auto 0;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,.55), rgba(255,59,122,.45), rgba(255,255,255,.55), transparent);
      opacity: .0;
      transform: translateY(6px);
      transition: opacity .7s ease, transform .7s ease;
    }
    .trailerDivider.on{
      opacity: .85;
      transform: translateY(0);
    }

    /* Final reveal block */
    .finalReveal{
      margin-top: 16px;
      opacity:0;
      transform: translateY(14px);
      transition: opacity .8s ease, transform .8s cubic-bezier(.2,1,.25,1);
    }
    .finalReveal.on{
      opacity:1;
      transform: none;
    }

    /* letter-by-letter title */
    .cinLine{
      font-family: 'Great Vibes', cursive;
      font-size: clamp(42px, 6vw, 78px);
      line-height: 1.02;
      color: rgba(255,255,255,.94);
      text-shadow: 0 2px 18px rgba(255,255,255,.22),
                   0 14px 90px rgba(255,59,122,.20);
      margin: 0;
      display:block;
      filter: drop-shadow(0 14px 40px rgba(255,59,122,.15));
    }
    .cinLine .ch{
      display:inline-block;
      opacity:0;
      transform: translateY(14px) rotate(-1deg);
      animation: charIn .55s cubic-bezier(.2,1,.25,1) forwards;
    }
    @keyframes charIn{ to{ opacity:1; transform:none; } }

    .pulseLine{
      width: min(360px, 76vw);
      height: 16px;
      margin: 18px auto 0;
      display:flex;
      align-items:flex-end;
      justify-content:center;
      gap: 6px;
      opacity:0;
      transform: translateY(10px);
      transition: opacity .6s ease, transform .6s ease;
    }
    .pulseLine.on{ opacity:1; transform:none; }
    .pulseLine span{
      width: 6px;
      height: 8px;
      border-radius: 999px;
      background: linear-gradient(180deg, rgba(255,255,255,.9), rgba(255,59,122,.7));
      box-shadow: 0 0 18px rgba(255,59,122,.18);
      animation: pulse 1.0s ease-in-out infinite;
      transform-origin: bottom;
    }
    .pulseLine span:nth-child(2){ animation-delay: .08s; }
    .pulseLine span:nth-child(3){ animation-delay: .16s; }
    .pulseLine span:nth-child(4){ animation-delay: .24s; }
    .pulseLine span:nth-child(5){ animation-delay: .32s; }
    @keyframes pulse{
      0%,100%{ transform: scaleY(1); opacity:.7; }
      50%{ transform: scaleY(2.2); opacity:1; }
    }

    .introBtnRow{
      display:flex;
      gap: 10px;
      justify-content:center;
      align-items:center;
      margin-top: 18px;
    }

    .introBtn{
      position: relative;
      padding: 14px 30px;
      border-radius: 999px;
      border: 1px solid rgba(255,255,255,.28);
      background: linear-gradient(135deg, rgba(255,59,122,.95), rgba(255,106,162,.92));
      color:#fff;
      font-weight: 800;
      font-size: 16px;
      box-shadow: 0 14px 50px rgba(255,59,122,.22);
      cursor:pointer;
      overflow:hidden;
      opacity:0;
      transform: translateY(12px) scale(.98);
      transition: transform .2s ease, box-shadow .2s ease, filter .2s ease, opacity .2s ease;
    }
    .introBtn.on{ opacity:1; transform:none; }
    .introBtn::before{
      content:"";
      position:absolute; inset:-2px;
      background: radial-gradient(60% 120% at 30% 0%, rgba(255,255,255,.35), transparent 60%);
      opacity:.0;
      transition: opacity .2s ease;
    }
    .introBtn:hover{
      transform: translateY(-1px) scale(1.03);
      box-shadow: 0 18px 65px rgba(255,59,122,.28);
    }
    .introBtn:hover::before{ opacity:1; }
    .introBtnText{ position: relative; z-index:2; }
    .introBtnIcon{
      position: relative;
      z-index:2;
      margin-left: 10px;
      display:inline-block;
      transform: translateX(0);
      transition: transform .2s ease;
      opacity:.9;
    }
    .introBtn:hover .introBtnIcon{ transform: translateX(3px); }

    .skipBtn{
      padding: 14px 22px;
      border-radius: 999px;
      border: 1px solid rgba(255,255,255,.25);
      background: rgba(255,255,255,.08);
      color: rgba(255,255,255,.9);
      font-weight: 800;
      cursor:pointer;
      opacity:.85;
      transition: transform .2s ease, opacity .2s ease, background .2s ease;
    }
    .skipBtn:hover{ transform: translateY(-1px) scale(1.02); opacity:1; background: rgba(255,255,255,.12); }

    /* cinematic shutter/flash at transition */
    .shutterFlash{
      position: fixed;
      inset: 0;
      z-index: 99;
      pointer-events:none;
      background:
        radial-gradient(1200px 800px at 50% 50%, rgba(255,255,255,.35), transparent 55%),
        linear-gradient(180deg, rgba(255,255,255,.18), rgba(255,255,255,0));
      opacity:0;
      transform: scale(1);
      mix-blend-mode: screen;
    }
    .shutterFlash.fire{ animation: flash 0.65s ease-out forwards; }
    @keyframes flash{
      0%{ opacity:0; transform: scale(1); }
      25%{ opacity:1; transform: scale(1.02); }
      100%{ opacity:0; transform: scale(1.05); }
    }

    /* Cinematic music toggle */
    #musicToggle{
      position:fixed;
      bottom:24px;
      right:24px;
      z-index:10;
      background:rgba(255,255,255,.7);
      border:none;
      border-radius:50%;
      width:54px;
      height:54px;
      box-shadow:0 4px 18px #ffb6d5;
      cursor:pointer;
      font-size:22px;
      display:flex;
      align-items:center;
      justify-content:center;
      transition:background .2s, transform .2s;
    }
    #musicToggle:hover{ transform: translateY(-1px) scale(1.03); }

    /* Polaroid area: cat container */
    .polaroid-cat {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .polaroid-cat .valentine-cat {
      width: 100%;
      max-width: 220px;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 200px;
    }

    /* ===== Inlined cat CSS (from cat-css.css), scoped + animations ===== */
    .valentine-cat article {
      --fur: #222;
      --fur-dark: #111;
      --skin: pink;
      font-size: 0.6vmin;
      width: 80em;
      aspect-ratio: 1;
      position: relative;
    }
    .valentine-cat article *,
    .valentine-cat article *::before,
    .valentine-cat article *::after {
      position: absolute;
      box-sizing: border-box;
    }
    .valentine-cat #alt_cat {
      width: 1px;
      height: 1px;
      overflow: hidden;
    }
    .valentine-cat .shadow {
      width: 80%;
      height: 5%;
      background: #0002;
      border-radius: 50% / 0 0 100% 100%;
      top: 99%;
      left: 50%;
      translate: -50%;
    }
    .valentine-cat .tail {
      width: 50%;
      height: 50%;
      border-radius: 50%;
      border: 7em solid #0000;
      border-top-color: var(--fur-dark);
      border-left-color: var(--fur-dark);
      clip-path: polygon(100% 0, 100% 100%, 0 30%, 0 0);
      top: 75%;
      left: 52%;
      animation: tailWave 1.4s ease-in-out infinite;
      transform-origin: 75% 20%;
    }
    .valentine-cat .tail::before {
      content: "";
      width: 7em;
      aspect-ratio: 1;
      background: var(--fur-dark);
      border-radius: 50%;
      left: 81%;
      top: -9%;
    }
    @keyframes tailWave {
      0%, 100% { transform: rotate(-8deg); }
      50% { transform: rotate(12deg); }
    }
    .valentine-cat .body {
      left: 50%;
      translate: -50%;
      bottom: 0;
      width: 35%;
      height: 40%;
      background:
        radial-gradient(100% 80% at 50% 0, var(--fur-dark) 50%, #0000 0),
        var(--fur);
      border-radius: 100% / 200% 200% 20% 20%;
    }
    .valentine-cat .body .leg {
      width: 165%;
      height: 38%;
      background: var(--fur);
      bottom: 0;
      left: 50%;
      translate: -50%;
      border-radius: 8em 8em 100% 100% / 10em 10em 16em 16em;
      scale: 1 -1;
    }
    .valentine-cat .body .paw {
      width: 35%;
      height: 49%;
      border: 0.75em solid #fff;
      border-top: 0;
      border-radius: 0 0 5em 5em;
      border-bottom: 1em solid #fff;
      top: 48%;
      rotate: -10deg;
      left: 10%;
      clip-path: polygon(0 20%, 100% 30%, 100% 100%, 0 100%);
    }
    .valentine-cat .body .paw + .paw {
      right: 7%;
      height: 50%;
      left: auto;
      rotate: 13deg;
      scale: -1 1;
      clip-path: polygon(0 25%, 100% 15%, 100% 100%, 0 100%);
    }
    .valentine-cat .ear {
      width: 40%;
      aspect-ratio: 1;
      border: 4em solid var(--fur);
      border-radius: 5% 90% 10% 80%;
      background: var(--skin);
    }
    .valentine-cat .ear + .ear {
      scale: -1 1;
      right: 0;
    }
    .valentine-cat .head {
      width: 80%;
      aspect-ratio: 1.1;
      background: linear-gradient(#0003, #0000 50%), var(--fur);
      left: 50%;
      translate: -50%;
      border-radius: 100% / 125% 125% 80% 75%;
    }
    .valentine-cat .head .whisker {
      width: 30%;
      height: 30%;
      border-radius: 50%;
      border: 2em solid #0000;
      border-top-color: var(--fur);
      border-left-color: var(--fur);
      clip-path: polygon(100% 0, 100% 100%, 0 30%, 0 0);
    }
    .valentine-cat .head .whisker:nth-child(1) { top: 70%; translate: -65%; }
    .valentine-cat .head .whisker:nth-child(2) { top: 80%; translate: -40%; rotate: -20deg; }
    .valentine-cat .head .whisker:nth-child(3) { right: 0%; top: 70%; translate: 65%; rotate: 10deg; }
    .valentine-cat .head .whisker:nth-child(4) { right: 0; top: 80%; translate: 40%; rotate: 24deg; }
    .valentine-cat .head .nose {
      width: 10%;
      height: 7%;
      background: var(--skin);
      border-radius: 50%;
      top: 75%;
      left: 50%;
      translate: -50% -50%;
      top: 78%;
    }
    .valentine-cat .head .eye {
      --pos: 25%;
      --x1: 50%;
      --x2: 42%;
      --pupil-x: 50%;
      --pupil-y: 52%;
      width: 35%;
      aspect-ratio: 1;
      border-radius: 50%;
      overflow: visible;
      background:
        radial-gradient(50% 50% at var(--x1) 47%, #fff 25%, #0000 0),
        radial-gradient(50% 50% at var(--x2) 65%, #fff 12%, #0000 0),
        radial-gradient(circle at var(--pupil-x) var(--pupil-y), #000 28%, #0000 0),
        white;
      top: 60%;
      left: var(--pos);
      translate: -50% -50%;
      top: 63%;
      animation: catBlinkLeft 4s ease-in-out infinite;
    }
    .valentine-cat .head .eye + .eye {
      /* Same --x1/--x2 as left eye so highlights mirror correctly under scale(-1,1) */
      --x1: 50%;
      --x2: 42%;
      --pupil-x: 50%;
      --pupil-y: 52%;
      left: calc(100% - var(--pos));
      animation: catBlinkRight 4s ease-in-out infinite;
    }
    @keyframes catBlinkLeft {
      0%, 45%, 55%, 100% { transform: translate(-50%, -50%) scaleY(1); }
      48%, 52% { transform: translate(-50%, -50%) scaleY(0.08); }
    }
    @keyframes catBlinkRight {
      0%, 45%, 55%, 100% { transform: translate(-50%, -50%) scale(-1, 1) scaleY(1); }
      48%, 52% { transform: translate(-50%, -50%) scale(-1, 1) scaleY(0.08); }
    }

    /* Reduced motion preference */
    @media (prefers-reduced-motion: reduce){
      *{ animation: none !important; transition: none !important; }
      #introOverlay{ display:none !important; }
      #mainApp{ opacity:1 !important; pointer-events:auto !important; }
    }
  </style>
</head>

<body>
  <div class="hearts" id="hearts"></div>
  <div class="sparkles" id="sparkles"></div>

  <!-- MOVIE TRAILER INTRO OVERLAY -->
  <div id="introOverlay" aria-label="Trailer intro overlay">
    <div class="introLayers" id="introLayers">
      <div class="introLayer layerA"></div>
      <div class="introLayer layerB"></div>
      <div class="introLayer layerC"></div>
    </div>
    <div class="spotlight" aria-hidden="true"></div>
    <div class="filmGrain" aria-hidden="true"></div>
    <div class="vignette" aria-hidden="true"></div>

    <div class="introStage">
      <div class="titleCards" aria-hidden="false">
        <!-- Beat 1 -->
        <div class="cardBeat" id="beat1">
          <div>
            <div class="beatText">Presented by</div>
            <h2 class="beatBig"><span class="pink">Luca</span></h2>
            <div class="beatSmall">A tiny production, with very serious feelings.</div>
          </div>
        </div>

        <!-- Beat 2 -->
        <div class="cardBeat" id="beat2">
          <div>
            <div class="beatText">Starring</div>
            <h2 class="beatBig"><span class="pink">Luca</span> &amp; <span class="pink">Bianca</span></h2>
            <div class="beatSmall">Two leads. One love story. Unlimited cute moments.</div>
          </div>
        </div>

        <!-- Beat 3 -->
        <div class="cardBeat" id="beat3">
          <div>
            <div class="beatText">This Valentine’s</div>
            <h2 class="beatBig">One question</h2>
            <div class="beatSmall">changes everything…</div>
          </div>
        </div>
      </div>

      <div class="trailerDivider" id="trailerDivider"></div>

      <!-- Final reveal -->
      <div class="finalReveal" id="finalReveal">
        <div class="cinLine" id="finalLine"></div>

        <div class="beatSmall" style="margin-top:14px; color: rgba(255,255,255,.82);">
          Bianca… are you ready? ✨
        </div>

        <div class="pulseLine" id="pulseLine" aria-hidden="true">
          <span></span><span></span><span></span><span></span><span></span>
        </div>

        <div class="introBtnRow">
          <button id="introContinue" class="introBtn" aria-label="Continue into the main app">
            <span class="introBtnText">Continue</span>
            <span class="introBtnIcon">▶</span>
          </button>
          <button id="skipIntro" class="skipBtn" aria-label="Skip intro">Skip</button>
        </div>
      </div>
    </div>
  </div>

  <div class="shutterFlash" id="shutterFlash" aria-hidden="true"></div>

  <!-- Music toggle (your original) -->
  <audio id="bgMusic" loop preload="auto" src="love-romantic-hopeful-music-333017.mp3"></audio>
  <button id="musicToggle" aria-label="Toggle music">🎵</button>

  <main class="wrap" id="mainApp" style="opacity:0;pointer-events:none;transition:opacity .7s;">
    <section class="card" aria-label="Valentine app">
      <div>
        <div class="title">
          <h1>Will you be my Valentine? 💘</h1>
          <div class="badge" id="daysBadge">💌</div>
        </div>

        <p class="subtitle" id="subtitle">
        </p>

        <div class="note">
          <div><strong>Pick your answer carefully…</strong> (I may have coded a tiny bit of mischief 😇)</div>
        </div>

        <div class="actions">
          <button class="yes" id="yesBtn">Yes! 💖</button>
          <button class="no" id="noBtn">No 🙈</button>
        </div>

        <p class="tiny" id="tinyHint">Tip: Try tapping “No” a couple times 😉</p>

        <div class="footer">
         
        </div>
      </div>

      <aside class="polaroid polaroid-cat" aria-label="Cute cat">
        <div class="valentine-cat" id="valentineCat">
          <article role="img" aria-labelledby="alt_cat">
            <div id="alt_cat">Cartoon of a black cat drawn in cute/kawaii style</div>
            <div class="shadow"></div>
            <div class="tail"></div>
            <div class="body">
              <div class="leg"></div>
              <div class="leg"></div>
              <div class="paw"></div>
              <div class="paw"></div>
            </div>
            <div class="ear"></div>
            <div class="ear"></div>
            <div class="head">
              <div class="whisker"></div>
              <div class="whisker"></div>
              <div class="whisker"></div>
              <div class="whisker"></div>
              <div class="eye"></div>
              <div class="eye"></div>
              <div class="nose"></div>
            </div>
          </article>
        </div>
        <div class="caption">Jupi is looking at you 🐱💖</div>
      </aside>
    </section>
  </main>

  <div class="overlay" id="overlay" role="dialog" aria-modal="true" aria-label="Success">
    <div class="modal">
      <button class="close" id="closeBtn" aria-label="Close">✕</button>
      <div class="burst" id="burst"></div>
      <h2>Yay!! It’s a date 💞</h2>
      <p id="successText">
        Bianca, I’m so lucky to have you. Saying yes to you is the easiest thing — and now we officially have Valentine’s together. I’m going to make it unforgettable. Can’t wait to see you. 💖
      </p>
      <div class="actions" style="margin-top:16px">
        <button class="yes" id="copyBtn">Copy a cute message 📩</button>
        <button class="no" id="resetBtn">Replay 🔁</button>
      </div>
      <p class="tiny" style="margin-top:12px; opacity:.85">
        You’re the best. 🫶
      </p>
    </div>
  </div>

  <script>
    /* =========
       SPARKLES
       ========= */
    const sparkles = document.getElementById("sparkles");
    for(let i=0;i<22;i++){
      const s = document.createElement("div");
      s.className = "sparkle";
      s.style.left = Math.random()*100 + "vw";
      s.style.top = Math.random()*100 + "vh";
      s.style.animationDelay = (Math.random()*2.2) + "s";
      s.style.animationDuration = (1.5 + Math.random()*1.5) + "s";
      s.style.opacity = (0.5 + Math.random()*0.5).toFixed(2);
      sparkles.appendChild(s);
    }

    /* ==========================
       MOVIE TRAILER INTRO (JS)
       ========================== */
    const introOverlay = document.getElementById("introOverlay");
    const mainApp = document.getElementById("mainApp");
    const introContinue = document.getElementById("introContinue");
    const skipIntro = document.getElementById("skipIntro");
    const shutterFlash = document.getElementById("shutterFlash");
    const introLayers = document.getElementById("introLayers");

    const beat1 = document.getElementById("beat1");
    const beat2 = document.getElementById("beat2");
    const beat3 = document.getElementById("beat3");

    const trailerDivider = document.getElementById("trailerDivider");
    const finalReveal = document.getElementById("finalReveal");
    const pulseLine = document.getElementById("pulseLine");

    const finalLine = document.getElementById("finalLine");

    // Hide main app initially
    mainApp.style.opacity = 0;
    mainApp.style.pointerEvents = "none";

    // Letter-by-letter final title
    function typeLine(el, text, startDelayMs){
      el.innerHTML = "";
      const chars = [...text];
      chars.forEach((c, i) => {
        const span = document.createElement("span");
        span.className = "ch";
        span.textContent = c === " " ? "\u00A0" : c;
        span.style.animationDelay = (startDelayMs/1000 + i*0.035) + "s";
        el.appendChild(span);
      });
    }
    typeLine(finalLine, "Will you be my Valentine?", 120);

    // Parallax camera drift (auto + mouse tilt)
    let mx = 0, my = 0;
    window.addEventListener("mousemove", (e) => {
      const x = (e.clientX / window.innerWidth) * 2 - 1;
      const y = (e.clientY / window.innerHeight) * 2 - 1;
      mx = x; my = y;
    });

    let t0 = performance.now();
    function parallaxTick(now){
      const t = (now - t0) / 1000;
      const autoX = Math.sin(t * 0.35) * 0.18;
      const autoY = Math.cos(t * 0.28) * 0.18;

      const x = (mx * 0.45 + autoX) * 18;  // px
      const y = (my * 0.45 + autoY) * 14;  // px

      introLayers.style.transform = `translate3d(${x*0.45}px, ${y*0.45}px, 0) scale(1.02)`;

      const a = introLayers.querySelector(".layerA");
      const b = introLayers.querySelector(".layerB");
      const c = introLayers.querySelector(".layerC");
      if(a) a.style.transform = `translate3d(${x*0.10}px, ${y*0.10}px, 0)`;
      if(b) b.style.transform = `translate3d(${x*0.18}px, ${y*0.18}px, 0)`;
      if(c) c.style.transform = `translate3d(${x*0.28}px, ${y*0.28}px, 0)`;

      requestAnimationFrame(parallaxTick);
    }
    requestAnimationFrame(parallaxTick);

    // WebAudio cinematic sting (no external files)
    function playCinematicSting(){
      try{
        const AudioCtx = window.AudioContext || window.webkitAudioContext;
        const ctx = new AudioCtx();
        const now = ctx.currentTime;

        const master = ctx.createGain();
        master.gain.value = 0.9;
        master.connect(ctx.destination);

        // boom
        const boomOsc = ctx.createOscillator();
        const boomGain = ctx.createGain();
        boomOsc.type = "sine";
        boomOsc.frequency.setValueAtTime(82, now);
        boomOsc.frequency.exponentialRampToValueAtTime(44, now + 0.30);
        boomGain.gain.setValueAtTime(0.0001, now);
        boomGain.gain.exponentialRampToValueAtTime(0.55, now + 0.03);
        boomGain.gain.exponentialRampToValueAtTime(0.0001, now + 0.55);
        boomOsc.connect(boomGain);
        boomGain.connect(master);
        boomOsc.start(now);
        boomOsc.stop(now + 0.58);

        // shimmer chord
        [523.25, 659.25, 783.99].forEach((f, i) => {
          const o = ctx.createOscillator();
          const g = ctx.createGain();
          o.type = "triangle";
          o.frequency.setValueAtTime(f, now + 0.08);
          g.gain.setValueAtTime(0.0001, now + 0.08);
          g.gain.exponentialRampToValueAtTime(0.15, now + 0.14 + i*0.02);
          g.gain.exponentialRampToValueAtTime(0.0001, now + 0.80);
          o.connect(g);
          g.connect(master);
          o.start(now + 0.08);
          o.stop(now + 0.82);
        });

        // whoosh noise
        const bufferSize = 2 * ctx.sampleRate;
        const noiseBuffer = ctx.createBuffer(1, bufferSize, ctx.sampleRate);
        const output = noiseBuffer.getChannelData(0);
        for (let i = 0; i < bufferSize; i++) output[i] = (Math.random() * 2 - 1) * 0.35;

        const noise = ctx.createBufferSource();
        noise.buffer = noiseBuffer;

        const filter = ctx.createBiquadFilter();
        filter.type = "lowpass";
        filter.frequency.setValueAtTime(650, now);
        filter.frequency.exponentialRampToValueAtTime(4600, now + 0.40);

        const nGain = ctx.createGain();
        nGain.gain.setValueAtTime(0.0001, now);
        nGain.gain.exponentialRampToValueAtTime(0.22, now + 0.12);
        nGain.gain.exponentialRampToValueAtTime(0.0001, now + 0.60);

        noise.connect(filter);
        filter.connect(nGain);
        nGain.connect(master);

        noise.start(now);
        noise.stop(now + 0.62);

        setTimeout(() => ctx.close(), 1500);
      }catch(e){}
    }

    // Beat sequencing
    let timelineTimers = [];
    function clearTimeline(){
      timelineTimers.forEach(t => clearTimeout(t));
      timelineTimers = [];
    }
    function showBeat(el){
      [beat1, beat2, beat3].forEach(b => {
        if(b !== el){
          b.classList.remove("show");
          b.classList.remove("hide");
        }
      });
      el.classList.remove("hide");
      el.classList.add("show");
    }
    function hideBeat(el){
      el.classList.remove("show");
      el.classList.add("hide");
    }

    function startTrailerTimeline(){
      clearTimeline();

      showBeat(beat1);
      // little sting on first beat (soft)
      timelineTimers.push(setTimeout(() => { /* subtle, no audio yet */ }, 150));

      timelineTimers.push(setTimeout(() => {
        hideBeat(beat1);
      }, 1850));

      timelineTimers.push(setTimeout(() => {
        showBeat(beat2);
      }, 2100));

      timelineTimers.push(setTimeout(() => {
        hideBeat(beat2);
      }, 4150));

      timelineTimers.push(setTimeout(() => {
        showBeat(beat3);
      }, 4400));

      timelineTimers.push(setTimeout(() => {
        hideBeat(beat3);
      }, 6400));

      // final reveal + controls appear
      timelineTimers.push(setTimeout(() => {
        trailerDivider.classList.add("on");
        finalReveal.classList.add("on");
        pulseLine.classList.add("on");
        introContinue.classList.add("on");
      }, 6750));
    }

    startTrailerTimeline();

    function revealMain(withSting){
      if(withSting) playCinematicSting();

      shutterFlash.classList.add("fire");
      introOverlay.classList.add("hide");

      setTimeout(() => {
        introOverlay.style.display = "none";
        mainApp.style.opacity = 1;
        mainApp.style.pointerEvents = "auto";
      }, 850);
    }

    introContinue.addEventListener("click", () => {
      if (navigator.vibrate) navigator.vibrate([18, 40, 18]);
      revealMain(true);
      startMusicIfAllowed();
    });

    skipIntro.addEventListener("click", () => {
      clearTimeline();
      revealMain(false);
      startMusicIfAllowed();
    });

    // Keyboard accessibility
    window.addEventListener("keydown", (e) => {
      if (introOverlay.style.display !== "none" && (e.key === "Enter" || e.key === " ")) {
        e.preventDefault();
        introContinue.click();
      }
      if (introOverlay.style.display !== "none" && e.key.toLowerCase() === "s") {
        skipIntro.click();
      }
    });

    /* ==========
       MUSIC TOGGLE
       ========== */
    const music = document.getElementById("bgMusic");
    const musicToggle = document.getElementById("musicToggle");
    let musicOn = false;

    function startMusicIfAllowed() {
      if (musicOn) return;
      const p = music.play();
      if (p && typeof p.then === "function") {
        p.then(function() {
          musicOn = true;
          musicToggle.style.background = "#ffb6d5";
          musicToggle.textContent = "🔊";
        }).catch(function() {});
      }
    }

    musicToggle.addEventListener("click", () => {
      if(musicOn){
        music.pause();
        musicOn = false;
        musicToggle.style.background = "rgba(255,255,255,.7)";
        musicToggle.textContent = "🎵";
      }else{
        music.play().then(function() {
          musicOn = true;
          musicToggle.style.background = "#ffb6d5";
          musicToggle.textContent = "🔊";
        }).catch(function() {});
      }
    });

    /* ==========================
       MAIN APP (unchanged behavior)
       ========================== */

    // background floating hearts
    const hearts = document.getElementById("hearts");
    const heartCount = 18;
    for(let i=0;i<heartCount;i++){
      const h = document.createElement("div");
      h.className = "heart";
      const left = Math.random()*100;
      const dur = 7 + Math.random()*9;
      const delay = Math.random()*-12;
      const size = 10 + Math.random()*18;
      h.style.left = left + "vw";
      h.style.animationDuration = dur + "s";
      h.style.animationDelay = delay + "s";
      h.style.width = size + "px";
      h.style.height = size + "px";
      hearts.appendChild(h);
    }

    // badge: days until Valentine's
    const badge = document.getElementById("daysBadge");
    (function updateBadge(){
      const now = new Date();
      const year = now.getFullYear();
      const valentines = new Date(year, 1, 14, 0, 0, 0);
      const target = (now > valentines) ? new Date(year+1, 1, 14, 0, 0, 0) : valentines;
      const ms = target - now;
      const days = Math.ceil(ms / (1000*60*60*24));
      badge.textContent = `⏳ ${days} day${days===1?"":"s"} to Feb 14`;
    })();

    // Mischievous "No" button (dodges)
    const noBtn = document.getElementById("noBtn");
    const yesBtn = document.getElementById("yesBtn");
    let noCount = 0;

    function moveNo(){
      const rect = noBtn.getBoundingClientRect();
      const pad = 12;
      const maxX = window.innerWidth - rect.width - pad;
      const maxY = window.innerHeight - rect.height - pad;

      const x = Math.max(pad, Math.random() * maxX);
      const y = Math.max(pad, Math.random() * maxY);

      noBtn.style.position = "fixed";
      noBtn.style.left = x + "px";
      noBtn.style.top = y + "px";
      noBtn.style.zIndex = 4;
      noBtn.style.transition = "left .18s ease, top .18s ease, transform .18s ease";
      noBtn.style.transform = "rotate(" + (Math.random()*10-5).toFixed(1) + "deg)";
    }

    noBtn.addEventListener("mouseenter", () => {
      noCount++;
      if(noCount >= 1) moveNo();
      if(noCount >= 3){
        yesBtn.style.transform = "scale(1.09)";
        yesBtn.style.boxShadow = "0 0 32px #7ef0c1, 0 18px 45px rgba(39,194,129,.28)";
      }
      if(noCount >= 5){
        document.getElementById("tinyHint").textContent = "Okay okay… I think the universe is hinting something 😌";
      }
    });

    noBtn.addEventListener("click", (e) => {
      noCount++;
      moveNo();
      e.preventDefault();
      e.stopPropagation();
    });

    // Success overlay
    const overlay = document.getElementById("overlay");
    const closeBtn = document.getElementById("closeBtn");
    const resetBtn = document.getElementById("resetBtn");
    const copyBtn = document.getElementById("copyBtn");
    const burst = document.getElementById("burst");

    function makeBurst(){
      burst.innerHTML = "";
      const n = 18;
      for(let i=0;i<n;i++){
        const el = document.createElement("i");
        el.style.left = (Math.random()*100) + "%";
        el.style.animationDelay = (Math.random()*0.9) + "s";
        el.style.animationDuration = (1 + Math.random()*1.2) + "s";
        el.style.opacity = (0.6 + Math.random()*0.4).toFixed(2);
        burst.appendChild(el);
      }
    }

    // Optional: get an email when she clicks Yes! Create a form at https://formspree.io,
    // then paste your form endpoint here (e.g. "https://formspree.io/f/abcdefgh"). Leave empty to disable.
    const NOTIFY_ON_YES = "";

    yesBtn.addEventListener("click", () => {
      makeBurst();
      overlay.classList.add("show");
      if (navigator.vibrate) navigator.vibrate([25, 30, 25]);
      if (NOTIFY_ON_YES) {
        fetch(NOTIFY_ON_YES, {
          method: "POST",
          headers: { "Content-Type": "application/json" },
          body: JSON.stringify({ message: "She said Yes! 💖", response: "Yes!", _subject: "Valentine: She said Yes! 💖" })
        }).catch(function() {});
      }
    });

    closeBtn.addEventListener("click", () => overlay.classList.remove("show"));
    overlay.addEventListener("click", (e) => { if(e.target === overlay) overlay.classList.remove("show"); });

    resetBtn.addEventListener("click", () => {
      overlay.classList.remove("show");
      noCount = 0;
      noBtn.style.position = "relative";
      noBtn.style.left = "auto";
      noBtn.style.top = "auto";
      noBtn.style.transform = "none";
      document.getElementById("tinyHint").textContent = "Tip: Try tapping “No” a couple times 😉";
    });

    copyBtn.addEventListener("click", async () => {
      const msg = "Happy Valentine’s 💖 Bianca, will you be my Valentine? — Luca 🫶";
      try{
        await navigator.clipboard.writeText(msg);
        copyBtn.textContent = "Copied! ✅";
        setTimeout(()=> copyBtn.textContent = "Copy a cute message 📩", 1600);
      }catch{
        alert(msg);
      }
    });
  </script>

  <script>
    // Cat in the card: pupils look around via CSS vars (tail + blink are CSS-only)
    (function animateCardCatEyes() {
      const container = document.getElementById("valentineCat");
      if (!container) return;
      const eyes = container.querySelectorAll(".head .eye");
      if (!eyes.length) return;

      function randomInRange(min, max) {
        return Math.random() * (max - min) + min;
      }
      function clamp(val, min, max) {
        return Math.max(min, Math.min(max, val));
      }
      function moveEyes() {
        const vw = window.innerWidth;
        const vh = window.innerHeight;
        const cx = vw * randomInRange(0.2, 0.8);
        const cy = vh * randomInRange(0.2, 0.6);
        const eyeList = Array.from(eyes);
        eyeList.forEach(function (eye, i) {
          const rect = eye.getBoundingClientRect();
          const ex = rect.left + rect.width / 2;
          const ey = rect.top + rect.height / 2;
          const dx = cx - ex;
          const dy = cy - ey;
          const maxDist = Math.max(rect.width * 0.28, 8);
          const dist = Math.min(maxDist, Math.hypot(dx, dy));
          const angle = Math.atan2(dy, dx);
          const tx = Math.cos(angle) * dist;
          const ty = Math.sin(angle) * dist;
          var pctX, pctY;
          if (i === 0) {
            pctX = 50 + (tx / rect.width) * 24;
            pctY = 52 + (ty / rect.height) * 24;
          } else {
            pctX = 50 - (tx / rect.width) * 24;
            pctY = 52 + (ty / rect.height) * 24;
          }
          pctX = clamp(pctX, 38, 62);
          pctY = clamp(pctY, 38, 62);
          eye.style.setProperty("--pupil-x", pctX + "%");
          eye.style.setProperty("--pupil-y", pctY + "%");
        });
      }
      setInterval(moveEyes, 1800);
      window.addEventListener("resize", moveEyes);
      setTimeout(moveEyes, 200);
    })();
  </script>
</body>
</html>
