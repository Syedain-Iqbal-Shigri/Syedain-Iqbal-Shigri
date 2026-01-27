<!--
  Next-level, animated, brand-first GitHub Profile README
  - Paste this entire file into your profile README.md
  - Replace any placeholders (links, usernames) as needed
-->

<p align="center">
  <!-- Typing header -->
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=36&duration=2800&pause=800&color=00FF88&center=true&vCenter=true&width=960&height=80&lines=Hi+👋,+I'm+Syedain+Iqbal+Shigri;Founder+—+Skardu+Adventures+%7C+MERN+%7C+AI+%26+NLP" alt="Typing SVG"/>
</p>

<!-- ===== Hero: inline SVG (animated sunrise + mountains) ===== -->
<div align="center">
  <!-- Inline SVG: animated sunrise over layered mountains -->
  <svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" role="img" aria-label="Skardu Adventures hero">
    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0%" stop-color="#011627"/>
        <stop offset="50%" stop-color="#0f1724"/>
        <stop offset="100%" stop-color="#031021"/>
      </linearGradient>

      <linearGradient id="sunGrad" x1="0" x2="1">
        <stop offset="0%" stop-color="#ffb347"/>
        <stop offset="100%" stop-color="#ffcc33"/>
      </linearGradient>

      <linearGradient id="sky" x1="0" x2="1">
        <stop offset="0%" stop-color="#021124"/>
        <stop offset="100%" stop-color="#05213a"/>
      </linearGradient>

      <filter id="soft" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="8" result="b"/>
        <feBlend in="SourceGraphic" in2="b"/>
      </filter>
    </defs>

    <!-- dark sky -->
    <rect width="1200" height="220" fill="url(#sky)"></rect>

    <!-- animated stars (subtle) -->
    <g id="stars" fill="#ffffff" opacity="0.8">
      <!-- multiple small circles; animate opacity to twinkle -->
      <circle cx="110" cy="30" r="1.6">
        <animate attributeName="opacity" values="0.2;1;0.2" dur="4s" repeatCount="indefinite" begin="0s"/>
      </circle>
      <circle cx="240" cy="70" r="1.2">
        <animate attributeName="opacity" values="0.1;0.9;0.1" dur="5s" repeatCount="indefinite" begin="0.5s"/>
      </circle>
      <circle cx="380" cy="25" r="1.8">
        <animate attributeName="opacity" values="0.2;1;0.2" dur="4.5s" repeatCount="indefinite" begin="1s"/>
      </circle>
      <circle cx="600" cy="40" r="1.4">
        <animate attributeName="opacity" values="0.1;0.95;0.1" dur="6s" repeatCount="indefinite" begin="0.7s"/>
      </circle>
      <circle cx="920" cy="20" r="1.3">
        <animate attributeName="opacity" values="0.15;1;0.15" dur="4.8s" repeatCount="indefinite" begin="1.2s"/>
      </circle>
    </g>

    <!-- rising sun (animated translate and scale) -->
    <g transform="translate(600,130)">
      <circle r="38" fill="url(#sunGrad)" filter="url(#soft)">
        <animate attributeName="cy" from="80" to="-10" dur="3.5s" begin="0.3s" fill="freeze" />
        <animate attributeName="r" from="8" to="38" dur="3.5s" begin="0.3s" fill="freeze"/>
      </circle>
    </g>

    <!-- mountain layers with parallax float (animated translateY) -->
    <g transform="translate(0,20)">
      <path d="M0 150 L120 110 L240 150 L360 100 L480 140 L600 110 L720 150 L840 105 L960 140 L1080 120 L1200 150 L1200 220 L0 220 Z" fill="#0b3b35" opacity="0.95">
        <animateTransform attributeName="transform" attributeType="XML" type="translate" from="0 0" to="0 -6" dur="6s" repeatCount="indefinite" />
      </path>
      <path d="M0 170 L120 130 L240 170 L360 120 L480 160 L600 130 L720 170 L840 125 L960 160 L1080 140 L1200 170 L1200 220 L0 220 Z" fill="#0e5667" opacity="0.85">
        <animateTransform attributeName="transform" attributeType="XML" type="translate" from="0 0" to="0 -10" dur="8s" repeatCount="indefinite" />
      </path>
      <path d="M0 190 L120 150 L240 190 L360 140 L480 180 L600 150 L720 190 L840 145 L960 180 L1080 160 L1200 190 L1200 220 L0 220 Z" fill="#13304b" opacity="0.95">
        <animateTransform attributeName="transform" attributeType="XML" type="translate" from="0 0" to="0 -3" dur="5s" repeatCount="indefinite" />
      </path>
    </g>

    <!-- foreground ridge -->
    <path d="M0 200 L120 170 L240 200 L360 165 L480 200 L600 170 L720 200 L840 180 L960 200 L1200 180 L1200 220 L0 220 Z" fill="#081921"></path>

    <!-- title on hero -->
    <g transform="translate(40,50)" font-family="Segoe UI, Roboto, Helvetica, Arial" fill="#E6F6FF">
      <text x="0" y="20" font-size="22" font-weight="700">Skardu Adventures</text>
      <text x="0" y="46" font-size="14" fill="#B8E7FF">Tourism · Bookings · Local guides · Custom itineraries</text>
    </g>

  </svg>
