# Frans Elstadt

**Senior Software Engineer** · .NET, Cloud, and Backend Systems  
California, United States · Open to remote or onsite

[Website](https://elstadt.com) · [GitHub](https://github.com/franselstadt) · [LinkedIn](https://linkedin.com/in/frans-elstadt) · [X](https://x.com/franselstadt) · [Email](mailto:franselstadt@gmail.com)

Senior software engineer and architect with 15+ years designing, building, and operating enterprise systems in finance, payments, supply chain, insurance, audit, and public-sector programs. Work spans C# / .NET, SQL Server and PostgreSQL, REST and event-driven services, and AWS / Azure deployment.

| | | | |
| :---: | :---: | :---: | :---: |
| **15+ years** | **4 continents** | **1,200-truck fleet** | **20,000+ reports / year** |
| **6-engineer team lead** | **5-bank payment integrations** | **Zero-downtime DB migration** | **AWS Networking, 100th percentile** |

---

## Experience

### Senior Software Engineer — Draftworx
*May 2024 – March 2026 · Remote*

Multi-tenant C# .NET and SQL Server audit platform supporting US GAAP, UK IFRS, and XBRL. Deployed across audit firms in Europe, Africa, Australia, and the United States, including banking and government tenants.

- Led a team of six engineers (planning, reviews, architecture, stakeholder reporting).
- REST APIs and microservices with RabbitMQ and Kafka; API versioning for integrated clients.
- SQL and C# performance work: execution-plan analysis, indexing, N+1 elimination, async pipeline tuning.
- CI/CD targeting Azure or AWS from the same codebase via pipeline parameters.
- Integrations with SAP, Sage, IBM Cognos TM1, QuickBooks, and Pastel.

### Founder / Senior Software Engineer — Elstadt Industries (Mitig8)
*April 2023 – May 2024*

National multi-tenant insurance platform connecting insurers, brokers, and surveyors. ASP.NET and SQL Server. Source: [Mitig8-WEB](https://github.com/franselstadt/Mitig8-WEB).

- 20,000+ reports annually for Bryte, Discover, and major South African banks.
- Payment integrations: EMV, ISO 8583, QR wallets, PAIN XML batch settlement, reconciliation, and audit trails.
- End-to-end ownership: schema, APIs, billing, security, and production operations.

### Lead Software Engineer — WAM Technology
*November 2022 – May 2023*

- South African TB / HIV national registry under government SLA (audit-grade data governance).
- Introduced domain-driven design (bounded contexts and ubiquitous language).
- Farm payroll and operations system with Android Bluetooth piecework weighing and ESP32 hardware.
- ESP32 diagnostic prototype with TensorFlow slide analysis ([Detecting_Tuberculosis_CNN](https://github.com/franselstadt/Detecting_Tuberculosis_CNN)).

### Software Architect — Hatronika (concurrent)
*April 2023 – May 2024*

AWS-hosted IoT backend for a solar controller network (EC2, S3, RDS), including schema design, payment gateway integration, and LoRaWAN device topology. Technical due diligence for City Venture Capital.

### Staff Software Engineer — City Logistics
*February 2016 – October 2022*

Enterprise software for a 1,200-truck national logistics operation: warehouse management, scanning, telematics, costing, and financial reporting.

- Last-mile suite (customer tracking, dispatch, back office).
- Zero-downtime migration from SQL Server to PostgreSQL; report times reduced to approximately one-third of baseline.
- Android applications for Honeywell and Zebra PDA scanners; Datamax printers, industrial scales, and serial hardware.
- IBM Planning Analytics (TM1) with SAP and Sage VIP feeds.
- Daily multi-region CI/CD; migration from Windows Forms to web and service-oriented architecture.

---

## Selected work

| Project | Description | Link |
| --- | --- | --- |
| CityOps | Government operations platform (DDD, GASB, vendor adapters, GIS, Azure Functions) | [merced.elstadt.com](https://merced.elstadt.com) |
| Gallo Platform | .NET 10 integration demo (SAP, SuccessFactors, UiPath, Prometheus, versioned API) | [gallo.elstadt.com](https://gallo.elstadt.com) |
| CorVel DataHub | Event-driven integration hub (sagas, Azure Functions, translation layer) | [corvel.elstadt.com](https://corvel.elstadt.com) |
| BunEHR | EHR implementing the openEHR REST API v1 (Bun, Hono, PostgreSQL) | [BunEHR](https://github.com/franselstadt/BunEHR) |
| Mitig8 | Insurance survey and valuation web application | [Mitig8-WEB](https://github.com/franselstadt/Mitig8-WEB) |
| TrajanOne | Case / medical-record platform (C#) | [TrajanOne](https://github.com/franselstadt/TrajanOne) |
| KitchenOS | C# application | [KitchenOS](https://github.com/franselstadt/KitchenOS) |
| codebase-memory-mcp | Code intelligence MCP server | [codebase-memory-mcp](https://github.com/franselstadt/codebase-memory-mcp) |

---

## Architecture

Layered design with dependencies pointing inward: presentation and infrastructure depend on application and domain; domain has no I/O.

```mermaid
flowchart TB
  subgraph adapters [Infrastructure and presentation]
    UI[Web / Functions]
    SQL[(SQL Server / PostgreSQL)]
    BUS[RabbitMQ / Kafka]
    CLOUD[AWS / Azure]
  end
  subgraph application [Application]
    UC[Use cases]
  end
  subgraph domain [Domain]
    M[Entities and collections]
  end
  UI --> UC
  UC --> M
  UC -.-> SQL
  UC -.-> BUS
  UI -.-> CLOUD
```

- Domain-driven design; CQRS where command/query split is useful.
- SQL written and tuned directly on hot paths (execution plans, indexing).
- Message brokers behind an application interface so RabbitMQ, Kafka, or in-memory test doubles can be swapped.

---

## Technical skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,azure,aws,postgres,sqlite,git,docker,kubernetes,linux,react,ts,nodejs" alt="skills"/>
</p>

- **Languages:** C# / .NET (ASP.NET, WPF, WinForms, Blazor), SQL, TypeScript, Java, Go, Node.js  
- **Data:** SQL Server, PostgreSQL, AWS RDS, Cosmos DB, SQLite  
- **Cloud:** AWS (EC2, S3, RDS, IAM, VPC), Azure (App Services, Functions), Docker, Kubernetes, Terraform  
- **Integration:** REST, SOAP, RabbitMQ, Kafka, SAP, Sage, IBM TM1, SWIFT  
- **Payments:** EMV, ISO 8583, PAIN XML, QR wallets  
- **Hardware / IoT:** Zebra/Honeywell PDAs, industrial printers and scales, ESP32, STM32, Raspberry Pi, LoRaWAN  

**Certifications:** AWS Networking (100th percentile) · Azure AI Fundamentals · MCSD · ASCP · IBM TM1 10.1 · CS50x · CCNA I  

**Education:** B.Tech, Computer Software Engineering — Nelson Mandela University · Accounting Sciences — UNISA

---

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=franselstadt&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=franselstadt&layout=compact&theme=transparent&hide_border=true&langs_count=8" alt="Top languages"/>
</p>

---

[elstadt.com](https://elstadt.com) · [LinkedIn](https://linkedin.com/in/frans-elstadt) · [X](https://x.com/franselstadt) · [franselstadt@gmail.com](mailto:franselstadt@gmail.com)
