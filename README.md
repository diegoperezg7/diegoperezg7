<p align="center">
  <img src="assets/banner-v2.svg" alt="Diego Pérez, AI Engineer" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/diego-perez-garcia"><img src="https://img.shields.io/badge/LinkedIn-diego--perez--garcia-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:diegoperezgarc@gmail.com"><img src="https://img.shields.io/badge/Email-diegoperezgarc%40gmail.com-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Based%20in-Madrid-555?logo=googlemaps&logoColor=white" alt="Madrid">
  <img src="https://img.shields.io/badge/Open%20to-Europe%20%26%20Switzerland-2ea44f" alt="Open to Europe and Switzerland">
</p>

## 👋 About me

I'm an **AI Engineer** who designs, builds and ships AI-powered products end to end: requirements, architecture, LLM integration, evaluation and deployment.

- 💼 **Now:** AI Engineer at BeAI Now, owning client-facing AI applications: full-stack products, multi-agent LLM workflows, document AI and production delivery.
- 🛡️ **Before:** cybersecurity support (IndraMind). Higher Technician in Computer Network Systems Management (ASIR).
- 🧭 **How I build:** AI where it measurably helps, deterministic logic everywhere else, and real users as the bar. Not demos that only work in a notebook.

---

## 🚀 Featured projects

### <a href="https://github.com/diegoperezg7/rentia-case-study"><img src="https://raw.githubusercontent.com/diegoperezg7/rentia-case-study/main/assets/logo-light.png" height="40" alt="RentIA"></a> &nbsp;![In production](https://img.shields.io/badge/status-in%20production-16a34a)
**Rental management for Spanish landlords, running in production with real users.**

<a href="https://github.com/diegoperezg7/rentia-case-study"><img src="https://raw.githubusercontent.com/diegoperezg7/rentia-case-study/main/docs/screenshots/dashboard.png" alt="RentIA dashboard" width="100%"></a>

LAU contracts, IPC/IRAV rent updates, receipts, passed-on bills, expenses, IRPF (Modelo 100) and document OCR, with AI on local models. Self-hosted with CI/CD and used every month.

> **Why I built it:** the paperwork around a few rental properties is tedious and error-prone, and existing tools are either generic or send your documents to someone else's cloud. *Code is private; the case study covers product, architecture and decisions.*

`FastAPI` `React` `PostgreSQL` `Ollama` `OCR` `Docker`

<br>

### <img src="https://raw.githubusercontent.com/diegoperezg7/ragcompass/main/docs/assets/logo.svg" height="28" align="top" alt=""> [ragcompass](https://github.com/diegoperezg7/ragcompass)
**Point it at your documents and get a benchmarked RAG configuration.**

<a href="https://github.com/diegoperezg7/ragcompass"><img src="https://raw.githubusercontent.com/diegoperezg7/ragcompass/main/docs/assets/web-report-light.png" alt="ragcompass report" width="100%"></a>

<p>
  <a href="https://github.com/diegoperezg7/ragcompass"><img src="https://raw.githubusercontent.com/diegoperezg7/ragcompass/main/docs/assets/web-explorer-light.png" alt="Chunk explorer A/B" width="32%"></a>
  <a href="https://github.com/diegoperezg7/ragcompass"><img src="https://raw.githubusercontent.com/diegoperezg7/ragcompass/main/docs/assets/web-bench-light.png" alt="Retrieval benchmark" width="32%"></a>
  <a href="https://github.com/diegoperezg7/ragcompass"><img src="https://raw.githubusercontent.com/diegoperezg7/ragcompass/main/docs/assets/web-projection-light.png" alt="Embedding map" width="32%"></a>
</p>

Every recommendation comes with its reason and its evidence: parser per format (OCR and vision for scans), chunking measured on your own files, a retrieval benchmark (BM25, dense, hybrid) with confidence intervals, top-k, index size and cost, plus ready-to-paste LangChain, LlamaIndex and Haystack code. CLI, web app, API and MCP server.

> **Why:** "how should I configure this RAG?" is usually answered by guesswork.

`Python` `FastAPI` `React` `RAG` `MCP` `Embeddings`

<br>

