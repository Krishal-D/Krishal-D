<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=8A63D2&center=true&vCenter=true&width=600&lines=Full-Stack+Developer;Cybersecurity+Student;React+%7C+TypeScript+%7C+Node.js+%7C+PostgreSQL" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Sydney%2C%20Australia-8A63D2?style=flat-square" alt="Location" />
  <a href="https://www.linkedin.com/in/krishal-dhungana"><img src="https://img.shields.io/badge/LinkedIn-Connect-8A63D2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:krishal.dh@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-8A63D2?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### About Me

Full-stack developer building deployed, production-style applications with React, TypeScript, Node.js, Express, and PostgreSQL. I've shipped four live projects covering secure authentication (JWT, RBAC), transactional backend logic, automated testing, and an AI-powered retrieval-augmented generation (RAG) pipeline.

I'm a final-year Cybersecurity student at Western Sydney University (ICT — Cybersecurity & Ethical Hacking), available part-time now and **full-time from November 2026**.

**Currently open to:** junior/graduate developer roles, full-stack or frontend developer roles, IT support/service desk roles, and entry-level cybersecurity roles in Australia.

---

### Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Router](https://img.shields.io/badge/-React%20Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Cloud & DevOps**
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/-Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Testing & Tools**
![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### Featured Projects

<details open>
<summary><b>🧠 CogIndex — AI Document Reader</b></summary>
<br>

**Stack:** React, TypeScript, Express, PostgreSQL, OpenAI API, JWT, Vercel
**Links:** [Live](#) · [GitHub](#) <!-- ADD-URL: paste live + repo links -->

A full-stack AI document reader where authenticated users upload PDFs, create document-specific conversations, and query their own content in natural language.

- Implemented a retrieval-augmented generation (RAG) pipeline: PDF parsing, text chunking, OpenAI embeddings, PostgreSQL vector storage (pgvector), semantic similarity search, and context-grounded answer generation.
- Designed protected REST APIs for authentication, document upload, conversation management, and message history, with per-user ownership enforcement on every route.

</details>

<details>
<summary><b>💼 TalentTrack — Applicant Tracking System</b></summary>
<br>

**Stack:** React 19, Express 5, PostgreSQL, JWT, Docker, Vercel, Render
**Links:** [Live](#) · [GitHub](#) <!-- ADD-URL: paste live + repo links -->

An applicant tracking system supporting separate candidate and employer workflows.

- Implemented JWT access tokens with refresh-token rotation, HttpOnly cookie storage, and single-session enforcement.
- Built role-based authorization enforced via authentication middleware and ownership checks on every protected route.
- Designed a relational PostgreSQL schema (users, jobs, applications) using foreign keys, cascading deletes, migrations, and joined dashboard queries.

</details>

<details>
<summary><b>🛒 Cartly — B2C E-Commerce Platform</b></summary>
<br>

**Stack:** React, TypeScript, Express, PostgreSQL, JWT, Jest, Supertest
**Links:** [Live](#) · [GitHub](#) <!-- ADD-URL: paste live + repo links -->

A B2C e-commerce platform with transactional checkout logic and automated test coverage.

- Built transactional checkout logic with guarded stock reduction, cart validation, and rollback-safe order creation to prevent overselling and race conditions.
- Secured authentication flows using JWT access/refresh tokens, HttpOnly cookies, role-protected admin routes, and stale-token rejection.
- Added automated backend test coverage with Jest and Supertest across authentication, protected routes, cart validation, checkout logic, and edge cases.

</details>

<details>
<summary><b>🎓 Student Wellbeing Platform</b></summary>
<br>

**Stack:** Express, EJS, PostgreSQL, Docker, JWT, bcrypt
**Links:** [GitHub](#) <!-- ADD-URL: paste repo link -->

A 4-person Agile team project covering mood tracking, messaging, events, and alert features.

- Highest committer in the team; drove backend delivery across mood tracking, messaging, events, and alert features.
- Cut teammate environment setup time from ~2 hours to under 10 minutes by building a Docker devcontainer configuration with connection pooling and migration scripts.
- Secured all protected routes with JWT cookie authentication, bcrypt password hashing, and RBAC middleware.

</details>

---

### Experience

**Personal Care Worker** — Aged Care Provider, Sydney *(Part-Time, 2024 – Present)*
- Maintained accurate documentation and confidentiality in a regulated environment requiring reliability, attention to detail, and duty-of-care standards.
- Communicated daily with clients, families, and multidisciplinary teams — stakeholder communication and teamwork skills directly transferable to product delivery environments.

---

### Education

**Bachelor of Information and Communications Technology — Cybersecurity & Ethical Hacking**
Western Sydney University, Sydney, Australia · Mar 2024 – Dec 2026

---

### Connect

<p align="left">
  <a href="https://www.linkedin.com/in/krishal-dhungana"><img src="https://img.shields.io/badge/-LinkedIn-8A63D2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:krishal.dh@gmail.com"><img src="https://img.shields.io/badge/-Email-8A63D2?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Krishal-D"><img src="https://img.shields.io/badge/-GitHub-8A63D2?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

<p align="center"><sub>Thanks for stopping by — always happy to connect with fellow developers and Australian tech teams.</sub></p>
