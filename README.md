<h1 align="center">Hi 👋, I'm Arafat Hossain</h1>
<h3 align="center">Senior Full-Stack Software Engineer · 7+ years · Vue.js · React · Node.js · Python<br/>Healthcare, EdTech & AI platforms, from architecture to cloud to CI/CD</h3>

<p align="center">
  <a href="https://arafat1023.github.io/portfolio" target="_blank">🌐 Portfolio</a> •
  <a href="mailto:arafathossain847@gmail.com">📫 Email</a> •
  <a href="https://linkedin.com/in/arafat-hossain-dev" target="_blank">💼 LinkedIn</a>
</p>

---

### 👨‍💻 About Me

- 🏢 **Senior Software Engineer** at [Nerddevs Ltd.](https://nerddevs.com) (Dhaka), building production apps for clients in the **USA & Europe**
- 🧭 I own products end to end: architecture, backend, frontend, mobile, cloud infrastructure and the pipelines that ship them
- 🏥 Led a **clinical MRI analytics platform** on **Azure**, with Key Vault envelope encryption for HIPAA-aligned patient data
- 📱 I ship my own products too: **Zikr One** is live on the **App Store and Google Play**
- 🎓 Taught **Laravel & Django** at RUET under Bangladesh's national EDGE program (2025)
- 🌍 Based in Dhaka, Bangladesh · open to **remote** roles
- 🗣️ Bengali (native) · English (fluent)

---

### 💼 Experience

| Role | Company | Period |
|---|---|---|
| **Senior Software Engineer** | Nerddevs Ltd., Dhaka | Jan 2023 – Present |
| **Software Engineer** | Nerddevs Ltd., Dhaka | Sep 2021 – Dec 2022 |
| **Software Engineer** | Sheraspace Ltd., Dhaka | Mar 2019 – Aug 2021 |

**Highlights**

- 🏥 **Medical imaging platform** (FDA-regulated): decision support for spinal disease. Led a team of 3 on the Flask backend, PostgreSQL schemas and **Azure** infrastructure
  - Envelope encryption for patient data: **Azure Key Vault** keys wrap AES-GCM data keys, with a blind index for search and a dual-write migration of the live system
  - Polished and fixed the client's analysis pipeline and ran it on Redis/RQ workers on **Azure GPU VMs**: 7 min → under 2 min per study
  - FDA verification test suite: pytest tests mapped to software requirements, with evidence generated from real runs
  - Clinician web and Electron apps, direct-to-Blob DICOM uploads, audit trail, OTP login for the patient app
- 🎓 **Biddaan**: multi-tenant EdTech platform (LMS + coaching-center management) where every institution gets its own site and admin portal
  - Tenant provisioning: per-school subdomains and custom domains, DNS checks, automated Nginx + Let's Encrypt SSL (130+ tenant domains) with health checks and rollback
  - Pro subscription flow with **bKash** payments and post-payment provisioning on a background worker
  - Live class comments on a **Redis** write buffer that keeps working through a Redis outage
  - Course and shop payments, quizzes with leaderboards, YouTube playlist import, SMS credit pools, push notifications
  - Tenant uploads moved from Cloudflare R2 to **S3 + CloudFront** under per-school prefixes
- 🤖 **AI Mate**: OpenAI GPT-powered chatbot with REST APIs built from OpenAPI specs and an admin dashboard
- 💃 **Daency.com**: live dance classes over **WebRTC**, with Stripe payments and Redis queues
- 📦 **Bikribatta.com**: inventory SaaS; led its **Backbone.js → Vue 3** migration
- 📊 Sheraspace: full-stack project-management app (React, Flask, PostgreSQL) with accounts, HR modules, advanced SQL reporting and a 3D SketchUp viewer

---

### ☁️ Cloud, DevOps & CI/CD

**Cloud platforms**
- **Azure**: Key Vault (envelope encryption, with an RSA key wrapping the data key via `DefaultAzureCredential`), Blob Storage, Functions, Azure ML endpoints, Ubuntu VMs including NVIDIA GPU VMs
- **AWS**: EC2, RDS, S3, CloudFront
- **DigitalOcean**: Droplets and private VPC networking with jump hosts
- **Also**: Oracle Cloud, Cloudflare R2, Firebase

**CI/CD pipelines I've written**
- **GitHub Actions**: SSH + PM2 deploys to development and production, test suites against Postgres service containers with Prisma migrations, automated **Google Play** uploads, cross-platform **Rust/Tauri** release builds with macOS signing, and GitHub Pages deploys
- **Bitbucket Pipelines**: frontend builds to **S3** with **CloudFront** cache invalidation, plus SSH deploys of backends for several production apps

**Infrastructure**
- Linux server administration, **Docker** / Docker Compose, **Nginx** reverse proxies, **PM2**
- Automated Let's Encrypt SSL provisioning for **130+ tenant domains**
- Self-managed PostgreSQL, MongoDB and Redis

---

### 🧩 Personal Projects

**Featured**

| Project | What it is | Stack |
|---|---|---|
| 🌙 **Zikr One** · [App Store](https://apps.apple.com/us/app/zikr-one/id6819017504) · [Google Play](https://play.google.com/store/apps/details?id=com.zikrflow.app) · [zikrone.com](https://zikrone.com) | Community dhikr app: counters, rooms, leaderboards, streaks. I migrated the live app's backend off Firebase and cut every user over | Flutter · NestJS · Prisma · PostgreSQL · Next.js admin |
| 🛒 **BinduShop** · [bindushop.com](https://bindushop.com) | Self-hosted e-commerce store for the Bangladesh market | Medusa v2 · Next.js · TypeScript |

**Also building** (private): native macOS apps in **Swift**, a cross-platform desktop app in **Rust + Tauri**, offline-first **Flutter** apps, and SaaS products on **Fastify + PostgreSQL + Vue 3**.

**Open source**

| Project | What it is |
|---|---|
| 🗣️ [**BhashaVoice**](https://github.com/arafat1023/bhashavoice) | Self-hostable voice-cloning TTS for Bangla and English. FastAPI, Postgres, Redis job queue, Docker workers, S3-compatible storage, LoRA fine-tuning |
| 🎬 [**voiceover-studio**](https://github.com/arafat1023/voiceover-studio) | Narrated demo videos in a cloned voice, made locally: script + screenshots in, captioned video out. Ships a Claude Code skill |
| 🗄️ [**QueryPlayground**](https://github.com/arafat1023/QueryPlayground) | Practice real PostgreSQL and MongoDB in the browser, with PostgreSQL compiled to WebAssembly via PGlite |
| 🖼️ [**ZeroShutter**](https://arafat1023.github.io/ZeroShutter/) | Privacy-first image editor that runs entirely client-side |
| 🌐 [**portfolio**](https://github.com/arafat1023/portfolio) | My portfolio site, in React + TypeScript |

---

### 🛠️ Tech Stack

**Languages: primary**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Languages: also ship in**

![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**Frontend, Mobile & Desktop**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat&logo=tauri&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat&logo=fastify&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Cloud**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Azure Key Vault](https://img.shields.io/badge/Azure_Key_Vault-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat&logo=digitalocean&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat&logo=oracle&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)

**DevOps & CI/CD**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Bitbucket Pipelines](https://img.shields.io/badge/Bitbucket_Pipelines-0052CC?style=flat&logo=bitbucket&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat&logo=pm2&logoColor=white)

**AI & ML**

![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat&logo=openai&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)

**Testing**

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![Mocha](https://img.shields.io/badge/Mocha-8D6748?style=flat&logo=mocha&logoColor=white)

---

### 🎓 Education, Teaching & Certification

- 🎓 **B.Sc. in Computer Science & Engineering**, BRAC University, Dhaka (2014 – 2018)
- 👨‍🏫 **Instructor, Laravel & Django**, RUET (EDGE Government Program), Rajshahi (Jan 2025): 14 sessions on modern web development for university students
- 📜 **Advanced Certificate for Management Professionals (ACMP 4.0)**, IBA, University of Dhaka (2025): leadership, strategy and digital transformation

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=arafat1023&theme=tokyonight" alt="Profile Summary" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=arafat1023&theme=tokyonight" height="165"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=arafat1023&theme=tokyonight" height="165"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=arafat1023&theme=tokyonight" alt="GitHub Streak" />
</p>

---

### 🤝 Connect with Me

<p align="left">
  <a href="https://linkedin.com/in/arafat-hossain-dev" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.facebook.com/arafat.hossain.79/" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
  <a href="mailto:arafathossain847@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