</div>

<!-- ===== Brand & Intro ===== -->
<h1 align="center">Brand — Skardu Adventures</h1>
<p align="center">High-conversion tourism platform for Skardu: tours, lodgings, local guides, secure payments, and instant booking updates.</p>

<!-- ===== Badges & Quick Links (animated shields & pro icons) ===== -->
<p align="center">
  <a href="https://github.com/Syedain-Iqbal-Shigri">
    <img alt="GitHub" src="https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="mailto:sishigree@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
  <a href="#">
    <img alt="Skardu Adventures" src="https://img.shields.io/badge/Skardu-Adventures-0082FF?style=for-the-badge&logo=tripadvisor&logoColor=white">
  </a>
  <img alt="Made with ❤" src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-ff69b4?style=for-the-badge">
</p>

---

<!-- ===== Pro Tech Row (icons loaded from jsDelivr for reliability) ===== -->
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40" alt="React"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="40" height="40" alt="Next.js"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="40" height="40" alt="Express"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="40" height="40" alt="MongoDB"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" width="40" height="40" alt="TailwindCSS"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" height="40" alt="Docker"/> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40" alt="Git"/>
</p>

---

<!-- ===== Animated Skill Rings (SVG) ===== -->
<h2 align="center">Skills — Visual & Animated</h2>
<p align="center">
  <!-- Container table for rings -->
  <table align="center"><tr>
    <td align="center">
      <!-- React ring -->
      <svg width="140" height="140" viewBox="0 0 36 36">
        <defs>
          <linearGradient id="r1" x1="0" x2="1"><stop offset="0%" stop-color="#00D1FF"/><stop offset="100%" stop-color="#61dafb"/></linearGradient>
        </defs>
        <path d="M18 2.0845a15.9155 15.9155 0 1 0 0 31.831A15.9155 15.9155 0 1 0 18 2.0845" fill="#081921"/>
        <circle cx="18" cy="18" r="10" fill="transparent" stroke="url(#r1)" stroke-width="2" stroke-dasharray="62 62" stroke-dashoffset="62">
          <animate attributeName="stroke-dashoffset" from="62" to="6" dur="1.6s" begin="0.3s" fill="freeze"/>
        </circle>
        <text x="18" y="22" font-size="3" text-anchor="middle" fill="#61dafb" font-weight="700">React</text>
      </svg>
      <div style="font-size:12px;margin-top:8px;text-align:center">UI & SPA</div>
    </td>

    <td align="center" style="padding-left:18px">
      <!-- Node ring -->
      <svg width="140" height="140" viewBox="0 0 36 36">
        <defs>
          <linearGradient id="r2" x1="0" x2="1"><stop offset="0%" stop-color="#8CE563"/><stop offset="100%" stop-color="#3C873A"/></linearGradient>
        </defs>
        <path d="M18 2.0845a15.9155 15.9155 0 1 0 0 31.831A15.9155 15.9155 0 1 0 18 2.0845" fill="#081921"/>
        <circle cx="18" cy="18" r="10" fill="transparent" stroke="url(#r2)" stroke-width="2" stroke-dasharray="62 62" stroke-dashoffset="62">
          <animate attributeName="stroke-dashoffset" from="62" to="18" dur="1.6s" begin="0.6s" fill="freeze"/>
        </circle>
        <text x="18" y="22" font-size="3" text-anchor="middle" fill="#A6F77B" font-weight="700">Node</text>
      </svg>
      <div style="font-size:12px;margin-top:8px;text-align:center">APIs & Servers</div>
    </td>

    <td align="center" style="padding-left:18px">
      <!-- Mongo ring -->
      <svg width="140" height="140" viewBox="0 0 36 36">
        <defs>
          <linearGradient id="r3" x1="0" x2="1"><stop offset="0%" stop-color="#4DE0B7"/><stop offset="100%" stop-color="#12B886"/></linearGradient>
        </defs>
        <path d="M18 2.0845a15.9155 15.9155 0 1 0 0 31.831A15.9155 15.9155 0 1 0 18 2.0845" fill="#081921"/>
        <circle cx="18" cy="18" r="10" fill="transparent" stroke="url(#r3)" stroke-width="2" stroke-dasharray="62 62" stroke-dashoffset="62">
          <animate attributeName="stroke-dashoffset" from="62" to="26" dur="1.6s" begin="0.9s" fill="freeze"/>
        </circle>
        <text x="18" y="22" font-size="3" text-anchor="middle" fill="#12B886" font-weight="700">Mongo</text>
      </svg>
      <div style="font-size:12px;margin-top:8px;text-align:center">Data & Schema</div>
    </td>
  </tr></table>
