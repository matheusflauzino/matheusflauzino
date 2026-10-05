<div align="right">

🇺🇸 **English** · [🇧🇷 Português](README.pt-BR.md)

</div>

# Hi, I'm Matheus Flauzino 👋

**Staff Backend Engineer** · Distributed Systems · High Scale · AWS & Kubernetes · Applied AI for Engineering

📍 Varginha, MG, Brazil &nbsp;·&nbsp; 🌐 [flauzino.dev](https://flauzino.dev) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/matheusflauzino)

---

## About

Software engineer with 15+ years of experience in backend, distributed systems and large-scale, mission-critical platforms.

Today I lead the **Pix core (SPI and DICT)** at [Efí Bank](https://sejaefi.com.br), a high-throughput, highly available payment system that holds an **A rating on the Central Bank's Service Quality Index**. Before that, I led the evolution of a **Credit Engine from an MVP into an event-driven platform that scaled ~100x**.

I act as a technical reference for other teams: deep performance and resilience analysis, engineering standards (idempotency, graceful degradation, observability), ADRs and post-mortems. I'm also the GenAI advocate on my team, where I standardized the use of AI assistants in development and built an AI agent that investigates anomalies automatically (AIOps).

## Highlights

| | |
|---|---|
| 🚀 **~100x** | Credit Engine growth, from ~300k to tens of millions of analyses per day |
| ⏱️ **12h → 2h** | Daily processing window after moving to async messaging |
| 🛡️ **99.9%** | Availability of the Pix core, with an A rating on the Central Bank's quality index |
| 📉 **-40%** | Critical production support load |

## Experience

### [Efí Bank](https://sejaefi.com.br) · Nov 2020 – Present

**Tech Lead & Team Lead – Pix Core (SPI & DICT)** · Jan 2026 – Present
- Technical lead of the Pix core, leading a team of 8 engineers (6 senior) and acting as the technical interface between engineering, product and compliance.
- Driving the architectural evolution of the settlement and directory services, focused on idempotency, consistency and graceful degradation when the SPI is unstable.
- Diagnosed a systemic failure where reprocessing and repeated lookups of non-existent keys triggered the Central Bank's anti-scraping rules and blocked legitimate accounts. Reworked the flow and built a Redis "non-existence cache" (SHA-256 hash, configurable TTL): no more unnecessary calls, no more wrongful blocks.
- Delivered Central Bank regulatory initiatives, including MED 2.0 and SPI Service Catalog updates.
- Standardized AI assistants in the development workflow (reusable prompts, skills, review guidelines for generated code).
- Write ADRs and TRDs, validate PRDs with Product, and run post-mortems that turn root causes into structural change.

**Tech Lead – Credit Analysis Engine** · Aug 2024 – Jan 2026
- Evolved an MVP into a distributed platform: ~300k to tens of millions of analyses per day (~100x).
- Replaced coupled synchronous processing with async messaging (SQS) and analytical queries (Athena), unlocking parallelism.
- Cut the execution window from 12h to ~2h per day, enabling new customers to join the credit ecosystem.
- Supported new products (cards, working capital, CDB-backed limit, invoice advance, guarantees) without rewriting the core.

**Software Engineer – E-commerce Card** · Jan 2024 – Aug 2024
- Built high-availability, PCI-compliant card payment APIs, improving authorization and capture success rates.

**Software Engineer – Open Finance** · Jan 2022 – Dec 2023
- Built the payment initiation API per Central Bank regulation and represented the company in Bacen technical working groups.

**Software Engineer – Card Receivables** · Nov 2020 – Dec 2021
- Built and optimized receivables registration and settlement systems (SLC and SILOC).

### Digisul · Nov 2017 – Nov 2020

**Senior Full Stack Developer – Logistics & Traceability**
- Designed the warehouse traceability and storage management system for one of Brazil's largest coffee cooperatives (~2 million bags per year, 8,000+ producers across ~90 municipalities).
- Implemented real-time tracking with RFID integrated into forklifts, digitizing warehouse logistics.
- Built the cooperative members' admin portal plus web and mobile solutions.

### Earlier
Mel Soluções (freelance Full Stack, 2014–2020) · UNIS Group (University Professor, 2018–2019) · ARF Soluções (ERP Consultant, 2013–2017) · Q1 Agência Digital (Systems Analyst, 2012–2013) · Digisul (Software Developer, 2010–2012)

## Projects & Open Source

- **[pix-brcode-parser](https://github.com/matheusflauzino)** – open source library for parsing Pix QR Codes (EMV), published on NPM (Node.js and TypeScript).
- **AIOps POC** – AI agent that automatically investigates anomalies over a local metrics and logs stack.
- **vscode-deploy-today** and **Deploy Assistant (Alexa)** – a VS Code extension and an Alexa skill with AWS integration, both published.

## Community

- **[GDG Varginha](https://gdg.community.dev/gdg-varginha/)** – volunteer organizer since 2017, including DevFest Sul de Minas (~300 attendees).
- Technical blog at [flauzino.dev](https://flauzino.dev).

## Tech Stack

**Languages**
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Lambda](https://img.shields.io/badge/-Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![S3](https://img.shields.io/badge/-S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![EC2](https://img.shields.io/badge/-EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Athena](https://img.shields.io/badge/-Athena-232F3E?style=flat-square&logo=amazonathena&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-333333?style=flat-square&logo=linux&logoColor=white)

**Messaging & Data**
![SQS / SNS](https://img.shields.io/badge/-SQS%20/%20SNS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![gRPC](https://img.shields.io/badge/-gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Oracle](https://img.shields.io/badge/-Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Architecture & Practices**
Distributed systems · Event-driven architecture · Microservices · System Design · Clean Architecture · REST · Idempotency · Consistency · Fault tolerance · Graceful degradation · Performance optimization · Observability · ADRs / RFCs / Design Docs

**Applied AI in Engineering**
AI assistant standardization (prompts, skills, generated-code review) · AI agents for observability (AIOps) · Responsible AI adoption in regulated environments

**Observability**
![Datadog](https://img.shields.io/badge/-Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![OpenSearch](https://img.shields.io/badge/-OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![Kibana](https://img.shields.io/badge/-Kibana-005571?style=flat-square&logo=kibana&logoColor=white)

**CI/CD & Tooling**
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/-GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Insomnia](https://img.shields.io/badge/-Insomnia-5849BE?style=flat-square&logo=insomnia&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

**Front-end & Full Stack (earlier work)**
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/-React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/-Sass-CC6699?style=flat-square&logo=sass&logoColor=white)

## Education

- **MBA in Software Engineering** – USP/ESALQ (2023 – 2025)
- **B.Sc. in Computer Science** – UNIS-MG (2009 – 2012)
- **AWS Certified Cloud Practitioner**
- Languages: Portuguese (native) · English (B2) · Spanish (basic)

---

*"Talk is cheap. Show me the code." – Linus Torvalds*

[![GitHub](https://img.shields.io/badge/-GitHub-000?style=flat-square&logo=github&logoColor=white)](https://github.com/matheusflauzino)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheusflauzino)
[![Blog](https://img.shields.io/badge/-flauzino.dev-111?style=flat-square&logo=hashnode&logoColor=white)](https://flauzino.dev)
