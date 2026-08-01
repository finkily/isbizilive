<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>bizi4l — is he live?</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,600&family=Sora:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg-1: #17122b;
    --bg-2: #2a1a4d;
    --glass: rgba(255,255,255,0.055);
    --glass-border: rgba(255,255,255,0.10);
    --text: #f3f1fb;
    --mute: #b3aad0;
    --live: #38e2bd;
    --live-dim: rgba(56,226,189,0.18);
    --off: #7d76a3;
    --off-dim: rgba(125,118,163,0.16);
  }
  *{ box-sizing:border-box; }
  html,body{ height:100%; margin:0; }
  body{
    font-family:'Sora', sans-serif;
    color: var(--text);
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    padding: 24px;
    background:
      radial-gradient(1100px 700px at 15% -10%, rgba(120,90,220,0.35), transparent 60%),
      radial-gradient(900px 600px at 110% 110%, rgba(56,226,189,0.12), transparent 55%),
      linear-gradient(160deg, var(--bg-1), var(--bg-2));
    background-attachment: fixed;
    position:relative;
    overflow:hidden;
  }

  .card{
    width:100%;
    max-width: 420px;
    background: var(--glass);
    border: 1px solid var(--glass-border);
    backdrop-filter: blur(18px);
    -webkit-backdrop-filter: blur(18px);
    border-radius: 22px;
    padding: 44px 36px 36px;
    text-align:center;
    box-shadow: 0 30px 60px -20px rgba(0,0,0,0.55);
    position:relative;
    z-index:1;
  }

  .eyebrow{
    font-family:'IBM Plex Mono', monospace;
    font-size: 11.5px;
    letter-spacing: .18em;
    text-transform: uppercase;
    color: var(--mute);
    margin: 0 0 26px;
  }

  /* signature element: breathing status badge */
  .badge{
    position:relative;
    width: 92px;
    height: 92px;
    margin: 0 auto 26px;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .ring{
    position:absolute;
    inset:0;
    border-radius:50%;
    border: 1.5px solid var(--off);
    opacity:.55;
  }
  .ring.r2{ inset:-10px; opacity:.25; }
  .dot{
    width: 16px;
    height: 16px;
    border-radius: 50%;
    background: var(--off);
    transition: background .4s ease;
  }

  .badge.live .ring{ border-color: var(--live); }
  .badge.live .dot{ background: var(--live); box-shadow: 0 0 16px 2px var(--live-dim); }
  .badge.live .ring.r1{ animation: pulse 2.4s ease-out infinite; }
  .badge.live .ring.r2{ animation: pulse 2.4s ease-out infinite .6s; }

  @keyframes pulse{
    0%   { transform: scale(0.85); opacity:.55; }
    80%  { transform: scale(1.55); opacity:0; }
    100% { transform: scale(1.55); opacity:0; }
  }

  h1{
    font-family:'Fraunces', serif;
    font-weight: 600;
    font-size: 30px;
    letter-spacing: -0.01em;
    margin: 0 0 10px;
    transition: color .3s ease;
  }
  h1.live{ color: var(--live); }
  h1.off{ color: var(--text); }

  p.sub{
    font-size: 14.5px;
    line-height:1.55;
    color: var(--mute);
    margin: 0 0 30px;
    min-height: 22px;
  }

  .cta{
    display:inline-flex;
    align-items:center;
    gap:8px;
    padding: 14px 28px;
    border-radius: 12px;
    text-decoration:none;
    font-family:'Sora', sans-serif;
    font-weight:600;
    font-size: 14.5px;
    color: #14102a;
    background: var(--off);
    transition: transform .18s ease, background .3s ease, box-shadow .3s ease;
  }
  .cta:hover{ transform: translateY(-2px); }
  .cta.live{
    background: var(--live);
    box-shadow: 0 10px 30px -8px var(--live-dim);
  }
  .cta.live:hover{ box-shadow: 0 14px 34px -6px rgba(56,226,189,0.4); }
  .cta svg{ width:15px; height:15px; }

  .meta{
    margin-top: 22px;
    font-family:'IBM Plex Mono', monospace;
    font-size: 10.5px;
    letter-spacing: .06em;
    color: rgba(179,170,208,0.55);
  }

  .clock{
    margin-top: 8px;
    font-family:'IBM Plex Mono', monospace;
    font-size: 13px;
    letter-spacing: .08em;
    color: var(--mute);
  }

  @media (prefers-reduced-motion: reduce){
    .badge.live .ring{ animation:none; }
  }
</style>
</head>
<body>

<div class="card">
  <p class="eyebrow">twitch · bizi4l</p>

  <div class="badge" id="badge">
    <div class="ring r2"></div>
    <div class="ring r1"></div>
    <div class="dot"></div>
  </div>

  <h1 id="heading" class="off">checking…</h1>
  <p class="sub" id="sub">Give me a second to check the signal.</p>

  <a class="cta" id="cta" href="https://twitch.tv/bizi4l" target="_blank" rel="noopener">
    <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4 2l-2 4v14h6v2h4l3-3h5l4-5V2H4z" fill="currentColor"/></svg>
    <span id="ctaText">Go to Twitch</span>
  </a>

  <p class="meta" id="meta">refreshes every 60s</p>
  <p class="clock" id="clock">--:--:--</p>
</div>

<script>
  const CHANNEL = "bizi4l";
  const POLL_MS = 60000;

  const badge = document.getElementById('badge');
  const heading = document.getElementById('heading');
  const sub = document.getElementById('sub');
  const cta = document.getElementById('cta');
  const ctaText = document.getElementById('ctaText');
  const meta = document.getElementById('meta');

  function setLive(isLive){
    badge.classList.toggle('live', isLive);
    if(isLive){
      heading.textContent = 'bizi4l is live';
      heading.className = 'live';
      sub.textContent = "He's streaming right now — come say hi.";
      cta.classList.add('live');
      ctaText.textContent = 'Watch Live';
    } else {
      heading.textContent = 'bizi4l is offline';
      heading.className = 'off';
      sub.textContent = "Not streaming at the moment. Follow so you catch the next one.";
      cta.classList.remove('live');
      ctaText.textContent = 'Go to Twitch';
    }
    meta.textContent = 'last checked ' + new Date().toLocaleTimeString();
  }

  async function checkStatus(){
    try{
      const res = await fetch(`https://decapi.me/twitch/uptime/${CHANNEL}`, { cache: "no-store" });
      const text = (await res.text()).trim().toLowerCase();
      setLive(!text.includes('offline'));
    } catch (err){
      sub.textContent = "Couldn't reach the signal check — retrying shortly…";
    }
  }

  const clock = document.getElementById('clock');
  function updateClock(){
    clock.textContent = new Date().toLocaleTimeString([], { hour: '2-digit', minute:'2-digit', second:'2-digit' });
  }
  updateClock();
  setInterval(updateClock, 1000);

  checkStatus();
  setInterval(checkStatus, POLL_MS);
</script>

</body>
</html>
