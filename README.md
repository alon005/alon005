### Hi, I'm Alon 👋

**Co-Founder · CTO & Head of AI** at Locksmith Connections, a US locksmith dispatch brand that has served close to one million customers since 2013.

I build AI-native systems that run a real business end to end: the CRM, an AI voice agent that answers and books calls, AI quality auditing, fraud detection, and the cloud and DevOps behind them. I work by directing AI coding agents (Claude Code): I set the requirements, make the product and architecture decisions, and verify every release.

---

#### What I've built

**[Ava Connects](https://github.com/alon005/ava-connects)** · multi-tenant SaaS CRM · *2026*

Replaced Workiz for the whole business: jobs, dispatch to technicians, SMS and WhatsApp messaging, payments and settlements, reporting. Live since 10 Aug 2026: 5,500+ jobs, 9,700+ inbound calls and 44,000+ SMS in its first ten weeks.

Automation-first: most of the operation runs on deterministic rules that read the data and act on it; AI models are used only where they add real value (call summaries, judgment calls), which keeps it fast, predictable and cheap. The database is profiled and tuned (indexes, query rewrites).

Secure and recoverable: passkey sign-in, a live sessions monitor, role-based permissions on every route, rate limiting, signed webhooks, health checks with alerts, and a separate recovery console that backs up and restores both the code and the database.

`Cloudflare Workers` `TypeScript` `Hono` `Neon Postgres (row-level security)` `React` `Twilio` `RingCentral` `Google Ads`

**[Ava](https://github.com/alon005/ava-voice-agent)** · AI voice agent · *2026*

Answers the company's calls and books jobs into the CRM through tool calls. An AI judge decides which dropped callers she calls back, and every change is replayed against real calls before release. 639 calls answered and 306 jobs booked on her own since go-live.

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

**[The company websites](https://github.com/alon005/lc-websites)**

The PPC landing pages and the organic site: built and run on WordPress for years, with conversion tracking I implemented by hand; rebuilt on Cloudflare in 2026.

`Cloudflare` `WordPress` `Google Ads conversion tracking`

---

Each project above has its own page. The code is private because it runs a live business; I'm happy to walk through it or share access on request.

📫 [LinkedIn](https://www.linkedin.com/in/alonschneidman) · alon005@gmail.com
