<div align="center">

# Adick Rincones

**Backend Engineer · Go & Rust · Real-time & distributed systems · Payments ledgers**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adickrincones-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adickrincones/)
[![Email](https://img.shields.io/badge/Email-rinconesadick%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rinconesadick@gmail.com)
![Location](https://img.shields.io/badge/Buenos_Aires-UTC--3-74ACDF?style=flat-square&logo=googlemaps&logoColor=white)
![Open to](https://img.shields.io/badge/Open_to-remote_backend_roles-2EA44F?style=flat-square)

</div>

---

Backend engineer with 6+ years of experience. I work mostly in Go and Rust, with PostgreSQL and Redis. I also ship mobile and frontend (Kotlin, React, React Native) when the product needs it.

### 🛠️ Currently: Founding Engineer at Yaju (Sep 2026 – present)

Ride-hailing and delivery startup in Venezuela, launching December 2026. I'm the only engineer: I built the backend, the infrastructure, the Android app and the web panels. *(private repos)*

- Modular monolith in Go (API, real-time, jobs). Rides and deliveries share one task core with a table-driven state machine, so both verticals launch at once.
- Append-only double-entry ledger in PostgreSQL with idempotency keys, deadlock-free locking and property-based tests of its invariants (zero-sum, no negative balances).
- Real-time location over WebSockets with Redis GEO and Pub/Sub fan-out across instances, no sticky sessions.
- Built for unstable mobile networks: idempotent orders, payouts that can't be duplicated, and offer/task recovery when the WebSocket reconnects.
- Deployed to production on Railway (2 replicas) with Neon Postgres/PostGIS and Sentry. WhatsApp OTP auth with rotating refresh tokens, GCRA rate limiting, CI with testcontainers, 27 ADRs.

### 📁 Before

- **Rigolo App** (Nov 2025 – Sep 2026): event-driven Rust microservices (Actix-Web, hexagonal architecture, NATS JetStream) for VaxVan, a US mobile pet-vaccination platform in daily production. Migrated staff user management from Firebase Cloud Functions to the Rust backend.
- **Vamos App** (Sep 2024 – Nov 2025): rewrote a ride-hailing app (100K+ active users, 1,000+ drivers) from B4A to React Native by myself in 4 weeks, shipping Android and iOS from one codebase.
- **Earlier:** multi-currency payroll and QR ticketing systems (Node.js, MongoDB, Next.js), C++ gameplay systems in Unreal Engine 5, and REST APIs in Rust.

### 🧭 How I work

- Correctness first: idempotency, retries with backoff, invariants covered by tests.
- Decisions written down as ADRs, with the alternatives I rejected and why.
- Design for failure: dropped connections, duplicate requests, restarts.

### 🎯 Looking for

Remote backend roles in Go or Rust with US or European teams, especially payments/fintech, real-time systems or logistics. Based in Buenos Aires (UTC-3). English C2.

### 🧰 Stack

<p>
  <img src="https://skillicons.dev/icons?i=go,rust,postgres,redis,docker,linux,kotlin,react,ts&theme=dark" alt="Go, Rust, PostgreSQL, Redis, Docker, Linux, Kotlin, React, TypeScript" />
</p>

- **Backend:** Go, Rust, PostgreSQL, PostGIS, Redis, WebSockets, NATS JetStream, REST APIs, sqlc
- **Infra:** Docker, CI/CD, testcontainers, Railway, Neon, Sentry, AWS (learning: SQS, Lambda, DynamoDB)
- **Mobile / Frontend:** Kotlin, Jetpack Compose, React, TypeScript, React Native
- **Also:** MongoDB, MySQL

### 🌱 Side projects & open source

- **[GoQueue](https://github.com/AdickRinconesM133/GoQueue)**: background job processing in Go on AWS (SQS, Lambda, DynamoDB). Work in progress.
- Merged PR to [caelestia-dots/caelestia](https://github.com/caelestia-dots/caelestia) (Hyprland desktop shell): window rules for Lutris/Wine and Gamescope.
