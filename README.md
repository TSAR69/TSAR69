<!--
██████╗ ███████╗ █████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██╔════╝██╔══██╗██╔══██╗████╗ ████║██╔════╝
██████╔╝█████╗  ███████║██║  ██║██╔████╔██║█████╗  
██╔══██╗██╔══╝  ██╔══██║██║  ██║██║╚██╔╝██║██╔══╝  
██║  ██║███████╗██║  ██║██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═════╝ ╚═╝     ╚═╝╚══════╝

// SYSTEM BOOT... INITIALIZING PROFILE...
// ACCESS GRANTED ✓
-->

<div align="center">

<!-- ═══════════════════════════════════════════════════════
     ██  HERO BANNER  ██
     ═══════════════════════════════════════════════════════ -->

<div style="
  background: #000;
  border: 4px solid #000;
  border-radius: 0px;
  padding: 0;
  margin: 0 auto 8px auto;
  max-width: 900px;
  position: relative;
  overflow: hidden;
  box-shadow: 8px 8px 0px #000;
  font-family: 'Courier New', monospace;
">

<!-- Scanlines overlay SVG -->
<svg width="100%" height="8" style="position:absolute;top:0;left:0;z-index:5;opacity:0.07;" preserveAspectRatio="none">
  <defs>
    <pattern id="scanlines" x="0" y="0" width="1" height="4" patternUnits="userSpaceOnUse">
      <rect width="1" height="1" fill="#fff"/>
    </pattern>
  </defs>
  <rect width="100%" height="100%" fill="url(#scanlines)"/>
</svg>

<!-- Halftone dot pattern background -->
<svg style="position:absolute;top:0;left:0;width:100%;height:100%;z-index:0;opacity:0.06;" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <pattern id="halftone" x="0" y="0" width="12" height="12" patternUnits="userSpaceOnUse">
      <circle cx="6" cy="6" r="2.2" fill="#fff"/>
    </pattern>
  </defs>
  <rect width="100%" height="100%" fill="url(#halftone)"/>
</svg>

<!-- WEB STRING  -->
<svg viewBox="0 0 900 320" style="position:absolute;top:0;right:0;width:100%;height:100%;z-index:2;pointer-events:none;" xmlns="http://www.w3.org/2000/svg">
  <!-- Web thread from top-right to Apiderman -->
  <line x1="850" y1="0" x2="820" y2="90" stroke="#bbb" stroke-width="1.2" stroke-dasharray="4,2" opacity="0.7"/>
  <line x1="850" y1="0" x2="810" y2="90" stroke="#bbb" stroke-width="0.7" stroke-dasharray="3,3" opacity="0.4"/>
</svg>

<!-- APIDERMAN Pixel Art (Full Color, Hanging Upside Down with swinging) -->
<div style="
  position: absolute;
  top: -8px;
  right: 32px;
  z-index: 10;
  transform-origin: top center;
  animation: apiderman-swing 3.2s ease-in-out infinite;
