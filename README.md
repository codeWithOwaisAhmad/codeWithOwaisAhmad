<!--
PASTE THIS INTO: README.md of your GitHub profile repo (github.com/YOUR_USERNAME/YOUR_USERNAME)
Replace:
- YOUR_NAME
- YOUR_TAGLINE
- YOUR_USERNAME
- YOUR_LINKEDIN, YOUR_TWITTER, YOUR_WEBSITE, YOUR_EMAIL
- PROJECT*_TITLE, PROJECT*_URL, PROJECT*_IMAGE_URL
-->

<!-- Header: Animated neon gradient + holographic name -->
<p align="center">
  <svg width="100%" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cyberpunk neon header">
    <defs>
      <!-- Animated background gradient -->
      <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#04020a"/>
        <stop offset="50%" stop-color="#0b0f2b"/>
        <stop offset="100%" stop-color="#04020a"/>
        <animate attributeName="x1" values="0%;-50%;0%" dur="14s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="100%;150%;100%" dur="14s" repeatCount="indefinite"/>
      </linearGradient>

      <!-- Floating neon gradient overlay -->
      <radialGradient id="halo-grad" cx="50%" cy="50%" r="70%">
        <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.55"/>
        <stop offset="45%" stop-color="#3B82F6" stop-opacity="0.35"/>
        <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
      </radialGradient>

      <!-- Subtle scanlines -->
      <pattern id="scanlines" width="4" height="4" patternUnits="userSpaceOnUse">
        <rect width="4" height="1" fill="#000000" opacity="0.25"/>
      </pattern>

      <!-- Holographic text gradient -->
      <linearGradient id="holo-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#8B5CF6"/>
        <stop offset="25%" stop-color="#06B6D4"/>
        <stop offset="50%" stop-color="#22D3EE"/>
        <stop offset="75%" stop-color="#A78BFA"/>
        <stop offset="100%" stop-color="#7C3AED"/>
        <animate attributeName="x1" values="0%;-50%;0%" dur="10s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="100%;150%;100%" dur="10s" repeatCount="indefinite"/>
      </linearGradient>

      <!-- Neon glow filter -->
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="3" result="blur1"/>
        <feGaussianBlur stdDeviation="6" in="blur1" result="blur2"/>
        <feMerge>
          <feMergeNode in="blur2"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <!-- Corner circuit motif -->
      <linearGradient id="circuit-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#06B6D4"/>
        <stop offset="100%" stop-color="#8B5CF6"/>
      </linearGradient>
    </defs>

    <!-- Background layers -->
    <rect x="0" y="0" width="1200" height="260" fill="url(#bg-grad)"/>
    <circle cx="900" cy="180" r="260" fill="url(#halo-grad)"/>
    <rect x="0" y="0" width="1200" height="260" fill="url(#scanlines)" opacity="0.2"/>

    <!-- Circuit corners -->
    <g stroke="url(#circuit-grad)" stroke-width="2" opacity="0.75">
      <polyline points="20,30 100,30 130,60 200,60" fill="none"/>
      <polyline points="1180,230 1100,230 1070,200 1000,200" fill="none"/>
      <circle cx="130" cy="60" r="3" fill="#22D3EE"/>
      <circle cx="1070" cy="200" r="3" fill="#A78BFA"/>
    </g>

    <!-- Name -->
    <text x="50%" y="53%" text-anchor="middle" font-size="64" font-weight="800"
          font-family="Segoe UI, Poppins, Montserrat, Arial, sans-serif"
          fill="url(#holo-grad)" filter="url(#glow)" letter-spacing="2">
      YOUR_NAME
    </text>

    <!-- Tagline -->
    <text x="50%" y="75%" text-anchor="middle" font-size="18" font-weight="500"
          font-family="Segoe UI, Poppins, Montserrat, Arial, sans-serif"
          fill="#c7d2fe" opacity="0.9">
      YOUR_TAGLINE • Building at the edge of code and neon
    </text>
  </svg>
</p>

<!-- Divider: animated neon line -->
<p align="center">
  <svg width="100%" height="22" viewBox="0 0 1200 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <linearGradient id="divider-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#06B6D4"/>
        <stop offset="50%" stop-color="#8B5CF6"/>
        <stop offset="100%" stop-color="#22D3EE"/>
      </linearGradient>
    </defs>
    <rect x="0" y="10" width="1200" height="2" fill="#0b1020"/>
    <rect x="0" y="10" width="1200" height="2" fill="url(#divider-grad)">
      <animate attributeName="x" values="-1200;0;-1200" dur="8s" repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

