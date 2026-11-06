# Gunnar Arias

Backend developer for systems where the numbers must be right: money ledgers and football data.

Final-year Computer Science student at Kristianstad University (HKR), Sweden, graduating June 2027.
Open to 2027 graduate roles and internships in backend, fintech and sports data.
Remote, or on-site in Sweden, Copenhagen, Spain or Portugal. EU citizen, no work permit needed.
English, Spanish and Swedish.

[Portfolio](https://gunnarwrld.com) · [LinkedIn](https://linkedin.com/in/gunnararias) · [Email](mailto:ariasgunnar@gmail.com) · [Stack Overflow](https://stackoverflow.com/users/29991169/gunnarwrld)

## Selected work

### HKIF sports platform — backend on a student team
Express 5 · TypeScript · Prisma · PostgreSQL · Vitest · Railway

- Built JWT authentication and a four-level role hierarchy (MEMBER < LEADER < BOARD_MEMBER < ADMIN).
- Set up the Vitest + Supertest integration test harness for the API.
- Fixed the ESM build so the server runs on Railway.

[My pull requests](https://github.com/jasminerezai/hkif-web/pulls?q=author%3Agunnarwrld) · [Live](https://hkif-web.vercel.app) · [Repo](https://github.com/jasminerezai/hkif-web)

### Fútbol Data Aggregator — solo
TypeScript · Express 5 · Prisma · PostgreSQL · Redis · BullMQ · Socket.io

Syncs API-Football through BullMQ workers, rate-limits with a Redis sliding window, and pushes live score changes over Socket.io.

[Live](https://futboldataaggregatorapi-production.up.railway.app) · [Repo](https://github.com/gunnarwrld/futbol_data_aggregator_api)

### Ledger Forge — solo
Kotlin · Spring Boot · PostgreSQL · Flyway · Docker

A double-entry wallet ledger: money in integer minor units, idempotent transfers, and ordered row locks so concurrent transfers cannot overdraw. Integration tests run on PostgreSQL in CI.

[Repo](https://github.com/gunnarwrld/ledger-api)

## In progress

- **[Fair Football Fee](https://github.com/gunnarwrld/fair-football-fee)** — predicts Transfermarkt market values (not transfer fees) from point-in-time player data. Data pipeline merged; model and evaluation in review.
- **[Forge Wallet](https://github.com/gunnarwrld/forge-wallet-android)** — offline-first Android client for Ledger Forge, built so a payment settles exactly once. Week 1.

## Stack

**Daily:** TypeScript, Node.js, PostgreSQL, Prisma, Redis, Docker.
**Also:** Kotlin, Java, Python, GitHub Actions.
