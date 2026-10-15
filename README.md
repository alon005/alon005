### Hi, I'm Alon 👋

**Co-Founder · CTO & Head of AI** at Locksmith Connections, a US locksmith dispatch brand that has served close to one million customers since 2013.

I build AI-native systems that run a real business end to end: the CRM, an AI voice agent that answers and books calls, AI quality auditing, fraud detection, and the cloud and DevOps behind them. I work by directing AI coding agents (Claude Code): I set the requirements, make the product and architecture decisions, and verify every release.

---

#### What I've built

**Ava Connects** · multi-tenant SaaS CRM · *2026*
Replaced Workiz for the whole business: jobs, dispatch to technicians, SMS and WhatsApp messaging, payments and settlements, reporting. Live since 10 Aug 2026: 5,500+ jobs, 9,700+ inbound calls and 44,000+ SMS in its first ten weeks.
Automation-first: most of the operation runs on deterministic rules that read the data and act on it; AI models are used only where they add real value (call summaries, judgment calls), which keeps it fast, predictable and cheap. The database is profiled and tuned (indexes, query rewrites).
`Cloudflare Workers` `TypeScript` `Hono` `Neon Postgres (row-level security)` `React` `Twilio` `RingCentral` `Google Ads`

**Ava** · AI voice agent · *2026*
Answers the company's calls and books jobs into the CRM through tool calls. An AI judge decides which dropped callers she calls back, and every change is replayed against real calls before release. 639 calls answered and 306 jobs booked on her own since go-live.
`Retell` `Gemini` `LLM tool design`

**Team operations on WhatsApp** · *part of Ava Connects*
The company runs its day inside WhatsApp groups, and this layer drives them: AI-written daily and intraday analyses for the founders and the agents, report cards rendered as images of the CRM's live dashboard, instant alerts with call recordings and voice clips (possible lost leads, escalations, callbacks, customer payment findings), and automatic reactions to the team's messages. Every send is scheduled, de-duplicated, logged and editable from the CRM's settings.
`WhatsApp API (WHAPI)` `Twilio` `Gemini` `Cloudflare Workers` `automated dashboard screenshots`

**AI quality auditing**
AI audits of call-center calls and agent performance, checked against the CRM's own data.
`Gemini` `Google Apps Script`

**The master dashboard** · *before 2026*
One view across Workiz (API), Google Ads and RingCentral VoIP, to run the call center, the leads and the money.
`Google Apps Script` `Workiz API` `Google Ads` `RingCentral`

**The company websites**
The PPC landing pages and the organic site: built and run on WordPress for years, with conversion tracking I implemented by hand; rebuilt on Cloudflare in 2026.
`Cloudflare` `WordPress` `Google Ads conversion tracking`

---

The code for these projects is private because it runs a live business. I'm happy to walk through it or share access on request.

📫 [LinkedIn](https://www.linkedin.com/in/alonschneidman) · alon005@gmail.com
