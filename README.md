# AI Automation Manual v3.0

**The whole word on AI automation.** From a single Tasker task to a distributed multi-agent system.

**Live site → [your-username.github.io/ai-automation-manual](https://your-username.github.io/ai-automation-manual)**

---

## What's covered

25 parts across the full AI automation stack:

- **Foundations** — the five-layer mental model, trigger taxonomy, idempotency, outbox pattern, economics
- **Mobile & Desktop** — Tasker, Akasha Bridge, iOS Shortcuts, AutoHotkey, KDE Connect, Raycast
- **Orchestration** — n8n, GitHub Actions, Makefiles, LangChain, LangGraph, CrewAI
- **Infrastructure** — Redis, Celery, MCP, Docker Compose, Cloudflare Workers
- **Security** — prompt injection, PII, compliance (GDPR/HIPAA), secrets management
- **Observability** — OpenTelemetry, Prometheus/Grafana, semantic drift detection *(new)*
- **Structured Outputs** — Instructor/Pydantic, function calling, validation pipelines *(new)*
- **Local Models** — Ollama, quantization, local-first fallback chains *(new)*
- **Vector Databases** — pgvector, Qdrant, hybrid search, re-ranking *(new)*
- **Agent Evaluation** — trajectory logging, the four trajectory metrics *(new)*
- **Code Volleyball** — the Prompt Ledger, LEDGER.md, multi-model relay, automated relay pipelines *(new)*
- **Decision-making** — when not to automate, pre-deployment checklist *(new)*

---

## Publishing to GitHub Pages

```bash
cd ai-automation-manual
git init
git add .
git commit -m "Initial publish: AI Automation Manual v3.0"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ai-automation-manual.git
git push -u origin main
```

Then: **GitHub repo → Settings → Pages → Source: main / root → Save.**

Live at `https://YOUR-USERNAME.github.io/ai-automation-manual/` within ~60 seconds.

---

## File structure

```
ai-automation-manual/
├── index.html              ← Table of contents / homepage
├── .nojekyll               ← Required: disables Jekyll on GitHub Pages
├── README.md
└── sections/
    ├── preface.html
    ├── part-01.html        ← Part I: The Automation Stack
    ├── part-02.html        ← Part II: Tasker
    ├── ...
    ├── part-22.html        ← Part XXII: Code Volleyball / Prompt Ledger
    ├── part-23.html        ← Part XXIII: Decision Checklist
    └── addendum.html
```

---

## Adding or editing sections

Each `sections/*.html` file is self-contained. To edit content, open the file and modify the `<article>` block. The shared CSS is inlined in each file — update it in `build_site.py` and re-run if you want a sitewide style change.

To add a new section: copy any existing section file, update the badge, h1, article content, and page-nav links, then add a card for it in `index.html`.

---

*Written by AI · Compiled by a human · The Compiler*
