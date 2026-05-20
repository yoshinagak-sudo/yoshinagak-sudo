# Hi, I'm Keigo Yoshinaga 👋

CEO of [Butai Farm](https://www.butaifarm.co.jp/) — a Japanese agricultural enterprise running rice production, B2B cut-vegetable wholesale, food logistics, and an indoor lettuce factory.
I also write the software that operates the company.

📍 Sendai, Japan ・ ✉️ keiggoo.0527@gmail.com

---

## What I build

Over the past 18 months I've shipped **20+ production systems** as a solo builder (with Claude Code as an extra pair of hands). The work spans the entire operational stack of an agricultural business.

| Area | What it does |
|---|---|
| **CRM** | Salesforce replacement. 587 accounts, 870 contacts migrated. Activity Kanban, opportunity pipeline, complaint approval workflow, Slack-wired events |
| **Sales Analytics** | 7-axis BI dashboard over ¥1.185B / 47K transactions / 10 months. Drill-down by product, ship-to, and base-period comparison |
| **Order Management** | Unified B2B order platform consolidating three customer-specific legacy forms. Cloud Run + Firebase Hosting + Firestore |
| **Dispatch AI** | In-house replacement of a routing SaaS. 21 trucks · 5 hubs · 129 ship-to locations. Next.js + VROOM solver + OSRM + Claude as translator. ~¥700K/year savings |
| **Computer-Vision Crop Grading** | Lettuce-root grading on 5 axes × 1–5pt with Claude Sonnet Vision. Every image + AI score + human correction is persisted to enable few-shot improvement |
| **Indoor Factory Monitoring** | Lettuce growth dashboard integrating environment sensors, 3-camera weight estimation, and AI yield prediction |
| **HR Knowledge Bot** | Employee-facing Q&A bot over internal HR documents. Gemini 2.5 Flash with implicit caching |
| **Daily ETL** | Zero-cost forecast-vs-actual sync (GitHub Actions + Python + Google Sheets API). ¥0/month operating cost |

Most of the business-critical code lives in private repositories. The public ones below are demos, side projects, and open-source-friendly slices.

---

## Tech I reach for

- **Languages**: TypeScript, Python, SQL
- **Framework**: Next.js 16 / React 19 / Prisma / Tailwind v4 / shadcn-ui
- **Data**: PostgreSQL, Supabase, Google Sheets API, Firestore
- **Cloud**: GCP (Cloud Run, Cloud SQL), Vercel, Firebase Hosting, GitHub Actions, Docker
- **AI**: Claude Sonnet 4.6 + Haiku 4.5 (Anthropic SDK, prompt caching, Vision), Gemini 2.5 Flash, mlx-whisper
- **Workflow**: Agentic development with Claude Code — multi-agent orchestration across architect / ui-designer / researcher / secretary roles

---

## How I work

I treat software as **operational infrastructure**, not features.
The systems above weren't built to demo well — they were built because the company couldn't run without them. That means:

- I live inside the operational problem before I write a line of code
- I design data models from the workflow up, not from the schema down
- I prefer integration over abstraction, and shipping over polishing
- I keep the AI in its lane: optimizers solve, LLMs translate

---

## Currently exploring

- WAGRI integration for rice grade inspection AI
- Two-stage hub-and-spoke VRP optimization at fleet scale
- Agentic Claude Code workflows for solo-builder velocity

---

## Get in touch

- 📧 keiggoo.0527@gmail.com
- 🌐 [butaifarm.co.jp](https://www.butaifarm.co.jp/)