">
<svg width="60" height="130" viewBox="0 0 60 130" xmlns="http://www.w3.org/2000/svg" style="image-rendering:pixelated;">
  <!-- Web anchor point -->
  <circle cx="30" cy="0" r="3" fill="#888"/>
  <!-- Web string to body -->
  <line x1="30" y1="0" x2="30" y2="28" stroke="#ccc" stroke-width="1.5"/>
  <!-- Apiderman body (upside down) - head at bottom -->
  <!-- CAPE / BACK -->
  <rect x="18" y="28" width="24" height="30" fill="#CC2200" rx="2"/>
  <!-- Suit body -->
  <rect x="20" y="30" width="20" height="26" fill="#CC0000"/>
  <!-- Web pattern on suit -->
  <line x1="20" y1="36" x2="40" y2="36" stroke="#800000" stroke-width="0.8"/>
  <line x1="20" y1="42" x2="40" y2="42" stroke="#800000" stroke-width="0.8"/>
  <line x1="20" y1="48" x2="40" y2="48" stroke="#800000" stroke-width="0.8"/>
  <line x1="26" y1="30" x2="26" y2="56" stroke="#800000" stroke-width="0.8"/>
  <line x1="32" y1="30" x2="32" y2="56" stroke="#800000" stroke-width="0.8"/>
  <line x1="38" y1="30" x2="38" y2="56" stroke="#800000" stroke-width="0.8"/>
  <!-- Belt -->
  <rect x="20" y="52" width="20" height="4" fill="#000080"/>
  <rect x="28" y="52" width="4" height="4" fill="#FFD700"/>
  <!-- Arms (spread out / dangling) -->
  <rect x="6" y="32" width="14" height="6" fill="#CC0000" rx="1"/>
  <rect x="40" y="32" width="14" height="6" fill="#CC0000" rx="1"/>
  <!-- Gloves -->
  <rect x="2" y="31" width="8" height="8" fill="#000080" rx="2"/>
  <rect x="50" y="31" width="8" height="8" fill="#000080" rx="2"/>
  <!-- Legs (up, since upside down) -->
  <rect x="22" y="56" width="7" height="22" fill="#CC0000"/>
  <rect x="31" y="56" width="7" height="22" fill="#CC0000"/>
  <!-- Boots -->
  <rect x="21" y="74" width="9" height="8" fill="#000080" rx="1"/>
  <rect x="30" y="74" width="9" height="8" fill="#000080" rx="1"/>
  <!-- HEAD (at bottom since body is upside down) -->
  <rect x="16" y="86" width="28" height="26" fill="#CC0000" rx="4"/>
  <!-- Face mask eyes (big spider eyes) -->
  <ellipse cx="23" cy="96" rx="5" ry="4" fill="#fff"/>
  <ellipse cx="37" cy="96" rx="5" ry="4" fill="#fff"/>
  <ellipse cx="23" cy="96" rx="3" ry="3" fill="#000080"/>
  <ellipse cx="37" cy="96" rx="3" ry="3" fill="#000080"/>
  <!-- Web pattern on head -->
  <line x1="16" y1="95" x2="44" y2="95" stroke="#800000" stroke-width="0.7"/>
  <line x1="30" y1="86" x2="30" y2="112" stroke="#800000" stroke-width="0.7"/>
  <!-- Spider logo on chest -->
  <ellipse cx="30" cy="43" rx="4" ry="3" fill="#000"/>
  <line x1="28" y1="46" x2="24" y2="50" stroke="#000" stroke-width="1.5"/>
  <line x1="32" y1="46" x2="36" y2="50" stroke="#000" stroke-width="1.5"/>
  <line x1="30" y1="46" x2="30" y2="51" stroke="#000" stroke-width="1.5"/>
  <line x1="27" y1="44" x2="22" y2="45" stroke="#000" stroke-width="1.2"/>
  <line x1="33" y1="44" x2="38" y2="45" stroke="#000" stroke-width="1.2"/>
</svg>
</div>

<!-- HERO TEXT BLOCK -->
<div style="
  position: relative;
  z-index: 3;
  padding: 44px 32px 16px 32px;
  text-align: left;
">

<!-- Terminal label -->
<pre style="
  color: #555;
  font-size: 10px;
  margin: 0 0 4px 0;
  font-family: 'Courier New', monospace;
  letter-spacing: 2px;
  border: none;
  background: transparent;
">// SYSTEM_BOOT :: PROFILE_LOAD :: v2.0.26</pre>

<!-- TYPING ANIMATION heading -->
<div style="
  font-family: 'Courier New', Courier, monospace;
  font-size: clamp(22px, 4vw, 42px);
  font-weight: 900;
  color: #fff;
  letter-spacing: 3px;
  text-transform: uppercase;
  white-space: nowrap;
  overflow: hidden;
  border-right: 4px solid #fff;
  width: fit-content;
  animation: typing 3s steps(18, end) forwards, blink-cursor 0.75s step-end infinite;
  animation-delay: 0.5s;
  max-width: 0;
  padding-right: 6px;
