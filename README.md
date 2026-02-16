<!-- =======================
     SURBHI AURA DOJO README
     Lucario + Pikachu (GitHub-safe, subtle animation)
     ======================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=190&section=header&text=Aura%20Dojo&fontSize=52&fontColor=E2E8F0&animation=fadeIn&fontAlignY=35&desc=Calm%20Execution.%20Clean%20Systems.%20Merge-ready%20Work.&descAlignY=58&descSize=18" width="100%"/>

<!-- Roaming Pets Playground (GitHub-safe SVG animation, no JS) -->
<svg width="100%" height="170" viewBox="0 0 1200 170" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Lucario and Pikachu roaming">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#0F172A"/>
      <stop offset="0.5" stop-color="#111B34"/>
      <stop offset="1" stop-color="#0F172A"/>
    </linearGradient>

    <filter id="glow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <pattern id="grid" width="48" height="48" patternUnits="userSpaceOnUse">
      <path d="M 48 0 L 0 0 0 48" fill="none" stroke="#1E2A44" stroke-width="1" opacity="0.35"/>
    </pattern>

    <!-- Aura sparkle -->
    <radialGradient id="spark" cx="50%" cy="50%" r="50%">
      <stop offset="0" stop-color="#38BDF8" stop-opacity="1"/>
      <stop offset="1" stop-color="#38BDF8" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <rect width="1200" height="170" rx="22" fill="url(#bg)"/>
  <rect width="1200" height="170" rx="22" fill="url(#grid)" opacity="0.7"/>

  <!-- Aura pulses -->
  <g filter="url(#glow)" opacity="0.9">
    <circle cx="260" cy="85" r="18" fill="#38BDF8" opacity="0.18">
      <animate attributeName="r" values="16;28;16" dur="2.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.12;0.22;0.12" dur="2.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="940" cy="85" r="18" fill="#06B6D4" opacity="0.16">
      <animate attributeName="r" values="14;26;14" dur="2.9s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.10;0.20;0.10" dur="2.9s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Label -->
  <g fill="#E2E8F0" opacity="0.95">
    <text x="40" y="44" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace"
          font-size="22" font-weight="700">
      Aura Playground
    </text>
    <text x="40" y="72" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace"
          font-size="14" opacity="0.8">
      Lucario + Pikachu roaming (GitHub-safe • no JS)
    </text>
  </g>

  <!-- Lucario (smooth roam) -->
  <image href="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/448.png"
         width="56" height="56" x="80" y="98" opacity="1">
    <animate attributeName="x" values="80; 520; 180; 760; 120; 80" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="y" values="98; 108; 70; 112; 98; 98" dur="10s" repeatCount="indefinite"/>
  </image>

  <!-- Pikachu (slightly faster roam) -->
  <image href="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/25.png"
         width="56" height="56" x="220" y="104" opacity="1">
    <animate attributeName="x" values="220; 860; 420; 1020; 260; 220" dur="9s" repeatCount="indefinite"/>
    <animate attributeName="y" values="104; 84; 118; 92; 104; 104" dur="9s" repeatCount="indefinite"/>
  </image>

  <!-- Interaction spark (pulsing) -->
  <g filter="url(#glow)">
    <circle cx="600" cy="120" r="6" fill="url(#spark)" opacity="0.0">
      <animate attributeName="opacity" values="0;1;0" dur="1.4s" repeatCount="indefinite"/>
      <animate attributeName="r" values="4;12;4" dur="1.4s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

<br/>

<h1>Hi, I'm Surbhi Agarwal</h1>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=860&lines=Open+Source+Contributor+%7C+Frontend+%2B+Python;Systems+mindset.+Clean+architecture.+Calm+execution.;One+merge-ready+PR+at+a+time." alt="Typing SVG" />

</div>

---

## 🎯 What I do
I build **maintainable systems** and contribute to open source with a focus on:
- clear problem framing  
- reproducible bug reports  
- clean, review-friendly PRs  
- documentation that reduces future friction  

