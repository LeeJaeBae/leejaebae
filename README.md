<!-- Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24,30&height=260&section=header&text=Jaewon%20Lee&fontSize=58&fontAlignY=34&desc=Full-Stack%20Engineer%20%C2%B7%20Product%20Builder%20%C2%B7%20Operations-Minded&descAlignY=52&descAlign=50&animation=twinkling" />

<!-- Typing introduction -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=25&duration=2800&pause=900&color=F46A25&center=true&vCenter=true&random=false&width=820&height=80&lines=I+turn+complex+workflows+into+reliable+products;Product+%E2%86%92+Architecture+%E2%86%92+Production+%E2%86%92+Operations;Building+software+that+survives+the+real+world" alt="Typing introduction" />
</p>

<!-- Social links -->
<div align="center">
  <a href="https://linkedin.com/in/wony-love" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/LeeJaeBae" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:leejaebae@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
</div>

<br />

<!-- About -->
<img align="right" alt="Developer at work" width="360" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" />

## 🚀 About Me

I'm a full-stack engineer who works across **product design, backend architecture, frontend implementation, deployment, and production operations**.

My strongest work begins where requirements are incomplete and operational processes are still manual. I map the real workflow, define the domain model, build the system, and improve it using feedback from production.

- 🔧 I build transactional systems, admin tools, and operational workflows.
- 🧩 I specialize in payments, permissions, data modeling, and legacy modernization.
- 📦 I care about the entire path from an idea to a system people can actually operate.
- 🇰🇷 Based in Korea.

<br clear="right" />

<!-- Impact summary -->
## ⚡ Impact at a Glance

<div align="center">
  <img src="https://img.shields.io/badge/Production_DB_Migrations-30-F46A25?style=for-the-badge" alt="30 production database migrations" />
  <img src="https://img.shields.io/badge/RBAC-4_Levels-6AD3F5?style=for-the-badge" alt="Four-level RBAC" />
  <img src="https://img.shields.io/badge/Legacy_Data-10K%2B_Records-8B5CF6?style=for-the-badge" alt="More than ten thousand legacy records" />
  <img src="https://img.shields.io/badge/DB_Calls_Audited-302-22C55E?style=for-the-badge" alt="302 database calls audited" />
</div>

<br />

<!-- Projects -->
## 🧭 Selected Work

### 🍊 To Orange — Letter Delivery Platform

> A production platform connecting online letter creation with physical printing, inspection, packaging, and dispatch operations.

<p>
  <img src="https://img.shields.io/badge/Role-Development_%26_Operations_Lead-F46A25?style=flat-square" alt="Development and Operations Lead" />
  <img src="https://img.shields.io/badge/Scope-End--to--End_Product-6AD3F5?style=flat-square" alt="End-to-end product scope" />
  <a href="https://github.com/LeeJaeBae/to-orange"><img src="https://img.shields.io/badge/Repository-View_Code-181717?style=flat-square&logo=github" alt="To Orange repository" /></a>
</p>

- Built core workflows covering **orders, payments, idempotent refunds, points, coupons, referrals, and recipient management**.
- Developed **OTP authentication, OCR-assisted processing, AI writing features, SMS notifications, and retry handling**.
- Built administrative tools for **printing queues, PDFs, envelopes, reports, customer support, and dispatch processing**.
- Designed a **four-level RBAC model** for headquarters, local managers, and operators, with automatic work logs for dispatch, scanning, and inspection.
- Improved the software using direct experience from fulfillment and customer-support operations.

`TypeScript` `Next.js` `Supabase` `PostgreSQL` `Vercel`

---

### 🏝️ Ulleung Sketch — Travel Reservation Platform

> A reservation platform for Ulleungdo packages, ferries, Dokdo tours, accommodations, and vehicle shipment.

<p>
  <img src="https://img.shields.io/badge/Role-Full--Stack_Developer-F46A25?style=flat-square" alt="Full-stack developer" />
  <img src="https://img.shields.io/badge/Existing_Data-10K%2B_Records-8B5CF6?style=flat-square" alt="More than ten thousand existing records" />
  <a href="https://github.com/LeeJaeBae/ulleung-sketch-dev"><img src="https://img.shields.io/badge/Web-Repository-181717?style=flat-square&logo=github" alt="Ulleung Sketch web repository" /></a>
  <a href="https://github.com/LeeJaeBae/ulleung-sketch-admin"><img src="https://img.shields.io/badge/Admin-Repository-181717?style=flat-square&logo=github" alt="Ulleung Sketch admin repository" /></a>
