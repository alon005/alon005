### Hi, I'm Alon 👋

**Founder & CTO · Growth & AI Automation**

For 13 years my core expertise has been advanced Google Ads architecture and campaign management, with conversion tracking built for call centers and lead-generation businesses: tracking that follows a click through the phone call to the finished job and the profit it made.

I'm a co-founder of Locksmith Connections, a US locksmith dispatch brand founded in 2013 that has served close to one million customers.

In 2026 I founded Ava Connects, my own AI-native SaaS CRM for field-service businesses. I build it by directing AI coding agents (Claude Code): I set the requirements, make the product and architecture decisions, and verify every release.

---

#### What I've built

**[Google Ads architecture & conversion tracking](https://github.com/alon005/google-ads-architecture)** · *2013 – present*

A US-wide account for a call-center business: at its peak about 9,500 campaigns and a few hundred thousand keywords across 40+ states and 100+ cities. Call tracking per market, offline conversions with each finished job's real value, Target ROAS on profit, and the landing pages behind it.

`Google Ads` `Target ROAS` `offline conversions` `call tracking` `landing pages`

**[Ava Connects](https://github.com/alon005/ava-connects)** · multi-tenant SaaS CRM · *2026*

Replaced a commercial field-service platform (Workiz) for a whole live operation: jobs, dispatch to technicians, SMS and WhatsApp messaging, payments and settlements, reporting. Live since 10 Aug 2026: 5,500+ jobs, 9,700+ inbound calls and 44,000+ SMS in its first ten weeks.

Automation-first: most of the operation runs on deterministic rules that read the data and act on it; AI models are used only where they add real value (call summaries, judgment calls), which keeps it fast, predictable and cheap. The database is profiled and tuned (indexes, query rewrites).

Secure and recoverable: passkey sign-in, a live sessions monitor, role-based permissions on every route, rate limiting, signed webhooks, health checks with alerts, and a separate recovery console that backs up and restores both the code and the database.

`Cloudflare Workers` `TypeScript` `Hono` `Neon Postgres (row-level security)` `React` `Twilio` `RingCentral` `Google Ads`

**[Ava](https://github.com/alon005/ava-voice-agent)** · AI voice agent · *2026*

Answers a field-service company's calls and books jobs into the CRM through tool calls. An AI judge decides which dropped callers she calls back, and every change is replayed against real calls before release. 639 calls answered and 306 jobs booked on her own since go-live.

`Retell` `Gemini` `LLM tool design`

**[AI QA & coaching system](https://github.com/alon005/ai-qa-coaching)** · *integrated into Ava Connects*

Calls go to Gemini, recording and transcript, to be analysed for how each one was handled. The system writes QA coaching messages for the agents and keeps a running database of performance analyses for both call-center agents and technicians, all inside the CRM.

`Gemini` `call recordings & transcripts` `Cloudflare Workers` `Postgres`

**[Operations reporting](https://github.com/alon005/ops-reporting)** · *part of Ava Connects*

A live performance dashboard on the CRM's home page: the day, the week, agents, technicians and the call center. Snapshots of it go out to the team's WhatsApp groups on a schedule, and every hour the numbers go to Gemini for a written analysis of the agents and the call center. Plus instant alerts with call recordings and voice clips (possible lost leads, escalations, callbacks, customer payment findings) and automatic reactions to the team's messages.

`WhatsApp API (WHAPI)` `Twilio` `Gemini` `automated dashboard screenshots`

**[The master dashboard](https://github.com/alon005/master-dashboard)** · *before 2026*

One view across Workiz (API), Google Ads and RingCentral VoIP, to run the call center, the leads and the money.

`Google Apps Script` `Workiz API` `Google Ads` `RingCentral`

---

Each project above has its own page. The code is private because it runs a live business; I'm happy to walk through it or share access on request.

📫 [LinkedIn](https://www.linkedin.com/in/alonschneidman) · alon005@gmail.com
