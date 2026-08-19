<div align="center">
  <img src="assets/banner.png" alt="" width="100%" />
</div>

<br />

<div align="center">
  <img src="assets/avatar.png" alt="Frans Elstadt" width="168" />
  &nbsp;&nbsp;
  <img src="assets/mascot.png" alt="" width="92" />
</div>

<h1 align="center">Frans Elstadt</h1>

<p align="center">
  <strong>Senior .NET &amp; Cloud Engineer</strong> · Architect · Founder<br />
  California, US · 15+ years shipping systems that have to stay up
</p>

<p align="center">
  <a href="https://elstadt.com"><img src="https://img.shields.io/badge/elstadt.com-0A0A0A?style=for-the-badge" alt="elstadt.com" /></a>
  <a href="https://github.com/franselstadt"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://x.com/franselstadt"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://linkedin.com/in/frans-elstadt"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:franselstadt@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Sans&weight=600&size=22&duration=3200&pause=1400&color=E8EEF5&center=true&vCenter=true&width=780&lines=I+design+the+system.+Then+I+ship+it.;IFRS+%2F+GAAP+%2F+XBRL+audit+platforms;EMV+%C2%B7+ISO+8583+%C2%B7+PAIN+XML+payment+rails;1%2C200-truck+logistics+with+zero+downtime+migrations;National+health+registries+under+government+SLA" alt="roles" />
</p>

---

I build **regulated, money-moving, SLA-bound software** — and I own it past the demo.

C# / .NET and SQL are the spine. Around that: event-driven backends, multi-tenant SaaS, industrial hardware, and cloud that has to survive real operators, real banks, and real auditors. I have led six-engineer teams, founded and run production platforms as the sole engineer, and taken systems from a WinForms monolith to cloud-native without taking the business down.

| | | | |
|:---:|:---:|:---:|:---:|
| **15+** | **4** | **1,200** | **20,000+** |
| years shipping | continents live | trucks on one platform | insurance reports / year |
| **6** | **5** | **1/3** | **100th** |
| engineers led | major banks integrated | of baseline report time | %ile AWS Networking |

<p align="center">
  <img src="https://img.shields.io/github/followers/franselstadt?style=flat-square&label=GitHub%20followers&color=238636" alt="followers" />
  <img src="https://img.shields.io/badge/LinkedIn-2%2C000%2B%20followers-0A66C2?style=flat-square" alt="linkedin" />
  <img src="https://img.shields.io/badge/US%20authorized-to%20work-111111?style=flat-square" alt="work auth" />
  <img src="https://img.shields.io/badge/Open%20to-remote%20or%20US%20onsite-111111?style=flat-square" alt="open" />
</p>

---

## What I actually shipped

### Draftworx — global audit platform
**Senior Software Engineer** · May 2024 – Mar 2026 · remote

Architected a **multi-tenant C# .NET + SQL Server** audit suite on **US GAAP, UK IFRS, and XBRL**, live with firms across **Europe, Africa, Australia, and the United States** — including banks on SWIFT rails and government / law-enforcement agencies.

- Led **6 engineers**: sprint planning, reviews, architecture, C-suite reporting, daily releases across time zones.
- REST + microservices on **RabbitMQ / Kafka**, versioned APIs that do not break globally integrated clients.
- Rewrote financial report SQL from execution plans: index strategy, N+1 elimination, set-based refactoring; C# async / pooling / memory work on the hot path.
- Code-first UI abstraction over Infragistics so the team composed screens the same way.
- Cloud-agnostic CI/CD: same product, **Azure or AWS CLI** selected by pipeline parameter — no forked codebase for client cloud mandates.
- ERP adjacency: **Sage, SAP, IBM Cognos TM1, QuickBooks, Pastel**.

### Mitig8 — national insurance SaaS, built solo
**Founder / Senior Software Engineer** · Elstadt Industries · Apr 2023 – May 2024

<p>
  <img src="assets/mitig8.png" alt="Mitig8" height="36" />
</p>

