# Danial Hendi

Backend engineer in Yerevan, Armenia, with 6+ years of Python and TypeScript. I build data-heavy APIs and production AI features, and I spend most of my care on the parts users never see: query plans, failure modes, and tests that catch real bugs.

Open to remote roles with European or US time-zone overlap.
[Email](mailto:danial.hendi@gmail.com) · [LinkedIn](https://www.linkedin.com/in/danial-hendi)

---

## DataPilot

<a href="https://github.com/danielwellz/datapilot">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielwellz/datapilot/main/docs/images/dashboard-dark.png">
    <img alt="DataPilot dashboard: key numbers and monthly revenue over 2 million orders" src="https://raw.githubusercontent.com/danielwellz/datapilot/main/docs/images/dashboard-light.png">
  </picture>
</a>

**[datapilot](https://github.com/danielwellz/datapilot)**: analytics over 2 million e-commerce orders, where plain-English questions become guarded, read-only SQL. Flask, SQLAlchemy, PostgreSQL, Redis and Angular.

- **Measured performance.** The orders list went from 189 ms to 9 ms at p95 with indexes the query plans actually use. A page one million rows deep takes 0.18 ms with keyset pagination, against 303 ms with `OFFSET`.
- **LLM output treated as untrusted input.** Curated views, a read-only database role, a `sqlglot` guard, statement timeouts, row limits and an audit log. Models on Groq and Gemini, with automatic fallback across providers.
- **Analytics in SQL.** Window functions and CTEs for revenue, rankings and retention cohorts, cached in Redis with a stampede lock.
- **Built to be checked.** 1,600+ tests with 100% backend coverage, and CI that starts the full Docker stack and runs a browser test on every pull request. `make demo` runs the whole app in under a minute.

## Other work

**[XIN](https://github.com/danielwellz/Xin)**: a multi-tenant AI assistant for marketing and support teams, answering on Instagram, WhatsApp and an embeddable web widget. Four services in Python and FastAPI with PostgreSQL, Redis and Qdrant, tenant-isolated RAG, and semantic caching that cut redundant LLM calls by about 30%. In production for about a year, serving 25+ businesses.

**[Atlas](https://github.com/danielwellz/Atlas)**: a fitness and biomechanics platform. Contract-first Go API with PostgreSQL and `sqlc`, a React Native client with offline-first sync, and native Kotlin, Swift and Unity modules.

| Project | What it is | Stack |
| --- | --- | --- |
| [omnisonic](https://github.com/danielwellz/omnisonic) | Media platform with an FFmpeg export worker and live progress events | TypeScript, Python, GraphQL, BullMQ, ClickHouse |
| [Hooshpod-RAG-Chatbot](https://github.com/danielwellz/Hooshpod-RAG-Chatbot) | RAG chatbot backend with a semantic cache and swappable embedding providers | TypeScript, Express, Redis, MongoDB |
| [radio-app2](https://github.com/danielwellz/radio-app2) | Multi-channel radio platform with listener and admin apps | FastAPI, async SQLAlchemy, Next.js |
| [Dyno](https://github.com/danielwellz/Dyno) | Workspace for planning and reviewing multimedia projects in real time | Next.js, Express, Prisma, Socket.IO |

## Experience

| When | Role |
| --- | --- |
| 2023–2026 | **Full-stack engineer (contract)**, Kampbusiness. Sole technical owner of 15+ e-commerce and corporate platforms: checkout, payments and admin tools in FastAPI and NestJS. |
| 2021–2022 | **Lead backend engineer**, IranDargah (fintech, about 18,000 users). Led a team of three through a monolith-to-microservices migration and cut response times by about 60%. |
| 2020–now | **Independent engineer.** Backend, data and AI systems for clients; mentored 10+ junior developers. |

## Tools

| Area | Tools |
| --- | --- |
| Languages | Python, TypeScript, Go, SQL |
| Backend | FastAPI, Flask, Django, NestJS, Express, REST, GraphQL, WebSockets |
| Data | PostgreSQL, Redis, Qdrant, MongoDB, SQLAlchemy, Pydantic, Prisma |
| AI | RAG, embeddings, text-to-SQL, LLM evaluation, OpenAI-compatible and Anthropic APIs |
| Frontend | Angular, React, Next.js |
| Delivery | Docker, Kubernetes, AWS, GitHub Actions, OpenTelemetry, Prometheus |

## How I work

- Measure first. Every performance claim above comes with the plan and the numbers behind it.
- Design for failure: timeouts, fallbacks and clear errors when a dependency goes down.
- I use AI coding agents every day. I write the specification, review every change, and keep tests that fail when the code is wrong.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielwellz/danielwellz/output/github-snake-dark.svg">
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/danielwellz/danielwellz/output/github-snake.svg">
</picture>
