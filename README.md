<!-- ============ ANIMATED HEADER ============ -->
<a href="https://github.com/MarAb9">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0234E,50:DD0031,100:6e0a1e&height=220&section=header&text=Marouane%20Ab&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=Full-Stack%20Web%20Developer%20%E2%80%A2%20Angular%20%C2%B7%20NestJS%20%C2%B7%20Laravel&descAlignY=60&descSize=18&animation=fadeIn" width="100%" alt="header"/>
</a>

<!-- ============ TYPING ANIMATION ============ -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=DD0031&center=true&vCenter=true&width=620&lines=I+build+and+ship+production+web+apps;Angular+%2B+NestJS+%2B+PostgreSQL+%2B+AI;From+database+schema+to+deployed+UI;Open+to+remote+%26+freelance+work" alt="Typing SVG" />
  </a>
</div>

<!-- ============ BADGES ============ -->
<div align="center">
  <a href="https://www.linkedin.com/in/marouane-ab-610960174/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://qrib-lik-demo.vercel.app/"><img src="https://img.shields.io/badge/Live%20Demo-Qrib%20Lik-2ea44f?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20%26%20Freelance-DD0031?style=for-the-badge" alt="Open to work"/>
  <img src="https://komarev.com/ghpvc/?username=MarAb9&style=for-the-badge&color=E0234E&label=PROFILE+VIEWS" alt="Profile views"/>
</div>

<br/>

<!-- ============ ABOUT ============ -->
<img align="right" width="38%" src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Developer.gif" alt="coding"/>

### 👨‍💻 About Me

- 🚀 Full-stack developer who ships **production web apps end to end**
- 🧠 Flagship project **Qrib Lik** — an AI-powered local-services marketplace with multilingual (Darija) search
- 🛠️ Daily stack: **Angular · NestJS · Laravel · TypeScript · PostgreSQL/PostGIS · Docker**
- ✅ LinkedIn-verified assessments in **PHP, JavaScript, Java, Node.js, C, CSS, NoSQL, Linux**
- 🌍 Based in Morocco — building for the web, open to remote & freelance projects
- 💬 Ask me about full-stack architecture, AI integrations, or geospatial apps

<br clear="right"/>

---

### 🧰 Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

> 🔒 Most of my work is client-delivered or proprietary, so the source is private.
> Sensitive projects are shown as **architecture diagrams** and short case studies instead of screenshots.

---

## 🚀 Featured Projects

### 🟢 Qrib Lik — AI-Powered Local Services Marketplace

<p>
  <a href="https://qrib-lik-demo.vercel.app/"><img src="https://img.shields.io/badge/▶_Live_Demo-qrib--lik--demo.vercel.app-2ea44f?style=flat-square&logo=vercel&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/seeded_data-no_real_users-blue?style=flat-square"/>
</p>

> **Problem.** Finding a trusted local professional (painter, electrician, plumber) usually means asking around or scrolling unverified listings.
>
> **What I built.** A marketplace where users describe a task in plain language — English, French, or **Moroccan Darija** ("bghit nsbgh l7it" → painter) — and the platform extracts intent with **Google Gemini**, then ranks nearby providers using **PostGIS** geospatial search and an explainable scoring system.
>
> **Engineering highlights.**
> - AI search pipeline with a deterministic keyword fallback — search never breaks when the AI is down, rate-limited, or low-confidence.
> - Prompt-injection-hardened AI layer — AI output is advisory only; deterministic backend rules own every final decision.
> - Explainable scoring split into provider-quality (**Qrib Score**) and request-relevance (**Match Score**).

**Stack:** `Angular 21 (Signals + SSR / Cloudflare Workers)` · `NestJS` · `PostgreSQL/PostGIS` · `Prisma` · `Google Gemini` · `Docker` · `Fly.io + Vercel`

<img width="900" alt="Qrib Lik" src="https://github.com/user-attachments/assets/0e69f457-430c-4a57-ae45-cb0151aca105" />

---

### 🗂️ Meeting Management Platform  ·  *client-delivered*

> **Problem.** A council managed meetings, minutes, tasks, and documents across scattered files and email.
>
> **What I built.** A full-stack platform to schedule meetings, link minutes to sessions, track tasks, store documents, and manage contacts — with a calendar view, reports, notifications, and role-based permissions. Arabic RTL interface.

**Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Laravel` · `PostgreSQL` · `Docker` · `Nginx` · `Oracle Cloud + Neon + Vercel`

<img width="900" alt="Meeting Management Platform" src="https://github.com/user-attachments/assets/399c5574-a2bc-44dc-bd3f-06f68776867d" />

---

### 🏖️ Leave Management System  ·  *client-delivered*

> **Problem.** A paper- and spreadsheet-based leave process, with manual balance tracking and hand-filled forms.
>
> **What I built.** A role-based HR/employee portal that calculates leave balances automatically, manages holidays and carry-over, and generates official leave forms and reports as one-click **Excel / PDF / Word** exports.

**Stack:** `Laravel 12` · `PHP 8.2` · `Blade` · `Tailwind CSS` · `MariaDB` · `Docker`

<img width="900" alt="Leave Management System" src="https://github.com/user-attachments/assets/1631a19d-ac69-4ffa-bce9-d3f8b1321b21" />

---

### 📨 InOutfiles — Correspondence Archive  ·  *client-delivered*

> **Problem.** Incoming and outgoing official letters were tracked on paper, making anything hard to find or audit.
>
> **What I built.** A document management system to register correspondence with attachments, search across all records instantly, import from Excel, and keep a full audit log of every action. S3-compatible file storage. Arabic RTL.
>
> *Holds confidential records, so the architecture is shown instead of the UI.*

**Stack:** `Laravel 11` · `PostgreSQL` · `Redis` · `MinIO (S3)` · `Nginx` · `Docker`

```mermaid
flowchart LR
    User["👤 User<br/>Arabic RTL UI"] --> Nginx["Nginx<br/>reverse proxy"]
    Nginx --> App["Laravel 11 API"]
    App --> PG[("PostgreSQL<br/>records & metadata")]
    App --> Redis[("Redis<br/>cache & queues")]
    App --> MinIO["MinIO (S3)<br/>letter attachments"]
    App --> Audit["Audit Log<br/>every action tracked"]
    App --> XLS["Excel import<br/>/ CSV export"]
```

---

### 🕌 Mosques Management  ·  *client-delivered*

> **What I built.** A regional administration app for managing mosque records, fully containerized for easy deployment.
>
> *Holds sensitive administrative data, so the architecture is shown instead of the UI.*

**Stack:** `PHP` · `MariaDB` · `Docker`

```mermaid
flowchart LR
    User["👤 Admin"] --> Apache["PHP App<br/>Apache"]
    Apache --> DB[("MariaDB<br/>mosque records")]
    subgraph Docker["🐳 Docker Compose"]
        Apache
        DB
    end
```

---

## 📊 GitHub Analytics

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=MarAb9&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github"/>
  <img height="170em" src="https://streak-stats.demolab.com?user=MarAb9&theme=tokyonight&hide_border=true" alt="streak"/>
</div>

<!-- ============ ACTIVITY GRAPH ============ -->
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MarAb9&theme=tokyo-night&hide_border=true&area=true&color=DD0031&line=E0234E&point=ffffff" width="95%" alt="activity graph"/>
</div>

<!-- ============ SNAKE (requires action, see setup) ============ -->
<div align="center">
  <img src="https://raw.githubusercontent.com/MarAb9/MarAb9/output/snake.svg" alt="snake animation"/>
</div>

---

<!-- ============ FOOTER ============ -->
<div align="center">
  <h3>💼 Available for remote & freelance projects</h3>
  <p>Need a web app, API, or marketplace built and shipped? Let's talk.</p>
  <a href="https://www.linkedin.com/in/marouane-ab-610960174/"><img src="https://img.shields.io/badge/Reach%20out%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6e0a1e,50:DD0031,100:E0234E&height=120&section=footer" width="100%" alt="footer"/>

<!--
============================================================
SETUP — read once, takes ~5 minutes
============================================================
1. Create a new PUBLIC repo named exactly "MarAb9" (same as your username).
2. Add this file as README.md → it renders at the top of github.com/MarAb9.
3. Mermaid diagrams (InOutfiles, Mosques) render automatically. Nothing to upload.

SNAKE ANIMATION (the contribution-grid snake at the bottom)
- It needs a GitHub Action to generate snake.svg. Without it, that one image is broken.
- In the MarAb9 repo, create .github/workflows/snake.yml with the Platane/snk action:

    name: Generate Snake
    on:
      schedule: [{ cron: "0 0 * * *" }]
      workflow_dispatch:
    jobs:
      generate:
        runs-on: ubuntu-latest
        steps:
          - uses: Platane/snk@v3
            with:
              github_user_name: ${{ github.repository_owner }}
              outputs: dist/snake.svg
          - uses: crazy-max/ghaction-github-pages@v3
            with:
              target_branch: output
              build_dir: dist
            env:
              GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

- Run the workflow once (Actions tab → Generate Snake → Run workflow).
- If you don't want it, just delete the snake <img> block above.

OPTIONAL OUTCOMES (powerful)
- Add a real number to any case study, e.g.
  "Replaced a paper-based leave process used by ~120 staff."
============================================================
-->