<!-- About Me -->
### 👾 About Me
- Cyberpunk-leaning engineer crafting resilient systems and luminous UIs.  
- I design data-driven interfaces, optimize performance, and automate anything that repeats.  
- Obsessive about DX, tooling, and pixel-perfect polish.

<!-- Divider -->
<p align="center">
  <svg width="100%" height="22" viewBox="0 0 1200 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <use href="#divider" />
    <defs>
      <linearGradient id="divider2" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#8B5CF6"/>
        <stop offset="50%" stop-color="#22D3EE"/>
        <stop offset="100%" stop-color="#06B6D4"/>
      </linearGradient>
    </defs>
    <rect x="0" y="10" width="1200" height="2" fill="#0b1020"/>
    <rect x="0" y="10" width="1200" height="2" fill="url(#divider2)">
      <animate attributeName="x" values="0;-1200;0" dur="9s" repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

<!-- Skills -->
### 🧪 Skills
<p align="center">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=0d1117" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=0d1117&labelColor=0d1117" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0d1117" alt="Python"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white&labelColor=0d1117" alt="Go"/>
  <br/>
  <!-- Frontend -->
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=06122b&labelColor=0d1117" alt="React"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white&labelColor=0d1117" alt="Vite"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white&labelColor=0d1117" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Tailwind-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=0b1020&labelColor=0d1117" alt="Tailwind CSS"/>
  <br/>
  <!-- Backend & Cloud -->
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white&labelColor=0d1117" alt="Node.js"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0d1117" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=0b1020&labelColor=0d1117" alt="Supabase"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0d1117" alt="Docker"/>
  <br/>
  <!-- Tools -->
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=0d1117" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=0d1117" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white&labelColor=0d1117" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white&labelColor=0d1117" alt="Prometheus"/>
</p>

<!-- Divider -->
<p align="center">
  <svg width="100%" height="22" viewBox="0 0 1200 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <rect x="0" y="10" width="1200" height="2" fill="#0b1020"/>
    <rect x="0" y="10" width="1200" height="2" fill="url(#divider-grad)">
      <animate attributeName="x" values="-600;0;-600" dur="7s" repeatCount="indefinite"/>
    </rect>
    <defs>
      <linearGradient id="divider-grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#22D3EE"/>
        <stop offset="50%" stop-color="#8B5CF6"/>
        <stop offset="100%" stop-color="#06B6D4"/>
      </linearGradient>
    </defs>
  </svg>
</p>

<!-- GitHub Stats -->
### 📊 GitHub Stats
<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=8B5CF6&text_color=c7d2fe&icon_color=22D3EE" alt="GitHub Stats"/>
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=8B5CF6&text_color=c7d2fe" alt="Top Languages"/>
    </td>
  </tr>
</table>

<!-- Divider -->
<p align="center">
  <svg width="100%" height="22" viewBox="0 0 1200 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <rect x="0" y="10" width="1200" height="2" fill="#0b1020"/>
    <rect x="0" y="10" width="1200" height="2" fill="url(#divider2)">
      <animate attributeName="x" values="0;-1200;0" dur="8s" repeatCount="indefinite"/>
    </rect>
    <defs>
      <linearGradient id="divider2" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#8B5CF6"/>
        <stop offset="50%" stop-color="#06B6D4"/>
        <stop offset="100%" stop-color="#22D3EE"/>
      </linearGradient>
    </defs>
  </svg>
</p>

<!-- Projects Showcase with cyber frames -->
### 🛠️ Featured Projects
<!-- Project 1 -->
<a href="PROJECT1_URL">
  <p align="center">
    <svg width="100%" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="PROJECT1_TITLE">
      <defs>
        <filter id="softGlow" x="-30%" y="-30%" width="160%" height="160%">
          <feGaussianBlur stdDeviation="6" result="b1"/>
          <feMerge>
            <feMergeNode in="b1"/><feMergeNode in="SourceGraphic"/>
          </feMerge>
        </filter>
        <linearGradient id="frameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#06B6D4"/>
          <stop offset="50%" stop-color="#8B5CF6"/>
          <stop offset="100%" stop-color="#22D3EE"/>
        </linearGradient>
      </defs>
      <!-- Image -->
      <image href="PROJECT1_IMAGE_URL" x="12" y="12" width="1176" height="236" preserveAspectRatio="xMidYMid slice"/>
      <!-- Frame -->
      <rect x="8" y="8" width="1184" height="244" fill="none" stroke="url(#frameGrad)" stroke-width="2" filter="url(#softGlow)"/>
      <!-- Corners -->
      <g stroke="url(#frameGrad)" stroke-width="4">
        <line x1="8" y1="8" x2="70" y2="8"/><line x1="8" y1="8" x2="8" y2="70"/>
        <line x1="1192" y1="8" x2="1130" y2="8"/><line x1="1192" y1="8" x2="1192" y2="70"/>
        <line x1="8" y1="252" x2="70" y2="252"/><line x1="8" y1="252" x2="8" y2="190"/>
        <line x1="1192" y1="252" x2="1130" y2="252"/><line x1="1192" y1="252" x2="1192" y2="190"/>
      </g>
    </svg>
  </p>
