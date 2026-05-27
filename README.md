# Hey, I'm Gunnar 👋

Computer Science student at Högskolan Kristianstad (HKR), Sweden, with a focus on backend engineering.
I build typed REST APIs, design relational data models, and ship full-stack web applications, always in TypeScript, always with production habits in mind.

Currently seeking a **software engineering internship** where backend architecture, data modelling, and code quality matter.

[![Portfolio](https://img.shields.io/badge/gunnarwrld.com-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=white)](https://gunnarwrld.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gunnararias)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ariasgunnar@gmail.com)

---

## 🚀 Featured Projects

| Project | Stack | Links |
|---|---|---|
| **HKIF Sports Platform** | Sports union platform with 4-tier RBAC, JWT auth, Prisma + PostgreSQL, and Vitest + Supertest integration tests. Express 5 · TypeScript · Prisma ORM · PostgreSQL · JWT · bcryptjs · Railway | [Live](https://hkif-web.vercel.app) · [Repo](https://github.com/jasminerezai/hkif-web) |
| **FinanceTracker** | Multi-currency personal finance PWA with Stripe billing, Supabase RLS policies, and Groq AI spending insights. React · TypeScript · Supabase (PostgreSQL + Auth + Edge Functions) · Stripe · Groq AI · Zod | [Live](https://personal-finance-web-app-psi.vercel.app) · [Repo](https://github.com/gunnarwrld/personal-finance-web-app) |
| **AI Study Assistant** | Edge AI chat with real-time WebSocket, Durable Objects, and persistent sessions per user. Cloudflare Workers · Durable Objects · Llama 3.3 · Workers AI · SQLite | [Live](https://cf-ai-study-assistant.pages.dev) · [Repo](https://github.com/gunnarwrld/cf_ai_study_assistant) |
| **Personal Portfolio** | Motion-first SPA with a server-validated contact form, per-IP rate limiting, and GitHub Actions CI. React · TypeScript · Framer Motion · Vercel Functions · Resend · Zod · Vitest + Playwright | [Live](https://gunnarwrld.com) · [Repo](https://github.com/gunnarwrld/PersonalPortfolio) |

---

## 🔐 Backend & Auth

- **REST API design:** Router to Controller to Service layering with consistent `ApiResponse<T>` contracts and a typed `ApiError` class with static factory methods (`unauthorized`, `forbidden`, `notFound`, `conflict`)
- **JWT authentication:** Bearer token verification with a live DB lookup on every request, ensuring tokens for deleted or suspended accounts are invalidated within the token window
- **Role-Based Access Control (RBAC):** 4-tier privilege hierarchy (`MEMBER < LEADER < BOARD_MEMBER < ADMIN`) with both exact-role (`restrictTo`) and hierarchical (`restrictToMinRole`) Express middleware guards
- **Password security:** bcryptjs hashing with appropriate salt rounds; passwords never stored or returned in plain text
- **Input validation:** Zod schemas enforced on both client and server (double-validation pattern), with a dedicated `validators/` layer in Express apps
- **Typed error handling:** Custom `asyncHandler` wrapper eliminates try/catch boilerplate across all route controllers; global `errorHandler` middleware formats every error response consistently
- **ORM and migrations:** Prisma with PostgreSQL: typed schema, enum-driven models, explicit relation definitions, `@@unique` constraints, `@@index` annotations for query performance, and versioned migration history
- **Supabase auth and RLS:** Row-Level Security policies for user-scoped data isolation, enforced at the database layer independent of application logic

---

## 💻 Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

**Backend and APIs**
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

**Databases and ORMs**
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)

**Testing**
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing%20Library-E33332?style=for-the-badge&logo=testing-library&logoColor=white)

**Cloud and DevOps**
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-131415?style=for-the-badge&logo=railway&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<p>
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=gunnarwrld&theme=gruvbox&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gunnarwrld&theme=gruvbox&hide_border=true&include_all_commits=true&count_private=true&layout=compact" />
</p>

![](https://nirzak-streak-stats.vercel.app/?user=gunnarwrld&theme=gruvbox&hide_border=true)

---

## 🌐 Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/gunnararias)
[![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/gunnarwrld)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/gunnarwrld)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:ariasgunnar@gmail.com)

[![](https://visitcount.itsvg.in/api?id=gunnarwrld&icon=1&color=7)](https://visitcount.itsvg.in)
