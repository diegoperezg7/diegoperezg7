# Hi, I'm Diego

**AI Engineer** based in Madrid. I design, build and ship AI-powered products end to end: requirements, architecture, LLM integration, evaluation and deployment.

Currently AI Engineer at BeAI Now, owning client-facing AI applications: full-stack products, multi-agent LLM workflows, RAG and document pipelines, and production delivery. Previously cybersecurity support (IndraMind). Higher Technician in Computer Network Systems Management (ASIR).

I care about systems that are reliable, explainable and useful, not demos that only work in a notebook. The projects below follow one thread: put AI where it measurably helps, keep the rest deterministic, and ship it to real users.

---

## Featured

### [RentIA](https://github.com/diegoperezg7/rentia-case-study) · in production

<a href="https://github.com/diegoperezg7/rentia-case-study"><img src="https://raw.githubusercontent.com/diegoperezg7/rentia-case-study/main/docs/screenshots/dashboard.png" alt="RentIA dashboard" width="100%"></a>

Rental management for Spanish landlords: contracts under the LAU, IPC/IRAV rent updates, receipts, expenses, IRPF (Modelo 100) and document OCR, with AI that runs on local models. Self-hosted, deployed with CI/CD and used every month by real landlords. **Why:** the paperwork around a few rental properties is tedious and error-prone, and the tools that exist are either generic or send your documents to someone else's cloud. Code is private; the case study covers product, architecture and engineering decisions.

### [Signoff](https://github.com/diegoperezg7/signoff)

<a href="https://github.com/diegoperezg7/signoff"><img src="https://raw.githubusercontent.com/diegoperezg7/signoff/main/docs/images/11-agents.png" alt="Signoff agents panel" width="100%"></a>

Software delivery assurance: trace a client agreement through requirements, change control, verification and evidence to a signed-off acceptance. Eight contextual AI agents with finite plans, allow-listed tools, resumable runs and human approval for every write. FastAPI + Next.js, runs in mock mode with no keys. **Why:** most delivery disputes come from scope nobody can prove; agents are useful here only if they are governed.

### RAG and agent tooling

| | |
|---|---|
| **[ragcompass](https://github.com/diegoperezg7/ragcompass)** | Point it at a document or a folder and get a reasoned RAG configuration: parser per format (including OCR and vision for scans and images), chunking strategy, size and overlap measured on your own files, vectors, index size, cost, top-k and hybrid search. CLI, API and web app. |
| **[evalsmith-mcp](https://github.com/diegoperezg7/evalsmith-mcp)** | MCP server and CLI that evaluate RAG retrieval (recall@k, MRR, nDCG), agent tool calls and prompt regressions, and fail CI when quality drops. No paid keys. |

**Why:** "how should I configure this RAG?" is usually answered by guesswork. The pair turns it into a loop: ragcompass recommends a configuration, evalsmith measures whether it holds up.

### Also built

| | |
|---|---|
| **[AI-Learn](https://github.com/diegoperezg7/ai-learn)** | The system I use to run my own AI engineering roadmap: scoped daily sessions, skill levels that only rise with evidence, spaced-repetition interview prep and a local LLM coach that reviews my work but never writes the solution. FastAPI + React, deployed behind SSO on my home server. |
| **[server-monitor-AI](https://github.com/diegoperezg7/server-monitor-AI)** | Dashboard for that home server: Netdata metrics, Docker, CrowdSec with an attack map, Telegram alerts, auto-recovery, and a daily security digest written by a local LLM that can only cite real events. |
| **[MyInvestIA](https://github.com/diegoperezg7/MyInvestIA)** | Investment intelligence dashboard: multi-provider market data, quant scoring, sentiment and macro context, with LLM-written explanations. FastAPI + Next.js. |
| **[Veyra](https://github.com/diegoperezg7/Veyra)** | On-device health dashboard for iPhone and Apple Watch: sleep, recovery and strain computed locally from HealthKit, with confidence on every score. SwiftUI. |

---

## Stack

| | |
|---|---|
| **Languages** | Python, TypeScript, Swift, SQL, Bash |
| **AI / LLM** | RAG, evaluation, MCP, multi-agent workflows, LangChain / LangGraph, Ollama and local models |
| **Full-stack** | React, Next.js, FastAPI, Supabase / PostgreSQL, Docker |
| **Ops** | CI/CD (GitHub Actions, Azure DevOps), self-hosted runners, Caddy, Cloudflare Tunnel, Tailscale |

---

## Open to

AI Engineer / LLM / forward-deployed roles, especially product-building teams in Europe (including Switzerland). English C1 · Spanish native · French basic (learning).

[LinkedIn](https://www.linkedin.com/in/diego-perez-garcia) · diegoperezgarc@gmail.com
