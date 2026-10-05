<div align="right">

[🇺🇸 English](README.md) · 🇧🇷 **Português**

</div>

# Olá, eu sou o Matheus Flauzino 👋

**Staff Backend Engineer** · Sistemas Distribuídos · Alta Escala · AWS e Kubernetes · IA aplicada à Engenharia

📍 Varginha, MG, Brasil &nbsp;·&nbsp; 🌐 [flauzino.dev](https://flauzino.dev) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/matheusflauzino)

---

## Sobre

Engenheiro de software com mais de 15 anos de experiência em backend, sistemas distribuídos e plataformas de alta escala e missão crítica.

Hoje lidero o **core de Pix (SPI e DICT)** no [Efí Bank](https://sejaefi.com.br), um sistema de pagamentos de alto volume e alta disponibilidade, com **nota A no Índice de Qualidade do Serviço do Banco Central**. Antes, conduzi a evolução do **Motor de Crédito de um MVP para uma plataforma orientada a eventos que escalou ~100x**.

Atuo como referência técnica para outros times: análises profundas de performance e resiliência, padrões de engenharia (idempotência, degradação controlada, observabilidade), ADRs e post-mortems. Também sou o propagador de GenAI no meu time, onde padronizei o uso de assistentes de IA no desenvolvimento e construí um agente de IA para investigação automática de anomalias (AIOps).

## Destaques

| | |
|---|---|
| 🚀 **~100x** | Crescimento do Motor de Crédito, de ~300 mil para dezenas de milhões de análises por dia |
| ⏱️ **12h → 2h** | Janela diária de processamento após migrar para mensageria assíncrona |
| 🛡️ **99,9%** | Disponibilidade do core de Pix, com nota A no índice de qualidade do Banco Central |
| 📉 **-40%** | Carga de suporte crítico em produção |

## Experiência

### [Efí Bank](https://sejaefi.com.br) · Nov 2020 – Atual

**Tech Lead & Team Lead – Pix Core (SPI & DICT)** · Jan 2026 – Atual
- Lidero tecnicamente o core de Pix, com um time de 8 desenvolvedores (6 seniores), atuando como interface técnica entre engenharia, produto e compliance.
- Conduzo a evolução arquitetural dos serviços de liquidação e de diretório, com foco em idempotência, consistência e degradação controlada em cenários de instabilidade do SPI.
- Diagnostiquei uma falha sistêmica em que reprocessamentos e consultas repetidas a chaves inexistentes acionavam as regras antiscraping do Banco Central e bloqueavam contas legítimas. Reordenei o fluxo e criei um cache de inexistência em Redis (hash SHA-256, TTL parametrizável): fim das chamadas desnecessárias e dos bloqueios indevidos.
- Entreguei iniciativas regulatórias do Banco Central, incluindo o MED 2.0 e as atualizações do Catálogo de Serviços do SPI.
- Padronizei o uso de assistentes de IA no fluxo de desenvolvimento (prompts reutilizáveis, skills e diretrizes de revisão de código gerado).
- Escrevo ADRs e TRDs, valido PRDs com Produto e conduzo post-mortems que convertem causa-raiz em mudança estrutural.

**Tech Lead – Motor de Análise de Crédito** · Ago 2024 – Jan 2026
- Evoluí um MVP para uma plataforma distribuída: de ~300 mil para dezenas de milhões de análises por dia (~100x).
- Substituí o processamento síncrono e acoplado por mensageria assíncrona (SQS) e consultas analíticas (Athena), destravando o paralelismo.
- Reduzi a janela de execução de 12h para ~2h por dia, viabilizando a entrada de novos clientes no ecossistema de crédito.
- Sustentei a expansão para novos produtos (cartão, capital de giro, CDB com limite, antecipação de boletos e garantias) sem reescrita do core.

**Engenheiro de Software – Cartão e-commerce** · Jan 2024 – Ago 2024
- Desenvolvi APIs de pagamento com cartão de alta disponibilidade e conformidade PCI, melhorando a taxa de sucesso de autorização e captura.

**Engenheiro de Software – Open Finance** · Jan 2022 – Dez 2023
- Desenvolvi a API de iniciação de pagamento conforme o Banco Central e representei a empresa em grupos técnicos do Bacen.

**Engenheiro de Software – Recebíveis de Cartão** · Nov 2020 – Dez 2021
- Desenvolvi e otimizei sistemas de registro e liquidação de recebíveis (SLC e SILOC).

### Digisul · Nov 2017 – Nov 2020

**Senior Full Stack Developer – Logística e Rastreabilidade**
- Projetei o sistema de rastreabilidade e gestão de armazenagem de uma das maiores cooperativas de café do país (~2 milhões de sacas por ano, +8 mil produtores em ~90 municípios).
- Implementei rastreamento em tempo real com RFID integrado a empilhadeiras, digitalizando o controle logístico dos armazéns.
- Desenvolvi o portal administrativo para cooperados e soluções web e mobile.

### Anterior
Mel Soluções (autônomo, Full Stack, 2014–2020) · Grupo UNIS (Professor Universitário, 2018–2019) · ARF Soluções (Consultor ERP, 2013–2017) · Q1 Agência Digital (Analista de Sistemas, 2012–2013) · Digisul (Desenvolvedor de Software, 2010–2012)

## Projetos e Open Source

- **[pix-brcode-parser](https://github.com/matheusflauzino)** – biblioteca open source para parsing de QR Code Pix (EMV), publicada no NPM (Node.js e TypeScript).
- **AIOps POC** – agente de IA que investiga anomalias automaticamente sobre uma stack local de métricas e logs.
- **vscode-deploy-today** e **Assistente de Deploy (Alexa)** – extensão do VS Code e skill para Alexa com integração AWS, ambas publicadas.

## Comunidade

- **[GDG Varginha](https://gdg.community.dev/gdg-varginha/)** – organizador voluntário desde 2017, incluindo o DevFest Sul de Minas (~300 participantes).
- Blog técnico em [flauzino.dev](https://flauzino.dev).

## Stack

**Linguagens**
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Cloud e Infraestrutura**
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Lambda](https://img.shields.io/badge/-Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![S3](https://img.shields.io/badge/-S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![EC2](https://img.shields.io/badge/-EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Athena](https://img.shields.io/badge/-Athena-232F3E?style=flat-square&logo=amazonathena&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-333333?style=flat-square&logo=linux&logoColor=white)

**Mensageria e Dados**
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

**Arquitetura e Práticas**
Sistemas distribuídos · Arquitetura orientada a eventos · Microsserviços · System Design · Clean Architecture · REST · Idempotência · Consistência · Tolerância a falhas · Degradação controlada · Otimização de performance · Observabilidade · ADRs / RFCs / Design Docs

**IA aplicada à Engenharia**
Padronização de assistentes de IA (prompts, skills, revisão de código gerado) · Agentes de IA para observabilidade (AIOps) · Adoção responsável de IA em ambiente regulado

**Observabilidade**
![Datadog](https://img.shields.io/badge/-Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![OpenSearch](https://img.shields.io/badge/-OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![Kibana](https://img.shields.io/badge/-Kibana-005571?style=flat-square&logo=kibana&logoColor=white)

**CI/CD e Ferramentas**
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/-GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Insomnia](https://img.shields.io/badge/-Insomnia-5849BE?style=flat-square&logo=insomnia&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

**Front-end e Full Stack (experiências anteriores)**
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/-React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/-Sass-CC6699?style=flat-square&logo=sass&logoColor=white)

## Formação

- **MBA em Engenharia de Software** – USP/ESALQ (2023 – 2025)
- **Bacharelado em Ciência da Computação** – UNIS-MG (2009 – 2012)
- **AWS Certified Cloud Practitioner**
- Idiomas: português nativo · inglês B2 · espanhol básico

---

*"Talk is cheap. Show me the code." – Linus Torvalds*

[![GitHub](https://img.shields.io/badge/-GitHub-000?style=flat-square&logo=github&logoColor=white)](https://github.com/matheusflauzino)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheusflauzino)
[![Blog](https://img.shields.io/badge/-flauzino.dev-111?style=flat-square&logo=hashnode&logoColor=white)](https://flauzino.dev)
