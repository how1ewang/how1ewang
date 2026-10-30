<a href="https://how1ewang.github.io/">
  <img alt="Howie Wang — AI-native solutions engineer. From first conversation to live product, one person with AI agents." src="assets/banner.svg" width="100%">
</a>

<p align="center">
  <a href="https://how1ewang.github.io/"><b>how1ewang.github.io</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:howiewang122@gmail.com">howiewang122@gmail.com</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://how1ewang.github.io/Howie_Wang_Resume.pdf">Résumé (PDF)</a>
</p>

<br>

I take a business from first conversation to live product on my own, with AI agents doing the build. Alongside a Master of IT at UNSW (graduating December 2026), I spent the past year as the only person on a biotech company's commerce platform — discovery, every screen and integration, the servers, the filings, the staff manuals and day-to-day support — with Cursor and then Claude Code writing the code under my direction: eleven partner systems, 67 releases, 900+ members.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img alt="67 releases · 900+ members · 17 product areas · 20 countries · 11 partner integrations · 1 person and AI agents" src="assets/stats-light.svg" width="100%">
</picture>

## How I build — one person, a team of AI agents

- **AI agents are the build team.** Cursor from the first commit, Claude Code since October 2026 — often several sessions at once: a server upgrade, a credential rotation and a media migration ran in the same week.
- **I own the what and the why.** The owner's goals become written specs and acceptance checks; a prompt template, Cursor rules, an AGENTS.md and persistent agent memory give every session the same context.
- **Verify, don't trust.** 760+ automated tests, scripted audits of every console screen, Mini Program page, API endpoint and media file, and my own test on a real phone before a release goes to WeChat review.
- **Guardrails before speed.** Hash-verified deploys that refuse stale code and roll back on their own; production, payment and credential changes wait for my approval.

This profile and [how1ewang.github.io](https://how1ewang.github.io/) were built the same way.

## Case study

### YuanQiPai — integrated commerce platform &nbsp;<sub>2025 – present · sole builder, with AI agents</sub>

A biotech company sells health products through a dealer network and directly to consumers on WeChat. It ran on disconnected tools: no single view of members, dealers, orders or commissions, and every marketing change needed outside help.

- **Discovery & scope** — mapped how members, dealers, orders and money actually moved, then shaped that into 17 product areas with a phased plan: storefront first, loyalty and dealer tools next, content and training after.
- **Implementation & integration** — a WeChat Mini Program storefront (60 screens), a staff console (100+ screens), the platform behind them, and a stand-alone registration tool; 11 partner systems integrated for payments, sign-in, ERP fulfilment, cloud media and notifications — including request signing where no SDK existed.
- **Go-live** — WeChat platform compliance, entity-change filing, food-seller registration paperwork, domain and HTTPS, a launch-readiness checklist, a zero-downtime data migration.
- **Training & support** — an illustrated operations guide so staff run day-to-day changes without a developer; four role-based staff manuals; structured feedback rounds turned into 67 releases; on call when something broke.
- **Decisions that mattered** — a drag-and-drop page builder so marketing never waits for a developer; commission rules as console settings rather than code; automatic refunds for payments that arrive after cancellation.

The source is private (client code). The full case study, with the decisions and their outcomes, is on [the site →](https://how1ewang.github.io/#work)

### Selected integrations

| Partner | What it does for the business | Notable |
|---|---|---|
| WeChat Pay v3 · Alipay · AdaPay | Consumer and dealer payments; refunds through the original channel | One payment abstraction across three providers; late payments after a cancellation are refunded automatically |
| WeChat Login · Order Centre | One-tap sign-in with phone number; orders visible in WeChat's native "My Orders" | Detects new vs. existing customers and merges accounts |
| WeCom (Enterprise WeChat) | Staff single sign-on to the console; contact directory sync | OAuth callback flow |
| Hupun ERP · store platform | Paid orders pushed to ERP and store systems for fulfilment | MD5 / HMAC-SHA256 signing without an SDK; retryable outbound queue so a partner outage never blocks a sale |
| Alibaba Cloud SMS · OSS · MTS | Notifications, media storage with direct upload, video transcoding | HMAC-SHA1 request signing without the vendor SDK |

### Customer Registration System &nbsp;<sub>2026 · sole builder, with AI agents</sub>

Sales staff in 20 countries were collecting customer details on paper. In ten weeks that became a phone form anyone can hand to a customer (3,423-district address picker, ID photo capture, feedback survey), a map dashboard the owner can check at any time, and a signed webhook with retry that keeps the main platform consistent without duplicate records. [Details →](https://how1ewang.github.io/#registration)

## What I bring

| Area | Evidence |
|---|---|
| **AI-native delivery** | One person directing AI coding agents (Claude Code, Cursor) from discovery to support; specs, tests and approval gates keep AI-written code safe in production |
| **Integration & implementation** | 11 partner systems integrated; environments, domains, HTTPS and CDN configured; signing schemes implemented where SDKs were missing |
| **Discovery & requirements** | An owner's goals turned into 17 scoped product areas with a phased plan |
| **Go-live & support** | Launch checklist; zero-downtime migration planned around dealers' business hours; health checks, runbooks, audit logs; first line of support |
| **Enablement & training** | Illustrated operations guide for non-technical staff; four role-based staff manuals and 17 operational documents; feedback rounds turned into prioritised releases |
| **Data & reporting** | Finance reconciliation and exports for the accountant; a map dashboard with four-level drill-down |
| **Compliance & platform administration** | WeChat platform requirements, entity-change filing, food-seller registration |
| **Communication** | English and Mandarin; owners, staff, accountants and vendors' engineers each got the document they needed |

## Technical foundation

**AI:** Claude Code (agentic coding, parallel sessions) · Cursor · spec-driven prompting · reviewing and testing AI output · approval gates for production work

**Stack:** Node.js · Express · PostgreSQL · SQLite · REST APIs · OAuth · Webhooks · WeChat Mini Program · HTML / CSS / JavaScript · WeChat Pay v3 · Alipay · AdaPay · Alibaba Cloud (ECS, OSS, SMS, MTS) · Docker · Nginx · DNS / TLS · GitHub Actions · Jest (760+ tests)

I built all of the above myself, directing AI agents, so I can talk to a customer's engineers as a peer, debug an integration from the logs, and prototype when a slide isn't enough. The engineering deep-dive — architecture, testing, security, annotated code — is at [how1ewang.github.io/engineering](https://how1ewang.github.io/engineering/).

<br>

<p align="center"><sub>Master of IT, UNSW — graduating December 2026 &nbsp;·&nbsp; Open to junior AI solutions engineer, AI implementation and forward deployed engineer roles &nbsp;·&nbsp; Canberra · Sydney · remote &nbsp;·&nbsp; English / 中文</sub></p>