</p>

- Developed separate customer-facing and administrative applications for a multi-domain reservation workflow.
- Worked with **10,000+ existing records** while reviewing a JSONB-heavy schema for long-term extensibility.
- Designed a normalization strategy separating **travelers, rooms, vehicles, schedules, payments, and audit history** from the reservation core.
- Structured the web and admin projects for gradual migration while preserving their existing Git histories.

`TypeScript` `Next.js` `NestJS` `Drizzle ORM` `Supabase` `PostgreSQL` `MUI` `Turborepo`

---

### 🔐 Supabase Security & Backend Architecture Review

> A security and architecture assessment for a client-side Supabase application moving toward a dedicated backend boundary.

<p>
  <img src="https://img.shields.io/badge/Tables_%2B_Views-31-F46A25?style=flat-square" alt="31 tables and views" />
  <img src="https://img.shields.io/badge/RPCs_%2B_Triggers-20-6AD3F5?style=flat-square" alt="20 RPCs and triggers" />
  <img src="https://img.shields.io/badge/RLS_Policies-35-8B5CF6?style=flat-square" alt="35 RLS policies" />
  <img src="https://img.shields.io/badge/Frontend_DB_Calls-302-22C55E?style=flat-square" alt="302 frontend database calls" />
</p>

- Reviewed **27 tables, 4 views, 15 RPCs, 5 triggers, and 35 RLS policies**.
- Traced **302 direct database calls across 43 frontend files**, including 136 write operations.
- Analyzed **1,040 lines of PL/pgSQL** to identify authorization and data-boundary risks.
- Proposed a phased migration that moved writes behind server functions first while temporarily retaining RLS-protected reads.

`PostgreSQL` `Supabase RLS` `Authorization` `API Boundaries` `Migration Strategy`

<!-- Skills -->
## 🛠️ Core Stack

<h3 align="center">Frontend</h3>
<div align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,typescript,javascript,html,css,tailwind,flutter" alt="Frontend technologies" />
</div>

<h3 align="center">Backend & Data</h3>
<div align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,postgres,supabase,redis,docker" alt="Backend and data technologies" />
</div>

<h3 align="center">Tools & Delivery</h3>
<div align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,jest,aws,vercel" alt="Development tools" />
</div>

<!-- Stats -->
## 📊 GitHub Activity

<div align="center">
  <img width="49%" height="195" src="https://github-readme-stats.vercel.app/api?username=LeeJaeBae&show_icons=true&count_private=true&hide_border=true&title_color=F46A25&icon_color=6AD3F5&text_color=c9d1d9&bg_color=0d1117" alt="Jaewon Lee's GitHub stats" />
  <img width="49%" height="195" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LeeJaeBae&layout=compact&hide_border=true&title_color=F46A25&text_color=c9d1d9&bg_color=0d1117" alt="Jaewon Lee's most used languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=LeeJaeBae&theme=tokyonight&hide_border=true&ring=F46A25&fire=F46A25&currStreakLabel=F46A25" alt="GitHub contribution streak" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=LeeJaeBae&theme=react-dark&hide_border=true&area=true&color=F46A25&line=6AD3F5&point=F46A25&custom_title=Jaewon's%20Contribution%20Graph" width="95%" alt="Contribution graph" />
</div>

<!-- Contribution visuals -->
## 🐍 Contributions

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LeeJaeBae/LeeJaeBae/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LeeJaeBae/LeeJaeBae/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/LeeJaeBae/LeeJaeBae/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<div align="center">
  <img src="./profile-3d-contrib/profile-night-rainbow.svg" width="95%" alt="3D contribution calendar" />
</div>

<!-- Footer -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24,30&height=120&section=footer&animation=twinkling" />

<div align="center">
  <sub><strong>Building software that survives contact with the real world.</strong></sub>
</div>
