# What I Build

I design and deploy AI-powered systems. From multi-agent platforms to single-purpose automations, everything here solves real problems for real businesses. Everything is built, deployed, and running in production.

**Stack:** Python, Railway, Claude API, Supabase, Netlify, FastAPI, Twilio

---

## Platforms & Operating Systems

### Signal & Structure AI: AI Discoverability Platform
> Helps businesses get found and accurately represented by AI assistants like ChatGPT, Claude, and Gemini.

Built a complete AI discoverability platform with four production MCP servers (Signal Watch, Signal Pulse, Signal Advisor, Knowledge Base) connected directly to Claude. The system scans websites for schema markup quality, checks AI platform mentions across all major models, and generates prioritized action plans.

Includes a multi-tenant client portal with three role-based dashboards (owner, client, VA), automated lead generation, and a research-backed white paper on AI discoverability.

`Python` `FastAPI` `Supabase` `Railway` `Netlify` `MCP Protocol` `Claude API`

---

### StormIQ: Municipal Compliance Platform
> AI-powered tools for stormwater professionals and municipal operators.

21-product platform for MS4 stormwater compliance. Features AI photo analysis using computer vision for field inspection reports, automated narrative generation from voice-to-text field notes, and compliance tracking dashboards.

Currently recruiting first municipal partner for pilot deployment. Five-service Railway deployment: FastAPI backend, Next.js dashboard, PostgreSQL database, MinIO object storage, and background worker. Targeting 7,500+ MS4 operators nationwide.

`Python` `FastAPI` `Next.js` `PostgreSQL` `MinIO` `Railway` `Gemini API` `Computer Vision`

---

### Content Command Center: Multi-Brand Content Management
> One system serving five brands with AI-powered content generation, scheduling, and engagement.

Full content operations platform with automated prospecting (discovers leads via Google Places API), AI-powered response generation across platforms (LinkedIn, email, Skool, WhatsApp), and brand voice enforcement with banned word filtering.

Includes Prospect Mail pipeline with auto-prospecting, draft generation, and scheduled sends. Each brand maintains its own voice profile, tone rules, and audience context.

`Python` `FastAPI` `Railway` `Google Places API` `Claude API` `Supabase`

---

### The Drop: AI Content Intelligence
> Replaces hours of video watching with a daily AI-curated digest from 21+ sources.

Monitors YouTube channels and content sources via RSS, automatically transcribes and summarizes new content, and delivers a formatted daily digest. Voice Mode allows listening to summaries instead of reading. Topic-based discovery lets you request specific subjects and have the system find, transcribe, and summarize relevant content automatically.

`Python` `Railway` `YouTube API` `Whisper` `Claude API`

---

## AI Tools & Products

### Opportunity Tracker: Revenue Dashboard
> Track every open opportunity, deadline, and revenue thread across all ventures.

CLI tool with Supabase backend that manages opportunities across five ventures. Add, update, list, and archive opportunities with auto-calculated priority based on deadline proximity and revenue potential. Daily HTML email summary highlights overdue items, cold leads, top revenue opportunities, and upcoming deadlines. Deployed on Railway as a cron job.

Built and deployed April 14, 2026.

`Python` `Typer` `Rich` `Supabase` `Railway` `smtplib`

---

### Personal CRM: Relationship Intelligence
> Never forget a conversation, follow-up, or connection again.

Contact and relationship management system designed for a solo operator running multiple ventures. Tracks interactions, follow-ups, and relationship context across all business contacts. Links to opportunities for full pipeline visibility.

Built and deployed April 14, 2026.

`Python` `Supabase`

---

### Proof of Work: Build Documentation System
> Automated capture of what you built, when, and how.

System that documents completed builds with screenshots, descriptions, and technical details. Generates proof-of-work artifacts for portfolio use, client credibility, and hackathon submissions.

Built and deployed April 14, 2026.

`Python`

---

### CueBoard: AI-Powered Zoom Meeting Plugin
> Real-time meeting intelligence with audience engagement tools. **Semifinalist: Top 50 of 1,300+ submissions.**

Zoom plugin with 34 actions including live flags, participant assignment, free-text notes, polls, transcript access, and full export. Built for the Logitech CueBoard hackathon. Reached semifinalist round (top 50 out of 1,300+ participants) and currently competing for the top 6 final round.

Three-page interface: quick actions dashboard, keyboard shortcuts panel, and full engagement suite with poll URL injection to Zoom chat.

