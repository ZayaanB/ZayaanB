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
[![Email](https://img.shields.io/badge/Email-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zayaan.bhanwadia@mail.utoronto.ca)
<br/>
</div>

---

### 🧠 About Me

I'm a Computer Science and Statistics student at the **University of Toronto** (Honours B.Sc., Co-op) and a 3x hackathon winner. I enjoy building across the stack, from low-level systems in C++ to production Node/FastAPI applications and applied AI/ML tooling. I care about **reliability, performance, and clean developer experience**, whether that means shaving lock contention out of an embedded key-value store or cutting API failure rates in a production service.


**🎯 Open To:** Software Engineering Internships · Software Engineer · Software Developer · Full-Stack & Backend Engineering · AI/ML Engineering

---

### 🛠️ Tech Stack

**Languages**

![Python](https://skillicons.dev/icons?i=py) ![Java](https://skillicons.dev/icons?i=java) ![JavaScript](https://skillicons.dev/icons?i=js) ![TypeScript](https://skillicons.dev/icons?i=ts) ![C++](https://skillicons.dev/icons?i=cpp) ![C](https://skillicons.dev/icons?i=c) ![Bash](https://skillicons.dev/icons?i=bash) ![HTML/CSS](https://skillicons.dev/icons?i=html,css)

**Frameworks & Databases**

![FastAPI](https://skillicons.dev/icons?i=fastapi) ![Node.js](https://skillicons.dev/icons?i=nodejs) ![Flask](https://skillicons.dev/icons?i=flask) ![PostgreSQL](https://skillicons.dev/icons?i=postgres) ![Supabase](https://skillicons.dev/icons?i=supabase)![React](https://skillicons.dev/icons?i=react)

**Cloud, DevOps & Tooling**

![Docker](https://skillicons.dev/icons?i=docker) ![Linux](https://skillicons.dev/icons?i=linux) ![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![GCP](https://skillicons.dev/icons?i=gcp) ![Vercel](https://skillicons.dev/icons?i=vercel) ![VS Code](https://skillicons.dev/icons?i=vscode)

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

**Software Engineer Intern (Incoming Full-Stack)** · FreshBooks
`Sept 2026 – Dec 2026` · Toronto, ON

- Incoming co-op developing Python backend microservices and React UI for a platform serving 10M+ users.
- Will ship production code on a product team, deploying with Docker, Azure DevOps, and Google Cloud Platform.

`Python` `React.js` `Docker` `Azure DevOps` `MySQL/Postgres` `GCP`

<br/>

**Autonomy Software Developer (Mapping & Planning)** · Formula Student Driverless
`July 2026 – Present` · Toronto, ON
- Developed mapping and path-planning software in C++/ROS2 for Canada’s first driverless FSAE car.
- Built a FastSLAM pipeline fusing LiDAR, IMU, GPS, and odometry to localize the car within 15 cm of the optimal line.
- Implemented Delaunay-based centerline and raceline planning to output low-latency, real-time trajectories to controls.
- Validated and optimized algorithms across 20+ simulation and rosbag-replay runs to catch failures before track tests.

`Python` `C++` `ROS2` `FoxGlove` 

<br/>

**Software Engineer Intern (Backend AI)** · FlyRank AI
`July 2026 – Present` · Toronto, ON

- Built a multi-tenant embeddable widget platform, routing form submissions to a dashboard via a one-line script tag.
- Secured public endpoint with validation, rate limiting, spam filtering, and a geolocation fallback, passing 80+ tests.
- Prevented duplicate charges under 50 concurrent requests by deduplicating billable events at the database level.
- Synced Stripe payment updates through secure, idempotent webhooks, eliminating duplicate records and manual fixes.

`TypeScript` `Node.js` `Express.js` `SQLite` `Stripe` `Zod`

<br/>

**Software Developer Intern (Full-Stack)** · KorraNet Creative (Riipen Program)
`May 2026 – Sept. 2026` · Remote

- Optimized Meta OAuth token handling and storage, reducing token refresh failures by 40%+ for AI integrations.
- Reduced system crashes and failed API calls by 85%+ through adding API error handling and timeout prevention.
- Migrated hardcoded secrets to Firebase Secret Manager and implemented real-time secret ingestion for API calls.
- Implemented logging across onboarding and authentication flows to isolate bugs and reduce debugging time.

`Python` `FastAPI` `OAuth` `Google Cloud Platform` `Logging & Observability` `API Reliability`
<br/>

---

<div align="center">

*"Build systems that don't wake you up at 3am."*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer)

</div>