---

## 🔭 Current focus
- **Open source:** UI fixes, bug investigation, documentation, review-ready improvements  
- **AI Reality Remix:** a multi-scenario AI web system (text/image/video flows) built for scalability  
- **Execution:** stronger PR communication, better merge rate, consistent shipping  

---

## 🧭 Aura Philosophy (how I work)
- **Discipline over noise:** consistency beats bursts  
- **Precision over patches:** small, correct changes win  
- **Clarity over complexity:** readable code is scalable code  
- **Review-ready mindset:** context, screenshots, testing notes  

---

## 🛠 Core Stack (accurate)
**Frontend:** React · JavaScript · TypeScript · HTML · CSS  
**Backend:** Python · Flask  
**Database:** SQL  
**Tools:** Git · GitHub · Figma · VS Code  

<div align="center">

![React](https://img.shields.io/badge/React-0F172A?style=for-the-badge&logo=react&logoColor=38BDF8)
![TypeScript](https://img.shields.io/badge/TypeScript-0F172A?style=for-the-badge&logo=typescript&logoColor=38BDF8)
![JavaScript](https://img.shields.io/badge/JavaScript-0F172A?style=for-the-badge&logo=javascript&logoColor=38BDF8)
![HTML5](https://img.shields.io/badge/HTML5-0F172A?style=for-the-badge&logo=html5&logoColor=38BDF8)
![CSS3](https://img.shields.io/badge/CSS3-0F172A?style=for-the-badge&logo=css3&logoColor=38BDF8)
![Python](https://img.shields.io/badge/Python-0F172A?style=for-the-badge&logo=python&logoColor=38BDF8)
![Flask](https://img.shields.io/badge/Flask-0F172A?style=for-the-badge&logo=flask&logoColor=38BDF8)
![SQL](https://img.shields.io/badge/SQL-0F172A?style=for-the-badge&logo=mysql&logoColor=38BDF8)
![Git](https://img.shields.io/badge/Git-0F172A?style=for-the-badge&logo=git&logoColor=38BDF8)
![GitHub](https://img.shields.io/badge/GitHub-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8)
![Figma](https://img.shields.io/badge/Figma-0F172A?style=for-the-badge&logo=figma&logoColor=38BDF8)
![VS%20Code](https://img.shields.io/badge/VS_Code-0F172A?style=for-the-badge&logo=visual-studio-code&logoColor=38BDF8)

</div>

---

## 📌 What I’m building
### 🤖 AI Reality Remix
A **multi-scenario AI web system** designed to adapt UX + generation flows based on context.  
**Stack:** React + TypeScript + Python + Flask  
**Goal:** production-grade AI integration without bloated complexity.

---

## 📊 Stats (clean)
<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=SurbhiAgarwal1&show_icons=true&theme=tokyonight&title_color=38BDF8&text_color=E2E8F0&icon_color=2563EB&bg_color=0F172A&border_color=2563EB&hide_border=false&include_all_commits=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=SurbhiAgarwal1&theme=tokyonight&background=0F172A&ring=38BDF8&fire=38BDF8&currStreakLabel=E2E8F0&sideLabels=E2E8F0&currStreakNum=E2E8F0&sideNums=E2E8F0&dates=E2E8F0&border=2563EB&stroke=2563EB" />

</div>

---

## 🤝 Connect
<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Follow-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8)](https://github.com/SurbhiAgarwal1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0F172A?style=for-the-badge&logo=linkedin&logoColor=38BDF8)](https://linkedin.com/in/yourprofile)
[![Email](https://img.shields.io/badge/Email-Contact-0F172A?style=for-the-badge&logo=gmail&logoColor=38BDF8)](mailto:your.email@example.com)

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=135&section=footer&text=Calm%20Execution.%20Real%20Impact.&fontSize=26&fontColor=E2E8F0&animation=twinkling" width="100%"/>

</div>
