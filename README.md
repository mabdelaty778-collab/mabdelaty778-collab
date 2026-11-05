# Mohamed Abdelaty

**AI & Software Engineer · Voice AI · Applied LLM Systems**

I build conversational AI systems and the software around them: APIs, data integrations, dashboards, and automation. My work connects voice and language models to business workflows, with a focus on reliable tool execution, clear failure handling, and maintainable services.

[LinkedIn](https://www.linkedin.com/in/mohamed-abdelaty22/) · [Watch my voice AI demo](https://www.linkedin.com/feed/update/urn:li:activity:7523886174831034368/) · [Explore the code](https://github.com/mabdelaty778-collab/voice-ai-lab)

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
