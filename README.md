# What I Build

I design and deploy AI-powered systems that run in production — multi-agent platforms, municipal compliance tools, content operations, and the internal infrastructure that keeps it all coordinated. Not prototypes. Not demos. Shipped.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?logo=anthropic&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)

**Jump to:** [Flagship Platforms](#flagship-platforms) · [Life OS](#life-os--personal-infrastructure) · [Products](#products) · [Infrastructure](#infrastructure) · [Hackathons](#hackathons) · [Teaching](#teaching--courses) · [Also Built](#also-built)

---

## Flagship Platforms

### Signal & Structure AI — AI Discoverability Platform
> Helps businesses get found and accurately represented by AI assistants like ChatGPT, Claude, and Gemini.

![Status](https://img.shields.io/badge/Status-Production-success) ![Started](https://img.shields.io/badge/Started-2023-informational) [![Live](https://img.shields.io/badge/Live-signalstructure.ai-blue)](https://signalstructure.ai)

Full AI discoverability platform with four production MCP servers (Signal Watch, Signal Pulse, Signal Advisor, Knowledge Base) connected directly into Claude. Scans websites for schema markup quality, checks AI platform mentions across every major model, and generates prioritized action plans. Multi-tenant client portal has three role-based dashboards (owner, client, VA), automated lead generation, and a research-backed white paper on AI discoverability.

`Python` `FastAPI` `Supabase` `Railway` `MCP Protocol` `Claude API`

---

### StormIQ — Municipal Compliance Platform
> AI-powered tools for stormwater professionals and municipal operators.

![Status](https://img.shields.io/badge/Status-Deployed_·_Pilot_Recruitment-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

21-product platform for MS4 stormwater compliance. AI photo analysis using computer vision for field inspection reports, automated narrative generation from voice-to-text field notes, and compliance tracking dashboards. Targeting 122 NC MS4 permittees as initial market. Five-service Railway deployment: FastAPI backend, Next.js dashboard, PostgreSQL, MinIO object storage, background worker.

`Python` `FastAPI` `Next.js` `PostgreSQL` `MinIO` `Railway` `Gemini API`

---

### Content Command Center — Multi-Brand Content Operations
> One system serving five brands with AI-powered content generation, scheduling, and automated outreach.

![Status](https://img.shields.io/badge/Status-Deployed-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

Full content ops platform. Automated prospecting pipeline: Google Places API discovers leads at 1 PM, email scraper pulls contacts, Signal Engine scores them, AI drafts outreach at 2 PM, approved emails send at 8:47 AM next day. Brand voice enforcement across LinkedIn, email, Skool, and Circle with banned-word filtering and per-brand tone rules. Each of five ventures has its own sender domain, voice profile, and audience context.

`Next.js` `Python` `Supabase` `Railway` `Google Places API` `Claude API` `Resend`

---

### The Drop — AI Content Intelligence
> Replaces hours of video watching with a daily AI-curated digest from 21+ sources.

![Status](https://img.shields.io/badge/Status-Deployed_·_Voice_Mode_Live-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

Monitors YouTube channels and RSS sources, auto-transcribes and summarizes new content, delivers a formatted daily digest with audio playback via OpenAI TTS. Webshare rotating residential proxy handles YouTube access at scale. Topic-based discovery in roadmap.

`Python` `Railway` `YouTube API` `OpenAI TTS` `Claude API` `Supabase`

---

### CueBoard — Zoom Meeting Control Plugin
> Hardware button surface for Zoom meeting management. Logitech MX Creative Console plugin.

![Semifinalist](https://img.shields.io/badge/Logitech_Hackathon-Semifinalist_·_Top_50_of_1%2C300%2B-gold) ![Status](https://img.shields.io/badge/Status-Functional-informational)

C#/.NET 8 plugin for the Logitech MX Creative Console. 34 mapped actions across 3 pages: quick controls (mute, spotlight, breakout rooms), host tools (flag moments, assign tasks, take notes, export summary), and accessibility controls (captions, timer, participant management). Reached semifinalist round (top 50 of 1,300+ participants). Submission ultimately withdrawn due to health circumstances.

`C#` `.NET 8` `Logitech Actions SDK` `Zoom SDK`

---

### Course Canon — AI Course & Presentation Evaluator
> Evaluates presentations and teaching quality, gives structured feedback.

![Status](https://img.shields.io/badge/Status-Deployed-success) ![Started](https://img.shields.io/badge/Started-2026-informational)

Next.js 14 web UI with Supabase brand library. Generates branded course outlines and materials, ZIP download, delivery pipeline wired to Gumroad webhook with daily cron enrollment emails via Resend.

`Next.js` `Supabase` `Railway` `Claude API` `Resend`

---

## Life OS — Personal Infrastructure

The systems that let me run five ventures in parallel without losing context, dropping leads, or missing deadlines. All deployed, all running daily.

### CORE — Persistent Memory & Decision System
Never-pruned decisions log, cross-session status tracking, per-venture context files, personal logistics, and health-aware scheduling. Slash commands (`/log`, `/summary`, `/log-chat`) route every session's output to the right place automatically. Every tool I build reads from CORE first.

`Markdown` `YAML` `Claude Code`

---

### Daily Briefing Agent
6:30 AM email pulling from Google Calendar, Opportunity Tracker, Personal CRM, book launch tracker, and a 14-day holiday/awareness calendar. Claude Haiku generates a health-aware 4-part recommendation: PRIMARY / WHY / SECONDARY / SKIP TODAY. Deployed on Railway.

`Python` `Railway` `Claude API` `Supabase` `Resend` · [Repo](https://github.com/TKHatton/daily-briefing)

---

### What's Next Agent
CLI agent that reads across Opportunity Tracker, Personal CRM, Routine Anchor, and book launch status to output a single structured daily recommendation. Health-aware (recovery days, infusion schedule). `python agent.py` gives the answer in seconds.

`Python` `Claude API` `Supabase` · [Repo](https://github.com/TKHatton/whats-next)

---

### Weekly Review Agent
Sunday 8 AM email summarizing the week: OT wins and pipeline, CRM interactions, habit streaks, book launch status. Claude Haiku generates a headline and three priorities. Deployed on Railway.

`Python` `Railway` `Claude API` `Supabase` `Resend` · [Repo](https://github.com/TKHatton/weekly-review)

---

### Opportunity Tracker
Revenue pipeline CLI with 13 active opportunities, automated priority scoring, and daily HTML email summary (overdue, due today, this week, top revenue). $82K tracked pipeline across all ventures.

`Python` `Typer` `Supabase` `Railway` `Resend` · [Repo](https://github.com/TKHatton/opportunity-tracker)

---

### Personal CRM
Relationship intelligence for a solo operator across 24 contacts: family, leads, collaborators, mentors, community. Fuzzy name matching, interaction logging, follow-up tracking, daily email reminders. 14 CLI commands.

`Python` `Click` `Supabase` `Railway` · [Repo](https://github.com/TKHatton/personal-crm)

---

### Client Onboarding
CLI that adds a new client to the CRM, creates an Opportunity Tracker entry, and sends a venture-specific welcome email — all in one command. Four ventures supported: DJ Academy, Course Cannon, Digital Jaywalking, StormIQ. Each has its own HTML email template and tone.

`Python` `Supabase` `Resend` · [Repo](https://github.com/TKHatton/client-onboarding)

---

### Routine Anchor
Nightly SMS check-in system. Texts 5 questions at 9 PM, parses free-text replies, logs to Supabase, tracks streaks. Code complete, pending second Twilio number for personal use.

`Python` `FastAPI` `Twilio` `Supabase` · [Repo](https://github.com/TKHatton/routine-anchor)

---

### Financial Runway Tracker
Next.js 14 + SQLite dashboard tracking income, expenses, burn rate, and projected runway. Pulls weighted pipeline from Opportunity Tracker for revenue projections. Daily email cron. Built, pending Railway deploy.

`Next.js` `SQLite` `Railway` `Resend` · [Repo](https://github.com/TKHatton/financial-runway)

---

## Products

Tools I built, packaged, and sell.

### InboxToSheet — Email-to-Spreadsheet Automation
Four Google Apps Scripts that read incoming emails, extract structured data, and write it to the correct spreadsheet tab automatically — every 5 minutes, no manual input. Security hardening, daily validation, Excel migration tool, and an AI customization prompt included. No coding required.

**$67 one-time** · [Landing page](https://inbox2sheet.netlify.app/) · [Buy on Gumroad](https://jaywalker73.gumroad.com/l/inbox2sheets)

`Google Apps Script` `Gmail API` `Google Sheets API`

---

### FolderSort — Automated File Organization
Desktop app that scans folders and sorts files into clean structures based on rules set once. Preview mode before anything moves. Full undo with backup manifest. File watcher for ongoing auto-sort. Duplicate and temp file cleanup advisor. Windows exe — no Python install needed.

**$97 one-time** · [Landing page](https://foldersort.netlify.app/) · Gumroad listing coming soon

`Python` `PyInstaller` `CustomTkinter` `SQLite`

---

### Protect Your Genius — Book
*Using AI Without Diluting Your Voice.* Thought leadership on maintaining creative and intellectual identity in an AI-augmented world. Kindle published April 22, 2026. Paperback launch May 4, 2026.

[Kindle on Amazon](https://amazon.com) · Paperback May 4, 2026

---

## Infrastructure

### MAOS — Meta-Agentic Operating System
12-component modular multi-agent system architecture across five layers: orchestration, intelligence, execution, memory, and meta. Blueprint complete. Build sequence starts with schema-driven design. Foundation for all future agent work.

---

## Hackathons

| Hackathon | Project | Result |
|-----------|---------|--------|
| Logitech CueBoard | CueBoard Zoom Plugin | Semifinalist — Top 50 of 1,300+ |
| Google Gemini 3 ($50K) | Sewer Sentinel (StormIQ) | Did not place |
| Google Live Agent | Adaptive Drive | Results pending |
| Auth0 | Signal Vault | Results pending |

---

## Teaching & Courses

20+ years of teaching experience, now applied to AI education across Girl Scouts, enterprise teams, and working professionals.

- **Building Agentic Systems That Actually Work** — 90–120 min advanced course on capability-scoped agent design, multi-layer infrastructure, and cost optimization
- **Agents Without the Jargon** — Beginner-friendly, opens with a live demo before definitions
- **Run Better Meetings with AI** — Half-day workshop for meeting-heavy professionals
- **AI in the Wild** — Girl Scout AI badge curriculum across all age levels
- **Start Smart: From Avoiding AI to AI Confidence** — 5-day email drip course
- **AI and Emotional Intelligence** — Conference presentation

---

## Also Built

- **Daily Clarity** — AI thinking assistant with 5 tools: Mind Dump, Find Words, Decision Helper, Write The Hard Thing, Quick Reset. Free. [Live](https://dailyclarity.netlify.app/) · [Repo](https://github.com/TKHatton/Daily-Clarity) · `React` `TypeScript` `Gemini API`
- **PageSpeak** — Chrome extension for text-to-speech accessibility. Reads articles, documents, and PDFs aloud. `JavaScript` `Chrome Extension API` `Web Speech API`
- **Signal Vault** — Encrypted credential storage for multi-service Railway deployments. Auth0 hackathon submission. `Python` `Railway`
- **Proof of Work** — Build documentation CLI. Captures projects with screenshots, tech stack, outcomes in under 60 seconds. [Repo](https://github.com/TKHatton/proof-of-work) · `Python`
- **Adaptive Drive** — Google Live Agent hackathon submission.
- **Build Catalog** — This repo. The public record of everything above.

---

## Let's Work Together

I build AI systems that actually run in production. Not prototypes, not demos. If you need agents, automations, or AI-powered platforms, let's talk.

**Find me on:** [Contra](https://contra.com/Lenise_Kenney) · [LinkedIn](https://www.linkedin.com/in/lenise-kenney/) · [Digital Jaywalking](https://digitaljaywalking.com)
