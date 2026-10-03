# Hi, I'm Tayyab 👋

**Senior AI Engineer** · AI agents, LLMs & RAG in production · Human-in-the-loop guardrails, evals & LLM cost optimization

I've spent 5+ years building production AI: LLM-powered agents, agentic workflows and RAG systems used by real customers. I focus on making agents **safe** (the model proposes, code decides), **measurable** (evaluation harnesses, adversarial tests) and **affordable** (metering every AI call, cutting cost per plan ~77%).

Today I build the AI service behind a multi-tenant AI workspace platform at a London-based AI company. I own features end to end: requirements, design docs, code, evals, CI and client demos.

## ⭐ Featured work

Clean-room re-implementations of production systems I designed and built. Each repo has tests, a runnable demo and docs. No employer code; all names and data are fictional.

| Repo | What it shows |
|---|---|
| [**agent-guardrails**](https://github.com/Tayyab-Bilal/agent-guardrails) | Deterministic permissions and human-in-the-loop approval for agent tool calls: deny by default, approve once, run exactly once |
| [**autonomous-agent**](https://github.com/Tayyab-Bilal/autonomous-agent) | A planner/executor that runs LLM plans unattended on a schedule or event: deterministic plan assembly, crash recovery, loop guard, honest outcomes |
| [**agent-kit**](https://github.com/Tayyab-Bilal/agent-kit) | A small runtime for safe multi-step specialist agents: YAML agent cards, read-only SQL result handles, guarded writes, code-checked consent |
| [**grep-first-agent**](https://github.com/Tayyab-Bilal/grep-first-agent) | Agentic retrieval with string matching instead of vector RAG: 17 tools in three layers, stampede-safe cache, strict JSON pointer contract |
| [**llm-cost-meter**](https://github.com/Tayyab-Bilal/llm-cost-meter) | One cost and token tracker for every AI call: integer micro-credits, Redis Lua balances, billing while streaming, a build-time guard against unbilled calls |
| [**model-price-registry**](https://github.com/Tayyab-Bilal/model-price-registry) | Audited LLM prices: one write path, provider sync that only files drafts, a human approval queue, explicit billing units |
| [**workflow-doctor**](https://github.com/Tayyab-Bilal/workflow-doctor) | Build automation workflows from plain language and diagnose why they fail: deterministic assembly, 15 checks, run forensics, drift |
| [**async-doc-ingestion**](https://github.com/Tayyab-Bilal/async-doc-ingestion) | Crash-safe, idempotent document ingestion for RAG: never pays for OCR twice, self-healing re-index sweep, per-tenant vectors |
| [**fastapi-prod-hardening**](https://github.com/Tayyab-Bilal/fastapi-prod-hardening) | Go-live hardening for a multi-tenant FastAPI + LLM service: per-caller rate limits, bounded LLM calls, log redaction, change-aware CI |

Also: [erpnext-mcp-server](https://github.com/Tayyab-Bilal/erpnext-mcp-server) (connect AI assistants to ERPNext over MCP) · [Langgraph-multiagent-demo](https://github.com/Tayyab-Bilal/Langgraph-multiagent-demo)

## 🧭 What I've worked on

- **Autonomous agents:** goal → scheduled or event-triggered plan → unattended execution, with idempotent writes, crash recovery and runaway limits.
- **Human-in-the-loop guardrails:** deny-by-default, fail-closed approvals with exactly-once execution of exactly what a person approved.
- **Agentic retrieval:** grep-first lexical and fuzzy search over live data instead of vector RAG, built before two May 2026 arXiv papers reported grep beating vector retrieval for agentic search.
- **LLM cost:** usage metering across text, audio, document and embedding APIs after finding only 68% of AI spend was billed; ~77% cheaper per agent plan.
- **Evaluation & quality:** parity evals, a 114-case adversarial (prompt-injection) suite, live end-to-end agent harnesses, CI built from scratch (PR runs 11m20s → 3m44s).
- **Earlier:** multi-modal RAG, real-time voice AI (sub-500 ms), 4-bit QLoRA fine-tuning that cut inference cost 80%, NLP, computer vision and recommendation systems.

## 🛠️ Core stack

- **AI & agents:** Python · LangGraph · LangChain · MCP · OpenAI / Anthropic / Gemini APIs · PyTorch
- **Retrieval & data:** RAG · Qdrant · pgvector · FAISS · PostgreSQL · Redis · Elasticsearch · Neo4j
- **Services & infra:** FastAPI · Celery · Docker · Kubernetes · GitHub Actions · AWS · Azure · GCP

## 📫 Get in touch

Open to remote Senior AI Engineer / LLM Engineer roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/tayyab-bilal-79b509187) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:tayyaib055766@gmail.com) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/12679810) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/Tayyaib_Bilal)
