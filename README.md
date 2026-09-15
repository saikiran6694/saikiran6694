# Hi, I'm Saikiran 👋

**`Full-Stack Engineer · LLM Applications · Distributed Systems`**

MSc Computer Science @ Memorial University of Newfoundland 🍁 · St. John's, NL
Previously Software Engineer @ Techolution · Presented at **New York AI Summit 2023** · First-author **IEEE** publication

---

## About

I build AI-powered products end to end — React and TypeScript on the front, Node/FastAPI services and Kafka-backed pipelines behind them. Most of my recent work sits where LLMs meet messy real-world documents: extraction, chunking, retrieval, and the unglamorous plumbing that keeps it reliable under load.

- 🔭 Building a distributed RAG pipeline — Kafka ingestion, Qdrant hybrid search, OpenTelemetry tracing
- 🏥 Software Developer Intern @ CAIR — YAML-driven clinical data platform, voice interaction, contract & invoice workflows
- 🤖 Two years shipping production React/TypeScript and LLM features at Techolution
- 📄 Looking for a **Winter 2027 work term** (4 or 8 months, Canada)

---

## Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Web**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

**AI & LLMs**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Data & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-FF4D4D?style=flat-square&logo=qdrant&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

---

## Featured Projects

### 🔀 [Distributed RAG Pipeline](https://github.com/saikiran6694/Distributed-RAG-Pipeline) · [Demo video ↗](https://drive.google.com/file/d/1v1J5rRRTQvvq9AchgDY2CXUc1n4MtFbo/view?usp=sharing)
Document-processing system built from scratch for retrieval at scale. Kafka routes PDFs and HTML through parallel workers → configurable chunking (fixed / semantic / hierarchical) → swappable embeddings (HuggingFace, OpenAI, Ollama) → Qdrant hybrid search with cross-encoder reranking. Redis semantic caching, dead-letter routing, and streaming responses on top; OpenTelemetry, Jaeger, and Prometheus underneath. Docker Compose integration tests run on every commit.

`Python` · `FastAPI` · `Kafka` · `Qdrant` · `PostgreSQL` · `Redis` · `Docker` · `GitHub Actions`

---

### 💰 [Arthium — AI Finance Platform](https://github.com/saikiran6694/arthium-finance) · [Live ↗](https://arthium-finance-ruddy.vercel.app/)
Full-stack app that turns unstructured receipts and statements into analytics-ready data. Gemini extracts structured fields from receipt images and PDFs; the frontend handles dashboards, charts, and natural-language queries over your transactions. JWT auth with refresh, protected routes, encrypted Redux state, Cloudinary uploads, and scheduled reports.

`Next.js` · `TypeScript` · `FastAPI` · `PostgreSQL` · `Gemini`

---

### 🗄️ [MiniDB — Relational Database Engine](https://github.com/saikiran6694/minidb)
A database written from scratch in Java 21, no runtime dependencies. Recursive-descent SQL parser, file-backed storage layer, constraint enforcement, transactions with locking and write-ahead logging, crash recovery, and an interactive shell. Layered architecture, tested with JUnit.

`Java 21` · `Maven` · `JUnit` · `Docker`

---

### 📊 [Unified Event Analytics Engine](https://github.com/saikiran6694/analytic-metric-app)
Multi-tenant analytics backend for collecting and querying application events over REST. API-key authentication, tenant isolation, rate limiting, connection pooling, and query tuning for ingestion-heavy workloads. 50+ unit, integration, and performance tests.

`Node.js` · `Express` · `PostgreSQL` · `REST`

---

### 🧠 [Research Mind](https://github.com/saikiran6694/research-mind) · [Live ↗](https://researchers-mind.streamlit.app/)
Autonomous research agent built on LangGraph — plans a query, fans out across sources, and synthesises what it finds.

`Python` · `LangGraph` · `LLMs` · `chromaDB` · `scraping` · `tool calling` · `ReAct`

---

## Experience

**Software Developer Intern · CAIR, Memorial University** — *Feb 2026 – Present*
Adaptive Case Generator for an AI-enhanced trauma-training platform; voice interaction with speech-to-text, TTS, and medical-terminology correction; a YAML-driven framework that generates Django models, REST APIs, and frontend forms from config; contract and invoice workflows with approval checks and document generation.

**Software Engineer · Techolution** — *Aug 2023 – Dec 2025*
Built ANA, an AI chatbot with a React interface, token-based access control, and rate limiting, plus a human-in-the-loop review workflow for low-confidence responses. Led frontend for Digital Twin (multilingual TTS, talking-avatar video, real-time voice and image editing), presented at the New York AI Summit 2023. Frontend for DataAI Studio, a micro-frontend ETL platform. Jest/RTL test coverage and GitHub Actions CI.

---

## Connect

[![Email](https://img.shields.io/badge/Email-saikiranbembalge123@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:saikiranbembalge123@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saikiran6694/)