</a>

<!-- Project 2 -->
<a href="PROJECT2_URL">
  <p align="center">
    <svg width="100%" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="PROJECT2_TITLE">
      <defs>
        <filter id="softGlow2" x="-30%" y="-30%" width="160%" height="160%">
          <feGaussianBlur stdDeviation="6" result="b2"/>
          <feMerge><feMergeNode in="b2"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
        <linearGradient id="frameGrad2" x1="100%" y1="0%" x2="0%" y2="0%">
          <stop offset="0%" stop-color="#22D3EE"/>
          <stop offset="50%" stop-color="#8B5CF6"/>
          <stop offset="100%" stop-color="#06B6D4"/>
        </linearGradient>
      </defs>
      <image href="PROJECT2_IMAGE_URL" x="12" y="12" width="1176" height="236" preserveAspectRatio="xMidYMid slice"/>
      <rect x="8" y="8" width="1184" height="244" fill="none" stroke="url(#frameGrad2)" stroke-width="2" filter="url(#softGlow2)"/>
      <g stroke="url(#frameGrad2)" stroke-width="4">
        <line x1="8" y1="8" x2="70" y2="8"/><line x1="8" y1="8" x2="8" y2="70"/>
        <line x1="1192" y1="8" x2="1130" y2="8"/><line x1="1192" y1="8" x2="1192" y2="70"/>
        <line x1="8" y1="252" x2="70" y2="252"/><line x1="8" y1="252" x2="8" y2="190"/>
        <line x1="1192" y1="252" x2="1130" y2="252"/><line x1="1192" y1="252" x2="1192" y2="190"/>
      </g>
    </svg>
  </p>
</a>

<!-- Divider -->
<p align="center">
  <svg width="100%" height="22" viewBox="0 0 1200 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <rect x="0" y="10" width="1200" height="2" fill="#0b1020"/>
    <rect x="0" y="10" width="1200" height="2" fill="url(#divider3)">
      <animate attributeName="x" values="-1200;0;-1200" dur="7s" repeatCount="indefinite"/>
    </rect>
    <defs>
      <linearGradient id="divider3" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#7C3AED"/>
        <stop offset="50%" stop-color="#22D3EE"/>
        <stop offset="100%" stop-color="#8B5CF6"/>
      </linearGradient>
    </defs>
  </svg>
</p>

