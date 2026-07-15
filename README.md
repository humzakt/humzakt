## Hey, I'm Humza

AI Engineer who ships GenAI solutions with enterprise clients. IEEE-published researcher. I build with AI-native tools and believe the best engineers will be the ones who learn to work *with* AI, not around it.

**Currently:** Software Engineer @ [Turing](https://www.turing.com) — building agentic automations and backend services on GCP.

**Previously:** Fine-tuned LLMs for **Apple, Meta, and Bytedance**. Delivered GenAI integrations for **Fortune 500 clients** at Royal Cyber. Published at **IEEE EMBC 2025** on explainable AI for medical imaging.

### What I work with

```
AI/ML        Agentic Systems · RAG · RLHF · LLM Fine-Tuning · PyTorch · LangChain
Backend      Python · FastAPI · PostgreSQL · Redis · Microservices
Cloud        GCP · AWS · Docker · CI/CD
Enterprise   Mulesoft · Salesforce · Apache Kafka · IBM ACE/MQ
AI Tools     Cursor · OpenAI Codex · Claude Code · GitHub Copilot
```

### Open Source

[![dev-starter-kit](https://img.shields.io/badge/dev--starter--kit-Clone_&_Ship-64ffda?style=for-the-badge&logo=github&logoColor=0a192f)](https://github.com/humzakt/dev-starter-kit)

Production-ready starter repo with **CI/CD workflows**, **test coverage enforcement**, **incident runbooks**, **pre-commit hooks**, and **AI coding tool configs** (Cursor, Claude Code, Codex, Copilot). Clone it, customize it, ship.

<details>
<summary>What's inside</summary>

- **3 GitHub Actions workflows** — PR checks with Ruff auto-fix, test coverage enforcement (posts PR comments with exact test guidance), merge readiness gates
- **Pre-commit hooks** — Ruff, syntax checks, YAML/JSON/TOML validation, private key detection, branch protection
- **Issue templates** — Bug reports, incident reports, infrastructure issues
- **Incident runbook** — Severity classification, triage checklists, diagnostic commands
- **AI tool instructions** — AGENTS.md, CLAUDE.md, .cursor/rules/, .claude/rules/, .github/copilot-instructions.md

</details>

[![psx-investor](https://img.shields.io/badge/psx--investor-Live_PSX_Buy_Planner-3fb950?style=for-the-badge&logo=github&logoColor=0a192f)](https://github.com/humzakt/psx-investor)

A local **FastAPI** tool for disciplined monthly investing on the **Pakistan Stock Exchange**. Enter an amount and it pulls **live PSX prices**, then computes exactly how many whole shares of each holding to buy to hit your target weights.

<details>
<summary>What's inside</summary>

- **Live price proxy** — async `httpx` fetch from the PSX data portal with an intraday -> end-of-day -> cached fallback chain and staleness flags
- **Buy-plan math** — whole-share flooring with an optional leftover-cash optimizer that nudges the book toward target weights
- **Purchase history & positions** — record actual fills, then track average cost, market value, and unrealized P/L at live prices
- **No-build frontend** — one self-contained HTML page (Tailwind CDN + vanilla JS) served by the Python backend
- **Privacy by design** — personal config and history stay in a git-ignored private repo; only the app and a generic example ship publicly
- **Tested & CI'd** — pytest unit tests, Ruff, and GitHub Actions

</details>

[![ai-writing-markers](https://img.shields.io/badge/ai--writing--markers-AI_Writing_Marker_Checker-64ffda?style=for-the-badge&logo=github&logoColor=0a192f)](https://github.com/humzakt/ai-writing-markers)

A source-backed catalogue of **AI-writing markers** with a zero-dependency Python checker. Built as a transparency and self-editing aid — explicitly **not** an AI detector, since detection is probabilistic and biased against non-native and academic writing.

<details>
<summary>What's inside</summary>

- **`markers.json`** — 6 categories, 87+ markers (overused vocab, formulaic transitions, cliché phrases, structural/rhetorical tells, punctuation/format, statistical), each with era tags and source ids
- **`check.py`** — zero-dependency CLI that scans any file/stdin, reporting marker hits by category with per-1000-word density
- **Real burstiness metric** — stdev/mean of sentence length; honest about not faking a perplexity score
- **Sourced** — distilled from Wikipedia's WikiProject AI Cleanup guide, 2026 detector research, and the peer-reviewed *Patterns* false-positive study
- **Open data** — MIT (code) / CC0 (dataset)

</details>

### Highlights

- Shipped GenAI solutions for Apple, Meta, Bytedance, and Fortune 500 clients
- Built AI agents that reduced client workloads by 60%
- Led a distributed team of 10+ engineers across 3 continents
- IEEE EMBC 2025 — [OptiGuard: Explainable Glaucoma Classification](https://ieeexplore.ieee.org/document/11253669)
- IBM Certified Cloud Automation Sales Consultant
- Mulesoft Certified Developer — Level 1
- Microsoft Certified: Power Platform Fundamentals (PL-900)

### Let's connect

[![Portfolio](https://img.shields.io/badge/Portfolio-humzakt.github.io-0a192f?style=flat-square&logo=google-chrome&logoColor=64ffda)](https://humzakt.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-humzakt-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/humzakt)
[![Email](https://img.shields.io/badge/Email-humzakhawartareen@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:humzakhawartareen@gmail.com)
[![IEEE](https://img.shields.io/badge/IEEE-OptiGuard-00629B?style=flat-square&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/11253669)

---

*Open to GTM Engineering, Forward Deployed, Solutions Engineering, AI, and PhD opportunities.*
