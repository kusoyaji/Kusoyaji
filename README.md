# Mehdi Boudar

**AI & Platform Engineer — production LLM systems in Java 21 and Spring Boot.**

Most LLM engineering happens in Python. Mine runs on Java and Spring Boot, inside enterprises
that already run Java. I build the conversational AI, the Meta API compliance layer and the CRM
integrations for a multi-tenant messaging platform serving 10+ enterprise brands across 8
channels — automotive, retail, real estate and education.

[![Portfolio](https://img.shields.io/badge/Portfolio-mehdiboudar.com-0b1220?style=flat-square)](https://mehdiboudar.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mehdi--boudar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mehdi-boudar/)
[![Email](https://img.shields.io/badge/Email-Meehdi99%40gmail.com-c14438?style=flat-square&logo=gmail&logoColor=white)](mailto:Meehdi99@gmail.com)
[![Oracle Certified Professional](https://img.shields.io/badge/Oracle_Certified_Professional-Java_SE_17-F80000?style=flat-square&logo=oracle&logoColor=white)](https://www.linkedin.com/in/mehdi-boudar/)

---

## What I'm building

**[safq.ai](https://safq.ai)** — Conversational AI for WhatsApp, Instagram and Messenger, with
campaigns, CRM sync and ad attribution in one place. Sole engineer: architecture, data model,
billing, deployment. Serving 6 enterprise clients.

**[useinvestment.com](https://useinvestment.com)** — Growth diagnostics for Shopify brands. Reads
a store's public catalogue and returns findings with the evidence attached, benchmarked against
named competitors.

**[mehdiboudar.com](https://mehdiboudar.com)** — Portfolio and engineering case studies: Meta
coexistence, five-tier model failover, hybrid retrieval, MCP servers.

Most of my production work lives in private repositories. The case studies above are the
detailed version.

---

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

---

## Selected public repos

| Repo | What it is |
| --- | --- |
| [Portfolio](https://github.com/kusoyaji/Portfolio) | This site. Next.js 16, Tailwind v4, scroll-driven motion with Motion, Lenis and GSAP. |
| [odc-fablab](https://github.com/kusoyaji/odc-fablab) | Orange Morocco FabLab platform. 9 Spring Boot microservices over Kafka, real-time reservations with optimistic locking, 10+ IoT devices. |
| [skypay-technical-tests](https://github.com/kusoyaji/skypay-technical-tests) | Banking and hotel-reservation systems in Java — a clean read of how I structure domain logic. |
| [Freelancer-Portal-Saas](https://github.com/kusoyaji/Freelancer-Portal-Saas) | Full-stack Spring Boot and Angular platform: project management, messaging, payments. |

---

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

---

## Background

**State Engineering Degree in Computer Science** — EMSI Rabat, 2022–2025
**Associate Degree in Software Development** — ISTA NTIC Safi, 2019–2021

**Oracle Certified Professional: Java SE 17** (1Z0-829) · **Oracle Database SQL Certified
Associate** (1Z0-082)

Rabat, Morocco (GMT+1). English (C2) · French (C1) · Arabic (native).
Open to remote roles with EU/US overlap, and to relocation.