I designed, wrote, billed, secured, and operated **[Mitig8](https://github.com/franselstadt/Mitig8-WEB)** — a multi-tenant platform connecting insurers, brokers, and field surveyors across South Africa. **20,000+ reports a year** for **Bryte, Discover, and all five major SA banks**.

- Full stack: schema, REST APIs, quoting, valuations, surveys, wallets, invoices, PDFs, production ops.
- Payment rails I owned end-to-end: **EMV**, **ISO 8583**, **QR wallets**, **PAIN XML** batch settlement, reconciliation, audit trails.
- 24/7 incident response across web, mobile, and Linux embedded firmware. One operator. No integrity failures.

The original production web is in this org: [`Mitig8-WEB`](https://github.com/franselstadt/Mitig8-WEB) — Database First EDMX, 80+ tables, 200+ procedures, now being lifted onto Domain / Application / Architecture / Infrastructure.

### City Logistics — 1,200-truck national supply chain
**Staff Software Engineer** · Feb 2016 – Oct 2022

Six years on the software that ran a **nationwide fleet**: warehouse, parcel scan, on-route telematics, costing, KPI, finance.

- Built **OnRoute** from scratch: customer app (live tracking / ETA), dispatch (routing + load approval), back office (ABC costing, SLA).
- **Zero-downtime MS SQL → PostgreSQL** on a live fleet. Parcel / telematics reports to **one-third of baseline**; CPU cost down with it.
- Shop floor: **Honeywell / Zebra** Android PDAs, Datamax (ZPL/DPL/PCL), Twain, Bluetooth industrial scales, serial legacy kit.
- IBM **Planning Analytics (TM1)** as the CFO’s source of truth — TurboIntegrator loads from **SAP** and **Sage VIP**.
- Daily multi-region CI/CD without breaking SLA-bound ops. WinForms monolith → Java / Go services + cloud web.

### WAM Technology — government health + industrial ops
**Lead Software Engineer** · Nov 2022 – May 2023

- Delivered the **South African TB / HIV national registry** under government SLA: multi-agency, audit-grade governance, no room for bad data.
- Introduced **DDD** (bounded contexts, ubiquitous language) across the org’s systems.
- **Donkerhoek**: custom payroll for hundreds of seasonal workers, Android Bluetooth piecework weighing on industrial scales, ESP32 conveyor boards.
- Custom **ESP32** diagnostic device: camera + Linux, **TensorFlow** on Ziehl-Neelsen / auramine O slides for TB — see also [`Detecting_Tuberculosis_CNN`](https://github.com/franselstadt/Detecting_Tuberculosis_CNN).

### Hatronika / City Venture Capital — AWS IoT + diligence
**Software Architect / CTO (concurrent)** · Apr 2023 – May 2024

- Owned the **PP500** solar IoT backend on **AWS (EC2, S3, RDS)**: schema, payment gateway, LoRaWAN topology (terminals → clusters → sites → devices → firmware).
- CTO diligence for City Venture Capital: architecture review, 65M ZAR ask, hardware path off Raspberry Pi onto industrial boards.

---

## Public systems & proofs of work

I do not argue capability in the abstract. I put a running system on the table.

<p align="center">
  <img src="assets/merced.png" alt="City of Merced" height="42" />
  &nbsp;&nbsp;&nbsp;
  <img src="assets/winchoice.png" alt="WinChoice" height="42" />
  &nbsp;&nbsp;&nbsp;
  <img src="assets/mitig8.png" alt="Mitig8" height="42" />
</p>

| System | What it is | Link |
| --- | --- | --- |
| **CityOps Merced** | Full government-ops platform: DDD bounded contexts, GASB accounting, CA regulatory rules, vendor adapters, GIS, WebRTC + live AI transcription, Azure Functions with AWS Lambda twins documented beside them. Built to show what I mean by “enterprise.” | [merced.elstadt.com](https://merced.elstadt.com) |
| **BunEHR** | Production-shaped EHR on the **openEHR REST API v1** — Bun, Hono, Drizzle, PostgreSQL 16. | [`BunEHR`](https://github.com/franselstadt/BunEHR) |
| **Mitig8 WEB** | Original national insurance web: assessments, valuations, surveys, quotes, wallets. | [`Mitig8-WEB`](https://github.com/franselstadt/Mitig8-WEB) |
| **WinChoice Ops** | Operations / benefits-style platform work — clean architecture, domain boundaries, ops workflows. | portfolio |
| **TrajanOne** | Case / medical-record style platform in C#. | [`TrajanOne`](https://github.com/franselstadt/TrajanOne) |
| **KitchenOS** | C# product system. | [`KitchenOS`](https://github.com/franselstadt/KitchenOS) |
| **TheTimes** | C# system. | [`TheTimes`](https://github.com/franselstadt/TheTimes) |
| **TB CNN** | CNN pipeline for bacilli detection on stained slides. | [`Detecting_Tuberculosis_CNN`](https://github.com/franselstadt/Detecting_Tuberculosis_CNN) |
| **House of Elstadt** | The house brand. Built on the Rock, or not built. | [elstadt.com](https://elstadt.com) |

---

## How I design

Dependencies point **inward**. Domain does not know about SQL, HTTP, or a cloud SDK. If a domain project references EF, the **compiler** fails the build.

```
Presentation / Functions / Web
        │
Application  (use cases, CQRS)
        │
Domain       (Items, Collections, rules — no IO)
        │
Infrastructure  (SQL, brokers, AWS/Azure as plugins)
```

I have been doing this in production for a long time — including **gmvTM-style** persistable `BaseItem` / `BaseCollection` (sync + async CRUD) and ViewItems for read models. Swap the broker (`IEventBus` → RabbitMQ, Kafka, or in-memory for tests) without rewriting the business.

Hot paths: I write the SQL. Execution plans, indexes, set-based work. Dapper when the plan matters; an ORM when schema velocity matters. Same discipline on Dynamo/Cosmos: access pattern first, partition key second.

---

## Stack I will go to war with

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,azure,aws,postgres,sqlite,git,docker,kubernetes,linux,react,ts,nodejs,vscode" alt="stack" />
</p>

**Languages** — C# / .NET (Core, ASP.NET, WPF, WinForms, Blazor), SQL, TypeScript / JavaScript, Java EE, Go, Node, PHP  

**Data** — SQL Server, PostgreSQL, AWS RDS, Cosmos DB, SQLite · query plans, indexing, zero-downtime cutovers, stored procedures, custom ORMs  

**Cloud** — AWS (EC2, S3, RDS, IAM, VPC — **100th percentile Networking**), Azure (App Services, Functions, **AI Fundamentals**), Terraform / ARM, Docker, Kubernetes, Azure DevOps  

**Integration** — REST, SOAP, RabbitMQ, Kafka, SAP, Sage, IBM TM1, QuickBooks, Pastel, SWIFT  

**Payments** — EMV, ISO 8583, PAIN XML, QR wallets, reconciliation, audit trails  

**Hardware** — Zebra / Honeywell PDAs, Datamax, industrial scales, ESP32 / STM32 / Raspberry Pi, LoRaWAN  

**Certs** — AWS Networking 100th %ile · Azure AI Fundamentals · MCSD · ASCP · IBM TM1 10.1 · CS50x · CCNA I · Remote team mgmt 91st %ile  

**Education** — B.Tech Computer Software Engineering, Nelson Mandela University · Accounting Sciences, UNISA

---

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=franselstadt&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=franselstadt&layout=compact&theme=transparent&hide_border=true&langs_count=8" alt="languages" />
</p>

Public GitHub is the **lab and the receipts**, not the full production estate. The 1,200-truck platform, the bank rails, and the government registry lived behind firewalls. What is here is what I can show: Mitig8, BunEHR, CityOps, TrajanOne, and the rest.

---

<div align="center">
  <img src="assets/daisy.png" alt="Daisy" width="280" />
  <p><sub>Daisy. Still the quality bar for loyalty and persistence.</sub></p>
</div>

---

<p align="center">
  <strong>Let’s build something that has to work on Monday morning.</strong><br />
  <a href="https://elstadt.com">elstadt.com</a> ·
  <a href="https://merced.elstadt.com">merced.elstadt.com</a> ·
  <a href="mailto:franselstadt@gmail.com">franselstadt@gmail.com</a> ·
  <a href="https://x.com/franselstadt">@franselstadt</a> ·
  <a href="https://linkedin.com/in/frans-elstadt">LinkedIn</a>
</p>

<p align="center">
  <sub>Unless the Lord builds the house, the builders labor in vain. — Psalm 127:1</sub>
</p>
