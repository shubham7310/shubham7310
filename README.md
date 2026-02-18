<!-- 
  SHUBHAM DARJI - GITHUB PROFILE README
  UNIQUE CYBERPUNK TERMINAL THEME WITH ANIMATIONS
  Just copy and paste this entire code into your README.md
-->

<div align="center">

<!-- MATRIX RAIN ANIMATION (CSS + HTML) -->
<style>
  @keyframes matrixRain {
    0% { transform: translateY(-100%); opacity: 1; }
    100% { transform: translateY(1000%); opacity: 0; }
  }
  
  @keyframes glitch {
    0% { text-shadow: 0.05em 0 0 #00ff00, -0.05em -0.025em 0 #0ff, 0.025em 0.05em 0 #f0f; }
    25% { text-shadow: -0.05em -0.025em 0 #00ff00, 0.025em 0.05em 0 #0ff, -0.05em -0.025em 0 #f0f; }
    50% { text-shadow: 0.025em 0.05em 0 #00ff00, 0.05em 0 0 #0ff, 0 -0.05em 0 #f0f; }
    75% { text-shadow: -0.025em 0 0 #00ff00, 0 -0.05em 0 #0ff, 0.05em 0 0 #f0f; }
    100% { text-shadow: 0.05em 0 0 #00ff00, -0.05em -0.025em 0 #0ff, 0.025em 0.05em 0 #f0f; }
  }
  
  @keyframes typing {
    from { width: 0; }
    to { width: 100%; }
  }
  
  @keyframes blink {
    50% { border-color: transparent; }
  }
  
  @keyframes pulse {
    0% { opacity: 1; }
    50% { opacity: 0.5; }
    100% { opacity: 1; }
  }
  
  @keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
    100% { transform: translateY(0px); }
  }
  
  .matrix-container {
    position: relative;
    width: 100%;
    height: 120px;
    overflow: hidden;
    background: #000;
    border-radius: 10px;
    border: 2px solid #0f0;
    margin: 20px 0;
  }
  
  .matrix-column {
    position: absolute;
    top: 0;
    color: #0f0;
    font-family: 'Courier New', monospace;
    font-size: 20px;
    animation: matrixRain 8s linear infinite;
    white-space: nowrap;
    writing-mode: vertical-rl;
    text-orientation: upright;
    letter-spacing: -5px;
  }
  
  .glitch-text {
    font-family: 'Courier New', monospace;
    font-size: 2.5rem;
    font-weight: bold;
    color: #0f0;
    animation: glitch 2s infinite;
    text-shadow: 2px 2px #000;
    margin: 20px 0;
  }
  
  .terminal-line {
    font-family: 'Courier New', monospace;
    color: #0f0;
    border-right: 3px solid #0f0;
    white-space: nowrap;
    overflow: hidden;
    width: 0;
    animation: typing 3.5s steps(40, end) forwards, blink 0.75s step-end infinite;
    font-size: 1.2rem;
    margin: 10px auto;
    display: inline-block;
  }
  
  .neon-box {
    border: 2px solid #0f0;
    border-radius: 15px;
    padding: 20px;
    box-shadow: 0 0 20px #0f0, inset 0 0 10px #0f0;
    transition: all 0.3s;
    background: rgba(0, 10, 0, 0.8);
    backdrop-filter: blur(2px);
  }
  
  .neon-box:hover {
    box-shadow: 0 0 40px #0f0, inset 0 0 20px #0f0;
    transform: scale(1.02);
  }
  
  .pulse-text {
    animation: pulse 2s infinite;
  }
  
  .float-element {
    animation: float 3s ease-in-out infinite;
  }
  
  .glitch-card {
    position: relative;
    overflow: hidden;
  }
  
  .glitch-card::before {
    content: '';
    position: absolute;
    top: -2px;
    left: -2px;
    right: -2px;
    bottom: -2px;
    background: linear-gradient(45deg, #0f0, #003300, #0f0);
    z-index: -1;
    filter: blur(10px);
    opacity: 0;
    transition: opacity 0.3s;
  }
  
  .glitch-card:hover::before {
    opacity: 1;
  }
  
  .progress-bar {
    height: 10px;
    background: linear-gradient(90deg, #0f0, #003300);
    border-radius: 5px;
    margin: 10px 0;
    position: relative;
    overflow: hidden;
  }
  
  .progress-bar::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
    animation: shine 2s infinite;
  }
  
  @keyframes shine {
    0% { transform: translateX(-100%); }
    100% { transform: translateX(100%); }
  }
  
  .ascii-border {
    border: 1px solid #0f0;
    padding: 10px;
    font-family: 'Courier New', monospace;
    color: #0f0;
  }
  
  .blink-cursor {
    animation: blink 1s step-end infinite;
  }
</style>

<!-- MATRIX RAIN BACKGROUND -->
<div class="matrix-container">
  <div class="matrix-column" style="left: 5%; animation-delay: 0s;">1011001010</div>
  <div class="matrix-column" style="left: 15%; animation-delay: 2s;">0100110011</div>
  <div class="matrix-column" style="left: 25%; animation-delay: 4s;">1100101101</div>
  <div class="matrix-column" style="left: 35%; animation-delay: 1s;">0011010110</div>
  <div class="matrix-column" style="left: 45%; animation-delay: 3s;">1010010101</div>
  <div class="matrix-column" style="left: 55%; animation-delay: 5s;">0110100110</div>
  <div class="matrix-column" style="left: 65%; animation-delay: 0.5s;">1101001011</div>
  <div class="matrix-column" style="left: 75%; animation-delay: 2.5s;">0010110101</div>
  <div class="matrix-column" style="left: 85%; animation-delay: 4.5s;">1011010010</div>
  <div class="matrix-column" style="left: 95%; animation-delay: 1.5s;">0101101001</div>
</div>

<!-- MAIN HEADER -->
<div class="glitch-text">
  > SHUBHAM DARJI_
</div>

<div class="terminal-line">
  root@shubham:~# ./deploy --profile=ai-data-engineer
</div>

<p style="color: #0f0; font-family: 'Courier New'; margin: 20px 0;">
  <span class="pulse-text">▶ SYSTEM: ONLINE</span> | 
  <span>▶ ENCRYPTION: AES-256</span> | 
  <span>▶ STATUS: ACTIVE</span> |
  <span>▶ IIT BOMBAY: CONNECTED</span>
</p>

<!-- ASCII ART -->
<pre style="color: #0f0; font-size: 0.7rem; line-height: 1.2;">
    ╔═══╗╔═══╗╔═══╗╔═══╗╔═══╗╔═══╗╔═══╗╔═══╗
    ║╔═╗║║╔═╗║║╔═╗║║╔═╗║║╔═╗║║╔═╗║║╔═╗║║╔═╗║
    ║╚═╝║║╚═╝║║╚═╝║║╚═╝║║╚═╝║║╚═╝║║╚═╝║║╚═╝║
    ╚═══╝╚═══╝╚═══╝╚═══╝╚═══╝╚═══╝╚═══╝╚═══╝
</pre>

</div>

<!-- PROFILE BADGES -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shubham7310&label=PROFILE_VIEWS&color=00ff00&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/shubham7310?label=FOLLOWERS&style=for-the-badge&color=00ff00" />
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=shubham7310&theme=matrix&no-frame=true&column=6&margin-w=15&margin-h=15" />
  </a>
</p>

<!-- MAIN PROFILE SECTION -->
<div class="neon-box" style="margin: 30px 0; padding: 30px;">

```bash
# whoami --verbose
