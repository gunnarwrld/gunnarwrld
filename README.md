# Hi, I'm Gunnar 👋

Final-year Computer Science student at Högskolan Kristianstad, Sweden (graduating June 2027). I build backend systems, and most of my side projects sit where I spend my free time: **finance** and **football**.

Open to software engineering internships and graduate roles in Sweden and Europe for 2027.

Every project gets better with mate. 🧉

[Portfolio](https://gunnarwrld.com) · [LinkedIn](https://linkedin.com/in/gunnararias) · [Email](mailto:ariasgunnar@gmail.com)

---

## Projects

### 💰 Ledger Forge
**Kotlin · Spring Boot · PostgreSQL · Testcontainers · GitHub Actions**

A double-entry wallet ledger API. Money is stored as integer minor units, transfers are idempotent, and accounts are locked in a fixed order so concurrent transfers can't deadlock or overspend. Journal entries are append-only and checked by database triggers. Integration tests run against real PostgreSQL in CI.

Companion app: [Forge Wallet](https://github.com/gunnarwrld/forge-wallet-android), an offline-first Android client that settles payments exactly once.

[Repository](https://github.com/gunnarwrld/ledger-api)

### 📒 Ledger Sentinel
**Java 21 · Spark Java · PostgreSQL · jOOQ · Flyway · Testcontainers**

A Java 21 double-entry payments ledger for synthetic account transfers: idempotent APIs, ordered row locks, operator reversals, and model-based tests against PostgreSQL. No machine-learning code is in this repository yet.

[Repository](https://github.com/gunnarwrld/ledger-sentinel-ai)

### ⚽ Fútbol Data Aggregator API
**TypeScript · Express · Prisma · PostgreSQL · Redis · BullMQ · Socket.IO**

Pulls live and historical match data from API-Football, normalizes it into PostgreSQL, and serves it through cached, rate-limited REST endpoints. Background workers sync leagues, teams and fixtures, and live score changes are pushed to clients over WebSockets.

[Live API](https://futboldataaggregatorapi-production.up.railway.app) · [Repository](https://github.com/gunnarwrld/futbol_data_aggregator_api)

### 🏟️ Matchday Hub
**C# · ASP.NET Core · PostgreSQL · SignalR · Redis · Testcontainers**

A local ASP.NET Core 10 match data service and companion to the Fútbol Data Aggregator. It stores fixtures and live events in PostgreSQL, streams them with SignalR, and serves team form.

[Repository](https://github.com/gunnarwrld/matchday-hub)

### 🏃 HKIF · student sports platform (team project)
**Node.js · Express · PostgreSQL**

Activity platform for students at Kristianstad University. My part of the backend: JWT authentication and role hierarchy, the API integration-test harness, and the schedule endpoints.

[Auth](https://github.com/jasminerezai/hkif-web/pull/38) · [Roles](https://github.com/jasminerezai/hkif-web/pull/44) · [API tests](https://github.com/jasminerezai/hkif-web/pull/105) · [Schedule API](https://github.com/jasminerezai/hkif-web/pull/133) · [Repository](https://github.com/jasminerezai/hkif-web)

### 📈 Predicting football scores (team project)
**Python · scikit-learn**

Machine learning course project on CONMEBOL matches. I tuned the Random Forest model and built the time-series evaluation. On a 90-match test set, both of our models beat the home-venue baseline.

[My pull request](https://github.com/larrymijo/Project_machine_learning/pull/5) · [Results](https://github.com/larrymijo/Project_machine_learning/blob/main/results/final_scoreboard.csv) · [Repository](https://github.com/larrymijo/Project_machine_learning)

### ⚽ Fair Football Fee
**Python · XGBoost · FastAPI · Next.js · Redis · Docker · GitHub Actions**

Premier League crowd-sourced market-value predictor: point-in-time XGBoost estimates with conformal intervals, TreeSHAP drivers and what-if scenarios, served by a FastAPI API and a Next.js UI.

[Repository](https://github.com/gunnarwrld/fair-football-fee)

---

## Now building

### 🔍 Finvigil
**Python · LangGraph · XGBoost**

An autonomous multi-agent AML and fraud investigation engine over a double-entry bank ledger.

[Repository](https://github.com/gunnarwrld/finvigil)

---

## Tech I use

**Backend:** TypeScript, Node.js, Express, Kotlin, Java, Spring Boot, C#, ASP.NET Core, Python, FastAPI
**Data & ML:** PostgreSQL, Redis, Prisma, XGBoost
**Frontend:** React, Next.js, Jetpack Compose
**Tooling:** Docker, GitHub Actions, Testcontainers, Vitest

**Languages:** English · Spanish · Swedish
