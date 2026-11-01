<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rupesh1541 — Naruto Edition GitHub README Preview</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body { background-color: #06070b; color: #e2e8f0; font-family: 'Inter', sans-serif; }
    .svg-card { width: 100%; height: auto; border-radius: 16px; box-shadow: 0 20px 50px rgba(0,0,0,0.6); }
    @keyframes pulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.35; transform: scale(0.85); } }
    .pulsing { animation: pulse 2s infinite ease-in-out; transform-box: fill-box; transform-origin: center; }
    @keyframes pendulum {
      0% { transform: rotate(-12deg); }
      25% { transform: rotate(9deg); }
      50% { transform: rotate(-5deg); }
      75% { transform: rotate(2.5deg); }
      100% { transform: rotate(0deg); }
    }
    .swing-badge { animation: pendulum 4.5s ease-out infinite alternate; transform-origin: 220px 0px; }
    @keyframes nudge { 0%, 100% { transform: translateX(0); } 50% { transform: translateX(6px); } }
    .arrow-nudge { animation: nudge 1.4s infinite ease-in-out; }
  </style>
</head>
<body class="min-h-screen py-10 px-4 md:px-10 max-w-6xl mx-auto space-y-10">

  <!-- Top GitHub Repo Bar Simulation -->
  <div class="flex items-center justify-between bg-[#0d0e16] border border-orange-500/30 rounded-xl px-5 py-3">
    <div class="flex items-center space-x-3">
      <span class="text-orange-500 text-xl">🍥</span>
      <span class="font-mono text-sm text-slate-300">Rupesh1541 / <strong class="text-white">README.md</strong> <span class="ml-2 px-2 py-0.5 text-xs bg-orange-500/20 text-orange-400 rounded-full border border-orange-500/40">Naruto Edition Live Preview</span></span>
    </div>
    <span class="text-xs text-slate-400 font-mono">All 5 Animated SVGs + Table</span>
  </div>

  <!-- 1. HERO.SVG -->
  <div class="space-y-2">
    <div class="text-xs font-mono text-orange-400 uppercase tracking-wider">1. hero.svg (Viewfinder + Animated Gradient + Pulsing Status)</div>
    <svg class="svg-card" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 630">
      <defs>
        <linearGradient id="grad-naruto" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#f97316" />
          <stop offset="50%" stop-color="#22d3ee" />
          <stop offset="100%" stop-color="#eab308" />
        </linearGradient>
        <linearGradient id="border-glow" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#f97316" stop-opacity="0.7" />
          <stop offset="50%" stop-color="#22d3ee" stop-opacity="0.3" />
          <stop offset="100%" stop-color="#f472b6" stop-opacity="0.6" />
        </linearGradient>
        <pattern id="dots" x="0" y="0" width="24" height="24" patternUnits="userSpaceOnUse">
          <circle cx="2" cy="2" r="1" fill="rgba(255,255,255,0.06)" />
        </pattern>
      </defs>
      <rect width="1200" height="630" fill="#0d0e16" rx="16" />
      <rect width="1200" height="630" fill="url(#dots)" rx="16" />
      <circle cx="200" cy="150" r="220" fill="#f97316" opacity="0.14" filter="blur(70px)" />
      <circle cx="980" cy="480" r="260" fill="#22d3ee" opacity="0.12" filter="blur(80px)" />
      <rect x="35" y="35" width="1130" height="560" fill="rgba(18, 20, 32, 0.82)" rx="16" stroke="url(#border-glow)" stroke-width="1.5" />

      <!-- Left Content -->
      <g transform="translate(80, 85)">
        <rect x="0" y="0" width="230" height="36" fill="rgba(249, 115, 22, 0.12)" stroke="#f97316" rx="18" />
        <circle cx="20" cy="18" r="5" fill="#f97316" class="pulsing" />
        <text x="36" y="23" font-family="Inter, sans-serif" font-weight="600" font-size="13" fill="#f97316">⚡ Open to Shinobi Collabs</text>

        <text x="0" y="85" font-family="Fira Code, monospace" font-size="18" fill="#94a3b8">Hi there, Dattebayo! I'm</text>
        <text x="0" y="145" font-family="Inter, sans-serif" font-weight="800" font-size="44" fill="url(#grad-naruto)">Rupesh Ganesh Badgujar</text>
        <text x="0" y="190" font-family="Fira Code, monospace" font-size="17" fill="#22d3ee">&gt; Coding Head • Student Innovator • Game Strategist</text>
        <text x="0" y="240" font-family="Inter, sans-serif" font-size="16" fill="#94a3b8">Forging high-speed applications, clean algorithms, and ninja-grade web tools.</text>

        <!-- Meta Row -->
        <g transform="translate(0, 300)">
          <rect x="0" y="0" width="165" height="40" fill="#141724" rx="8" stroke="rgba(255,255,255,0.08)" />
          <circle cx="20" cy="20" r="5" fill="#f97316" />
          <text x="35" y="25" font-family="Inter, sans-serif" font-size="14" fill="#e2e8f0">Hyderabad, IN</text>

          <rect x="180" y="0" width="175" height="40" fill="#141724" rx="8" stroke="rgba(255,255,255,0.08)" />
          <circle cx="200" cy="20" r="5" fill="#22d3ee" />
          <text x="215" y="25" font-family="Inter, sans-serif" font-size="14" fill="#e2e8f0">School Student</text>

          <rect x="370" y="0" width="185" height="40" fill="#141724" rx="8" stroke="rgba(255,255,255,0.08)" />
          <circle cx="390" cy="20" r="5" fill="#eab308" />
          <text x="405" y="25" font-family="Inter, sans-serif" font-size="14" fill="#e2e8f0">@Rupesh1541</text>
        </g>
      </g>

      <!-- Right Camera Viewfinder -->
      <g transform="translate(730, 80)">
        <rect x="0" y="0" width="390" height="460" fill="#090a0f" rx="14" stroke="rgba(255,255,255,0.12)" />
        <path d="M 18 38 L 18 18 L 38 18" fill="none" stroke="#f97316" stroke-width="2.5" />
        <path d="M 372 38 L 372 18 L 352 18" fill="none" stroke="#f97316" stroke-width="2.5" />
        <path d="M 18 422 L 18 442 L 38 442" fill="none" stroke="#f97316" stroke-width="2.5" />
        <path d="M 372 422 L 372 442 L 352 442" fill="none" stroke="#f97316" stroke-width="2.5" />

        <circle cx="38" cy="42" r="5" fill="#ef4444" class="pulsing" />
        <text x="52" y="46" font-family="Fira Code, monospace" font-size="12" fill="#ef4444">REC • 60FPS</text>
        <text x="245" y="46" font-family="Fira Code, monospace" font-size="12" fill="#94a3b8">rupesh_wave.mp4</text>

        <rect x="30" y="65" width="330" height="330" fill="#121521" rx="10" />
        <!-- Animated Chakra Aura + Waving Character Illustration -->
        <circle cx="195" cy="230" r="95" fill="url(#grad-naruto)" opacity="0.18">
          <animate attributeName="r" values="85;105;85" dur="3s" repeatCount="indefinite" />
        </circle>
        <!-- Stylised Shinobi Headband & Waving Avatar -->
        <circle cx="195" cy="210" r="52" fill="#1e293b" stroke="#f97316" stroke-width="3" />
        <rect x="150" y="175" width="90" height="18" rx="4" fill="#334155" stroke="#94a3b8" stroke-width="1" />
        <circle cx="195" cy="184" r="5" fill="#f97316" />
        <!-- Waving Hand Animation -->
        <g transform="translate(255, 195)">
          <animateTransform attributeName="transform" type="rotate" values="255 195 -15; 255 195 20; 255 195 -15" dur="1.2s" repeatCount="indefinite" />
          <text x="0" y="0" font-size="34">👋</text>
        </g>
        <text x="195" y="315" font-family="Fira Code, monospace" font-weight="600" font-size="14" fill="#f97316" text-anchor="middle">🍃 KONOHA CODING HEAD</text>
        <text x="195" y="340" font-family="Inter, sans-serif" font-size="12" fill="#94a3b8" text-anchor="middle">SMIL Frame Loop • 4.0s Cycle</text>

        <!-- Scrubber Bar -->
        <rect x="30" y="415" width="330" height="5" fill="rgba(255,255,255,0.1)" rx="2.5" />
        <rect x="30" y="415" width="100" height="5" fill="#f97316" rx="2.5">
          <animate attributeName="width" values="0;330;330;0" keyTimes="0;0.65;0.9;1" dur="4s" repeatCount="indefinite" />
        </rect>
      </g>
    </svg>
  </div>

  <!-- 2. ABOUT-LIFE.SVG -->
  <div class="space-y-2">
    <div class="text-xs font-mono text-cyan-400 uppercase tracking-wider">2. about-life.svg (Browser Window + Hobbies Carousel & Daily Rings)</div>
    <svg class="svg-card" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 480">
      <rect width="1200" height="480" fill="#0d0e16" rx="16" />
      <!-- Left Card -->
      <g transform="translate(35, 30)">
        <rect width="545" height="420" fill="rgba(18, 20, 32, 0.85)" rx="16" stroke="rgba(249,115,22,0.35)" stroke-width="1.5" />
        <path d="M 0 16 C 0 7 7 0 16 0 L 529 0 C 538 0 545 7 545 16 L 545 46 L 0 46 Z" fill="#141724" />
        <circle cx="24" cy="23" r="5.5" fill="#f97316" />
        <circle cx="42" cy="23" r="5.5" fill="#eab308" />
        <circle cx="60" cy="23" r="5.5" fill="#22d3ee" />
        <rect x="85" y="12" width="430" height="22" fill="#090a0f" rx="5" />
        <text x="98" y="27" font-family="Fira Code, monospace" font-size="12" fill="#22d3ee">https://github.com/Rupesh1541/shinobi-skills</text>
        <rect x="425" y="16" width="2" height="14" fill="#f97316">
          <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite" />
        </rect>

        <g transform="translate(30, 75)">
          <text x="0" y="15" font-family="Inter, sans-serif" font-weight="700" font-size="21" fill="#ffffff">Core Coding Capabilities</text>
          <g transform="translate(0, 45)">
            <rect width="485" height="78" fill="#141724" rx="10" stroke="rgba(249,115,22,0.2)" />
            <text x="25" y="46" font-size="26">⚡</text>
            <text x="70" y="34" font-family="Inter, sans-serif" font-weight="600" font-size="16" fill="#ffffff">Coding &amp; Algorithmic Problem Solving</text>
            <text x="70" y="56" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Writing fast, structured code &amp; leading school tech initiatives</text>
          </g>
          <g transform="translate(0, 140)">
            <rect width="485" height="78" fill="#141724" rx="10" stroke="rgba(34,211,238,0.2)" />
            <text x="25" y="46" font-size="26">🌐</text>
            <text x="70" y="34" font-family="Inter, sans-serif" font-weight="600" font-size="16" fill="#ffffff">Modern Frontend &amp; Tooling</text>
            <text x="70" y="56" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Building interactive interfaces with React, Vite, and Git workflows</text>
          </g>
          <g transform="translate(0, 235)">
            <rect width="485" height="78" fill="#141724" rx="10" stroke="rgba(244,114,182,0.2)" />
            <text x="25" y="46" font-size="26">🎯</text>
            <text x="70" y="34" font-family="Inter, sans-serif" font-weight="600" font-size="16" fill="#ffffff">Coding Head Leadership</text>
            <text x="70" y="56" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Mentoring fellow students, organizing hackathons &amp; code reviews</text>
          </g>
        </g>
      </g>

      <!-- Right Card -->
      <g transform="translate(620, 30)">
        <rect width="545" height="420" fill="rgba(18, 20, 32, 0.85)" rx="16" stroke="rgba(34,211,238,0.35)" stroke-width="1.5" />
        <g transform="translate(30, 35)">
          <text x="0" y="20" font-family="Inter, sans-serif" font-weight="700" font-size="21" fill="#ffffff">Hobbies &amp; Daily Chakra Rings</text>
          <text x="0" y="42" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Coding projects &amp; competitive video gaming in Hyderabad</text>

          <g transform="translate(0, 65)">
            <rect width="485" height="195" fill="#141724" rx="12" />
            <rect x="20" y="15" width="215" height="4" fill="rgba(255,255,255,0.15)" rx="2" />
            <rect x="20" y="15" width="215" height="4" fill="#f97316" rx="2">
              <animate attributeName="width" values="0;215;215" dur="4s" repeatCount="indefinite" />
            </rect>
            <rect x="250" y="15" width="215" height="4" fill="rgba(255,255,255,0.15)" rx="2" />
            <rect x="250" y="15" width="0" height="4" fill="#22d3ee" rx="2">
              <animate attributeName="width" values="0;0;215" keyTimes="0;0.5;1" dur="4s" repeatCount="indefinite" />
            </rect>

            <text x="242" y="95" font-size="36" text-anchor="middle">🎮 ⚡ 💻</text>
            <text x="242" y="135" font-family="Inter, sans-serif" font-weight="700" font-size="18" fill="#ffffff" text-anchor="middle">Coding &amp; Playing Video Games</text>
            <text x="242" y="162" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8" text-anchor="middle">Tactical gaming reflexes + late-night software building</text>
          </g>

          <!-- 3 Daily Rings -->
          <g transform="translate(35, 290)">
            <circle cx="45" cy="35" r="28" fill="none" stroke="#1e293b" stroke-width="6" />
            <circle cx="45" cy="35" r="28" fill="none" stroke="#f97316" stroke-width="6" stroke-dasharray="175" stroke-dashoffset="25" stroke-linecap="round" />
            <text x="45" y="39" font-family="Fira Code, monospace" font-size="11" fill="#fff" text-anchor="middle">92%</text>
            <text x="45" y="80" font-family="Inter, sans-serif" font-size="12" fill="#94a3b8" text-anchor="middle">Coding</text>

            <circle cx="205" cy="35" r="28" fill="none" stroke="#1e293b" stroke-width="6" />
            <circle cx="205" cy="35" r="28" fill="none" stroke="#22d3ee" stroke-width="6" stroke-dasharray="175" stroke-dashoffset="40" stroke-linecap="round" />
            <text x="205" y="39" font-family="Fira Code, monospace" font-size="11" fill="#fff" text-anchor="middle">85%</text>
            <text x="205" y="80" font-family="Inter, sans-serif" font-size="12" fill="#94a3b8" text-anchor="middle">Gaming</text>

            <circle cx="365" cy="35" r="28" fill="none" stroke="#1e293b" stroke-width="6" />
            <circle cx="365" cy="35" r="28" fill="none" stroke="#f472b6" stroke-width="6" stroke-dasharray="175" stroke-dashoffset="18" stroke-linecap="round" />
            <text x="365" y="39" font-family="Fira Code, monospace" font-size="11" fill="#fff" text-anchor="middle">95%</text>
            <text x="365" y="80" font-family="Inter, sans-serif" font-size="12" fill="#94a3b8" text-anchor="middle">Learning</text>
          </g>
        </g>
      </g>
    </svg>
  </div>

  <!-- 3. STACK.SVG -->
  <div class="space-y-2">
    <div class="text-xs font-mono text-purple-400 uppercase tracking-wider">3. stack.svg (React Orbiting Core with Vite &amp; Git Moons + Glowing Chip Grid)</div>
    <svg class="svg-card" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 460">
      <rect width="1200" height="460" fill="#0d0e16" rx="16" />
      <rect x="35" y="30" width="1130" height="400" fill="rgba(18, 20, 32, 0.85)" rx="16" stroke="rgba(167,139,250,0.4)" stroke-width="1.5" />

      <text x="75" y="80" font-family="Inter, sans-serif" font-weight="700" font-size="22" fill="#ffffff">Ninjutsu Tech Arsenal — Vite &amp; Git Orbiting React</text>
      <text x="75" y="105" font-family="Inter, sans-serif" font-size="14" fill="#94a3b8">Three tilted elliptical orbits with React carrying Vite &amp; Git moons in safe clearance</text>

      <!-- Left: Glowing Core & Orbits -->
      <g transform="translate(270, 265)">
        <ellipse cx="0" cy="0" rx="170" ry="65" fill="none" stroke="rgba(249,115,22,0.25)" stroke-width="1.5" transform="rotate(-15)" />
        <ellipse cx="0" cy="0" rx="150" ry="55" fill="none" stroke="rgba(34,211,238,0.25)" stroke-width="1.5" transform="rotate(28)" />
        <ellipse cx="0" cy="0" rx="115" ry="42" fill="none" stroke="rgba(167,139,250,0.25)" stroke-width="1.5" transform="rotate(-48)" />

        <!-- Glowing Core -->
        <circle cx="0" cy="0" r="34" fill="#f97316" opacity="0.25" />
        <circle cx="0" cy="0" r="22" fill="#141724" stroke="#f97316" stroke-width="2" />
        <text x="0" y="5" font-family="Fira Code, monospace" font-weight="700" font-size="11" fill="#f97316" text-anchor="middle">CORE</text>

        <!-- React Planet with Orbiting Vite & Git Moons -->
        <g>
          <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="14s" repeatCount="indefinite" />
          <g transform="translate(135, 0)">
            <circle cx="0" cy="0" r="18" fill="#090a0f" stroke="#22d3ee" stroke-width="2" />
            <text x="0" y="5" font-family="Inter, sans-serif" font-size="14" fill="#22d3ee" text-anchor="middle">⚛</text>
            <!-- Orbiting Vite & Git Moons -->
            <g>
              <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="3.2s" repeatCount="indefinite" />
              <circle cx="0" cy="0" r="34" fill="none" stroke="rgba(255,255,255,0.12)" stroke-dasharray="3 3" />
              <circle cx="34" cy="0" r="10" fill="#eab308" />
              <text x="34" y="3.5" font-family="Fira Code, monospace" font-weight="700" font-size="7.5" fill="#090a0f" text-anchor="middle">VITE</text>
              <circle cx="-34" cy="0" r="10" fill="#f97316" />
              <text x="-34" y="3.5" font-family="Fira Code, monospace" font-weight="700" font-size="7.5" fill="#090a0f" text-anchor="middle">GIT</text>
            </g>
          </g>
        </g>
      </g>

      <!-- Right: Grouped Chip Grid -->
      <g transform="translate(550, 125)">
        <text x="0" y="0" font-family="Inter, sans-serif" font-weight="600" font-size="14" fill="#f97316">Frontend &amp; Core Languages</text>
        <g transform="translate(0, 15)">
          <rect x="0" y="0" width="130" height="38" fill="#141724" rx="8" stroke="#f97316" stroke-width="1.2" />
          <text x="65" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">React.js</text>
          <rect x="145" y="0" width="130" height="38" fill="#141724" rx="8" stroke="#22d3ee" stroke-width="1.2" />
          <text x="210" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">JavaScript</text>
          <rect x="290" y="0" width="130" height="38" fill="#141724" rx="8" stroke="#a78bfa" stroke-width="1.2" />
          <text x="355" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">HTML / CSS</text>
          <rect x="435" y="0" width="130" height="38" fill="#141724" rx="8" stroke="#f472b6" stroke-width="1.2" />
          <text x="500" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">Tailwind</text>
        </g>

        <text x="0" y="95" font-family="Inter, sans-serif" font-weight="600" font-size="14" fill="#22d3ee">Build Tools &amp; Version Control (Orbiting Moons)</text>
        <g transform="translate(0, 110)">
          <rect x="0" y="0" width="130" height="38" fill="#141724" rx="8" stroke="#eab308" stroke-width="1.5" />
          <text x="65" y="24" font-family="Fira Code, monospace" font-size="13" fill="#eab308" text-anchor="middle">⚡ Vite</text>
          <rect x="145" y="0" width="130" height="38" fill="#141724" rx="8" stroke="#f97316" stroke-width="1.5" />
          <text x="210" y="24" font-family="Fira Code, monospace" font-size="13" fill="#f97316" text-anchor="middle">🌿 Git</text>
          <rect x="290" y="0" width="130" height="38" fill="#141724" rx="8" stroke="rgba(255,255,255,0.15)" />
          <text x="355" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">GitHub</text>
          <rect x="435" y="0" width="130" height="38" fill="#141724" rx="8" stroke="rgba(255,255,255,0.15)" />
          <text x="500" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">VS Code</text>
        </g>

        <text x="0" y="190" font-family="Inter, sans-serif" font-weight="600" font-size="14" fill="#f472b6">Logic, Data &amp; Gaming Mindset</text>
        <g transform="translate(0, 205)">
          <rect x="0" y="0" width="150" height="38" fill="#141724" rx="8" stroke="rgba(244,114,182,0.4)" />
          <text x="75" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">Algorithms</text>
          <rect x="165" y="0" width="160" height="38" fill="#141724" rx="8" stroke="rgba(244,114,182,0.4)" />
          <text x="245" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">Problem Solving</text>
          <rect x="340" y="0" width="160" height="38" fill="#141724" rx="8" stroke="rgba(244,114,182,0.4)" />
          <text x="420" y="24" font-family="Fira Code, monospace" font-size="13" fill="#fff" text-anchor="middle">Game Strategy</text>
        </g>
      </g>
    </svg>
  </div>

  <!-- 4. ID-DASHBOARD.SVG -->
  <div class="space-y-2">
    <div class="text-xs font-mono text-yellow-400 uppercase tracking-wider">4. id-dashboard.svg (Swinging Lanyard Shinobi Badge + Repo Bar Chart)</div>
    <svg class="svg-card" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 500">
      <rect width="1200" height="500" fill="#0d0e16" rx="16" />

      <!-- Swinging Lanyard ID Card -->
      <g class="swing-badge" transform="translate(40, 30)">
        <line x1="180" y1="-30" x2="180" y2="15" stroke="#f97316" stroke-width="14" />
        <rect x="162" y="8" width="36" height="16" fill="#eab308" rx="4" />
        <rect x="10" y="20" width="340" height="420" fill="rgba(18, 20, 32, 0.9)" rx="16" stroke="#f97316" stroke-width="1.5" />
        <text x="180" y="55" font-family="Inter, sans-serif" font-weight="800" font-size="15" fill="#f97316" text-anchor="middle">🍃 KONOHA SHINOBI PASS</text>
        <text x="180" y="75" font-family="Fira Code, monospace" font-size="11" fill="#94a3b8" text-anchor="middle">ID: RUPESH-1541-HYD</text>

        <rect x="105" y="95" width="150" height="150" fill="#141724" rx="12" stroke="#22d3ee" stroke-width="1.5" />
        <circle cx="180" cy="155" r="38" fill="#f97316" opacity="0.2" />
        <text x="180" y="165" font-size="38" text-anchor="middle">🥷</text>
        <text x="180" y="225" font-family="Fira Code, monospace" font-size="11" fill="#22d3ee" text-anchor="middle">RANK: CODING HEAD</text>

        <text x="35" y="280" font-family="Inter, sans-serif" font-weight="700" font-size="15" fill="#fff">Rupesh Ganesh Badgujar</text>
        <text x="35" y="305" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Role: Coding Head &amp; Student</text>
        <text x="35" y="330" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Location: Hyderabad, India</text>

        <!-- Gold Chip + Barcode -->
        <rect x="35" y="360" width="52" height="38" fill="#eab308" rx="6" />
        <rect x="105" y="360" width="215" height="38" fill="#090a0f" rx="6" />
        <path d="M120 368v22M132 368v22M140 368v22M155 368v22M168 368v22M185 368v22M200 368v22M215 368v22M232 368v22M248 368v22M265 368v22M285 368v22M300 368v22" stroke="#fff" stroke-width="2" />
      </g>

      <!-- Right Dashboard -->
      <g transform="translate(420, 50)">
        <rect width="740" height="420" fill="rgba(18, 20, 32, 0.85)" rx="16" stroke="rgba(34,211,238,0.35)" stroke-width="1.5" />
        <text x="35" y="42" font-family="Inter, sans-serif" font-weight="700" font-size="20" fill="#fff">Shinobi Mission Telemetry &amp; Top Repositories</text>

        <g transform="translate(35, 65)">
          <rect width="205" height="88" fill="#141724" rx="10" />
          <text x="20" y="42" font-family="Inter, sans-serif" font-weight="800" font-size="30" fill="#f97316">15+</text>
          <text x="20" y="68" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Active Repositories</text>

          <rect x="230" y="0" width="205" height="88" fill="#141724" rx="10" />
          <text x="250" y="42" font-family="Inter, sans-serif" font-weight="800" font-size="30" fill="#22d3ee">100+</text>
          <text x="250" y="68" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Total GitHub Stars</text>

          <rect x="460" y="0" width="210" height="88" fill="#141724" rx="10" />
          <text x="480" y="42" font-family="Inter, sans-serif" font-weight="800" font-size="24" fill="#eab308">NOW: CODING</text>
          <text x="480" y="68" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8">Status: Building &amp; Gaming</text>
        </g>

        <!-- Single-Hue Bar Chart -->
        <g transform="translate(35, 180)">
          <rect width="670" height="205" fill="#141724" rx="12" />
          <text x="25" y="32" font-family="Inter, sans-serif" font-weight="600" font-size="14" fill="#fff">Most-Starred Repositories</text>

          <text x="25" y="75" font-family="Fira Code, monospace" font-size="13" fill="#e2e8f0">ninja-portfolio</text>
          <rect x="195" y="60" width="380" height="18" fill="#090a0f" rx="4" />
          <rect x="195" y="60" width="340" height="18" fill="#f97316" rx="4" />
          <text x="590" y="74" font-family="Fira Code, monospace" font-size="13" fill="#f97316">45 ★</text>

          <text x="25" y="120" font-family="Fira Code, monospace" font-size="13" fill="#e2e8f0">algorithm-jutsu</text>
          <rect x="195" y="105" width="380" height="18" fill="#090a0f" rx="4" />
          <rect x="195" y="105" width="260" height="18" fill="#fb923c" rx="4" />
          <text x="590" y="119" font-family="Fira Code, monospace" font-size="13" fill="#fb923c">32 ★</text>

          <text x="25" y="165" font-family="Fira Code, monospace" font-size="13" fill="#e2e8f0">student-dashboard</text>
          <rect x="195" y="150" width="380" height="18" fill="#090a0f" rx="4" />
          <rect x="195" y="150" width="195" height="18" fill="#fdba74" rx="4" />
          <text x="590" y="164" font-family="Fira Code, monospace" font-size="13" fill="#fdba74">24 ★</text>
        </g>
      </g>
    </svg>
  </div>

  <!-- 5. CONNECT.SVG -->
  <div class="space-y-2">
    <div class="text-xs font-mono text-pink-400 uppercase tracking-wider">5. connect.svg (Pointing Character + Nudging Link Cards)</div>
    <svg class="svg-card" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320">
      <rect width="1200" height="320" fill="#0d0e16" rx="16" />
      <rect x="35" y="25" width="1130" height="270" fill="rgba(18, 20, 32, 0.85)" rx="16" stroke="rgba(244,114,182,0.4)" stroke-width="1.5" />

      <g transform="translate(70, 55)">
        <rect width="330" height="210" fill="#141724" rx="12" stroke="rgba(249,115,22,0.3)" />
        <text x="165" y="85" font-size="44" text-anchor="middle">🥷👉</text>
        <text x="165" y="135" font-family="Inter, sans-serif" font-weight="700" font-size="18" fill="#f97316" text-anchor="middle">Summon Rupesh!</text>
        <text x="165" y="162" font-family="Inter, sans-serif" font-size="13" fill="#94a3b8" text-anchor="middle">Click a scroll on the right to connect</text>
      </g>

      <g transform="translate(435, 55)">
        <rect x="0" y="0" width="690" height="60" fill="#141724" rx="10" stroke="rgba(249,115,22,0.3)" />
        <text x="30" y="36" font-family="Inter, sans-serif" font-weight="600" font-size="16" fill="#fff">🐙 GitHub Profile — github.com/Rupesh1541</text>
        <text x="640" y="36" font-family="Inter, sans-serif" font-size="20" fill="#f97316" class="arrow-nudge">→</text>

        <rect x="0" y="75" width="690" height="60" fill="#141724" rx="10" stroke="rgba(34,211,238,0.3)" />
        <text x="30" y="111" font-family="Inter, sans-serif" font-weight="600" font-size="16" fill="#fff">✉️ Direct Email — rupesh15415811h@gmail.com</text>
        <text x="640" y="111" font-family="Inter, sans-serif" font-size="20" fill="#22d3ee" class="arrow-nudge">→</text>

        <rect x="0" y="150" width="690" height="60" fill="#141724" rx="10" stroke="rgba(234,179,8,0.3)" />
        <text x="30" y="186" font-family="Inter, sans-serif" font-weight="600" font-size="16" fill="#fff">🎮 Location &amp; Guild — Hyderabad • Coding Head &amp; Gamer</text>
        <text x="640" y="186" font-family="Inter, sans-serif" font-size="20" fill="#eab308" class="arrow-nudge">⚡</text>
      </g>
    </svg>
  </div>

</body>
</html>
