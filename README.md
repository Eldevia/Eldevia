### Elvinas Miltenis · Senior Product & Applied AI Engineer (`Eldevia MB`)

Building production AI platforms, multi-tenant SaaS infrastructure, and high-craft interfaces from **Vilnius, Lithuania (UTC+2)**.

- **Stack:** TypeScript · Bun (`Bun.serve`, native `Bun.sql` / PostgreSQL 17) · React 19 · TanStack Start · React Router v7 · Tailwind CSS v4 · Figma (Apple HIG)
- **Applied AI & Agent Systems:** Multi-Model Adversarial PR Auditing (`Gemini 4 Argon` × `Claude Opus` at `high`/`xhigh` effort) · 10+ Concurrent Subagent Orchestration · Google GenAI (`Gemini Live` WebSockets, `Gemini 3.8 Flash` structured evals, `Gemini Embeddings` RAG) · Anthropic `Claude API` (human-in-the-loop approval gates) · Google Cloud DLP
- **Infrastructure:** Self-managed **ARM64 (`aarch64`)** & **x86_64** Linux fleets · Kamal blue-green zero-downtime deployments · Docker Compose TLS bridge isolation

---

### Shipped Production Systems (Private Commercial Repositories)

1. **[DULTRA (`dultra.lt`)](https://dultra.lt)** — *Enterprise B2B Voice-AI Sales Coaching, Live Call Copilot & Call Evaluation Platform*
   - Dual-mode **Gemini Live** WebSocket audio streaming (interactive voice role-play simulator + silent-listener live call copilot with browser WebAudio VAD).
   - **Gemini Embeddings** vector RAG over company playbooks + **Gemini 3.8 Flash** deterministic post-call JSONB scoring rubrics.
   - Enterprise EU data residency, **Google Cloud DLP** automated PII redaction, **Okta & Microsoft Entra ID SAML/SSO**, and bi-directional **Salesforce / HubSpot / Pipedrive** sync.

2. **[fossil.gg (`fossil.gg`)](https://fossil.gg)** — *Multi-Tenant Gaming Economy, Self-Serve Storefronts & AI Analytics SaaS (2021–2025 Private Discord Engine → 2026 Public Web SaaS)*
   - Evolved from a private headless Discord economy bot launched in **2021** (Discord Bot Snowflake ID `943975987870335006`) into a public multi-tenant web SaaS in **2026**, serving **160,000+ players** and **70,000,000+ logged operations** on zero-ORM **Bun + PostgreSQL 17** (`sslmode=require`).
   - White-label community storefront builder with automated **Stripe Connect** multi-party payouts and Discord slash-command reconciliation.
   - Operator control plane (`app.fossil.gg` on TanStack Start) featuring **Claude API** economy telemetry evaluations behind explicit **human-in-the-loop approval gates**.

3. **[Eldevia Research & Infrastructure (`eldevia.com`)](https://eldevia.com)** — *Applied AI Architecture & GDPR-Compliant Multimodal Systems*
   - Technical papers on GDPR-compliant real-time multimodal AI deployments, latent reasoning, and multi-agent engineering harnesses.

---

### Open-Source & Public Packages
- **[`tw-squircle`](https://github.com/Eldevia/tw-squircle)** — Pure-CSS Apple HIG squircle utility plugin for Tailwind CSS v4 (zero Houdini overhead).
- **[`remix-authjs`](https://github.com/Eldevia/remix-authjs)** — Auth.js integration for Remix / React Router applications (★ 7).

📫 **Contact:** [hello@eldevia.com](mailto:hello@eldevia.com) · [eldevia.com](https://eldevia.com)