">This is Aloobhujia</div>

<!-- Tagline -->
<div style="
  color: #888;
  font-family: 'Courier New', monospace;
  font-size: 12px;
  margin-top: 10px;
  letter-spacing: 2px;
">[ DEVELOPER · BUILDER · BREAKER OF THINGS ]</div>

<!-- Sound effect stamps row -->
<div style="
  display: flex;
  gap: 10px;
  margin-top: 14px;
  flex-wrap: wrap;
">
  <span style="
    background: #fff;
    color: #000;
    font-family: 'Courier New', monospace;
    font-size: 9px;
    font-weight: bold;
    padding: 3px 8px;
    letter-spacing: 1px;
    border: 2px solid #000;
    box-shadow: 2px 2px 0 #000;
  ">// BOOM</span>
  <span style="
    background: #000;
    color: #fff;
    font-family: 'Courier New', monospace;
    font-size: 9px;
    font-weight: bold;
    padding: 3px 8px;
    letter-spacing: 1px;
    border: 2px solid #fff;
  ">// ACCESS GRANTED</span>
  <span style="
    background: #fff;
    color: #000;
    font-family: 'Courier New', monospace;
    font-size: 9px;
    font-weight: bold;
    padding: 3px 8px;
    letter-spacing: 1px;
    border: 2px solid #000;
    box-shadow: 2px 2px 0 #000;
  ">// SYSTEM OVERRIDE</span>
</div>

</div>

<!-- ─── CHROME DINO-STYLE RUNNER GAME ─── -->
<div style="
  position: relative;
  width: 100%;
  height: 68px;
  background: #111;
  border-top: 3px solid #333;
  overflow: hidden;
  margin-top: 12px;
">

<!-- Ground line -->
<div style="
  position: absolute;
  bottom: 14px;
  left: 0;
  width: 100%;
  height: 2px;
  background: #444;
"></div>

<!-- Scrolling ground dots -->
<svg style="position:absolute;bottom:0;left:0;width:200%;height:14px;animation:ground-scroll 1.4s linear infinite;" xmlns="http://www.w3.org/2000/svg">
  <rect x="0"   y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="40"  y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="80"  y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="140" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="200" y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="240" y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="280" y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="340" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="400" y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="440" y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="480" y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="540" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="600" y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="640" y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="680" y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="740" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="800" y="4" width="20" height="3" fill="#333" rx="1"/>
  <!-- repeat for seamless loop -->
  <rect x="900"  y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="940"  y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="980"  y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="1040" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="1100" y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="1140" y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="1180" y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="1240" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="1300" y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="1340" y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="1380" y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="1440" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="1500" y="4" width="20" height="3" fill="#333" rx="1"/>
  <rect x="1540" y="5" width="10" height="2" fill="#333" rx="1"/>
  <rect x="1580" y="4" width="30" height="3" fill="#333" rx="1"/>
  <rect x="1640" y="5" width="15" height="2" fill="#333" rx="1"/>
  <rect x="1700" y="4" width="20" height="3" fill="#333" rx="1"/>
</svg>

<!-- PIXEL DINO RUNNER (pure SVG pixel-art, animated legs) -->
<div style="
  position: absolute;
  bottom: 16px;
  left: 60px;
  width: 40px;
  height: 40px;
