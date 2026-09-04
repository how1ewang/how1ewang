<a href="https://how1ewang.github.io/">
  <img alt="Howie Wang — One engineer. The whole system." src="assets/banner.svg" width="100%">
</a>

<p align="center">
  <a href="https://how1ewang.github.io/"><b>how1ewang.github.io</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:howiewang122@gmail.com">howiewang122@gmail.com</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://how1ewang.github.io/Howie_Wang_Resume.pdf">Résumé (PDF)</a>
</p>

<br>

I'm a full-stack engineer in Canberra. I design, build, test, ship and operate production software end to end — most recently a complete commerce platform for a biotech company, taken from an empty repository to paying customers, alone.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img alt="126K lines of code · 300+ automated tests · 37 database migrations · 100 UI pages · 11 integrations · 1 engineer" src="assets/stats-light.svg" width="100%">
</picture>

## Selected work

### YuanQiPai — integrated business platform &nbsp;<sub>2025 – present · sole developer</sub>

Admin console (42 pages) · Node.js / Express API (17 route modules, 33 services) · WeChat Mini Program (58 pages) · a stand-alone customer registration system — serving a dealer network and consumer members for a biotech company.

- **Payments** — WeChat Pay v3, Alipay and AdaPay behind one abstraction; a complete refund state machine; payments that land after an order was cancelled are detected and refunded automatically through the original channel.
- **Data** — moved production from JSON files to PostgreSQL with zero downtime using dual-track reads; 37 incremental migrations apply themselves at boot.
- **Security** — Helmet, tiered rate limiting, endpoint-level RBAC, PII masking on list endpoints, audit trails, constant-time token comparison.
- **Integrations** — 11 third-party APIs (WeChat, WeCom, Aliyun SMS / OSS / MTS, Hupun ERP, …); request signing implemented by hand where an SDK was heavy or missing.
- **Quality** — 300+ Jest tests, GitHub Actions CI with a Docker build, ESLint at zero errors; runs on Alibaba Cloud ECS behind Nginx with PM2.

The source is private (client code). The architecture diagram, two annotated code excerpts and the full write-up are on [the site →](https://how1ewang.github.io/#work)

### Customer Registration System &nbsp;<sub>2026 · sole developer</sub>

A stand-alone Node.js + SQLite system for collecting customer records across 20 countries: a 3,423-district cascading selector, an ECharts China map with three-level drill-down, per-IP rate limiting, and an HMAC-signed sync pipeline with exponential back-off that keeps the main platform consistent. [Details →](https://how1ewang.github.io/#registration)

## Stack

| Area | Technologies |
|---|---|
| **Back end** | Node.js, Express, REST API design, JWT + RBAC, PostgreSQL, SQLite |
| **Front end** | HTML / CSS / JavaScript, WeChat native Mini Program (WXML / WXSS / WXS), ECharts |
| **Payments & integrations** | WeChat Pay v3, Alipay, AdaPay, WeChat Login & Order Centre, WeCom SSO, Aliyun SMS / OSS / MTS, Hupun ERP |
| **Cloud & operations** | Alibaba Cloud ECS / OSS / DNS, Docker Compose, Nginx, Let's Encrypt, PM2, GitHub Actions |
| **Quality** | Jest, Supertest, ESLint, miniprogram-ci |

## How I work

No hand-offs. Requirements, schema, code, tests, deployment and the 11 pm on-call were all mine — and so were the consequences. I optimise for systems that hold up: idempotent handlers, migrations that can be reversed, and tests that fail before customers notice.

<br>

<p align="center"><sub>Open to full-stack and back-end roles &nbsp;·&nbsp; Canberra, Australia</sub></p>
