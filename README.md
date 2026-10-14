<h1 align="center">Hi, I'm Mateusz Mazur 👋</h1>
<h3 align="center">Full-stack developer building business tools and local-LLM systems</h3>

I turn messy, real company processes (steel pricing, contract registers, H&S programmes,
supplier email) into software that people use every day: Next.js + PostgreSQL on the web
side, Python for data, ML and LLM pipelines.

- 🏭 Three of my apps run in production or internal testing at a large industrial company
- 🧠 Currently learning **RAG pipelines in Python** (retrieval, chunking, evaluation)
- 🤝 **Open to B2B collaboration**: internal tools, process automation, local/private LLM integrations
- 📫 [LinkedIn](https://www.linkedin.com/in/mateusz-mazur-041670302) · [matitrampolin@gmail.com](mailto:matitrampolin@gmail.com)

---

## Featured projects

### Business applications
| Project | What it is | Stack |
|---|---|---|
| **[SteelQuote](https://github.com/Kotsur69/SteelQuote)** | Pricing and offer platform for steel sales teams: real-time pricing for 6 steel types, configurable approval flows and validation rules, role-based visibility, PDF/Excel export, analytics. **v2.0 live in production.** | Next.js 14 · TypeScript · PostgreSQL |
| **[AMSafe](https://github.com/Kotsur69/AMSafe)** | Gamified H&S (BHP) PWA for a production warehouse: daily quizzes, missions, points and ranks, worker → leader → manager hierarchy, push notifications. **In production.** | Next.js · Prisma · PostgreSQL · Web Push · S3 |
| **[CRU2026](https://github.com/Kotsur69/CRU2026-public-version)** | Rebuild of a legacy CakePHP contract registry: server-side read authorization, SharePoint storage through Microsoft Graph, migration of ~20k legacy records. | Next.js 14 · Prisma · PostgreSQL · MS Graph |
| **[Logistics Network Map](https://github.com/Kotsur69/Logistics_Network_Map)** | Turns shipment exports into an interactive route map with tonnage-weighted routes, hubs and top customers, in one offline HTML file. | Python · pandas · OSRM |

### AI & LLM systems
| Project | What it is | Stack |
|---|---|---|
| **[AI_Mail_Arbitrium](https://github.com/Kotsur69/AI_Mail_Arbitrium)** | Classifies supplier email replies with a **local** LLM: JSON-Schema constrained decoding, verbatim evidence grounding and a deterministic human-review queue. Nothing leaves the machine. 217 tests. | Python · LM Studio · Qwen3 · Outlook COM |
| **Synthara** *(private)* | Multi-persona AI content platform: FastAPI + Celery workers, ComfyUI image/video generation, n8n scheduling and a Next.js human-in-the-loop review dashboard. | FastAPI · Celery · Redis · PostgreSQL · ComfyUI · n8n · Docker |
| **[LunaCore HUD](https://github.com/Kotsur69/Luna-Core-HUD)** | Electron dashboard for the Claude Code CLI: context and usage telemetry, session tabs, and parallel AI workers in git worktrees that finish as PRs. | Electron · JavaScript · Python |

### Quant & trading research
| Project | What it is | Stack |
|---|---|---|
| **[money_printer_turbo](https://github.com/Kotsur69/money_printer_turbo)** | Research harness for US-equity strategies with pre-registered kill gates, a deflated Sharpe ratio and fill-realism checks on real quotes. Three theses honestly killed, and **$1,759 of data purchases avoided** by gates. | NautilusTrader · CatBoost · Databento |
| **[crypto-regime-trader](https://github.com/Kotsur69/crypto-regime-trader)** | Binance bot: pattern + market-regime engine, LLM news sentiment, Kelly sizing, scale-out exits, walk-forward backtests, pytest suite. Testnet-first. | Python · Flask · pandas |

<sub>Older experiments: [news & analyzer tools](https://github.com/Kotsur69/news-and-analyzer-tools-archive) · [newsletter tools](https://github.com/Kotsur69/newsletter-tools-archive)</sub>

---

## Stack

- **Frontend:** TypeScript · React · Next.js (App Router) · Tailwind CSS · shadcn/ui · PWA
- **Backend:** Node.js · Prisma · PostgreSQL · NextAuth · FastAPI · Celery · Redis · REST
- **Data / ML:** Python · pandas · NumPy · CatBoost · NautilusTrader · walk-forward / CPCV validation
- **LLM:** local models (LM Studio, Ollama, Qwen) · structured output / JSON Schema · prompt pipelines · ComfyUI · *learning: RAG*
- **Integrations & ops:** Microsoft Graph / SharePoint · Outlook COM · n8n · Docker · Vercel · Electron · Git

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,nodejs,prisma,postgres,python,fastapi,redis,docker,electron,git,linux,vercel&perline=16" alt="Languages and tools" />
</p>

---

## Interests & currently

- 🔎 **RAG pipelines in Python**: retrieval, chunking strategies, evaluating answer quality
- 🧠 Applied ML and LLMs **beyond demos**: private, local models doing real business work
- 📈 Algorithmic decision systems and finance, validated honestly (walk-forward, kill gates)
- 🏗️ Backend architecture: authorization, data migrations, systems that are easy to run
- 🌐 Networking fundamentals: TCP/IP, traffic analysis (Wireshark, tcpdump)

> I like building systems designed for an AI-focused future, grounded in solid understanding.
> I believe AI is often misunderstood, but it has the potential to fundamentally change the way
> we live and interact with the world.
