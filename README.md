<h1 align="center">Hi, I'm Ashmita Mazumdar 👋</h1>

<p align="center">
  <b>Computer Science Undergraduate · Full-Stack & Backend Developer</b><br/>
  B.Tech CSE @ SVKM's NMIMS (MPSTME), Shirpur · Class of 2028
</p>

<p align="center">
  <a href="https://final-portfolio-liard-sigma.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0A66C2?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/ashmita-mazumdar-009863394/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ashmita110609@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

I build **complete, tested, deployed systems**: event-driven backends, databases that do real work, and clean frontends on top.
My recent work includes a **Kafka-based fraud-monitoring platform**, a **fraud engine written inside Oracle with PL/SQL**,
a **compiler I wrote by hand** from lexer to C++ code generation, and a **webcam-controlled game** built with classical computer vision.

- 🔭 **Focus:** backend engineering, event-driven architecture, databases, and full-stack web apps
- ✅ **How I work:** every project is deployed live and backed by automated tests and CI (**450+ tests** across projects)
- 🎯 **Looking for:** Software Engineering internship opportunities

---

## 🚀 Featured Projects

### 💳 [FinPulse](https://github.com/ashmita-dev/finpulse) — Real-Time Fraud Monitoring Platform · [Live Demo](https://finpulse-frontend-0lj2.onrender.com/)
`FastAPI` `Apache Kafka` `PostgreSQL` `WebSockets` `React` `TypeScript` `Docker` `Airflow`

- Event-driven pipeline: **API → PostgreSQL → Kafka → risk engine → WebSocket**, pushing **APPROVE / REVIEW / BLOCK** decisions to the dashboard in real time
- Risk engine scores amount, new-device, transaction-velocity and behavioural-anomaly signals, with explainable reasons
- 6 containerized services behind an Nginx reverse proxy; CI with Pytest, Jest and Cypress end-to-end tests

### 🏦 [SmartBank](https://github.com/ashmita-dev/SmartBank) — Database-Driven Fraud Detection · [Live Demo](https://ashmita-dev.github.io/SmartBank/)
`Oracle 21c` `PL/SQL` `ORDS` `React 19` `Playwright`

- Fraud detection runs **inside the database**: a compound trigger scores every transaction, raises alerts and assigns them to the least-loaded analyst
- Normalized **12-table schema** with constraints, reporting views and indexes checked with EXPLAIN PLAN
- Authenticated REST API with role-based access, a two-role React dashboard, and **150+ automated checks**

### ⚙️ [CodeBridge](https://github.com/ashmita-dev/CodeBridge) — Pseudocode-to-C++ Compiler · [Live Demo](https://codebridge-swart.vercel.app)
`Python` `FastAPI` `React` `TypeScript` `C++17`

- Every phase hand-written, **no parser generators**: lexer, recursive-descent parser, typed AST, semantic analysis, three-address code, optimizer, C++ code generator
- Optimizer verified by a **300-program randomized differential test**; **233 tests** in total, including g++ build-and-run checks
- Interactive workbench that shows tokens, AST, symbol table, original vs. optimized TAC, and the generated C++ live

### 🎮 [Pixel Quest](https://github.com/ashmita-dev/PixelQuest) — Webcam-Controlled Arcade Game · [Play in Browser](https://ashmita-dev.github.io/PixelQuest/)
`Python` `OpenCV` `NumPy` `Pygame`

- Steer a spaceship by moving a coloured object in front of your webcam, tracked in **~1.2 ms per frame** at **60 FPS**
- Classical computer vision only: HSV segmentation, morphology, contour centroids and motion smoothing
- **65 tests** using synthetic frames and fake cameras, so no webcam is needed to run them

<details>
<summary><b>More projects</b></summary>
<br/>

- **[Developer Portfolio](https://final-portfolio-liard-sigma.vercel.app)**: interactive portfolio with a command palette, GitHub activity and scroll-driven animations. `React` `Vite` `Tailwind CSS` `GSAP` `Framer Motion`
- **Career Copilot**: full-stack platform that helps students find skill gaps, review their GitHub profile and plan a learning roadmap. `React` `Node.js` `Express.js` `PostgreSQL` `GitHub API` `JWT`

</details>

---

## 🛠️ Tech Stack

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL%20%2F%20PL%2FSQL-4479A1?style=flat-square&logo=oracle&logoColor=white)

**Backend & Data**<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle%20DB-F80000?style=flat-square&logo=oracle&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)

**Frontend**<br/>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)

**DevOps & Testing**<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

---

## 🏆 Achievements

- 🥈 **2nd Prize**, Python Mini Project Competition
- 💡 **Smart India Hackathon 2025**: Round-1 selection through the Yugantar 2.0 Inter-Institute Hackathon
- 📜 **JPMorgan Chase & Co.** Software Engineering Virtual Experience (Forage) · **Microsoft Learn** Cloud Computing badges

---

<p align="center">
  <b>Open to Software Engineering internships.</b> If you're hiring or want to talk tech, reach out at
  <a href="mailto:ashmita110609@gmail.com">ashmita110609@gmail.com</a>.
</p>
