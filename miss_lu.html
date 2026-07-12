<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Para Miss Lu</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400&family=Playfair+Display:ital,wght@0,600;1,500&family=Alex+Brush&display=swap" rel="stylesheet">
<style>
  :root{
    --cream:#f7ede0;
    --paper:#fffbf4;
    --plum:#43212e;
    --plum-soft:#6b3a49;
    --rose:#c98198;
    --rose-deep:#a85a74;
    --gold:#b8923f;
    --gold-light:#e9d19c;
    --shadow: rgba(67,33,46,0.28);
  }

  *{box-sizing:border-box;}

  html,body{
    height:100%;
    margin:0;
    overflow:hidden;
  }

  body{
    height:100vh;
    background:
      radial-gradient(circle at 18% 12%, #fdf2e4 0%, transparent 42%),
      radial-gradient(circle at 88% 85%, #f2ddce 0%, transparent 48%),
      var(--cream);
    font-family:'Cormorant Garamond', serif;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    gap:clamp(8px,2vh,18px);
    padding:clamp(10px,3vh,24px);
  }

  .hint{
    color:var(--plum-soft);
    font-size:clamp(11px,1.6vh,14px);
    letter-spacing:0.16em;
    text-transform:uppercase;
    opacity:0.6;
    animation: fade-pulse 2.6s ease-in-out infinite;
    text-align:center;
  }

  @keyframes fade-pulse{
    0%,100%{opacity:0.35;}
    50%{opacity:0.75;}
  }

  /* ---------- STAGE (auto-fits viewport) ---------- */
  .stage{
    position:relative;
    width:min(90vw, 420px, calc(66vh * 0.72));
    aspect-ratio: 0.72 / 1;
    perspective:2000px;
    flex:0 0 auto;
  }

  /* outer gold frame for a "stationery" feel */
  .frame{
    position:absolute;
    inset:-10px;
    border:1px solid var(--gold-light);
    border-radius:10px;
    pointer-events:none;
    opacity:0.7;
  }

  /* ---------- ENVELOPE ---------- */
  .envelope{
    position:absolute;
    inset:0;
    cursor:pointer;
  }

  .envelope-body{
    position:absolute;
    inset:0;
    background: linear-gradient(165deg, #fdf3e6, #f2ddc4 55%, #e9cea6);
    border-radius:8px;
    box-shadow: 0 25px 45px -14px var(--shadow), 0 0 0 1px rgba(184,146,63,0.3);
    overflow:hidden;
  }

  .envelope-body::before{
    content:'';
    position:absolute;
    top:0; left:0;
    width:0; height:0;
    border-style:solid;
    border-width:0 0 100% 50%;
    border-color: transparent transparent rgba(0,0,0,0.05) transparent;
  }
  .envelope-body::after{
    content:'';
    position:absolute;
    top:0; right:0;
    width:0; height:0;
    border-style:solid;
    border-width:100% 50% 0 0;
    border-color: rgba(0,0,0,0.05) transparent transparent transparent;
  }

  .inner-border{
    position:absolute;
    inset:10px;
    border:1px solid rgba(184,146,63,0.45);
    border-radius:4px;
    pointer-events:none;
  }

  .to-line{
    position:absolute;
    left:16%;
    bottom:16%;
    font-family:'Alex Brush', cursive;
    font-size:clamp(24px, 5.5vh, 36px);
    color:var(--plum-soft);
    opacity:0.9;
    transform: rotate(-1.5deg);
  }
  .to-line span{
    display:block;
    font-family:'Cormorant Garamond', serif;
    font-size:clamp(9px,1.5vh,12px);
    letter-spacing:0.3em;
    text-transform:uppercase;
    color: var(--rose-deep);
    opacity:0.85;
    margin-bottom:3px;
  }

  .flourish{
    position:absolute;
    right:8%;
    bottom:8%;
    font-size:clamp(14px,2.4vh,20px);
    color:var(--gold);
    opacity:0.55;
  }

  .flap{
    position:absolute;
    top:0; left:0; right:0;
    height:54%;
    background: linear-gradient(165deg, #f7e6d0, #e9cda6);
    clip-path: polygon(0 0, 100% 0, 50% 94%);
    transform-origin: top center;
    transform-style: preserve-3d;
    transition: transform 1.1s cubic-bezier(.6,0,.35,1.4);
    box-shadow: 0 2px 10px rgba(0,0,0,0.08);
    z-index: 5;
  }
  .flap::after{
    content:'';
    position:absolute;
    inset:8px 10px auto 10px;
    height:1px;
    background: linear-gradient(to right, transparent, rgba(184,146,63,0.5), transparent);
  }

  .seal{
    position:absolute;
    left:50%;
    top:45%;
    width:clamp(46px,10vh,68px);
    height:clamp(46px,10vh,68px);
    transform:translate(-50%,-50%);
    border-radius:50%;
    background: radial-gradient(circle at 35% 30%, #dd91a5, var(--rose-deep) 68%, #832f4c 100%);
    box-shadow: 0 6px 14px rgba(67,33,46,0.4), inset 0 -3px 6px rgba(0,0,0,0.25), inset 0 3px 5px rgba(255,255,255,0.28);
    display:flex;
    align-items:center;
    justify-content:center;
    font-family:'Alex Brush', cursive;
    font-size:clamp(24px,5vh,36px);
    color:#fbe9ee;
    z-index:6;
    transition: transform .6s ease, opacity .5s ease;
  }
  .seal::before{
    content:'';
    position:absolute;
    inset:-6px;
    border-radius:50%;
    border:1px solid rgba(251,233,238,0.35);
  }

  .envelope.open .flap{
    transform: rotateX(-172deg);
    z-index: 1;
  }
  .envelope.open .seal{
    opacity:0;
    transform:translate(-50%,-50%) scale(0.4) rotate(25deg);
  }

  /* ---------- LETTER ---------- */
  .letter{
    position:absolute;
    left:6%;
    right:6%;
    bottom:5%;
    height:90%;
    background:
      linear-gradient(var(--paper), var(--paper)) padding-box,
      repeating-linear-gradient(transparent, transparent 26px, rgba(201,129,152,0.09) 27px);
    border-radius:4px;
    box-shadow: 0 10px 28px rgba(67,33,46,0.3), inset 0 0 0 1px rgba(184,146,63,0.25);
    padding: clamp(16px,3.4vh,32px) clamp(16px,3vw,28px) clamp(14px,2.4vh,22px);
    z-index:3;
    transform: translateY(6%);
    transition: transform 1s cubic-bezier(.2,.7,.2,1), box-shadow .6s ease;
    overflow:hidden;
  }

  .envelope.open .letter{
    transform: translateY(-13%);
    box-shadow: 0 28px 55px rgba(67,33,46,0.38), inset 0 0 0 1px rgba(184,146,63,0.3);
  }

  .letter-inner{
    height:100%;
    overflow-y:auto;
    padding-right:6px;
  }
  .letter-inner::-webkit-scrollbar{width:4px;}
  .letter-inner::-webkit-scrollbar-thumb{background:var(--rose); border-radius:4px;}

  .letter h1{
    font-family:'Playfair Display', serif;
    font-style:italic;
    font-weight:600;
    font-size:clamp(18px,3.4vh,26px);
    color:var(--plum);
    margin: 2px 0 4px;
    text-align:center;
  }

  .ornament{
    text-align:center;
    color:var(--gold);
    font-size:clamp(12px,2vh,17px);
    letter-spacing:0.4em;
    margin-bottom:clamp(10px,1.8vh,16px);
    opacity:0.75;
  }

  .letter p{
    font-size:clamp(13.5px,2.2vh,18px);
    line-height:1.6;
    color:var(--plum-soft);
    margin:0 0 clamp(8px,1.6vh,13px);
  }

  .letter p:first-of-type::first-letter{
    font-family:'Playfair Display', serif;
    font-size:clamp(30px,5vh,42px);
    float:left;
    line-height:0.8;
    padding:5px 8px 0 0;
    color:var(--rose-deep);
  }

  .sign-off{
    text-align:right;
    margin-top:clamp(6px,1.2vh,14px);
  }
  .sign-off .name{
    font-family:'Alex Brush', cursive;
    font-size:clamp(22px,4vh,30px);
    color:var(--rose-deep);
    display:block;
  }

  .close-btn{
    position:absolute;
    top:8px;
    right:12px;
    width:24px;height:24px;
    border-radius:50%;
    border:1px solid var(--rose);
    background:var(--paper);
    color:var(--rose-deep);
    font-size:13px;
    line-height:1;
    cursor:pointer;
    opacity:0;
    pointer-events:none;
    transition:opacity .4s ease .35s;
  }
  .envelope.open .close-btn{
    opacity:0.85;
    pointer-events:auto;
  }
</style>
</head>
<body>

  <div class="hint" id="hint">toca el sello para abrir la carta</div>

  <div class="stage">
    <div class="frame"></div>

    <div class="envelope" id="envelope">

      <div class="letter">
        <button class="close-btn" id="closeBtn" aria-label="Cerrar carta">✕</button>
        <div class="letter-inner">
          <div class="ornament">✦ ✧ ✦</div>
          <h1>Para Miss Lu</h1>
          <p>Hay personas que entran a una habitación y simplemente cambian el aire, y tú eres una de ellas. Quiero que sepas, sin adornos ni exageraciones, que eres hermosa: por fuera, con esa luz que no necesita esfuerzo, y por dentro, que es donde de verdad importa.</p>
          <p>Tu sonrisa tiene ese poder extraño de hacer que hasta los días grises parezcan un poco más amables. Y no hablo solo de belleza física, sino de esa forma tuya de ser, de mirar, de hacer sentir bien a quien tienes cerca. Eso no se aprende, se tiene, y tú lo tienes de sobra.</p>
          <p>Ojalá algún día puedas verte con los mismos ojos con los que te ven las personas que te quieren, porque descubrirías que eres, sin lugar a dudas, extraordinaria.</p>
          <p>Que tengas un día tan bonito como tú.</p>
          <div class="sign-off">
            <span class="name">Con cariño</span>
          </div>
        </div>
      </div>

      <div class="envelope-body">
        <div class="inner-border"></div>
        <div class="to-line"><span>para</span>Miss Lu</div>
        <div class="flourish">❦</div>
      </div>

      <div class="flap"></div>
      <div class="seal">L</div>
    </div>
  </div>

<script>
  const envelope = document.getElementById('envelope');
  const hint = document.getElementById('hint');
  const closeBtn = document.getElementById('closeBtn');

  function openEnvelope(e){
    if(e) e.stopPropagation();
    envelope.classList.add('open');
    hint.style.opacity = '0';
  }
  function closeEnvelope(e){
    if(e) e.stopPropagation();
    envelope.classList.remove('open');
    hint.style.opacity = '';
  }

  envelope.addEventListener('click', function(){
    if(!envelope.classList.contains('open')) openEnvelope();
  });
  closeBtn.addEventListener('click', closeEnvelope);
</script>

</body>
</html>
