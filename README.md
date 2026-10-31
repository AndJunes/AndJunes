# Hi, I'm Andrea 👋

**Backend engineer · Python & FastAPI · LLM agents in production**

I build backends that hold up in production and put LLMs to work inside them, with guardrails, evals and tests from day one. I came to backend through QA and frontend, so I think about edge cases and what users actually see.

📍 Argentina (UTC-3) · 🌎 Open to **remote Backend / Full-stack (Python)** roles, full-time or contract · 🗣️ Spanish (native), English (B2)

[Portfolio](https://www.andreajunes.com/) · [LinkedIn](https://www.linkedin.com/in/andrea-junes/) · [Substack](https://andreajunes.substack.com/) · [Email](mailto:junesandrea56@gmail.com)

---

## Experience

**Backend Engineer (Python / LLM agents)** · Freelance, remote · Jan 2026 – Jul 2026\
Event-driven multi-agent system on Google Cloud that turns technical specs into Jira tickets, with a second agent that picks them up for evaluation. FastAPI workers on Pub/Sub with deduplication, Cloud Run, Cloud Scheduler, PostgreSQL, Cloud Trace.

**Frontend Developer** · MindDev Perú, part-time, remote · Jun 2025 – Nov 2025\
Built the company blog and a client landing page with React and TypeScript.

**QA Analyst** · Gearthlogic, full-time, remote · Jan 2025 – Sep 2025\
End-to-end testing of a web app, defect reporting and release coordination between clients and developers.

🎓 Tecnicatura Universitaria en Desarrollo Web, Universidad Nacional de Entre Ríos (2024 – 2026)

## Highlights

- 🏆 **#4 of 1,771** in [HackerRank Orchestrate](https://www.hackerrank.com/contests/hackerrank-orchestrate-june26/challenges/multi-modal-review/leaderboard) (June 2026): a multimodal agent that reviews insurance damage claims, built in 24 hours. Score 70.0/100. It later became [Zipshield](https://github.com/AndJunes/Zipshield).
- 💸 **Stellar Community Fund Instaward** for Brújula, after being selected for the Código Alebrije *Scale* track (8 spots across LATAM). [The full story](https://andreajunes.substack.com/p/viaje-conmigo-como-construi-brujula)
- 🥇 **1st place, Frontend Mentor FM30 hackathon** (July 2026) with [FX Checker](https://github.com/AndJunes/Foreign-exchange-currency-converter).
- 🔍 **Security write-up:** [I analyzed the Shai-Hulud npm worm](https://substack.com/home/post/p-198619514), which steals tokens and wipes your home directory.

## Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [**Zipshield**](https://github.com/AndJunes/Zipshield) · [Live](https://zipshield.vercel.app) | Insurance claims platform where a vision model reviews photo evidence before a human does. Role-based access enforced on every endpoint, layered prompt-injection defense, Decimal-exact pricing. CI runs lint, types and tests. | FastAPI · SQLAlchemy · PostgreSQL · Alembic · Angular · OpenRouter |
| [**Interview Simulator**](https://github.com/AndJunes/simulador-entrevistas) | Builds interview questions from a real job posting and a CV, interviews you by voice and scores answers with anchored rubrics. RAG over a sourced corpus, LLM evals, local-only audio, WCAG 2.2 AA e2e checks. | FastAPI · LangGraph · pgvector · React · Playwright |
| [**mini-redis**](https://github.com/AndJunes/mini-redis) | Redis-compatible server from scratch: works with `redis-cli`, 240k–380k req/s with pipelining, AOF persistence with crash recovery, benchmarked against real Redis. | Python (stdlib only) |
| [**Brújula**](https://github.com/jubitcode/agentbrujula) · [Live](https://www.agentbrujula.com/) | Marketplace for AI agents. USDC payments sit in an on-chain escrow and are released only if the output passes an on-chain check, refunded otherwise. Team project. | Next.js · FastAPI · Soroban (Rust) · Go · x402 · A2A |
| [**FX Checker**](https://github.com/AndJunes/Foreign-exchange-currency-converter) · [Live](https://foreign-exchange-currency-converter-mocha.vercel.app/?from=USD&to=EUR) | Hackathon-winning currency converter: live ECB rates, hand-built responsive SVG chart, full keyboard accessibility, unit and component tests. | React · TypeScript · Vite · Vitest |

<sub>Also: [habit-tracker](https://github.com/AndJunes/habit-tracker), a desktop app in Python/Tkinter with a layered architecture checked by tests, plus ruff and mypy in CI.</sub>

## How I work

- **Tests from day one.** In Zipshield, mini-redis and habit-tracker, lint, type checks and tests run in CI on every push.
- **Security on the server.** Permissions are checked per endpoint, user text never becomes model instructions, and containers run as non-root.
- **Measure before choosing.** I pick models and designs with evals and benchmarks, and I write down known limitations instead of hiding them.

## Stack

**Core:** Python · FastAPI · SQLAlchemy · PostgreSQL · LLM agents (LangGraph, OpenRouter, RAG with pgvector)\
**Cloud & tooling:** Google Cloud (Cloud Run, Pub/Sub, Scheduler, Trace) · Docker · GitHub Actions · pytest · ruff · mypy\
**Frontend:** TypeScript · React · Angular\
**Also built with:** Next.js · Svelte · Go · Stellar / Soroban (Rust)

<sub>Off the clock: Pokémon cards.</sub>
