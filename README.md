# AI Automation Manual v3.0

**The whole word on AI automation.** From a single Tasker task to a distributed multi-agent system.

**Live site → [thegreatoleander.github.io/Automation_-_AI](https://thegreatoleander.github.io/Automation_-_AI/)**

---

## What's covered

25 parts across the full AI automation stack:

- **Foundations** — the five-layer mental model, trigger taxonomy, idempotency, outbox pattern, economics
- **Mobile & Desktop** — Tasker, Akasha Bridge, iOS Shortcuts, AutoHotkey, KDE Connect, Raycast
- **Orchestration** — n8n, GitHub Actions, Makefiles, LangChain, LangGraph, CrewAI
- **Infrastructure** — Redis, Celery, MCP, Docker Compose, Cloudflare Workers
- **Security** — prompt injection, PII, compliance (GDPR/HIPAA), secrets management
- **Observability** — OpenTelemetry, Prometheus/Grafana, semantic drift detection *(new in v3)*
- **Structured Outputs** — Instructor/Pydantic, function calling, validation pipelines *(new in v3)*
- **Local Models** — Ollama, quantization, local-first fallback chains *(new in v3)*
- **Vector Databases** — pgvector, Qdrant, hybrid search, re-ranking *(new in v3)*
- **Agent Evaluation** — trajectory logging, the four trajectory metrics *(new in v3)*
- **Code Volleyball** — the Prompt Ledger, LEDGER.md, multi-model relay, automated relay pipelines *(new in v3)*
- **Decision-making** — when not to automate, pre-deployment checklist *(new in v3)*

---

## File structure

```
Automation_-_AI/
├── index.html              ← Table of contents / homepage
├── .nojekyll               ← Disables Jekyll on GitHub Pages
├── README.md
└── sections/
    ├── preface.html
    ├── part-01.html        ← Part I: The Automation Stack
    ├── part-02.html        ← Part II: Tasker
    ├── part-03.html        ← Part III: Open Interpreter
    ├── part-04.html        ← Part IV: n8n
    ├── part-05.html        ← Part V: GitHub Actions & Makefiles
    ├── part-06.html        ← Part VI: Bash & Python
    ├── part-07.html        ← Part VII: Redis & Celery
    ├── part-08.html        ← Part VIII: LangChain, LlamaIndex, LangGraph
    ├── part-09.html        ← Part IX: Model Context Protocol
    ├── part-10.html        ← Part X: Docker Compose
    ├── part-11.html        ← Part XI: Security & Compliance
    ├── part-12.html        ← Part XII: Cost Modeling & Evals
    ├── part-13.html        ← Part XIII: Edge Functions & Webhooks
    ├── part-14.html        ← Part XIV: Advanced Agent Patterns
    ├── part-15.html        ← Part XV: Operational Runbooks
    ├── part-16.html        ← Part XVI: Complete Reference
    ├── part-17.html        ← Part XVII: Observability & Telemetry
    ├── part-18.html        ← Part XVIII: Structured Outputs
    ├── part-19.html        ← Part XIX: Local Models with Ollama
    ├── part-20.html        ← Part XX: Vector Databases
    ├── part-21.html        ← Part XXI: Agent Evaluation
    ├── part-22.html        ← Part XXII: Prompt Ledger & Code Volleyball
    ├── part-23.html        ← Part XXIII: Automation Decision Checklist
    └── addendum.html
```

---

## Adding or editing sections

Each `sections/*.html` file is self-contained — the CSS is inlined. To edit content, open the file and modify the `<article>` block directly.

To add a new section:
1. Copy any existing section file as a template
2. Update the badge, `<h1>`, article content, and `page-nav` prev/next links
3. Add a card for it in `index.html`
4. Commit and push — GitHub Pages redeploys automatically

---

*Written by AI · Compiled by a human · The Compiler*