">
<svg viewBox="0 0 20 20" width="40" height="40" style="image-rendering:pixelated;" xmlns="http://www.w3.org/2000/svg">
  <!-- Body -->
  <rect x="5" y="4" width="10" height="7" fill="#eee" rx="1"/>
  <!-- Head -->
  <rect x="10" y="1" width="7" height="6" fill="#eee" rx="1"/>
  <!-- Eye -->
  <rect x="15" y="2" width="1" height="1" fill="#000"/>
  <!-- Mouth -->
  <rect x="16" y="4" width="2" height="1" fill="#000"/>
  <!-- Tail -->
  <rect x="2" y="8" width="4" height="2" fill="#eee"/>
  <rect x="1" y="10" width="3" height="1" fill="#eee"/>
  <!-- Arm -->
  <rect x="12" y="8" width="3" height="2" fill="#eee"/>
  <!-- Legs (alternating via animation groups) -->
  <g style="animation: dino-legs-a 0.3s steps(1) infinite;">
    <rect x="7" y="11" width="2" height="5" fill="#eee"/>
    <rect x="11" y="11" width="2" height="3" fill="#eee"/>
  </g>
  <g style="animation: dino-legs-b 0.3s steps(1) infinite;">
    <rect x="7" y="11" width="2" height="3" fill="#eee"/>
    <rect x="11" y="11" width="2" height="5" fill="#eee"/>
  </g>
</svg>
</div>

<!-- Scrolling cactus obstacles -->
<svg style="position:absolute;bottom:16px;animation:cactus-scroll 3.5s linear infinite;" width="900" height="40" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 40" preserveAspectRatio="none">
  <!-- Cactus 1 at x=300 -->
  <rect x="300" y="12" width="6" height="28" fill="#eee"/>
  <rect x="294" y="18" width="6" height="10" fill="#eee"/>
  <rect x="300" y="15" width="6" height="10" fill="#eee" style="transform-origin:left;"/>
  <!-- Cactus 2 at x=650 -->
  <rect x="650" y="16" width="5" height="24" fill="#eee"/>
  <rect x="644" y="22" width="5" height="8"  fill="#eee"/>
  <rect x="655" y="20" width="5" height="8"  fill="#eee"/>
  <!-- Cloud pixel-art at top -->
  <rect x="80"  y="4" width="30" height="6" fill="#333" rx="3"/>
  <rect x="86"  y="1" width="18" height="6" fill="#333" rx="3"/>
  <rect x="500" y="6" width="25" height="5" fill="#333" rx="3"/>
  <rect x="505" y="2" width="15" height="6" fill="#333" rx="3"/>
</svg>

<!-- Score label -->
<div style="
  position: absolute;
  top: 6px;
  right: 16px;
  color: #444;
  font-family: 'Courier New', monospace;
  font-size: 10px;
  letter-spacing: 1px;
">HI 99999&nbsp;&nbsp;∞∞∞∞∞</div>

</div><!-- /dino runner -->

</div><!-- /hero banner -->

