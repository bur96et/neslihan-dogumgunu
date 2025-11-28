<!doctype html>
<html lang="tr">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Neslihan Abla'ya Sürpriz ♥</title>
<style>
  html,body{height:100%;margin:0;padding:0;font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; overflow:hidden;}
  
  body{
    background: linear-gradient(135deg, #ffeef8 0%, #ffd1dc 30%, #ff9ec1 70%, #ff6b9d 100%);
    display:flex;
    align-items:center;
    justify-content:center;
    position:relative;
  }

  .message{
    position:relative;
    z-index:50;
    text-align:center;
    color:#fff;
    user-select:none;
    padding:2rem 3rem;
    border-radius:24px;
    background: rgba(255,255,255,0.15);
    backdrop-filter: blur(12px);
    border: 2px solid rgba(255,255,255,0.3);
    box-shadow: 0 20px 40px rgba(0,0,0,0.2);
  }

  .message h1{
    margin:0 0 1rem 0;
    font-size: clamp(32px, 8vw, 68px);
    font-weight:900;
    letter-spacing:2px;
    text-shadow: 0 8px 20px rgba(0,0,0,0.4);
    transform: translateY(30px);
    opacity:0;
    transition: all 900ms cubic-bezier(0.22,1,0.36,1);
  }

  .message.show h1{
    transform: translateY(0);
    opacity:1;
  }

  .subtitle{
    font-size: clamp(18px, 4vw, 28px);
    opacity:0;
    transform: translateY(20px);
    transition: all 900ms 300ms cubic-bezier(0.22,1,0.36,1);
  }
  .message.show .subtitle{ opacity:0.95; transform:none; }

  .hearts, .balloons{
    position: fixed;
    left:0; top:0; width:100%; height:100%;
    pointer-events:none;
    z-index:40;
  }

  .heart, .balloon{
    position: absolute;
    will-change: transform, opacity;
    animation: floatUp var(--dur) linear forwards;
    user-select:none;
  }

  .heart{
    font-size: clamp(24px, 5vw, 48px);
    filter: drop-shadow(0 6px 12px rgba(0,0,0,.3));
  }

  .balloon{
    font-size: clamp(30px, 6vw,60px);
    animation-duration: calc(var(--dur) * 1.4);
  }

  @keyframes floatUp {
    0%{ transform: translateY(100vh) scale(0.5) rotate(0deg); opacity:0; }
    10%{ opacity:1; }
    100%{ transform: translateY(-120vh) scale(1.2) rotate(30deg); opacity:0; }
  }

  .tap-hint{
    position:fixed;
    bottom:30px;
    left:50%;
    transform:translateX(-50%);
    background:rgba(0,0,0,0.3);
    color:white;
    padding:12px 24px;
    border-radius:50px;
    font-size:16px;
    backdrop-filter: blur(8px);
    z-index:60;
  }

  .click-area{ position:fixed; inset:0; z-index:45; cursor:pointer; }
</style>
</head>
<body>

  <div class="hearts" id="hearts"></div>
  <div class="balloons" id="balloons"></div>

  <div class="message" id="msg">
    <h1>Neslihan Abla<br>Doğum Günün Kutlu Olsun!</h1>
    <div class="subtitle">♥ Nice mutlu, sağlıklı, bol kahkahalı yıllara ♥</div>
  </div>

  <div class="click-area" id="clickArea"></div>
  <div class="tap-hint" id="hint">Ekrana dokun veya tıkla → Sürpriz başlasın!</div>

  <!-- SES DOSYANI DEĞİŞTİR: src="senin_dosya_adin.mp3" yap -->
  <audio id="bgMusic" loop preload="auto">
    <source src="sesim.mp3" type="audio/mpeg">
    Tarayıcın ses desteklemiyor.
  </audio>

<script>
(function(){
  const hearts = document.getElementById('hearts');
  const balloons = document.getElementById('balloons');
  const msg = document.getElementById('msg');
  const hint = document.getElementById('hint');
  const clickArea = document.getElementById('clickArea');
  const audio = document.getElementById('bgMusic');

  const HEART_COLORS = ['#ff6b9d','#ff8cb3','#ffa3c4','#ffb3d4','#ff9ec1','#ff77a9'];
  const BALLOON_EMOJIS = ['🎈','🎉','🎊','🎀','✨','🌸','💖'];

  let triggered = false;

  function rnd(min,max){ return Math.random()*(max-min)+min; }

  function createHeart(xPercent){
    const el = document.createElement('div');
    el.className = 'heart';
    el.innerHTML = '❤';  // Kalp emoji düzeltildi
    el.style.left = xPercent + '%';
    el.style.color = HEART_COLORS[Math.floor(rnd(0,HEART_COLORS.length))];
    el.style.setProperty('--dur', rnd(3000,5000)+'ms');
    hearts.appendChild(el);
    setTimeout(()=>el.remove(), 6000);
  }

  function createBalloon(xPercent){
    const el = document.createElement('div');
    el.className = 'balloon';
    el.innerHTML = BALLOON_EMOJIS[Math.floor(rnd(0,BALLOON_EMOJIS.length))];  // Balon emoji'leri düzeltildi
    el.style.left = xPercent + '%';
    el.style.setProperty('--dur', rnd(5000,8000)+'ms');
    balloons.appendChild(el);
    setTimeout(()=>el.remove(), 9000);
  }

  function burst(xPercent){
    for(let i=0; i<22; i++){
      const offset = rnd(-18,18);
      createHeart(Math.max(5, Math.min(95, xPercent + offset)));
    }
    for(let i=0; i<10; i++){
      const offset = rnd(-25,25);
      createBalloon(Math.max(5, Math.min(95, xPercent + offset)));
    }
  }

  function startCelebration(x = 50){
    if(triggered) return;
    triggered = true;

    hint.style.opacity = '0';
    setTimeout(()=> hint.style.display = 'none', 600);

    msg.classList.add('show');

    burst(x);
    setTimeout(()=>burst(x), 400);
    setTimeout(()=>burst(x), 800);

    const interval = setInterval(()=>{
      burst(rnd(20,80));
    }, 1200);

    setTimeout(()=>{
      clearInterval(interval);
      setInterval(()=>burst(rnd(10,90)), 3000);
    }, 15000);

    audio.volume = 0.6;
    audio.play().catch(()=>{});
  }

  window.onload = () => {
    setTimeout(()=> startCelebration(50), 800);
  };

  clickArea.onclick = clickArea.ontouchstart = (e) => {
    e.preventDefault();
    const x = e.type === 'touchstart' ? e.touches[0].clientX : e.clientX;
    const xPercent = (x / window.innerWidth) * 100;
    if(!triggered) startCelebration(xPercent);
    else burst(xPercent);
  };

})();
</script>
</body>
</html>