`JavaScript` `Zoom SDK` `Netlify`

---

### Course Canon: AI Course Evaluator
> Evaluates presentations and teaching quality, gives structured feedback.

AI-powered system that analyzes educational content for structure, engagement, learning objectives alignment, and delivery quality. Multiple audience-specific landing pages: pastors, school presenters, conference speakers, educators.

`Python` `Claude API` `Railway`

---

### PageSpeak: Browser Extension for Accessibility
> Text-to-speech browser extension with intelligent reading capabilities.

Chrome extension that reads any web content aloud. Articles, documents, PDFs. Built with Web Speech API for zero-cost TTS. Designed for accessibility and productivity, particularly for users with dyslexia or visual processing needs.

`JavaScript` `Chrome Extension API` `Web Speech API`

---

### FolderSort: AI File Organization
> Drop files in, get them organized automatically.

AI-powered file sorting that analyzes document content and organizes files into logical folder structures. Currently in beta.

`Python` | Live on Stripe ($67)

---

### InboxToSheets: Email-to-Spreadsheet Automation
> Connects email accounts, extracts structured data, outputs clean spreadsheets.

Automated pipeline that monitors email inboxes, identifies structured data (invoices, receipts, confirmations, reports), and extracts it into organized spreadsheets without manual copy-paste.

`Python` | Live on Stripe ($67 DIY / $500 Done-For-You)

---

## Automation Systems

### Prospect Mail: Automated Lead Generation Engine
> Discovers, researches, and contacts potential clients on autopilot.

End-to-end outreach automation: discovers local businesses via Google Places API, researches their AI readiness, generates personalized outreach emails, and sends on a daily schedule. Full pipeline runs autonomously on Railway with three daily cron jobs (prospect at 1 PM, draft at 2 PM, send at 8:47 AM).

`Python` `Railway` `Google Places API` `Claude API` `SendGrid`

---

### Signal Vault: Secure Credential Storage
> Encrypted credential management for multi-service deployments.

Secure storage system for API keys, tokens, and service credentials across multiple deployed applications. Built for managing credentials across Railway services. Submitted to hackathon.

`Python` `Encryption` `Railway`

---

## Education & Courses

### 20+ Years of Teaching Experience

I create and deliver AI education for audiences ranging from Girl Scouts to enterprise teams.

**Courses Built:**

- **Run Better Meetings with AI.** Complete course, production-ready.
- **Start Smart: From Avoiding AI to AI Confidence.** 5-day email drip course.
- **Complete Guide to AI for Over-Thinkers.** Self-paced course.
- **AI and Emotional Intelligence.** Conference presentation.
- **Building Agentic Systems That Actually Work.** Advanced course (90-120 min) on capability-scoped agent design, multi-layer infrastructure, and cost optimization.
- **Agents Without the Jargon.** Beginner-friendly course that opens with a live demo before definitions.
- **AI in the Wild.** Girl Scout AI badge curriculum across all age levels.

---

## Architecture Work

### MAOS: Meta-Agentic Operating System
> 12-component modular multi-agent system architecture.

Designed a complete multi-agent operating system with five layers: orchestration, intelligence, execution, memory, and meta. Each of the 12 components is independently deployable but works as a unified system. Built on the principle that 5-8 capability-scoped agents backed by strong infrastructure beats 40 single-task agents on cost, speed, accuracy, and reliability.

Architecture documented. Build sequence starts with schema-driven design.

---

## Currently Building

New systems in active development. Details available on request.

- Automated daily briefing agent
- Client onboarding automation
- AI avatar content pipeline
- Content repurposing engine

---

## Hackathon Track Record

| Hackathon | Project | Status |
|-----------|---------|--------|
| Logitech CueBoard | CueBoard Zoom Plugin | **Semifinalist (Top 50 of 1,300+), advancing to final round** |
| Google Gemini 3 | Sewer Signal (StormIQ) | Submitted, awaiting results ($50K prize) |
| Google Live Agent | Adaptive Drive | Submitted, awaiting results |
| Auth0 | Signal Vault | Submitted, awaiting results |

---

## Let's Work Together

I build AI systems that actually run in production. Not prototypes, not demos. If you need agents, automations, or AI-powered platforms, let's talk.

**Find me on:** [Contra](https://contra.com) | [LinkedIn](https://linkedin.com)