<!-- ═══════════════════════════════════ CSS ANIMATIONS ═══════════════════════════════════ -->
<style>
@keyframes typing {
  from { max-width: 0; }
  to   { max-width: 600px; }
}
@keyframes blink-cursor {
  from, to { border-color: transparent; }
  50%       { border-color: #fff; }
}
@keyframes apiderman-swing {
  0%,100% { transform: rotate(-8deg); }
  50%     { transform: rotate(8deg); }
}
@keyframes ground-scroll {
  from { transform: translateX(0); }
  to   { transform: translateX(-50%); }
}
@keyframes cactus-scroll {
  from { transform: translateX(110%); }
  to   { transform: translateX(-120%); }
}
@keyframes dino-legs-a {
  0%,49% { opacity:1; }
  50%,100%{ opacity:0; }
}
@keyframes dino-legs-b {
  0%,49% { opacity:0; }
  50%,100%{ opacity:1; }
}
@keyframes glitch {
  0%,100% { transform: translate(0); }
  20% { transform: translate(-2px, 1px); filter: hue-rotate(90deg); }
  40% { transform: translate(2px, -1px); }
  60% { transform: translate(-1px, 2px); }
  80% { transform: translate(1px, -2px); filter: hue-rotate(0deg); }
}
</style>

<!-- ═══════════════════════════════════════════════════════════════
     STATS BADGES ROW
═══════════════════════════════════════════════════════════════ -->

<br/>

![GitHub followers](https://img.shields.io/github/followers/Aloobhujia?style=flat-square&color=000000&labelColor=ffffff&logo=github)
![Profile Views](https://komarev.com/ghpvc/?username=Aloobhujia&style=flat-square&color=000000&label=VISITORS)
![GitHub stars](https://img.shields.io/github/stars/Aloobhujia?style=flat-square&color=000000&labelColor=ffffff)

</div>

---

<!-- ███████████████████████████████████████████████████████████
     SECTION 01 · ABOUT ME
     ███████████████████████████████████████████████████████████ -->

<div align="center">

<table><tr><td>

```
╔══════════════════════════════════════════════════════╗
║  PANEL 01  //  WHO IS THIS GUY?                      ║
╚══════════════════════════════════════════════════════╝
```

</td></tr></table>

</div>

<!--  SPEECH BUBBLE  -->
<div align="left" style="
  display: inline-block;
  background: #fff;
  border: 3px solid #000;
  border-radius: 0px;
  padding: 18px 24px;
  margin: 8px 0 24px 0;
  box-shadow: 6px 6px 0 #000;
  font-family: 'Courier New', monospace;
  max-width: 700px;
  position: relative;
">

```
  ┌─────────────────────────────────────────┐
  │  > whoami                               │
  │                                         │
  │  NAME     : Aloobhujia                  │
  │  ROLE     : Full-Stack Dev / Hacker     │
  │  STATUS   : Building things that break  │
  │             other things (on purpose)   │
  │  TIMEZONE : Asia/Kolkata (UTC+5:30)     │
  │  MOOD     : [ ████████░░ ] CAFFEINATED  │
  └─────────────────────────────────────────┘
```

> *"The quieter you become, the more you are able to hear the stack traces."*

</div>

---

<!-- ███████████████████████████████████████████████████████████
     SECTION 02 · TECH ARSENAL
     ███████████████████████████████████████████████████████████ -->

<div align="center">

<table><tr><td>

```
╔══════════════════════════════════════════════════════╗
║  PANEL 02  //  TECH ARSENAL  [ LOCKED & LOADED ]     ║
╚══════════════════════════════════════════════════════╝
```

</td></tr></table>

</div>

<div align="center" style="font-family:'Courier New',monospace;">

<!-- HALFTONE DIVIDER SVG -->
<svg width="700" height="16" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <pattern id="ht-div" x="0" y="0" width="10" height="10" patternUnits="userSpaceOnUse">
      <circle cx="5" cy="5" r="2.5" fill="#000"/>
    </pattern>
  </defs>
  <rect width="100%" height="100%" fill="url(#ht-div)"/>
</svg>

</div>

<br/>

| ⚡ WEAPONS | 🛡️ DEFENSES | 🔧 UTILITIES |
|:-----------:|:------------:|:------------:|
| ![Python](https://img.shields.io/badge/Python-000?style=flat-square&logo=python&logoColor=white) | ![Linux](https://img.shields.io/badge/Linux-000?style=flat-square&logo=linux&logoColor=white) | ![Git](https://img.shields.io/badge/Git-000?style=flat-square&logo=git&logoColor=white) |
| ![JavaScript](https://img.shields.io/badge/JavaScript-000?style=flat-square&logo=javascript&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-000?style=flat-square&logo=docker&logoColor=white) | ![VSCode](https://img.shields.io/badge/VSCode-000?style=flat-square&logo=visualstudiocode&logoColor=white) |
| ![TypeScript](https://img.shields.io/badge/TypeScript-000?style=flat-square&logo=typescript&logoColor=white) | ![Nginx](https://img.shields.io/badge/Nginx-000?style=flat-square&logo=nginx&logoColor=white) | ![Postman](https://img.shields.io/badge/Postman-000?style=flat-square&logo=postman&logoColor=white) |
| ![React](https://img.shields.io/badge/React-000?style=flat-square&logo=react&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000?style=flat-square&logo=postgresql&logoColor=white) | ![Figma](https://img.shields.io/badge/Figma-000?style=flat-square&logo=figma&logoColor=white) |
| ![Node.js](https://img.shields.io/badge/Node.js-000?style=flat-square&logo=nodedotjs&logoColor=white) | ![Redis](https://img.shields.io/badge/Redis-000?style=flat-square&logo=redis&logoColor=white) | ![Bash](https://img.shields.io/badge/Bash-000?style=flat-square&logo=gnubash&logoColor=white) |

<div align="center">

<svg width="700" height="16" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <pattern id="ht-div2" x="0" y="0" width="10" height="10" patternUnits="userSpaceOnUse">
      <circle cx="5" cy="5" r="2.5" fill="#000"/>
    </pattern>
  </defs>
  <rect width="100%" height="100%" fill="url(#ht-div2)"/>
</svg>

</div>

---

<!-- ███████████████████████████████████████████████████████████
     SECTION 03 · CURRENT MISSIONS
     ███████████████████████████████████████████████████████████ -->

<div align="center">

<table><tr><td>

```
╔══════════════════════════════════════════════════════╗
║  PANEL 03  //  CURRENT MISSIONS  [ IN PROGRESS ]     ║
╚══════════════════════════════════════════════════════╝
```

</td></tr></table>

</div>

```
  MISSION BRIEFING :: CLASSIFIED
  ════════════════════════════════════════════════════
  ▶  [ACTIVE]   Building an AI-powered CLI assistant
                 STATUS : ████████░░  80%

  ▶  [ACTIVE]   Exploring distributed systems & chaos engineering
                 STATUS : █████░░░░░  50%

  ▶  [ACTIVE]   Learning Rust (send help)
                 STATUS : ████░░░░░░  40%

  ▶  [QUEUE]    Open-source contribution sprint
                 STATUS : ██░░░░░░░░  20%
  ════════════════════════════════════════════════════
  // SYSTEM NOTE: All missions subject to caffeine supply
```

---

<!-- ███████████████████████████████████████████████████████████
     SECTION 04 · OPEN TO COLLABORATIONS
     ███████████████████████████████████████████████████████████ -->

<div align="center">

<table><tr><td>

```
╔══════════════════════════════════════════════════════╗
║  PANEL 04  //  OPEN TO COLLABORATIONS                ║
║                  [ PING ME. SERIOUSLY. ]             ║
╚══════════════════════════════════════════════════════╝
```

</td></tr></table>

<div style="
  background: #000;
  border: 3px solid #000;
  border-radius: 0;
  padding: 20px 32px;
  max-width: 600px;
  box-shadow: 6px 6px 0 #555;
  font-family: 'Courier New', monospace;
  color: #fff;
  text-align: left;
  margin: 12px auto;
">

```
  ██████████████████████████████████████████████
  █                                            █
  █   I AM AVAILABLE FOR:                      █
  █                                            █
  █   ► Open Source Projects                   █
  █   ► Hackathons & Code Sprints              █
  █   ► Interesting Side-Quests                █
  █   ► Breaking Things Together               █
  █   ► Building AI-Powered Tools              █
  █                                            █
  █   // TERMS: Must involve coffee or chaos   █
  █                                            █
  ██████████████████████████████████████████████
```

</div>

</div>

---

<!-- ███████████████████████████████████████████████████████████
     SECTION 05 · GITHUB STATS
     ███████████████████████████████████████████████████████████ -->

<div align="center">

<table><tr><td>

```
╔══════════════════════════════════════════════════════╗
║  PANEL 05  //  COMBAT STATS                          ║
╚══════════════════════════════════════════════════════╝
```

</td></tr></table>


```
  ╔══════════════════════════════════════════════════════════════╗
  ║  COMBAT STATS  ::  Aloobhujia                               ║
  ╠══════════════════════════════════════════════════════════════╣
  ║                                                              ║
  ║  COMMITS      ████████████████████░░░░  push or be pushed   ║
  ║  PULL REQs    █████████████░░░░░░░░░░░  merge or die        ║
  ║  ISSUES       ██████████░░░░░░░░░░░░░░  bugs are features   ║
  ║  CODE REVIEW  ███████████████░░░░░░░░░  approved with fear  ║
  ║                                                              ║
  ╠══════════════════════════════════════════════════════════════╣
  ║  TOP LANGS  :  Python · JavaScript · TypeScript · Bash      ║
  ║  STREAK     :  ∞ days (powered by existential dread)        ║
  ║  BEST TIME  :  2am :: environment: pitch dark + energy drink║
  ║                                                              ║
  ║  // git commit -m "it works don't touch it"                ║
  ╚══════════════════════════════════════════════════════════════╝
```

</div>

---

<!-- ███████████████████████████████████████████████████████████
     SECTION 06 · CONTACT
     ███████████████████████████████████████████████████████████ -->

<div align="center">

<table><tr><td>

```
╔══════════════════════════════════════════════════════╗
║  PANEL 06  //  SIGNAL CHANNELS  [ ESTABLISH LINK ]   ║
╚══════════════════════════════════════════════════════╝
```

</td></tr></table>


<!-- HALFTONE CONTACT CARD -->
<svg width="560" height="110" xmlns="http://www.w3.org/2000/svg" style="max-width:100%;">
  <defs>
    <pattern id="ht-card" x="0" y="0" width="8" height="8" patternUnits="userSpaceOnUse">
      <circle cx="4" cy="4" r="1.5" fill="#ddd"/>
    </pattern>
  </defs>
  <!-- Card BG with halftone -->
  <rect width="560" height="110" fill="url(#ht-card)" rx="0"/>
  <rect x="3" y="3" width="554" height="104" fill="none" stroke="#000" stroke-width="3"/>
  <!-- Inner label -->
  <text x="28" y="35" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#000" letter-spacing="3">// CONTACT PROTOCOLS</text>
  <line x1="28" y1="42" x2="532" y2="42" stroke="#000" stroke-width="1.5"/>
  <text x="28" y="64" font-family="'Courier New', monospace" font-size="11" fill="#000">▶  GitHub  :  github.com/Aloobhujia</text>
  <text x="28" y="84" font-family="'Courier New', monospace" font-size="11" fill="#000">▶  Email   :  [ check pinned repo for contact ]</text>
  <text x="28" y="102" font-family="'Courier New', monospace" font-size="10" fill="#444">▶  DMs open on GitHub Issues · No spam · Coffee first</text>
</svg>

<br/><br/>

[![GitHub](https://img.shields.io/badge/GITHUB-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Aloobhujia)

</div>

---

<!-- ███████████████████████████████████████████████████████████
     FOOTER ASCII ART
     ███████████████████████████████████████████████████████████ -->

<div align="center">

```
 ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
 ░                                                     ░
 ░   ▄▀▄ █   ▄▀▄ ▄▀▄ ██▄ █  █ ░░█ █  █  ░░█ ▄▀▄     ░
 ░   █▀█ █   █ █ █ █ █▄█ █▀▀█ ░░█ █▀▀█  ░░█ █▀█     ░
 ░   ▀ ▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀  ▀ ░░▀ ▀  ▀  ░░▀ ▀ ▀     ░
 ░                                                     ░
 ░           // SYSTEM SHUTDOWN :: GOODBYE             ░
 ░           // THANKS FOR READING THIS FAR            ░
 ░           // YOU'RE EITHER IMPRESSED OR LOST        ░
 ░           // BOTH ARE FINE.                         ░
 ░                                                     ░
 ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
```

<sub style="color:#666;font-family:'Courier New',monospace;letter-spacing:1px;">
Made with obsessive attention to detail · <b>Aloobhujia</b> · 2024<br/>
<code>// COMIC BOOK MODE: ACTIVE &nbsp;|&nbsp; CYBERPUNK ENGAGED &nbsp;|&nbsp; COFFEE: LOW</code>
</sub>

</div>