<table>
<tr>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/diegoperezg7/mcp-guard/main/docs/assets/logo.svg" height="28" align="top" alt=""> [mcp-guard](https://github.com/diegoperezg7/mcp-guard)
**Security scanner for MCP servers and AI agents, built for CI.**

<a href="https://github.com/diegoperezg7/mcp-guard"><img src="https://raw.githubusercontent.com/diegoperezg7/mcp-guard/main/docs/assets/report.png" alt="mcp-guard report"></a>

24 rules for tool poisoning (hidden instructions, invisible Unicode, homoglyphs), tool shadowing, excessive permissions, leaked secrets and unsafe transports, plus an opt-in probe for indirect prompt injection. SARIF output for GitHub code scanning and a `--fail-on` gate. Hardened against hostile servers.

> **Why:** agents are only as safe as the tools they are given, and MCP makes those tools easy to add.

`TypeScript` `MCP` `AppSec` `SARIF`

</td>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/diegoperezg7/evalsmith-mcp/main/docs/assets/logo.svg" height="28" align="top" alt=""> [evalsmith-mcp](https://github.com/diegoperezg7/evalsmith-mcp)
**Evaluate agent tool calls, prompt changes and retrieval, and fail CI when quality drops.**

<a href="https://github.com/diegoperezg7/evalsmith-mcp"><img src="https://raw.githubusercontent.com/diegoperezg7/evalsmith-mcp/main/docs/assets/cli.png" alt="evalsmith CLI run"></a>

**MCP server and CLI** with deterministic metrics: recall@k, MRR and nDCG for retrieval, strict or lax tool-call matching for agents, and golden-set checks for prompts. JUnit and SARIF-friendly reports, no paid keys.

> **Why:** ragcompass recommends a configuration; evalsmith proves whether it holds up.

