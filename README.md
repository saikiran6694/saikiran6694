# Hi, I'm Saikiran 👋

**`Software Engineer · GenAI Developer · Distributed Systems`**

MSc Computer Science @ Memorial University of Newfoundland, Canada 🍁  
Previously Software Engineer @ Techolution · Presented at **New York AI Summit 2023** · Published in **IEEE**

---

## About Me

I build production-grade AI-powered systems end-to-end — from Kafka-backed ingestion pipelines and vector search to user-facing APIs and interfaces. I care about systems that are fast, observable, and built to scale.

- 🔭 Currently building a distributed RAG pipeline with Kafka + Qdrant + OpenTelemetry
- 🏥 Developing a YAML-driven clinical data platform and contract/invoice generation pipeline @ CAIR
- 🤖 Built AI SaaS platforms processing enterprise data at scale (100K concurrent users)
- 📄 First-author IEEE publication on deep learning-based product classification

---

## Tech Stack

### AI & ML
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

### Distributed Systems & Infrastructure
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

### Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

### Databases & Vector Search
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-FF4D4D?style=flat-square&logo=qdrant&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=google-bigquery&logoColor=white)
![Azure Data Lake](https://img.shields.io/badge/Azure_Data_Lake-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

### Frontend
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

---

## Featured Projects

### 🔀 [Distributed RAG Pipeline](https://github.com/saikiran6694/Distributed-RAG-Pipeline)
Production-grade distributed RAG system built from scratch. Kafka (4-partition) routes documents through parallel PDF/HTML workers → adaptive chunker (fixed/semantic/hierarchical) → swappable embeddings (HuggingFace / OpenAI / Ollama) → Qdrant vector store + PostgreSQL metadata. Fully instrumented with OpenTelemetry + Jaeger tracing and Prometheus metrics. CI/CD via GitHub Actions with Docker Compose integration tests on every commit.

`Python` `FastAPI` `Kafka` `Qdrant` `PostgreSQL` `OpenTelemetry` `Prometheus` `Docker` `GitHub Actions`

---

### ❄️ [Serverless Cold Start Optimizer](https://github.com/saikiran6694/serverless_cold_start)
ML-driven system that predicts invocation patterns and triggers pre-warming before demand spikes — achieving an **83% reduction in cold start frequency**. Real-time metrics pipeline with adaptive thresholding feeds live system signals into the prediction engine.

`Python` `Scikit-learn` `AWS Lambda` `Real-time Metrics`

---

### 💰 [Arthium — AI Finance Platform](https://github.com/saikiran6694/arthium-finance) · [Live](https://arthium-finance-ruddy.vercel.app/)
Full-stack AI platform extracting, classifying, and structuring financial transactions from unstructured documents — **cutting manual data entry by 70%**. Extraction and classification pipelines normalise raw documents into analytics-ready data.

`Next.js` `FastAPI` `LLMs` `Document AI` `PostgreSQL`

---

### ☁️ [StoreIt — SaaS Storage Platform](https://github.com/saikiran6694/storage-management-app) · [Live](https://storage-management-app.vercel.app)
Cloud-native file management platform with secure authentication, role-based access, and usage analytics. Optimised UX flows lifted **onboarding conversion by 40%**.

`Next.js` `Appwrite` `TypeScript` `TailwindCSS`

---

## Experience Highlights

| | |
|---|---|
| 🏥 **CAIR, MUN** | YAML-driven form builder · auto-generates Django models, REST APIs, UI forms · Contract & Invoice generation pipeline |
| 🤖 **Techolution** | CDN-powered AI chatbot (100K concurrent / 250K peak) · Micro frontend ETL platform · AI SaaS @ NY AI Summit 2023 · CoPilot (60% accuracy boost) |

---

## Connect

[![Email](https://img.shields.io/badge/Email-saikiranbembalge123@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:saikiranbembalge123@gmail.com)
