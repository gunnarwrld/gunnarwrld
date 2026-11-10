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

### ⚽ Fútbol Data Aggregator API
**TypeScript · Express · Prisma · PostgreSQL · Redis · BullMQ · Socket.IO**

Pulls live and historical match data from API-Football, normalizes it into PostgreSQL, and serves it through cached, rate-limited REST endpoints. Background workers sync leagues, teams and fixtures, and live score changes are pushed to clients over WebSockets.

[Live API](https://futboldataaggregatorapi-production.up.railway.app) · [Repository](https://github.com/gunnarwrld/futbol_data_aggregator_api)

### 🏃 HKIF · student sports platform (team project)
**Node.js · Express · PostgreSQL**

Activity platform for students at Kristianstad University. My part of the backend: JWT authentication and role hierarchy, the API integration-test harness, and the schedule endpoints.

[Auth](https://github.com/jasminerezai/hkif-web/pull/38) · [Roles](https://github.com/jasminerezai/hkif-web/pull/44) · [API tests](https://github.com/jasminerezai/hkif-web/pull/105) · [Schedule API](https://github.com/jasminerezai/hkif-web/pull/133) · [Repository](https://github.com/jasminerezai/hkif-web)

### 📈 Predicting football scores (team project)
**Python · scikit-learn**

Machine learning course project on CONMEBOL matches. I tuned the Random Forest model and built the time-series evaluation. On a 90-match test set, both of our models beat the home-venue baseline.

[My pull request](https://github.com/larrymijo/Project_machine_learning/pull/5) · [Results](https://github.com/larrymijo/Project_machine_learning/blob/main/results/final_scoreboard.csv) · [Repository](https://github.com/larrymijo/Project_machine_learning)

### 🚧 Currently building: Fair Football Fee
Estimates football players' market values from point-in-time player data. The data pipeline is done; the modelling is in progress. [Repository](https://github.com/gunnarwrld/fair-football-fee)

---

## Tech I use

**Backend:** TypeScript, Node.js, Express, Kotlin, Java, Spring Boot, Python
**Data:** PostgreSQL, Redis, Prisma
**Tooling:** Docker, GitHub Actions, Testcontainers, Vitest

**Languages:** English · Spanish · Swedish
