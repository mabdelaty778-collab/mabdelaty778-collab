# Mohamed Abdelaty

**AI & Software Engineer · AI SaaS · Voice AI · Applied LLM Systems**

I build AI products and the software around them: SaaS platforms, voice agents, APIs, data integrations, dashboards, and automation. My work connects language models to business workflows, with a focus on clear integration boundaries, reliable tool execution, and maintainable services.

[LinkedIn](https://www.linkedin.com/in/mohamed-abdelaty22/) · [Watch my voice AI demo](https://www.linkedin.com/feed/update/urn:li:activity:7523886174831034368/) · [Explore the code](https://github.com/mabdelaty778-collab/voice-ai-lab)

## Flagship engineering work

| Project | Engineering scope | Review |
|---|---|---|
| **Elite Créatif AI SaaS** | Business discovery, AI personalization, tenant-aware campaign APIs, sending workflows, and dashboards | [Case study & architecture](https://github.com/mabdelaty778-collab/elite-creatif-ai-saas) · [Product walkthrough](https://www.linkedin.com/feed/update/urn:li:activity:7412500377901719552/) |
| **Academy & clinic Voice AI** | Conversational agents, knowledge tools, database/CRM workflows, and GSM/SIP integration | [Academy case study](https://github.com/mabdelaty778-collab/voice-ai-lab/blob/main/docs/production-case-study.md) · [Clinic demo](https://github.com/mabdelaty778-collab/voice-ai-lab/blob/main/docs/clinic-voice-demo-redacted.mp4) |

## Elite Créatif: AI lead-generation and outreach SaaS

I built AI and backend workflows connecting business discovery, company enrichment, personalized email/WhatsApp content, and campaign operations. The implementation includes Python/FastAPI tenant and campaign workflows, Qwen-based generation, batch imports/exports, and application reporting.

**[Explore the engineering showcase](https://github.com/mabdelaty778-collab/elite-creatif-ai-saas)** · **[Implementation decisions](https://github.com/mabdelaty778-collab/elite-creatif-ai-saas/blob/main/docs/engineering-case-study.md)** · **[Source evidence](https://github.com/mabdelaty778-collab/elite-creatif-ai-saas/blob/main/docs/architecture.md)**

The showcase connects the original product gallery to a fixed public source snapshot and distinguishes demonstrated implementation from production metrics that still need operational evidence.

## Production case study: academy voice AI

I document the academy application's architecture, speech-provider tradeoffs, and the Arabic audio-framing failure addressed by its custom WebSocket adapter. The case study links to a fixed source snapshot and separates implemented behavior from measured results and remaining reliability work.

**[Read the production case study](https://github.com/mabdelaty778-collab/voice-ai-lab/blob/main/docs/production-case-study.md)**

## Featured work: Voice AI Lab

[![CI](https://github.com/mabdelaty778-collab/voice-ai-lab/actions/workflows/test.yml/badge.svg)](https://github.com/mabdelaty778-collab/voice-ai-lab/actions)

A runnable, open-source learning environment for the engineering behind voice agents. Built with **Python, FastAPI, and SQLite**, with an optional **LiveKit + OpenAI Realtime** voice exercise.

| Engineering concern | What you can inspect |
|---|---|
| Grounding | Knowledge lookup with visible source IDs and explicit no-match responses |
| Persistence | Transactional writes and confirmation after commit |
| Safe retries | Request-level idempotency and payload conflict detection |
| Failure recovery | Deliberate write failures, rollback, and repeatable recovery exercises |
| Verification | Isolated tests, locked dependencies, Docker, and CI |

**[Code & setup](https://github.com/mabdelaty778-collab/voice-ai-lab)** · **[Redacted demo](https://github.com/mabdelaty778-collab/voice-ai-lab/blob/main/docs/clinic-voice-demo-redacted.mp4)** · **[Engineering case study](https://github.com/mabdelaty778-collab/voice-ai-lab/blob/main/docs/engineering-case-study.md)** · **[Architecture](https://github.com/mabdelaty778-collab/voice-ai-lab/blob/main/docs/architecture.md)**

The recording shows my original receptionist application. The public lab is a separate educational implementation with fictional data. Its free mode is a deterministic text simulation; optional real voice requires a learner's own provider key and audio devices.

## Production experience

- **Voice AI:** Built two agents for clinic and academy workflows, including dashboards and database, CRM, and GSM/SIP integrations.
- **Web engineering:** Built and launched **50 microsites** supporting organic acquisition for the group's official websites.
- **Engineering automation:** Created website bug-fixing workflows and connected Semrush, Google Analytics, and Google Search Console through MCP servers and plugins to support technical SEO maintenance.
- **AI SaaS:** Built a multi-tenant lead-generation and outreach platform covering data collection, personalized email and WhatsApp content, campaign delivery, and tracking.

## How I approach engineering

- Define success at the business-action boundary: a spoken promise needs a confirmed tool result.
- Make retries, failure paths, and storage behavior explicit and testable.
- Keep integration boundaries clear, document tradeoffs, and provide reproducible setup.

## Core stack

| Area | Technologies |
|---|---|
| AI & voice | LiveKit, OpenAI Realtime, LLM tool calling, RAG, SIP/GSM integration |
| Backend & data | Python, FastAPI, SQL, SQLite, PostgreSQL, Redis |
| Delivery & operations | Docker, AWS, GitHub Actions, automated tests, API integrations |

## Connect

For AI engineering, voice-agent systems, and software collaboration, reach me on [LinkedIn](https://www.linkedin.com/in/mohamed-abdelaty22/).
