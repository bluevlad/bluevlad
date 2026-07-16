## AI-Driven Self-Evolving Operations Framework

> A heterogeneous service fleet that **inspects itself · repairs itself · learns from itself** — built on three pillars. **Self-Evolving Operations**: autonomous agents close the observe → inspect → repair → learn loop, and every fix becomes training data for the next cycle. **Domain AI Verticals**: one ingestion → RAG → digest engine, abstracted into domain packs, spawns new AI products per domain without touching the core. **Local-First AI Economics**: local models run first, cloud models handle complexity, and every LLM call is measured — so the whole loop stays economically sustainable.

<sub>Closed-loop autonomy · one engine, N domains · local-first LLM strategy · multi-corpus RAG · measured AI (LLMOps SSoT)</sub>

**AI/ML**&ensp;
![Claude API](https://img.shields.io/badge/Claude_API-191919?style=flat&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=googlegemini&logoColor=white)
![Gemma](https://img.shields.io/badge/Gemma_4-673AB7?style=flat&logo=google&logoColor=white)
![MLX](https://img.shields.io/badge/MLX-000000?style=flat&logo=apple&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat)
![RAG](https://img.shields.io/badge/RAG-555555?style=flat)

**Backend**&ensp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-437291?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)

**Frontend**&ensp;
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant_Design-0170FE?style=flat&logo=antdesign&logoColor=white)

**Infra**&ensp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![OrbStack](https://img.shields.io/badge/OrbStack-2A2A2A?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's_Encrypt-003A70?style=flat&logo=letsencrypt&logoColor=white)
![launchd](https://img.shields.io/badge/launchd-000000?style=flat&logo=apple&logoColor=white)

**Testing**&ensp;
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

---

### The Three Pillars

> 🎯 Services may pause; **capabilities compound**. Each pillar is a set of reusable capabilities, not a fixed service list — when a service retires, its engine is recombined into the next one.

<table align="center">
<tr>
<th align="center">① Self-Evolving Operations</th>
<th align="center">② Domain AI Verticals</th>
<th align="center">③ Local-First AI Economics</th>
</tr>
<tr>
<td valign="top">The fleet observes, inspects, and repairs itself. Every fix — agent-made or developer-made — ships with a structured root-cause footer that lands in a single prevention dataset. Each cycle trains the next.</td>
<td valign="top">One pipeline — multi-source ingestion → normalization → dedup → RAG index → LLM digest → delivery — abstracted into domain packs. Medical proved it; AI-learning curation is the second domain on the same engine.</td>
<td valign="top">Local models (Gemma 4 on MLX, qwen2.5-coder on Ollama) run first; Claude handles complex multi-layer work; Gemini covers free-tier RAG. LLMOps meters every call, so model choices are data, not habit.</td>
</tr>
<tr>
<td align="center"><sub>📡 InfraWatcher · 🔍 QA-Agent · 🤖 Auto-Tobe-Agent · 📊 QA Dashboard</sub></td>
<td align="center"><sub>🧬 AllergyInsight · 🎯 SkillRadar · 📰 NewsletterPlatform · DomainPack YAML</sub></td>
<td align="center"><sub>💻 Ollama + MLX · 🧠 Claude API · 🔍 Gemini · 📈 LLMOps</sub></td>
</tr>
</table>

---

### Pillar ① — The Operations Loop

> 🎯 **Operator's view** — every box runs on its own schedule. The operator sets thresholds and approves merges; **the loop closes itself**.

<table align="center">
<tr><th colspan="3" align="center">Observe → Inspect → Repair</th></tr>
<tr>
<td align="center">📡 <b>InfraWatcher</b><br/><sub>Real-time Docker telemetry<br/>WebSocket push · auto-recovery<br/>single pane for the whole fleet</sub></td>
<td align="center">🔍 <b>QA-Agent</b><br/><sub>Nightly Playwright E2E/API<br/>origin-tagged findings<br/>Git-verified GitHub Issues</sub></td>
<td align="center">🤖 <b>Auto-Tobe-Agent</b><br/><sub>Dual-engine fix + to-be enhancement<br/>Claude + local Ollama<br/>auto-PR with rationale</sub></td>
</tr>
<tr><th colspan="3" align="center">⬇ &nbsp;&nbsp;&nbsp; Record → Measure → Learn &nbsp;&nbsp;&nbsp; ⬇</th></tr>
<tr>
<td align="center">📊 <b>QA Dashboard</b><br/><sub>Fix-result aggregation<br/>agent + developer fixes converge<br/>into one prevention dataset</sub></td>
<td align="center">📈 <b>LLMOps</b><br/><sub>Every local-LLM call metered<br/>fire-and-forget SDK<br/>per-model usage / latency / ROI lens</sub></td>
<td align="center">🧾 <b>Fix Compliance Standard</b><br/><sub>Structured commit footers<br/>Discovery-Method · Root-Cause<br/>Recurrence · Prevention</sub></td>
</tr>
<tr><td colspan="3" align="center">↺ &nbsp;<b>feeds back into Operate</b> — every merged PR and every recorded fix refines the next cycle</td></tr>
</table>

#### 🔍 QA-Agent — *Inspects every service nightly*

A remote QA machine runs Playwright E2E/API across the active fleet at the late-night slot. Findings are **Git-verified, origin-tagged** (regression / new-feature / external-tech adoption) and committed to GitHub Issues with the `qa-agent` label. RAG quality is evaluated on chatbot endpoints; verified fixes are auto-closed.

> 🎯 **Operator sees** → labeled Issues with reproduction trace. **Decides** → which to fix this cycle.

#### 🤖 Auto-Tobe-Agent — *Fixes and enhances autonomously*

**Dual-engine** — Claude Code CLI for complex multi-layer fixes; an Ollama ReAct loop (qwen2.5-coder) for routine fixes at zero cost, with auto-fallback to Claude on local-engine failure. Output is a PR with a fix-compliance footer (Discovery-Method · Root-Cause · Recurrence · Prevention) — the same footer feeds the QA Dashboard's prevention dataset, so **every fix becomes training data for the next cycle**.

> 🎯 **Operator sees** → PR with rationale + risk note. **Decides** → merge.

#### 📡 InfraWatcher — *Single pane for the whole fleet*

Real-time Docker telemetry over WebSocket — CPU / memory / health-check / restart counts across the multi-subdomain fleet. **Auto-recovery on health-check failure**, time-series analytics for rolling-deploy regression detection, and a container-action surface (start / stop / restart / logs) gated by Google-OAuth admin.

> 🎯 **Operator sees** → live state of every container, anywhere. **Decides** → manual intervention only when auto-recovery exhausts retries.

#### 📊 QA Dashboard — *The loop's memory*

Aggregates fix results from **two sources into one schema**: the QA/Auto-Tobe agent pipeline posts directly; developer `fix:` commits are parsed by GitHub Actions from their structured footers. Both land in a single table (`fix_source='agent' | 'developer'`) — the single source of truth for the prevention-model dataset.

> 🎯 **Operator sees** → recurrence patterns and root-cause distribution. **Decides** → which prevention rule to promote into standards.

#### 📝 Self-Documenting Operations — *the fleet writes its own history*

AllergyInsight's ingestion and RAG state is snapshotted automatically on a two-track schedule: a detailed daily status report (read-only container exec → private repo commit) and a whitelist-filtered weekly academic summary published to the public service wiki. Numbers come from the same helpers the dashboard uses — the report and the UI can never disagree.

> 🎯 **Operator sees** → drift and anomalies in collection/RAG health, without asking. **Decides** → nothing, unless the trendline demands it.

#### 📈 LLMOps — *Metering the AI itself*

Every local-LLM consumer in the fleet emits a per-run report through a fire-and-forget SDK (Python + TypeScript, stdlib-only, short timeout, no retry) into a single PostgreSQL store, plus model-inventory pollers for Ollama and MLX. **Design constraint**: LLMOps downtime never propagates to producers. A sunset clause is baked in — if ROI is insufficient, it folds back into InfraWatcher.

> 🎯 **Operator sees** → service ↔ model usage matrix. **Decides** → which model serves which workload.

#### 🧱 Shared Capability Libraries — *where compounding becomes code*

Proven patterns are extracted from services into shared libraries, then re-applied fleet-wide:

| Library | Extracted from | Provides |
|---------|----------------|----------|
| `shared/ingestion` | AllergyInsight's cursor-delta drug ingest | incremental cursors · exponential backoff · near-dup detection · upsert / retention / run history |
| `shared/security` | SkillRadar hardening | SSRF defense — public-URL assertion + redirect re-validation guards for requests/httpx |
| `shared/llm_eval` | vertical digest pipelines | deterministic output checks + injectable LLM-as-judge harness (stdlib-only) |

Fleet-wide supply-chain posture: weekly Dependabot across pip / npm / docker / actions + PyPA `pip-audit` on every service.

---

### Pillar ② — Vertical Engine: One Engine, N Domains

> 🎯 The same collection-to-delivery pipeline is **abstracted into domain packs** (DomainPack YAML + Source Connector Registry + pack linter) — a new domain attaches via configuration and prompts, with zero core changes.

| | 🧬 **AllergyInsight** — Medical <sub>(Vertical #1)</sub> | 🎯 **SkillRadar** — AI Learning <sub>(Vertical #2)</sub> |
|---|---|---|
| **Sources** | PubMed · Semantic Scholar · Europe PMC · openFDA · MFDS · community Q&A corpus · news feeds | K-MOOC · KDT bootcamps · seminars & conferences · AI-policy news |
| **Knowledge store** | canonical store + per-allergen ChromaDB, three-stage dedup | pgvector corpus on the shared ingestion framework — natural-key corrective upsert (app + DB constraint), watermark-based incremental collection, weekly retention |
| **Surfaces** | anonymous public portal (MAST · symptoms · RAG chatbot · drug groups · clinical images) + daily clinical briefing | personalized daily digest (web + email) for job seekers and senior professionals reskilling into AI |
| **LLM strategy** | Gemini 2.5 Flash primary · local Gemma 4 12B fallback | local-first summarize / classify digest cascade |
| **Guardrails** | diagnosis-disallowed phrasing · citation + license on every response · emergency-keyword bypass | SSRF-guarded fetchers (internal-network / metadata / loopback egress blocked) · fail-fast production secrets · source-weighted relevance scoring before any LLM call |

> **Engine lineage** — SkillRadar was built by **recombining proven parts of the fleet**: StandUp's ingestion + local-LLM digest cascade and HopenVision's full-stack web/auth architecture. Both parent services are on hold as products; their engines live on. The same thesis was stress-tested in reverse on NewsletterPlatform: the TechBriefing tenant pivoted its entire collection domain (Java/React ecosystem → AI/LLM ecosystem — model repos, research-lab feeds, AI CVE keywords) through **configuration alone, zero core changes**. Services may pause — capabilities compound.

#### 📰 NewsletterPlatform — *Shared delivery, hardened by real incidents*

The delivery layer that productizes vertical outputs into email channels. Multi-tenant on a shared core with a `BaseTenant` abstraction and API-driven collection (no cross-tenant DB access). Hardening came from production incidents, not speculation: stale-cache send guard with an admin-only alert mode, SQL-layer article dedup, multi-slot sends off a single collection cache, and subscription-abuse defenses (Turnstile · rate limits · honeypot · bot-pattern detection).

> 🎯 **Operator sees** → stale-cache alerts, per-slot statistics, abuse telemetry. **Decides** → which tenant to onboard next.

---

### Pillar ③ — Local-First AI Economics

#### Dual-Engine — Claude + Local LLM

Auto-Tobe-Agent's two engines map to task complexity, with automatic fallback.

| | Engine A — Claude | Engine B — Local LLM |
|---|---|---|
| **Engine** | Claude Code CLI | Ollama ReAct loop (qwen2.5-coder) |
| **Strength** | Complex multi-layer fixes · long context | Zero-cost · offline · fast for routine fixes |
| **Fallback** | — | Auto-fallback to Claude on failure |

#### Local Model Pool — deliberate, measured swaps

The resident local model is **Gemma 4 12B on MLX** (a larger on-demand variant is kept for heavy jobs), alongside qwen2.5-coder and small llama models on Ollama. The pool has been swapped twice — Qwen 2.5 → EXAONE 3.5 → Gemma 4 — each time for documented reasons (license terms, multilingual quality, ecosystem). Because every consumer speaks an OpenAI-compatible interface, a model swap is an environment-variable change, not a redeploy — and LLMOps data validates the swap afterwards.

#### Document RAG — Free vs Paid

The same RAG pipeline (ingestion → chunking → embedding → vector DB → hybrid search → LLM synthesis) supports two stacks, selectable per use case.

| | **Free Tier — Gemini** | **Paid Tier — OpenAI + Claude** |
|---|---|---|
| **Repo** | [Google-Gemini-Ai-PipeLine](https://github.com/bluevlad/Google-Gemini-Ai-PipeLine) | DocumetsToAiPipeLine *(private)* |
| **Embedding** | Gemini `text-embedding-004` | OpenAI `text-embedding-3-large` |
| **LLM** | Gemini 2.x Flash | Anthropic Claude |
| **Vector DB** | ChromaDB | ChromaDB → pgvector |
| **When to Pick** | Fast validation · offline · small | High-precision recall · long context |

---

### Service Fleet Topology — 5 Layers

> 🎯 **What the pillars run on** — the active fleet behind `*.unmong.com`, all containerized on a single operations host.

<table align="center">
<tr><th colspan="4" align="left">Layer 1 — User-Facing AI Verticals</th></tr>
<tr>
<td align="center" colspan="2">🧬 <b>AllergyInsight</b><br/><sub>allergyinsight.unmong.com<br/>B2C anonymous medical-info portal<br/>RAG chatbot + daily clinical briefing</sub></td>
<td align="center" colspan="2">🎯 <b>SkillRadar</b><br/><sub>skillradar.unmong.com<br/>AI-learning curation for reskilling<br/>daily digest · web + email</sub></td>
</tr>

<tr><th colspan="4" align="left">Layer 2 — Shared Platform Services</th></tr>
<tr>
<td align="center" colspan="2">📰 <b>NewsletterPlatform</b><br/><sub>newsletter.unmong.com<br/>multi-tenant delivery core<br/>incident-hardened send guards</sub></td>
<td align="center" colspan="2">📊 <b>QA Dashboard</b><br/><sub>qaagent.unmong.com<br/>fix-result aggregator<br/>prevention-model dataset</sub></td>
</tr>

<tr><th colspan="4" align="left">Layer 3 — Operations & Gateway</th></tr>
<tr>
<td align="center">📡 <b>InfraWatcher</b><br/><sub>infrawatcher.unmong.com<br/>real-time Docker telemetry<br/>+ container actions</sub></td>
<td align="center">🪵 <b>LogAnalyzer</b><br/><sub>loganalyzer.unmong.com<br/>error-pattern source<br/>for the ops loop</sub></td>
<td align="center">📈 <b>LLMOps</b><br/><sub>llmops.unmong.com<br/>local-LLM usage SSoT<br/>fire-and-forget ingest</sub></td>
<td align="center">🔐 <b>Nginx Gateway</b><br/><sub>www.unmong.com<br/>Let's Encrypt wildcard SSL<br/>multi-subdomain routing<br/>+ Docker / launchd schedules</sub></td>
</tr>

<tr><th colspan="4" align="left">Layer 4 — Autonomous Agents</th></tr>
<tr>
<td align="center" colspan="2">🔍 <b>QA-Agent</b> <i>(Inspector)</i><br/><sub>Playwright E2E/API · multi-stage nightly<br/>origin-tagged · Git-verified Issues</sub></td>
<td align="center" colspan="2">🤖 <b>Auto-Tobe-Agent</b> <i>(Builder)</i><br/><sub>dual-engine fix + to-be<br/>auto-PR + rolling deploy</sub></td>
</tr>

<tr><th colspan="4" align="left">Layer 5 — AI Foundation</th></tr>
<tr>
<td align="center">🧠 <b>Claude API</b><br/><sub>complex multi-layer fixes<br/>long-context work</sub></td>
<td align="center">💻 <b>Ollama + MLX (Local)</b><br/><sub>Gemma 4 12B resident<br/>qwen2.5-coder · zero-cost</sub></td>
<td align="center">🔍 <b>Gemini</b><br/><sub>2.5 Flash<br/>free-tier RAG</sub></td>
<td align="center">🗂️ <b>ChromaDB / pgvector</b><br/><sub>per-allergen vector store<br/>+ vertical corpora</sub></td>
</tr>
</table>

<sub>⏸️ **On hold** — HopenVision · StandUp (engines inherited by SkillRadar) · CompanyAnalyzer · Academy · OpsConsole · ImageInsight · ImagesToAiPipeLine &nbsp;|&nbsp; 🗄️ **Archived** — EduFit · medium-digest-agent</sub>

> 📐 **Live interactive view** → [unmong.com/architecture.html](https://www.unmong.com/architecture.html) — full layered flow with hyperlinks to each service. The table above is the README snapshot; **unmong.com is canonical**.

---

### Selected Projects

> Detailed STAR+ sheets live under `portfolio/projects/` in [Claude-Opus-bluevlad](https://github.com/bluevlad/Claude-Opus-bluevlad). The table below is the architecture map.

| Project | Stack | Description |
|---------|-------|-------------|
| [Auto-Tobe-Agent](https://github.com/bluevlad/Auto-Tobe-Agent) | TypeScript, Claude Code CLI, Ollama | Dual-engine autonomous agent — monitor, repair, deploy |
| AllergyInsight <sub>*(private)*</sub> | FastAPI, React, ChromaDB, Gemini + Gemma 4 | Medical vertical #1 — anonymous portal · RAG chatbot · daily clinical briefing · DomainPack framework |
| SkillRadar <sub>*(private)*</sub> | FastAPI, React, PostgreSQL + pgvector | AI-learning vertical #2 — daily curation digest for reskilling, built on inherited fleet engines |
| [InfraWatcher](https://github.com/bluevlad/InfraWatcher) | FastAPI, React, WebSocket | Real-time Docker container observability + control |
| [QA-Dashboard](https://github.com/bluevlad/QA-Dashboard) | FastAPI, React, PostgreSQL | Fix-result aggregator — agent + developer fixes in one prevention dataset |
| LLMOps <sub>*(private)*</sub> | FastAPI, React, PostgreSQL, Google OAuth | Local-LLM usage SSoT — fire-and-forget SDK · model-inventory pollers (Ollama + MLX) |
| [NewsLetterPlatform](https://github.com/bluevlad/NewsLetterPlatform) | Python, multi-tenant core | Shared delivery layer — `BaseTenant` abstraction · incident-hardened send guards |
| [LogAnalyzer](https://github.com/bluevlad/LogAnalyzer) | FastAPI, React, PostgreSQL | Docker log analysis — error-pattern source for the ops loop |
| [StandUp](https://github.com/bluevlad/StandUp) <sub>⏸️</sub> | FastAPI, PostgreSQL + pgvector, Ollama | Ops-insight synthesis — 3-stage local LLM cascade + self-referencing RAG · engine inherited by SkillRadar |
| [HopenVision](https://github.com/bluevlad/hopenvision) <sub>⏸️</sub> | Spring Boot 3.2, JPA, React 19, PostgreSQL | Learning-operations platform — commerce / LMS / exam scoring · web-auth architecture inherited by SkillRadar |
| ImagesToAiPipeLine <sub>*(private)* ⏸️</sub> | FastAPI, rembg, OWL-ViT v2, React + Vite | Local vision pipeline — BG-removal crop + text & image-guided detection |
