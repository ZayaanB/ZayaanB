<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Zayaan%20Bhanwadia&fontSize=42&fontColor=E0D4FF&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Full%20Stack%20%2B%20AI/ML&descAlignY=55&descSize=18)

<a href="https://github.com/ZayaanB">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=560&lines=Full-Stack+Engineer+%7C+Systems+%2B+AI%2FML;University+of+Toronto+%E2%80%94+CS+%2B+Stats" alt="Typing SVG" />
</a>

<br/>

![University of Toronto](https://img.shields.io/badge/University%20of%20Toronto-Honours%20B.Sc.%20CS%20(Co--op)-6D28D9?style=flat-square&logo=google-scholar&logoColor=white)
![Location](https://img.shields.io/badge/Toronto,%20ON-4C1D95?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://zayaanb.github.io/Zayaan/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zayaan-bhan)
[![Email](https://img.shields.io/badge/Email-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zayaan1509@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-2E1065?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ZayaanB)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ZayaanB&color=6D28D9&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/ZayaanB?color=6D28D9&style=flat-square&label=Followers)
![Stars](https://img.shields.io/github/stars/ZayaanB?color=6D28D9&style=flat-square&label=Stars)

</div>

---

### 🧠 About Me

I'm a Computer Science student at the **University of Toronto** (Honours B.Sc., Co-op) building across the stack. From low-level systems in C++ to production Node/FastAPI applications and applied AI/ML tooling. I care about **reliability, performance, and clean developer experience**, whether that means shaving lock contention out of an embedded key-value store or cutting API failure rates in a production service by 85%+.

Hands-on experience in **secure credential management, OAuth architecture, and real-time computer vision systems**.

**🎯 Open To:** Software Engineering Internships · Software Engineer · Software Developer · Full-Stack & Backend Engineering · AI/ML Engineering

---

### 🛠️ Tech Stack

**Languages**

![Python](https://skillicons.dev/icons?i=py) ![Java](https://skillicons.dev/icons?i=java) ![JavaScript](https://skillicons.dev/icons?i=js) ![TypeScript](https://skillicons.dev/icons?i=ts) ![C++](https://skillicons.dev/icons?i=cpp) ![C](https://skillicons.dev/icons?i=c) ![Bash](https://skillicons.dev/icons?i=bash) ![HTML/CSS](https://skillicons.dev/icons?i=html,css)

**Frontend**

![React](https://skillicons.dev/icons?i=react) ![Next.js](https://skillicons.dev/icons?i=nextjs)

**Backend & Databases**

![FastAPI](https://skillicons.dev/icons?i=fastapi) ![Node.js](https://skillicons.dev/icons?i=nodejs) ![Flask](https://skillicons.dev/icons?i=flask) ![PostgreSQL](https://skillicons.dev/icons?i=postgres) ![Supabase](https://skillicons.dev/icons?i=supabase)

**Cloud, DevOps & Tooling**

![Docker](https://skillicons.dev/icons?i=docker) ![Linux](https://skillicons.dev/icons?i=linux) ![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![GCP](https://skillicons.dev/icons?i=gcp) ![Vercel](https://skillicons.dev/icons?i=vercel) ![VS Code](https://skillicons.dev/icons?i=vscode)

---

### 🤖 AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| Computer Vision | Applied | Real-time fall detection system with 98%+ accuracy using OpenCV |
| Applied ML Systems | Applied | Built clinical AI assistant automating intake/check-in workflows |
| AI Integration & Tooling | Applied | VS Code extension automating AI chat context-sharing (Copilot integration) |
| Data Engineering for AI | Working Knowledge | Structured patient/session data schemas for downstream model use |

---

### 🚀 Featured Projects

<details>
<summary><b>🗃️ Embedded Key-Value Store</b> — C++ / POSIX Threads / Linux</summary>
<br/>

An embedded C++ database engineered for high-throughput concurrent access via sharding and lock-free reads.

| | |
|---|---|
| **Stack** | C++, POSIX Threads, Linux |
| **Scale** | 4-thread concurrent read/write workloads |
| **Performance** | 45%+ disk usage reduction via compaction |
| **Reliability** | Write-ahead log persistence for crash recovery |
| **Repository** | [github.com/ZayaanB](https://github.com/ZayaanB) |

- Built data sharding to eliminate global lock bottlenecks and improve throughput
- Implemented shared locks enabling non-blocking reads across 4 threads while preventing write race conditions
- Designed WAL-based persistence, writing updates to a log file before memory for crash durability
- Created a background file compaction routine to reclaim disk space without pausing the application

</details>

<details>
<summary><b>🔗 Context Sync Extension</b> — TypeScript / VS Code Extension API</summary>
<br/>

A VS Code extension automating AI chat context continuity across developer environments — 500+ downloads.

| | |
|---|---|
| **Stack** | TypeScript, VS Code Extension API |
| **Scale** | 500+ downloads |
| **Integrations** | GitHub Copilot, OneDrive, Google Drive |
| **Impact** | One-click environment setup, denser AI context per token |
| **Repository** | [github.com/ZayaanB](https://github.com/ZayaanB) |

- Automates AI chat context sharing to maintain workspace continuity across environments
- Designed a graph-based Markdown schema to maximize context density per token in AI assistant sessions
- Integrated GitHub Copilot, OneDrive, and Google Drive for automated syncing

</details>

<details>
<summary><b>🏥 Clinical AI Assistant</b> — Python / SQL / OpenCV — Top 10 @ GenAI Genesis</summary>
<br/>

An AI-powered clinical assistant automating patient intake with real-time computer-vision monitoring.

| | |
|---|---|
| **Stack** | Python, SQL, OpenCV |
| **Scale** | Full intake-to-monitoring pipeline |
| **Performance** | 98%+ real-time fall detection accuracy |
| **Recognition** | Top 10 Projects @ GenAI Genesis |
| **Repository** | [github.com/ZayaanB](https://github.com/ZayaanB) |

- Deployed an AI-powered clinical assistant automating patient check-ins/intake with structured data schemas
- Engineered a live monitoring dashboard using computer vision for real-time fall detection
- Built a spatial visualization algorithm generating 3D labelled hospital models by extruding floor plans

</details>

---

### 💼 Experience

**Software Engineer Intern (Incoming)** · FreshBooks
`Sept 2026 – Dec 2026` · Toronto, ON

- Incoming intern developing backend microservices in Python and UI components in React for 10M+ users
- Set to deploy applications using Docker and Azure DevOps with RESTful APIs and MySQL/Postgres databases
- Will collaborate in an agile team to automate testing, optimize data via Redis, and ship production features

`Python` `React` `Docker` `Azure DevOps` `MySQL/Postgres` `Redis`

<br/>

**Software Engineer Intern** · KorraNet Creative
`May 2026 – Present` · Winnipeg, MB (Remote)

- Restructured secret ingestion and eliminated hardcoded credentials across 3 core services, migrating to secure environment management
- Optimized Meta OAuth token handling and storage architecture, reducing token refresh failures by 40%+
- Reduced system crashes and failed API calls by 85%+ through robust error handling and timeout prevention
- Implemented logging across onboarding and authentication flows to isolate bugs for new developer teams

`Python` `OAuth` `Secrets Management` `Logging & Observability` `API Reliability`

<br/>

**Co-President & Lead Engineer** · NASA Hunch
`Sept 2023 – June 2025` · Toronto, ON

- Secured a 3rd-place international finish as executive of the first Canadian team to compete in NASA Hunch
- Built an autonomous Lunar Bot using Arduino and CAD, achieving 95%+ obstacle avoidance in simulated terrain
- Programmed a real-time C++ control algorithm with non-blocking execution loops for synchronized image capture

`C++` `Arduino` `CAD` `Real-Time Systems`

---

### 🏆 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🥉 3rd Place, International | NASA Hunch — first Canadian team to compete |
| 🏅 Top 10 Projects | GenAI Genesis — Clinical AI Assistant |
| 🏆 Finalist | Hack Canada |
| 🥉 3rd Place Overall | UTRA Hacks |
| 📦 500+ Downloads | Context Sync Extension (VS Code Marketplace) |

</div>

---

### 📈 Contribution Activity

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ZayaanB&theme=tokyo-night&hide_border=true&bg_color=0D0221&color=A78BFA&line=8B5CF6&point=C4B5FD)

</div>

### 🐍 Contribution Snake

<div align="center">

![Snake animation](https://raw.githubusercontent.com/ZayaanB/ZayaanB/output/github-contribution-grid-snake.svg)

</div>

---

### 🎯 Current Focus

```yaml
Learning:
  - Distributed systems & database internals
  - Applied ML infrastructure & context-engineering for AI tooling

Building:
  - Backend microservices ahead of FreshBooks internship
  - Extensions to the Context Sync VS Code tool

Exploring:
  - Real-time computer vision applications
  - Secure-by-default backend architecture patterns

Open To:
  - Software Engineering Internships / New Grad roles
  - AI/ML Engineering opportunities
```

---

### 📬 Connect

[![Gmail](https://img.shields.io/badge/Gmail-6D28D9?style=flat-square&logo=gmail&logoColor=white)](mailto:zayaan1509@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4C1D95?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/zayaan-bhan)
[![GitHub](https://img.shields.io/badge/GitHub-2E1065?style=flat-square&logo=github&logoColor=white)](https://github.com/ZayaanB)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=flat-square&logo=vercel&logoColor=white)](https://zayaanb.github.io/Zayaan/)

---

<div align="center">

*"Build systems that don't wake you up at 3am."*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer)

</div>
