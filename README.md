<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1F6FEB&height=170&section=header&text=Mehdi%20Boudar&fontColor=FFFFFF&fontSize=44&fontAlignY=34&desc=AI%20%26%20Platform%20Engineer&descAlignY=54&descSize=18" width="100%" alt="Mehdi Boudar — AI and Platform Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=23&duration=3400&pause=900&color=2F81F7&center=true&vCenter=true&width=760&lines=Production+LLM+systems+in+Java+21+%26+Spring+Boot;Multi-model+orchestration%2C+hybrid+RAG%2C+MCP+servers;10%2B+enterprise+brands+across+8+channels" alt="Production LLM systems in Java 21 and Spring Boot" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-mehdiboudar.com-0D1117?style=for-the-badge)](https://mehdiboudar.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mehdi--boudar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mehdi-boudar/)
[![Email](https://img.shields.io/badge/Email-Meehdi99@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Meehdi99@gmail.com)
[![Oracle Certified](https://img.shields.io/badge/Oracle_Certified_Professional-Java_SE_17-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.linkedin.com/in/mehdi-boudar/)

</div>

---

Most LLM engineering happens in Python. Mine runs on **Java 21 and Spring Boot**, inside
enterprises that already run Java. I build the conversational AI, the Meta API compliance layer
and the CRM integrations for a multi-tenant messaging platform serving **10+ enterprise brands
across 8 channels** — automotive, retail, real estate and education.

## What I'm building

**[safq.ai](https://safq.ai)** — Conversational AI for WhatsApp, Instagram and Messenger, with
campaigns, CRM sync and ad attribution in one place. Sole engineer: architecture, data model,
billing, deployment. Serving 6 enterprise clients.

**[useinvestment.com](https://useinvestment.com)** — Growth diagnostics for Shopify brands. Reads
a store's public catalogue and returns findings with the evidence attached, benchmarked against
named competitors.

**[mehdiboudar.com](https://mehdiboudar.com)** — Portfolio and engineering case studies: Meta
coexistence, five-tier model failover, hybrid retrieval, MCP servers.

## Things I've solved that were genuinely hard

**Meta WhatsApp coexistence.** Connecting a client's number to the Cloud API used to mean
deleting their WhatsApp Business app outright — a non-starter for a sales team that lives in it.
The same number now runs through both, with history synced in both directions.

**Five-tier model failover.** Language models degrade in ways ordinary services do not: rate
limits, regional outages, silent truncation, quietly worse output. Gemini → Claude → Gemini Flash
→ GPT-4o-mini → a deterministic path that always answers. Each tier is a complete fallback, not a
retry, and the agentic tools stay available the whole way down.

**Retrieval for Moroccan Darija.** Semantic search plus BM25 for exact part numbers, plus HyDE
for questions phrased in words that never appear in the source. Customers write Darija and French
mixed inside a single sentence.

**MCP servers over CRM.** Two in production: a centralizer federating several Zoho tenants behind
one interface, and an 18-tool conversation server, both under per-user token auth.

## Selected public repos

**[Chatwoot](https://github.com/kusoyaji/Chatwoot)** · Ruby on Rails
The messaging platform whose campaign and broadcast subsystem I re-engineered for Meta API
compliance: rate limiting, retry, scheduling and delivery tracking. Imports 500,000 contacts in
under 10 minutes and broadcasts 100,000 template messages in under 30.

**[odc-fablab](https://github.com/kusoyaji/odc-fablab)** · Java, Spring Boot
Orange Morocco FabLab platform. 9 Spring Boot microservices over Apache Kafka, real-time
reservations with optimistic locking, and 10+ IoT devices integrated over REST.

**[Freelancer-Portal-Saas](https://github.com/kusoyaji/Freelancer-Portal-Saas)** · Spring Boot, Angular
Full-stack platform: project management, client tracking, real-time messaging and payments.

<sub>Most of my production work lives in private repositories. The case studies on
<a href="https://mehdiboudar.com">mehdiboudar.com</a> are the detailed version.</sub>

## Stack

**Core** — Java 21 · Spring Boot 3 · PostgreSQL / pgvector · Redis · Docker

**AI** — Multi-model orchestration (Gemini, Claude, OpenAI) · Agents & function calling · Hybrid
RAG (BM25, HyDE) · Model Context Protocol · LLM-as-judge evaluation

**Integration** — Meta WhatsApp Cloud API · Zoho CRM · Salesforce · Stripe · Webhooks ·
OAuth2 / HMAC · Apache Kafka

**Web** — Next.js · TypeScript · React · Angular

**Delivery** — Digital Ocean · Railway · Vercel · Nginx · Jenkins CI/CD

<sub>Also worked with: Python, C#, PHP, MongoDB, SQL Server, Kubernetes, GraphQL. Listed
separately because I would not claim them as strengths.</sub>

## Background

- **State Engineering Degree in Computer Science** — EMSI Rabat, 2022–2025
- **Associate Degree in Software Development** — ISTA NTIC Safi, 2019–2021
- **Oracle Certified Professional: Java SE 17** (1Z0-829)
- **Oracle Database SQL Certified Associate** (1Z0-082)

Rabat, Morocco (GMT+1) · English (C2) · French (C1) · Arabic (native)
Open to remote roles with EU/US overlap, and to relocation.

<div align="center">

<img src="https://streak-stats.demolab.com?user=kusoyaji&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="Contribution streak" />

</div>
