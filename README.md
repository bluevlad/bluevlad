## AI-Driven Self-Evolving Operations Framework

> A heterogeneous service fleet that **inspects itself · repairs itself · learns from itself** — built on three pillars. **Self-Evolving Operations**: autonomous agents close the observe → inspect → repair → learn loop, and every fix becomes training data for the next cycle. **Domain AI Verticals**: one ingestion → RAG → digest engine, abstracted into domain packs, spawns new AI products per domain without touching the core — and is now growing from retrieval-only answers into **tool-calling agents** with validated outputs. **Local-First AI Economics**: local models run first, cloud models handle complexity, and every LLM call is measured and evaluated — so model choices are data, not habit.

<sub>Closed-loop autonomy · one engine, N domains · tool-calling over RAG · local-first LLM strategy · multi-corpus RAG · measured AI (LLMOps SSoT)</sub>

**AI/ML**&ensp;
![Claude API](https://img.shields.io/badge/Claude_API-191919?style=flat&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=googlegemini&logoColor=white)
![Gemma](https://img.shields.io/badge/Gemma_4-673AB7?style=flat&logo=google&logoColor=white)
![MLX](https://img.shields.io/badge/MLX-000000?style=flat&logo=apple&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat)
![RAG](https://img.shields.io/badge/RAG-555555?style=flat)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B0?style=flat)

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
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat&logo=pwa&logoColor=white)

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
<td valign="top">One pipeline — multi-source ingestion → normalization → dedup → RAG index → LLM digest → delivery — abstracted into domain packs. Medical proved it; AI-learning curation and document intelligence run on the same engine. The medical vertical has since moved from free-generation RAG to a <b>tool-calling agent with a response validator</b>.</td>
<td valign="top">Local models (Gemma 4 on MLX, qwen2.5-coder on Ollama) run first; Claude handles complex multi-layer work; Gemini covers free-tier RAG and native function calling. LLMOps meters every call and <b>gates every model swap with an eval run</b>, so model choices are data, not habit.</td>
</tr>
<tr>
<td align="center"><sub>📡 InfraWatcher · 🔍 QA-Agent · 🤖 Auto-Tobe-Agent · 📊 QA Dashboard</sub></td>
<td align="center"><sub>🧬 AllergyInsight · 🎯 SkillRadar · 🗂️ DocPipeline · 📰 NewsletterPlatform · DomainPack YAML</sub></td>
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
<td align="center">📈 <b>LLMOps</b><br/><sub>Every local-LLM call metered<br/>fire-and-forget SDK<br/>eval-gated model swaps</sub></td>
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

AllergyInsight's ingestion and RAG state is snapshotted automatically on a two-track schedule, driven by a GitHub Actions **self-hosted runner** on the operations host: a detailed daily status report (read-only container exec → private repo commit) and a whitelist-filtered weekly academic summary rendered to a **MkDocs** wiki behind the service gateway. Numbers come from the same helpers the dashboard uses — the report and the UI can never disagree.

> 🎯 **Operator sees** → drift and anomalies in collection/RAG health, without asking. **Decides** → nothing, unless the trendline demands it.

#### 📈 LLMOps — *Metering and evaluating the AI itself*

Every local-LLM consumer in the fleet emits a per-run report through a fire-and-forget SDK (Python + TypeScript, stdlib-only, short timeout, no retry) into a single PostgreSQL store, plus model-inventory pollers for Ollama and MLX. A **batch-run reporting standard** fixes the metric key vocabulary (crawl/ingest, corpus growth, golden-set growth, review outcomes) so trends aggregate across consumers, push-only — LLMOps never queries a producer's store. On top sits an **Eval Profile**: deterministic checks (accuracy · macro-F1 · set-F1 · schema conformance), an injectable LLM-as-judge rubric, and ops metrics (latency · tokens · cost · win-rate), with pass/fail `gates:` declared in a prompt-set YAML. The same harness is offered to external systems as a managed, masked-data evaluation track. **Design constraint**: LLMOps downtime never propagates to producers.

> 🎯 **Operator sees** → service ↔ model usage matrix + gate results per candidate model. **Decides** → which model serves which workload.

#### 🧱 Shared Capability Libraries — *where compounding becomes code*

Proven patterns are extracted from services into shared libraries, then re-applied fleet-wide:

| Library | Extracted from | Provides |
|---------|----------------|----------|
| `shared/ingestion` | AllergyInsight's cursor-delta drug ingest | incremental cursors · exponential backoff · near-dup detection · upsert / retention / run history |
| `shared/security` | SkillRadar hardening | SSRF defense — public-URL assertion + redirect re-validation guards for requests/httpx |
| `shared/llm_eval` | vertical digest pipelines | deterministic output checks + injectable LLM-as-judge harness (stdlib-only) — the kernel behind the LLMOps Eval Profile |

Fleet-wide supply-chain posture: weekly Dependabot across pip / npm / docker / actions + PyPA `pip-audit` on every service.

---

### Pillar ② — Vertical Engine: One Engine, N Domains

> 🎯 The same collection-to-delivery pipeline is **abstracted into domain packs** (DomainPack YAML + Source Connector Registry + pack linter) — a new domain attaches via configuration and prompts, with zero core changes.

| | 🧬 **AllergyInsight** — Medical <sub>(Vertical #1)</sub> | 🎯 **SkillRadar** — AI Learning <sub>(Vertical #2)</sub> | 🗂️ **DocPipeline** — Document Intelligence <sub>(Vertical #3)</sub> |
|---|---|---|---|
| **Sources** | PubMed · Semantic Scholar · Europe PMC · open-license drug registries (openFDA · MFDS · DailyMed · DSLD · RxNorm) · community Q&A corpus · news feeds | K-MOOC · KDT bootcamps · seminars & conferences · AI-policy news | user-uploaded document batches — PDF · scanned images · HWP / HWPX (Korean office format) |
| **Knowledge store** | canonical store + ChromaDB paper index with nightly refresh, three-stage dedup; SAVEPOINT-isolated incremental drug ingest on the shared framework | pgvector corpus on the shared ingestion framework — natural-key corrective upsert (app + DB constraint), watermark-based incremental collection, weekly retention | dedicated PostgreSQL + pgvector (ChromaDB in dev) · pluggable embedding (local `bge-m3`-family on Apple MPS or OpenAI) · SQLAlchemy + Alembic |
| **Surfaces** | anonymous public portal (MAST · symptoms · RAG chatbot · drug groups · clinical images) · daily clinical briefing with staleness-aware spotlight rotation · **tool-calling drug-agent API** · **device-paired PWA surface** · **consent-scoped shareable profile tokens** | personalized daily digest (web + email) for job seekers and senior professionals reskilling into AI · admin SPA on a gateway sub-path | Google-OAuth analysis requests → queued worker → LLM overview · pipeline flow-diagram UI · admin history/aggregate views · S2S parse API consumed by other fleet services |
| **LLM strategy** | Gemini 2.5 Flash primary (native function calling) · local Gemma 4 12B on MLX as tool-use fallback · keyword fallback last | local-first summarize / classify digest cascade (Gemma 4 12B on MLX) | local Gemma 4 12B on MLX for overview generation · cloud switch kept as a config flag, not a dependency |
| **Guardrails** | citation-required / banned-phrase response validator with forced regeneration · no free-generation fallback (refuse instead) · diagnosis-disallowed phrasing · emergency-keyword bypass · derived-data minimization + revocable opaque session tokens · rule-engine-only matching paths (no LLM) | SSRF-guarded fetchers (internal-network / metadata / loopback egress blocked) · fail-fast production secrets · source-weighted relevance scoring before any LLM call | dual-engine OCR (PaddleOCR + Tesseract) for scanned input · gateway upload limits synced to app spec · sensitive client material kept out of the public tree |

#### 🧬 From RAG to Tool-Calling — *the medical vertical's agent layer*

Free-generation RAG answers were replaced by a **tool-calling agent**: a `ToolRegistry` exposes OpenAI/Ollama-compatible tool schemas (symptom lookup · drug-class mapping · ingredient detail · cross-check · route-burden calculation · evidence fetch · guideline snippet) with name-based dispatch; the system prompt injects citation-required, no-prescription, uncertainty-hedging, auto-cross-check and disclaimer disciplines; a **response validator** enforces PMID citations and banned phrases with bounded regeneration; every tool-call sequence and validation outcome is audit-logged. The LLM adapter is a single OpenAI-compatible client — Gemini native function calling primary, local MLX/Ollama tool-use fallback — and multi-symptom queries deliberately induce the cross-check tool.

New surfaces follow the same discipline. A **PWA** (manifest + service worker, app-shell caching only, API paths excluded from cache) runs on a **device auth plane separated from user JWT**: one-time pairing code → hashed device token → short-lived opaque DB session header with instant revocation and rate limits; the matching path is a rule engine with no real-time LLM, and payloads carry derived `avoid` / `caution` classes only. User-shareable profiles are **consent-gated, rotatable, revocable tokens** served over unauthenticated public endpoints (revoked → 404), with bilingual notes and no raw identifiers in the payload. Community Q&A ingestion (search-API scoped to question text + timestamp) feeds classification, seasonality trends and RAG-grounded answer drafts into a **human-in-the-loop review UI** — unanswerable questions become new collection triggers, closing the corpus flywheel.

> **Engine lineage** — SkillRadar was built by **recombining proven parts of the fleet**: StandUp's ingestion + local-LLM digest cascade and HopenVision's full-stack web/auth architecture. Both parent services are on hold as products; their engines live on. DocPipeline reuses the document-RAG kernel first proven in the Gemini pipeline repo, now local-first. The same thesis was stress-tested in reverse on NewsletterPlatform: the TechBriefing tenant pivoted its entire collection domain (Java/React ecosystem → AI/LLM ecosystem — model repos, research-lab feeds, AI CVE keywords) through **configuration alone, zero core changes**. Services may pause — capabilities compound.

#### 📰 NewsletterPlatform — *Shared delivery, hardened by real incidents*

The delivery layer that productizes vertical outputs into email channels. Multi-tenant on a shared core with a `BaseTenant` abstraction and API-driven collection (no cross-tenant DB access). Hardening came from production incidents, not speculation: stale-cache send guard with an admin-only alert mode, SQL-layer article dedup, multi-slot sends off a single collection cache, subscription-abuse defenses (Turnstile · rate limits · honeypot · bot-pattern detection), stateless signed admin sessions, rate-limited token endpoints, proxy-aware client-IP resolution, and origin-enforced CSRF on admin writes.

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

The resident local model is **Gemma 4 12B on MLX** (a larger on-demand variant is kept for heavy jobs), alongside qwen2.5-coder on Ollama. The pool has been swapped across generations — Qwen 2.5 → EXAONE 3.5 → Gemma 4 — each time for documented reasons (license terms, multilingual quality, ecosystem), and the latest summarization-consumer swap (small llama → Gemma 4) was **gated by an LLMOps label-match eval** before rollout. Because every consumer speaks an OpenAI-compatible interface, a model swap is an environment-variable change, not a redeploy. Operational lessons are written down as standards: Gemma 4 is a *thinking* model, so short structured outputs must disable reasoning (`reasoning_effort: "none"`) or the budget is consumed before any content is emitted; and context-length caps apply to the GGUF runner only — MLX runners load the model's native context, so memory must be planned accordingly.

#### Document RAG — Free vs Local-First Production

The same RAG pipeline (ingestion → chunking → embedding → vector DB → hybrid search → LLM synthesis) runs on two stacks, selectable per use case.

| | **Free Tier — Gemini** | **Local-First Production — DocPipeline** |
|---|---|---|
| **Repo** | [Google-Gemini-Ai-PipeLine](https://github.com/bluevlad/Google-Gemini-Ai-PipeLine) | DocumetsToAiPipeLine *(private)* |
| **Embedding** | Gemini `text-embedding-004` | local `bge-m3`-family on Apple MPS (OpenAI pluggable) |
| **LLM** | Gemini 2.x Flash | Gemma 4 12B on MLX (cloud switch = config flag) |
| **Vector DB** | ChromaDB | ChromaDB (dev) → pgvector (prod, dedicated container) |
| **Input** | text documents | PDF · scanned images (PaddleOCR + Tesseract) · HWP / HWPX |
| **When to Pick** | Fast validation · offline · small | Korean office documents · private corpora · zero per-token cost |

---

### Service Fleet Topology — 5 Layers

> 🎯 **What the pillars run on** — the active fleet behind `*.unmong.com`, all containerized on a single operations host.

<table align="center">
<tr><th colspan="4" align="left">Layer 1 — User-Facing AI Verticals</th></tr>
<tr>
<td align="center" colspan="2">🧬 <b>AllergyInsight</b><br/><sub>allergyinsight.unmong.com<br/>B2C anonymous medical-info portal<br/>tool-calling agent · RAG chatbot · daily briefing · PWA</sub></td>
<td align="center">🎯 <b>SkillRadar</b><br/><sub>skillradar.unmong.com<br/>AI-learning curation for reskilling<br/>daily digest · web + email</sub></td>
<td align="center">🗂️ <b>DocPipeline</b><br/><sub>docpipeline.unmong.com<br/>document RAG + analysis requests<br/>local LLM · OCR · HWP · pgvector</sub></td>
</tr>

<tr><th colspan="4" align="left">Layer 2 — Shared Platform Services</th></tr>
<tr>
<td align="center" colspan="2">📰 <b>NewsletterPlatform</b><br/><sub>newsletter.unmong.com<br/>multi-tenant collection + delivery core<br/>AI/LLM briefing tenant · incident-hardened send guards</sub></td>
<td align="center" colspan="2">📊 <b>QA Dashboard</b><br/><sub>qaagent.unmong.com<br/>fix-result aggregator<br/>prevention-model dataset</sub></td>
</tr>

<tr><th colspan="4" align="left">Layer 3 — Operations & Gateway</th></tr>
<tr>
<td align="center">📡 <b>InfraWatcher</b><br/><sub>infrawatcher.unmong.com<br/>real-time Docker telemetry<br/>+ container actions</sub></td>
<td align="center">🪵 <b>LogAnalyzer</b><br/><sub>loganalyzer.unmong.com<br/>error-pattern source<br/>for the ops loop</sub></td>
<td align="center">📈 <b>LLMOps</b><br/><sub>llmops.unmong.com<br/>local-LLM usage SSoT<br/>fire-and-forget ingest · eval gates</sub></td>
<td align="center">🔐 <b>Nginx Gateway</b><br/><sub>www.unmong.com<br/>Let's Encrypt wildcard SSL<br/>multi-subdomain + sub-path routing<br/>+ Docker / launchd schedules</sub></td>
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
<td align="center">🔍 <b>Gemini</b><br/><sub>2.5 Flash<br/>free-tier RAG · function calling</sub></td>
<td align="center">🗂️ <b>ChromaDB / pgvector</b><br/><sub>paper corpus index<br/>+ vertical & document corpora</sub></td>
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
| AllergyInsight <sub>*(private)*</sub> | FastAPI, React multi-app + PWA, ChromaDB, PostgreSQL, Gemini + Gemma 4 | Medical vertical #1 — anonymous portal · tool-calling drug agent with response validator · RAG chatbot · daily clinical briefing · device-session auth plane · DomainPack framework |
| [SkillRadar](https://github.com/bluevlad/SkillRadar) | FastAPI, React, PostgreSQL + pgvector | AI-learning vertical #2 — daily curation digest for reskilling, built on inherited fleet engines · hardened shared-framework ingestion |
| DocPipeline <sub>*(private)*</sub> | FastAPI, SQLAlchemy + Alembic, pgvector, Gemma 4 (MLX), PaddleOCR + Tesseract | Document vertical #3 — local-first document RAG with OCR and Korean office-format parsing · queued analysis worker · S2S parse API |
| [InfraWatcher](https://github.com/bluevlad/InfraWatcher) | FastAPI, React, WebSocket | Real-time Docker container observability + control |
| [QA-Dashboard](https://github.com/bluevlad/QA-Dashboard) | FastAPI, React, PostgreSQL | Fix-result aggregator — agent + developer fixes in one prevention dataset |
| [LLMOps](https://github.com/bluevlad/LLMOps) | FastAPI, React, PostgreSQL, Google OAuth | Local-LLM usage SSoT — fire-and-forget SDK · model-inventory pollers (Ollama + MLX) · Eval Profile with YAML-declared gates |
| [NewsLetterPlatform](https://github.com/bluevlad/NewsLetterPlatform) | Python, multi-tenant core | Shared delivery layer — `BaseTenant` abstraction · config-only domain pivots · incident-hardened send guards |
| [LogAnalyzer](https://github.com/bluevlad/LogAnalyzer) | FastAPI, React, PostgreSQL | Docker log analysis — error-pattern source for the ops loop |
| [StandUp](https://github.com/bluevlad/StandUp) <sub>⏸️</sub> | FastAPI, PostgreSQL + pgvector, Ollama | Ops-insight synthesis — 3-stage local LLM cascade + self-referencing RAG · engine inherited by SkillRadar |
| [HopenVision](https://github.com/bluevlad/hopenvision) <sub>⏸️</sub> | Spring Boot 3.2, JPA, React 19, PostgreSQL | Learning-operations platform — commerce / LMS / exam scoring · web-auth architecture inherited by SkillRadar |
| [CompanyAnalyzer](https://github.com/bluevlad/CompanyAnalyzer) <sub>⏸️</sub> | FastAPI, React, PostgreSQL, Ollama | Website-driven company strengths / improvement analysis on local LLM |
| [OpsConsole](https://github.com/bluevlad/OpsConsole) <sub>⏸️</sub> | FastAPI, React, PostgreSQL | Internal developer portal — section catalog · owners · change requests (foundation phase) |
| ImagesToAiPipeLine <sub>*(private)* ⏸️</sub> | FastAPI, rembg, OWL-ViT v2, React + Vite | Local vision pipeline — BG-removal crop + text & image-guided detection |