</p>

---

<!-- ===== Highlighted Project Card (clean & interactive look) ===== -->
<h2 align="center">Featured — Skardu Adventures</h2>
<p align="center">
  <img src="https://img.shields.io/badge/Status-Prototype-yellow?style=for-the-badge&logo=appveyor" alt="Status"/>
</p>

<p align="center">
  <strong>Skardu Adventures</strong> • A modern tourism platform for Skardu with mobile-first booking flows, secure payments, and local-guide integration.<br/>
  <em>Stack</em>: React / Next.js (SSG) · Tailwind · Node.js · Express · MongoDB · Stripe · WebSockets
</p>

<p align="center">
  <!-- buttons -->
  <a href="#"><img src="https://img.shields.io/badge/Live-Open%20Demo-00B894?style=for-the-badge&logo=vercel" alt="Live Demo"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Repo-GitHub-181717?style=for-the-badge&logo=github" alt="Repo"/></a>
</p>

---

<!-- ===== GitHub Stats (pro widgets) ===== -->
<h2 align="center">GitHub Pulse</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Syedain-Iqbal-Shigri&show_icons=true&theme=dark" alt="GitHub Stats" />
  &nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Syedain-Iqbal-Shigri&theme=dark" alt="Streak Stats" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Syedain-Iqbal-Shigri&theme=dark" alt="Trophies" />
</p>

---

<!-- ===== Footer / CTA ===== -->
<p align="center">
  <strong>Want a custom SVG hero, brand colors, or a live demo card with screenshots?</strong><br/>
  I can generate: a unique SVG banner (logo + mountains), a deployment-ready demo button, or branded project cards — tell me which and I'll add it directly.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Syedain-Iqbal-Shigri&color=brightgreen" alt="Profile views" />
</p>
