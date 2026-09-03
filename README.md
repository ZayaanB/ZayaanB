<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,50:0EA5E9,100:0369A1&height=220&section=header&text=Zayaan%20Bhanwadia&fontSize=42&fontColor=E0F2FE&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Full%20Stack%20%2B%20AI/ML&descAlignY=55&descSize=18)

<a href="https://github.com/ZayaanB">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=560&lines=Full-Stack+Engineer+%7C+Systems+%2B+AI%2FML;University+of+Toronto+%E2%80%94+CS+%2B+Stats" alt="Typing SVG" />
</a>

<br/>

![University of Toronto](https://img.shields.io/badge/University%20of%20Toronto-Honours%20B.Sc.%20CS%20(Co--op)-0284C7?style=flat-square&logo=google-scholar&logoColor=white)
![Location](https://img.shields.io/badge/Toronto,%20ON-0C4A6E?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white)](https://zayaanb.github.io/Zayaan/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0C4A6E?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zayaan-bhan)
[![Email](https://img.shields.io/badge/Email-0284C7?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zayaan.bhanwadia07@gmail.com)
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

![FastAPI](https://skillicons.dev/icons?i=fastapi) ![Node.js](https://skillicons.dev/icons?i=nodejs) ![Express.js](https://skillicons.dev/icons?i=express) ![Flask](https://skillicons.dev/icons?i=flask) ![PostgreSQL](https://skillicons.dev/icons?i=postgres) ![Supabase](https://skillicons.dev/icons?i=supabase)![React](https://skillicons.dev/icons?i=react)

**Cloud, DevOps & Tooling**

![Docker](https://skillicons.dev/icons?i=docker) ![Linux](https://skillicons.dev/icons?i=linux) ![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![GCP](https://skillicons.dev/icons?i=gcp) ![AWS](https://skillicons.dev/icons?i=aws) ![Azure](https://skillicons.dev/icons?i=azure) ![Vercel](https://skillicons.dev/icons?i=vercel) ![VS Code](https://skillicons.dev/icons?i=vscode)

**Robotics & ML**

![ROS 2](https://img.shields.io/badge/ROS%202-0284C7?style=flat-square&logo=ros&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-0C4A6E?style=flat-square&logo=yolo&logoColor=white)

---

### 🚀 Featured Projects

<details>
<summary><b>🗃️ Embedded Key-Value Store</b> — C++ / CMake / Multithreading / Linux</summary>
<br/>

An embedded C++ database engineered for high-throughput concurrent access via sharding and lock-free reads.

| | |
|---|---|
| **Stack** | C++, CMake, Multithreading, Linux |
| **Scale** | 16-way sharded locking, 5x read throughput (8M → 40M ops/sec) |
| **Performance** | 45%+ disk usage reduction via compaction |
| **Reliability** | Checksummed write-ahead log for crash recovery |
| **Repository** | [github.com/ZayaanB](https://github.com/ZayaanB) |

- Built an embedded database with 16-way sharded locking, boosting read throughput 5x (8M to 40M ops/sec)
- Implemented reader-writer locks so reads proceed during disk writes, preventing race conditions across 16 threads
- Created a file compaction routine to safely clean up keys, reducing disk usage by 45%+ without pausing the app
- Guaranteed crash recovery by persisting every update to a checksummed write-ahead log before applying changes

</details>

<details>
<summary><b>🔗 Context Sync Extension</b> — TypeScript / VS Code Extension API</summary>
<br/>

A VS Code extension automating AI chat context continuity across developer environments — 700+ downloads.

| | |
|---|---|
| **Stack** | TypeScript, VS Code Extension API |
| **Scale** | 700+ downloads |
| **Integrations** | GitHub Copilot, OneDrive, Google Drive |
| **Impact** | One-click environment setup, denser AI context per token |
| **Repository** | [github.com/ZayaanB](https://github.com/ZayaanB) |

- Developed a VS Code extension with 700+ downloads that automates AI chat context sharing across environments
- Reduced token use 25%+ by modeling chats as a weighted graph and selecting context via shortest-path search
- Designed a Markdown schema that packs more context into fewer tokens across AI assistant sessions
- Integrated GitHub Copilot, Google Drive, and OneDrive to automate syncing and enable one-click AI workspace setup

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

**Full-Stack Software Developer Intern** · FreshBooks
`Sept 2026 – Dec 2026` · Toronto, ON

- Selected to join a product team developing Python/Ruby microservices and React interfaces supporting 10M+ users.

`Python` `Ruby` `React.js` `Microservices`

<br/>

**Autonomy Software Engineer (Mapping & Planning)** · University of Toronto Formula Racing – Driverless
`July 2026 – Present` · Toronto, ON
- Developed mapping and path-planning software in C++ and ROS 2 for Canada's first driverless FSAE car.
- Built a SLAM pipeline mapping new racetracks to within 18 cm accuracy using Kalman filters and factor graphs.
- Rebuilt the path planner to keep 96% of paths on track in simulation, fixing sharp turns that stalled the old system.
- Cut ~20 ms of planning latency by switching to LiDAR-only planning and removing the camera neural network.

`Python` `C++` `ROS2` `LiDAR`

<br/>

**Software Engineer Intern (Backend AI)** · FlyRank AI
`July 2026 – Sept 2026` · Toronto, ON

- Built a centralized embeddable widget platform, routing form submissions to a dashboard via a one-line script tag.
- Secured a public endpoint with validation, rate limiting, and geolocation checks, cutting spam by 80%.
- Prevented duplicate charges under 50+ simultaneous requests by deduplicating payment events in the database.

`TypeScript` `Node.js` `Express.js` `SQLite` `Zod`

<br/>

**Full-Stack Software Developer Intern** · KorraNet Creative
`May 2026 – July 2026` · Remote

- Optimized Meta OAuth token handling and storage, reducing token refresh failures by 40%+ for AI integrations.
- Reduced system crashes and failed API calls by 85%+ by adding API error handling and timeout prevention.
- Migrated hardcoded secrets to Firebase Secret Manager, enabling key rotation without redeploying services.

`Python` `FastAPI` `OAuth` `Google Cloud Platform`
<br/>

---

<div align="center">

*"Build systems that don't wake you up at 3am."*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,50:0EA5E9,100:0369A1&height=120&section=footer)

</div>