<!-- Contact -->
### 🔗 Connect
<p align="center">
  <!-- GitHub -->
  <a href="https://github.com/YOUR_USERNAME" title="GitHub">
    <svg width="38" height="38" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <filter id="iconGlow1"><feGaussianBlur stdDeviation="2"/></filter>
        <linearGradient id="ig1" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#06B6D4"/><stop offset="100%" stop-color="#8B5CF6"/>
        </linearGradient>
      </defs>
      <circle cx="12" cy="12" r="10" fill="url(#ig1)" opacity="0.15"/>
      <path d="M12 .5a12 12 0 0 0-3.79 23.39c.6.11.82-.26.82-.58
               0-.29-.01-1.06-.02-2.08-3.34.73-4.04-1.61-4.04-1.61
               -.55-1.39-1.35-1.76-1.35-1.76-1.1-.75.08-.74.08-.74
               1.22.09 1.86 1.25 1.86 1.25 1.08 1.85 2.83 1.31 3.52 1
               .11-.79.42-1.31.76-1.61-2.66-.3-5.47-1.33-5.47-5.93
               0-1.31.47-2.38 1.24-3.22-.12-.3-.54-1.52.12-3.18 0 0 1.01-.32 3.3 1.23A11.5 11.5 0 0 1 12 6.8
               c1.02 0 2.04.14 3 .41 2.29-1.55 3.3-1.23 3.3-1.23.66 1.66.24 2.88.12 3.18.77.84 1.24 1.91 1.24 3.22
               0 4.61-2.81 5.63-5.49 5.93.43.37.81 1.1.81 2.22
               0 1.6-.01 2.89-.01 3.29 0 .32.22.69.83.57A12 12 0 0 0 12 .5z"
            fill="url(#ig1)" filter="url(#iconGlow1)"/>
    </svg>
  </a>

  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN" title="LinkedIn">
    <svg width="38" height="38" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <filter id="iconGlow2"><feGaussianBlur stdDeviation="2"/></filter>
        <linearGradient id="ig2" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#3B82F6"/><stop offset="100%" stop-color="#8B5CF6"/>
        </linearGradient>
      </defs>
      <circle cx="12" cy="12" r="10" fill="url(#ig2)" opacity="0.15"/>
      <path d="M4.98 3.5C4.98 4.88 3.86 6 2.5 6S0 4.88 0 3.5 1.12 1 2.5 1s2.48 1.12 2.48 2.5zM.5 8h4V23h-4zM8.5 8h3.8v2.05h.05c.53-1 1.83-2.05 3.77-2.05 4.03 0 4.78 2.62 4.78 6.02V23h-4v-5.4c0-1.29-.02-2.96-1.8-2.96-1.8 0-2.08 1.4-2.08 2.86V23h-4z"
            fill="url(#ig2)" filter="url(#iconGlow2)"/>
    </svg>
  </a>

  <!-- X / Twitter -->
  <a href="https://twitter.com/YOUR_TWITTER" title="X (Twitter)">
    <svg width="38" height="38" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <filter id="iconGlow3"><feGaussianBlur stdDeviation="2"/></filter>
        <linearGradient id="ig3" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#22D3EE"/><stop offset="100%" stop-color="#7C3AED"/>
        </linearGradient>
      </defs>
      <circle cx="12" cy="12" r="10" fill="url(#ig3)" opacity="0.15"/>
      <path d="M18.9 2H21l-6.53 7.46L21.5 22h-5.08l-3.98-6.4L7.7 22H3.5l6.99-8-6.32-12H9l3.57 5.98L18.9 2zM8.63 6.2l8.37 13.57h1.03L9.67 7.23 8.63 6.2z"
            fill="url(#ig3)" filter="url(#iconGlow3)"/>
    </svg>
  </a>

  <!-- Website -->
  <a href="https://YOUR_WEBSITE" title="Website">
    <svg width="38" height="38" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <filter id="iconGlow4"><feGaussianBlur stdDeviation="2"/></filter>
        <linearGradient id="ig4" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#8B5CF6"/><stop offset="100%" stop-color="#22D3EE"/>
        </linearGradient>
      </defs>
      <circle cx="12" cy="12" r="10" fill="url(#ig4)" opacity="0.15"/>
      <path d="M12 2a10 10 0 1 0 .001 20.001A10 10 0 0 0 12 2zm0 2c1.93 0 3.69.76 5 2H7a7.98 7.98 0 0 1 5-2zm-8 8c0-.69.1-1.36.29-2h15.42c.19.64.29 1.31.29 2s-.1 1.36-.29 2H4.29A7.98 7.98 0 0 1 4 12zm3 6h10a7.98 7.98 0 0 1-10 0z"
            fill="url(#ig4)" filter="url(#iconGlow4)"/>
    </svg>
  </a>

  <!-- Email -->
  <a href="mailto:YOUR_EMAIL" title="Email">
    <svg width="38" height="38" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <filter id="iconGlow5"><feGaussianBlur stdDeviation="2"/></filter>
        <linearGradient id="ig5" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#06B6D4"/><stop offset="100%" stop-color="#7C3AED"/>
        </linearGradient>
      </defs>
      <circle cx="12" cy="12" r="10" fill="url(#ig5)" opacity="0.15"/>
      <path d="M2 6h20v12H2V6zm2 1.5v.3l8 5.2 8-5.2v-.3H4zm16 9V9.3l-8 5.2-8-5.2V16.5h16z"
            fill="url(#ig5)" filter="url(#iconGlow5)"/>
    </svg>
  </a>
</p>

<!-- Footer micro-line -->
<p align="center">
  <img src="https://img.shields.io/badge/𝙲𝚢𝚋𝚎𝚛𝚠𝚊𝚟𝚎-Active-8B5CF6?style=flat-square&labelColor=0d1117&logoColor=white" alt="Cyberwave Active badge"/>
</p>
