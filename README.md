## Mihály Galicz

Full-stack engineer — TypeScript and Python — building production systems with LLMs inside them.
Six years of shipping web applications; before that, seven years as an officer in the Hungarian
Defence Forces.

Based in Budapest (CET), working remotely. **Open to contract and full-time roles.**

### What I work on

- **LLM pipelines that have to be right.** Document extraction for invoices and receipts, bill
  processing, structured output from messy real-world input. Model output is untrusted input:
  validated against a schema, checked against the source, and measured on a labelled test set
  before it is allowed to act.
- **End-to-end products.** Schema, API, UI, integrations, Docker deployment — including payments
  and tax-authority (NAV) e-invoicing, where mistakes cost money.
- **Evaluating models and agents on numbers**, not vendor claims: benchmark harnesses, holdout
  sets, regression loops.

### Selected public work

| Project | What it shows |
| --- | --- |
| [**aidm**](https://github.com/Galicz555/aidm) | Voice-first AI game master: WebRTC → speech-to-text → LLM orchestrator → text-to-speech as separate services behind an LLM gateway that switches between local llama.cpp models and cloud APIs. Documented design decisions, a simulated-play regression loop scored by an LLM judge, sanitised rendering and path-contained vault access. Python, FastAPI, Svelte, Docker. |
| [**szamlak**](https://github.com/Galicz555/szamlak) | Local bill tracker: Gmail over IMAP → LLM extraction verified against the PDF text → payment matching over PSD2 open banking. Strict validation at every boundary, an extraction eval gated on zero *accepted-but-wrong* results, DKIM-checked mail admission. TypeScript, SQLite, Hono. |
| [**bestLocation**](https://github.com/Galicz555/bestLocation) | Ranks all 3,178 Hungarian settlements by a user-weighted mix of ~20 open-data metrics (schools, commute, prices, air quality, landscape). A Python data pipeline over a dozen public sources with per-source licence tracking, a framework-free MapLibre front end with rank-based scoring tests, and Docker. |

### Stack

TypeScript · Node.js · NestJS · Next.js · React · Vue · Svelte · Python · FastAPI ·
PostgreSQL · SQLite · Docker · llama.cpp · Claude API

### Contact

[LinkedIn](https://www.linkedin.com/in/mig555/)
