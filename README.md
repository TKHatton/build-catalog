# What I Build

I design and deploy AI-powered systems that run in production — multi-agent platforms, municipal compliance tools, content operations, and the internal infrastructure that keeps it all coordinated. Not prototypes. Not demos. Shipped.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?logo=anthropic&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?logo=twilio&logoColor=white)

**Jump to:** [Flagship Platforms](#flagship-platforms) · [Infrastructure](#infrastructure-i-built-for-myself) · [Hackathons](#hackathons) · [Teaching & Courses](#teaching--courses) · [Also Built](#also-built) · [Currently Building](#currently-building) · [Contact](#lets-work-together)

---

## Flagship Platforms

### Signal & Structure AI — AI Discoverability Platform
> Helps businesses get found and accurately represented by AI assistants like ChatGPT, Claude, and Gemini.

![Status](https://img.shields.io/badge/Status-Production-success) ![Started](https://img.shields.io/badge/Started-2023-informational) [![Live](https://img.shields.io/badge/Live-signalstructure.ai-blue)](https://signalstructure.ai)

Full AI discoverability platform with four production MCP servers (Signal Watch, Signal Pulse, Signal Advisor, Knowledge Base) connected directly into Claude. Scans websites for schema markup quality, checks AI platform mentions across every major model, and generates prioritized action plans. Multi-tenant client portal has three role-based dashboards (owner, client, VA), automated lead generation, and a research-backed white paper on AI discoverability.

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?logo=supabase&logoColor=white)
![Railway](https://img.shields.io/badge/-Railway-0B0D0E?logo=railway&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP_Protocol-D97757)
![Claude API](https://img.shields.io/badge/-Claude_API-D97757?logo=anthropic&logoColor=white)

<!-- Screenshot: uncomment once image is added to /screenshots
![Signal & Structure AI screenshot](screenshots/signal-structure.png)
-->

---

### StormIQ — Municipal Compliance Platform
> AI-powered tools for stormwater professionals and municipal operators. Hackathon submission: **Sewer Sentinel** (Google Gemini 3, $50K prize).

![Status](https://img.shields.io/badge/Status-Deployed_·_Pilot_Recruitment-success) ![Started](https://img.shields.io/badge/Started-2026-informational) ![Hackathon](https://img.shields.io/badge/Google_Gemini_3-Submitted-yellow)

21-product platform for MS4 stormwater compliance. AI photo analysis using computer vision for field inspection reports, automated narrative generation from voice-to-text field notes, and compliance tracking dashboards. Currently recruiting first municipal partner for pilot deployment. Five-service Railway deployment (FastAPI backend, Next.js dashboard, PostgreSQL, MinIO object storage, background worker). Targeting 7,500+ MS4 operators nationwide.

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MinIO](https://img.shields.io/badge/-MinIO-C72E49?logo=minio&logoColor=white)
![Railway](https://img.shields.io/badge/-Railway-0B0D0E?logo=railway&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini_API-8E75B2?logo=google&logoColor=white)

<!-- Screenshot: uncomment once image is added to /screenshots
![StormIQ screenshot](screenshots/stormiq.png)
-->

---

### Content Command Center — Multi-Brand Content Operations
> One system serving five brands with AI-powered content generation, scheduling, and engagement.

![Status](https://img.shields.io/badge/Status-Deployed-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

Full content ops platform with automated prospecting (Google Places API lead discovery), AI-powered response generation across LinkedIn, email, Skool, and WhatsApp, and brand voice enforcement with banned-word filtering. Includes the Prospect Mail pipeline (auto-prospecting, draft generation, scheduled sends). Each brand maintains its own voice profile, tone rules, and audience context.

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white)
![Railway](https://img.shields.io/badge/-Railway-0B0D0E?logo=railway&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?logo=supabase&logoColor=white)
![Google Places](https://img.shields.io/badge/-Google_Places-4285F4?logo=google&logoColor=white)
![Claude API](https://img.shields.io/badge/-Claude_API-D97757?logo=anthropic&logoColor=white)

<!-- Screenshot: uncomment once image is added to /screenshots
![Content Command Center screenshot](screenshots/ccc.png)
-->

---

### The Drop — AI Content Intelligence
> Replaces hours of video watching with a daily AI-curated digest from 21+ sources.

![Status](https://img.shields.io/badge/Status-Deployed_·_Voice_Mode_Live-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

Monitors YouTube channels and RSS sources, auto-transcribes and summarizes new content, delivers a formatted daily digest. Voice Mode for listening instead of reading. Topic-based discovery lets you request a subject and have the system find, transcribe, and summarize matching content automatically.

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Railway](https://img.shields.io/badge/-Railway-0B0D0E?logo=railway&logoColor=white)
![YouTube API](https://img.shields.io/badge/-YouTube_API-FF0000?logo=youtube&logoColor=white)
![Whisper](https://img.shields.io/badge/-Whisper-412991?logo=openai&logoColor=white)
![Claude API](https://img.shields.io/badge/-Claude_API-D97757?logo=anthropic&logoColor=white)

<!-- Screenshot: uncomment once image is added to /screenshots
![The Drop screenshot](screenshots/the-drop.png)
-->

---

### CueBoard — AI-Powered Zoom Meeting Plugin
> Real-time meeting intelligence with audience engagement tools.

![Semifinalist](https://img.shields.io/badge/Logitech_Hackathon-Semifinalist_·_Top_50_of_1%2C300%2B-gold) ![Status](https://img.shields.io/badge/Status-Advancing_to_Final-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

Zoom plugin with 34 actions: live flags, participant assignment, free-text notes, polls, transcript access, and full export. Built for the Logitech CueBoard hackathon — reached semifinalist round (top 50 of 1,300+ participants) and currently competing for the top 6 final round in Switzerland. Three-page interface: quick actions dashboard, keyboard shortcuts panel, and full engagement suite with poll URL injection into Zoom chat.

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Zoom SDK](https://img.shields.io/badge/-Zoom_SDK-2D8CFF?logo=zoom&logoColor=white)
![Netlify](https://img.shields.io/badge/-Netlify-00C7B7?logo=netlify&logoColor=white)

<!-- Screenshot: uncomment once image is added to /screenshots
![CueBoard screenshot](screenshots/cueboard.png)
-->

---

### Course Canon — AI Course & Presentation Evaluator
> Evaluates presentations and teaching quality, gives structured feedback.

![Status](https://img.shields.io/badge/Status-Deployed-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

AI-powered system that analyzes educational content for structure, engagement, learning-objective alignment, and delivery quality. Multiple audience-specific landing pages for pastors, school presenters, conference speakers, and educators.

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Claude API](https://img.shields.io/badge/-Claude_API-D97757?logo=anthropic&logoColor=white)
![Railway](https://img.shields.io/badge/-Railway-0B0D0E?logo=railway&logoColor=white)

<!-- Screenshot: uncomment once image is added to /screenshots
![Course Canon screenshot](screenshots/course-canon.png)
-->

---

## Infrastructure I Built For Myself

The systems that let me run multiple ventures in parallel without dropping context.

### CORE — Persistent Memory & Decision System
> The shared brain that powers every venture. Ongoing since April 2026.

![Status](https://img.shields.io/badge/Status-Ongoing-success) ![Started](https://img.shields.io/badge/Started-April_2026-informational)

CORE is the unified markdown, YAML, and Supabase architecture that keeps every venture, decision, and deadline coordinated across sessions. Slash commands (`/log`, `/summary`) route new information to the right place — a living decisions log that's never pruned, a persistent status file across all projects, priorities, personal logistics, and per-venture context. Every tool I build and every session I run reads from CORE first, so nothing gets lost between days, projects, or ventures.

This is the system that makes the rest of the catalog possible.

![Markdown](https://img.shields.io/badge/-Markdown-000000?logo=markdown&logoColor=white)
![YAML](https://img.shields.io/badge/-YAML-CB171E?logo=yaml&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?logo=supabase&logoColor=white)
![Claude Code](https://img.shields.io/badge/-Claude_Code-D97757?logo=anthropic&logoColor=white)

<!-- Screenshot: uncomment once image is added to /screenshots
![CORE screenshot](screenshots/core.png)
-->

---

### MAOS — Meta-Agentic Operating System
> 12-component modular multi-agent system architecture.

![Status](https://img.shields.io/badge/Status-Architecture_Complete-informational) ![Started](https://img.shields.io/badge/Started-2026-informational)

Complete multi-agent OS design across five layers: orchestration, intelligence, execution, memory, and meta. Each of the 12 components is independently deployable but works as a unified system. Built on the principle that 5–8 capability-scoped agents backed by strong infrastructure beats 40 single-task agents on cost, speed, accuracy, and reliability. Build sequence starts with schema-driven design.

---

## Hackathons

| Hackathon | Project | Status |
|-----------|---------|--------|
| Logitech CueBoard | CueBoard Zoom Plugin | **Semifinalist — Top 50 of 1,300+, advancing to final round** |
| Google Gemini 3 | **Sewer Sentinel** (StormIQ) | Submitted, awaiting results ($50K prize) |
| Google Live Agent | Adaptive Drive | Submitted, awaiting results |
| Auth0 | Signal Vault | Submitted, awaiting results |

---

## Teaching & Courses

20+ years of teaching experience, now applied to AI education for audiences ranging from Girl Scouts to enterprise teams.

- **Run Better Meetings with AI** — Complete course, production-ready.
- **Start Smart: From Avoiding AI to AI Confidence** — 5-day email drip course.
- **Complete Guide to AI for Over-Thinkers** — Self-paced course.
- **AI and Emotional Intelligence** — Conference presentation.
- **Building Agentic Systems That Actually Work** — 90–120 min advanced course on capability-scoped agent design, multi-layer infrastructure, and cost optimization.
- **Agents Without the Jargon** — Beginner-friendly, opens with a live demo before definitions.
- **AI in the Wild** — Girl Scout AI badge curriculum across all age levels.

---

## Also Built

Shipped tools, automations, and products. Smaller in scope than the flagships above, bigger in number.

- **Daily Clarity** — AI-powered thinking assistant with 5 tools: Mind Dump (organize mental clutter), Find Words (say difficult things clearly), Decision Helper (think through choices without judgment), Write The Hard Thing (draft difficult communications), Quick Reset (2-minute grounding when overwhelmed). Warm, human tone — no corporate speak. Free mode uses localStorage ($0 cost), cloud mode adds user accounts. [Repo](https://github.com/TKHatton/Daily-Clarity) · `React` `TypeScript` `Gemini API` `Supabase` `Netlify`
- **Opportunity Tracker** — Revenue dashboard CLI with daily email summary. Shipped April 14, 2026. `Python` `Typer` `Supabase` `Railway`
- **Personal CRM** — Relationship intelligence for a solo operator running multiple ventures. Shipped April 14, 2026. `Python` `Supabase`
- **Proof of Work** — Automated build documentation with screenshots and technical details. Shipped April 14, 2026. `Python`
- **PageSpeak** — Chrome text-to-speech extension for accessibility. Reads articles, documents, and PDFs aloud. Designed for dyslexia and visual processing needs. [Landing page](https://pagespeak.netlify.app/) · `JavaScript` `Chrome Extension API` `Web Speech API`
- **InboxToSheets** — Email-to-spreadsheet automation. Monitors inboxes, extracts structured data from invoices/receipts/confirmations, outputs clean spreadsheets. [Live →](https://inbox2sheet.netlify.app/) · `Python`
- **Prospect Mail** — End-to-end outreach automation with three daily cron jobs on Railway. `Python` `Google Places API` `Claude API` `SendGrid`
- **Signal Vault** — Encrypted credential storage for multi-service Railway deployments. (Auth0 hackathon submission.) `Python` `Railway`
- **Adaptive Drive** — Google Live Agent hackathon submission.
- **Routine Anchor** — Nightly SMS health check-in. Code complete, pending Twilio activation. `Python` `Twilio`
- **Build Catalog** — This repo.

---

## Currently Building

Active development. Details on request.

- **FolderSort** — AI file organization. [Landing page live](https://foldersort.netlify.app/); finalizing Apple Developer integration before launch.
- Automated daily briefing agent
- Client onboarding automation
- AI avatar content pipeline
- Content repurposing engine

---

## Let's Work Together

I build AI systems that actually run in production. Not prototypes, not demos. If you need agents, automations, or AI-powered platforms, let's talk.

**Find me on:** [Contra](https://contra.com/Lenise_Kenney) · [LinkedIn](https://www.linkedin.com/in/lenise-kenney/)
