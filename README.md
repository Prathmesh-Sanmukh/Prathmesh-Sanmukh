<svg width="800" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#161b22"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff">
        <animate attributeName="stop-color" values="#58a6ff;#79c0ff;#a5d6ff;#58a6ff" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#a5d6ff">
        <animate attributeName="stop-color" values="#a5d6ff;#58a6ff;#79c0ff;#a5d6ff" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#79c0ff">
        <animate attributeName="stop-color" values="#79c0ff;#a5d6ff;#58a6ff;#79c0ff" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="800" height="120" rx="12" fill="url(#bg)"/>

  <!-- Animated border -->
  <rect width="798" height="118" x="1" y="1" rx="11" fill="none" stroke="#58a6ff" stroke-width="1" opacity="0.4">
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- Wave emoji -->
  <text x="40" y="72" font-size="38" text-anchor="middle">
    👋
    <animateTransform attributeName="transform" type="rotate" values="0 40 72;15 40 72;-10 40 72;15 40 72;0 40 72" dur="1.5s" repeatCount="indefinite"/>
  </text>

  <!-- "Hi mate," text -->
  <text x="85" y="58" font-family="'Courier New', monospace" font-size="22" fill="#8b949e" opacity="0">
    Hi mate,
    <animate attributeName="opacity" values="0;0;1;1" keyTimes="0;0.1;0.3;1" dur="3s" fill="freeze"/>
  </text>

  <!-- "I'm Prathmesh Sanmukh" text -->
  <text x="85" y="90" font-family="'Courier New', monospace" font-size="28" font-weight="bold" fill="url(#textGrad)" filter="url(#glow)" opacity="0">
    I'm Prathmesh Sanmukh
    <animate attributeName="opacity" values="0;0;0;1;1" keyTimes="0;0.2;0.4;0.6;1" dur="3s" fill="freeze"/>
  </text>

  <!-- Typing cursor -->
  <rect x="453" y="68" width="3" height="26" fill="#58a6ff" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite" begin="3s"/>
    <animate attributeName="opacity" values="0;0;0;0;1" keyTimes="0;0.2;0.4;0.6;1" dur="3s" fill="freeze"/>
  </rect>

  <!-- Decorative dots -->
  <circle cx="740" cy="30" r="3" fill="#58a6ff" opacity="0.5">
    <animate attributeName="cy" values="30;20;30" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="760" cy="50" r="2" fill="#79c0ff" opacity="0.4">
    <animate attributeName="cy" values="50;38;50" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.9;0.4" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="80" r="4" fill="#a5d6ff" opacity="0.3">
    <animate attributeName="cy" values="80;65;80" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3s" repeatCount="indefinite"/>
  </circle>
</svg>
      


# 💫 About Me:
## 👨‍💻 About Me<br><br>🔭 Currently working on **Data Analysis and Visualization Projects**<br><br>🌱 Learning **Python, SQL, Power BI, and Data Analytics**<br><br>📊 Interested in **Data Analysis, Business Insights, and Dashboards**<br><br>💬 Ask me about **SQL, Excel, Python, and Data Visualization**<br><br>🎯 Goal: **Become a Data Analyst and work on real-world data problems**<br><br>⚡ Fun fact: **I enjoy exploring datasets and finding hidden patterns**


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/_sanmukh.rao) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/prathmesh-sanmukh) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![CrateDB](https://img.shields.io/badge/CrateDB-009DC7?style=for-the-badge&logo=CrateDB&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Adobe Lightroom](https://img.shields.io/badge/Adobe%20Lightroom-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Proto.io](https://img.shields.io/badge/Proto.io-161637?style=for-the-badge&logo=proto.io&logoColor=00e5ff) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username= Prathmesh-Sanmukh&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user= Prathmesh-Sanmukh&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username= Prathmesh-Sanmukh&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username= Prathmesh-Sanmukh&theme=nightowl&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username= Prathmesh-Sanmukh&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id= Prathmesh-Sanmukh&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