`TypeScript` `MCP` `Evaluation` `CI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/diegoperezg7/lora-vs-prompt/main/docs/assets/icon.svg" height="28" align="top" alt=""> [lora-vs-prompt](https://github.com/diegoperezg7/lora-vs-prompt)
**When is fine-tuning worth it? A LoRA on a small model vs prompting, measured.**

<a href="https://github.com/diegoperezg7/lora-vs-prompt"><img src="https://raw.githubusercontent.com/diegoperezg7/lora-vs-prompt/main/docs/figures/quality-vs-latency-light.png" alt="Exact match vs latency"></a>

Fully local study on Spanish rental-expense documents: a 1.5B model with LoRA doubles its own prompted accuracy (54.7% vs 26.7%), matches a model twice its size at 4x lower latency, and wins category classification by 19 to 35 points. Unseen layouts, a hard split with heavy OCR, paired bootstrap intervals, and an honest look at template memorisation.

> **Why:** "should we fine-tune?" deserves numbers, not opinions.

`Python` `MLX` `LoRA` `Qwen2.5` `Evaluation`

</td>
<td width="50%" valign="top">

### <a href="https://github.com/diegoperezg7/docbench"><img src="https://raw.githubusercontent.com/diegoperezg7/docbench/main/docs/assets/logo-light.svg" height="34" alt="docbench"></a>
**Open benchmark for document extraction in Spanish and English: OCR + LLM vs vision models.**

<a href="https://github.com/diegoperezg7/docbench"><img src="https://raw.githubusercontent.com/diegoperezg7/docbench/main/docs/assets/samples-degradations.png" alt="Synthetic documents and degradations"></a>

Synthetic, reproducible ES/EN dataset of invoices, utility bills, leases, rent receipts, store receipts and clearly fictitious IDs, from clean PDFs to bad scans and phone photos. Field-level accuracy, latency and memory for local pipelines: a vision model leads at 84.1% (91.1% in English), ahead of Tesseract + LLM (64.6%) and rule baselines, and text LLMs are shown to invent values on bad scans.

> **Why:** document AI is where most business automation starts, and it is rarely measured.

`Python` `OCR` `Vision LLM` `MLX` `Benchmark` `ES/EN`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/diegoperezg7/signoff/main/apps/web/app/icon.svg" height="28" align="top" alt=""> [Signoff](https://github.com/diegoperezg7/signoff)
**Prove what was agreed, built, verified and accepted, with governed AI agents.**

<a href="https://github.com/diegoperezg7/signoff"><img src="https://raw.githubusercontent.com/diegoperezg7/signoff/main/docs/images/11-agents.png" alt="Signoff agents panel"></a>

Software delivery assurance: from the client agreement to a signed-off acceptance, with requirements, change control, verification and evidence. **8 governed AI agents** with finite plans, allow-listed tools, resumable runs and human approval for every write.

> **Why:** most delivery disputes come from scope nobody can prove.

`FastAPI` `Next.js` `PostgreSQL` `Redis` `Agents`

</td>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/diegoperezg7/ai-learn/main/frontend/public/assets/ai-learn-mark-light.png" height="28" align="top" alt=""> [AI-Learn](https://github.com/diegoperezg7/ai-learn)
**The system I use to run my own AI engineering roadmap.**

<a href="https://github.com/diegoperezg7/ai-learn"><img src="https://raw.githubusercontent.com/diegoperezg7/ai-learn/main/docs/dashboard-dark.png" alt="AI-Learn dashboard"></a>

Scoped daily sessions, skill levels that only rise with evidence, spaced-repetition interview prep and a **local LLM coach** that reviews my work but never writes the solution.

> **Why:** progress is easy to fake; this one only counts evidence.

`FastAPI` `React` `Ollama` `SSO`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/diegoperezg7/server-monitor-AI/main/public/icon-192.png" height="28" align="top" alt=""> [server-monitor-AI](https://github.com/diegoperezg7/server-monitor-AI)
**Home-server dashboard with a security digest written by a local LLM.**

<a href="https://github.com/diegoperezg7/server-monitor-AI"><img src="https://raw.githubusercontent.com/diegoperezg7/server-monitor-AI/main/docs/screenshots/attack-map.png" alt="server-monitor attack map"></a>

Runs on the same home server as everything else: Netdata, Docker, CrowdSec with an attack map, Telegram alerts, auto-recovery and a **daily security digest written by a local LLM** that can only cite real events.

`Node.js` `CrowdSec` `Docker` `Ollama`

</td>
<td width="50%" valign="top">

### <img src="https://raw.githubusercontent.com/diegoperezg7/MyInvestIA/main/frontend/src/app/icon.svg" height="28" align="top" alt=""> [MyInvestIA](https://github.com/diegoperezg7/MyInvestIA)
**Investment dashboard: deterministic signals, LLM-written explanations.**

<a href="https://github.com/diegoperezg7/MyInvestIA"><img src="https://raw.githubusercontent.com/diegoperezg7/MyInvestIA/main/docs/screenshots/home.png" alt="MyInvestIA home"></a>

Multi-provider market data, quant scoring, sentiment and macro context, with **LLM-written explanations** on top of deterministic signals.

`FastAPI` `Next.js` `Quant` `LLM`

</td>
</tr>
</table>

---

## 🛠️ Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=python,ts,swift,fastapi,react,nextjs,nodejs,postgres,supabase,redis,docker,githubactions,linux,bash&perline=14" alt="Tech stack icons">
</p>

| | |
|---|---|
| 🤖 **AI engineering** | AI agents (tool use, multi-agent orchestration, human-in-the-loop approvals), LLM application architecture, evals and guardrails, MCP, LangChain / LangGraph, RAG and document AI (OCR, vision), local models with Ollama |
| 🧱 **Full-stack** | React, Next.js, FastAPI, Supabase / PostgreSQL, Docker |
| ⚙️ **Ops** | CI/CD (GitHub Actions, Azure DevOps), self-hosted runners, Caddy, Cloudflare Tunnel, Tailscale |
| 🗣️ **Languages** | Spanish (native) · English (C1) · French (learning) |

---

<p align="center">
  <b>🎯 Open to AI Engineer, LLM and forward-deployed roles</b>, especially product-building teams in Europe, including Switzerland.<br>
  <a href="https://www.linkedin.com/in/diego-perez-garcia">LinkedIn</a> · <a href="mailto:diegoperezgarc@gmail.com">diegoperezgarc@gmail.com</a>
</p>
