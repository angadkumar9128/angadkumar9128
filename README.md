<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0B132B,45:1C2541,100:3A506B&text=ANGAD%20KUMAR&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=DATA%20ENGINEERING%20%7C%20AI%20%26%20GENAI&descSize=18&descAlignY=58&descColor=5BC0BE" alt="Angad Kumar — Data Engineering and AI"/>

<p>
  <a href="https://www.linkedin.com/in/angadkumar54/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:angadkumar9128@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/angadkumar9128"><img src="https://img.shields.io/badge/GitHub-Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=angadkumar9128&style=flat-square&color=3A506B&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

---

## 👋 About Me

I'm a **Data Engineer working at the intersection of data platforms and AI engineering**. I enjoy turning raw, semi-structured and streaming data into reliable datasets—and building AI applications that make information easier to use.

**What I focus on**
- **Data platforms:** ELT/ETL, PySpark, Spark SQL, Delta Lake and Medallion Architecture.
- **Streaming systems:** Kafka-compatible event ingestion, Structured Streaming and downstream lakehouse pipelines.
- **AI engineering:** RAG pipelines, semantic retrieval, reranking and LLM-backed applications.
- **Production-minded development:** APIs, containers, data quality, observability and clear setup documentation.

I'm interested in **Data Engineer, AI Engineer and Data/AI Platform Engineer** opportunities.

---

## 🚀 Selected Projects

These projects are the best starting points for reviewing my recent engineering work.

<table>
<tr>
<td width="50%" valign="top">

### 🌊 [StreamHub](https://github.com/angadkumar9128/StreamHub)

**Kafka-compatible streaming ingestion platform**

A self-hostable streaming service built with FastAPI, Redpanda and PostgreSQL, with a path into Databricks Lakehouse processing.

**Highlights**
- REST and batch event producers, topic/partition configuration and retention.
- Incremental CSV, JSON, JSONL and Parquet ingestion.
- Dead-letter topics, versioned schema checks, API-key roles and rate limiting.
- Kafka consumer-group lag inspection and a REST receiver.
- Databricks Structured Streaming starter and Bronze → Silver workflow guidance.

**Stack:** Python · FastAPI · Redpanda/Kafka · PostgreSQL · Docker · Databricks · Delta Lake

[Repository →](https://github.com/angadkumar9128/StreamHub)

</td>
<td width="50%" valign="top">

### 🏥 [FHIR Healthcare Analytics](https://github.com/angadkumar9128/FHIR_Healthcare_Analytics)

**Healthcare data lakehouse pipeline**

An implementation for transforming nested FHIR JSON bundles into governed, analytics-ready datasets using a Medallion Architecture. The repository documents a sample built from synthetic Synthea data.

**Highlights**
- Bronze ingestion of raw FHIR bundles with metadata.
- Silver normalization of clinical resources such as Patient, Encounter, Observation and Condition.
- Gold-layer datasets for clinical and claims analytics.
- Delta Lake, schema evolution and Unity Catalog governance concepts.

**Stack:** Databricks · PySpark · Spark SQL · Delta Lake · Unity Catalog · FHIR JSON

[Repository →](https://github.com/angadkumar9128/FHIR_Healthcare_Analytics)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💳 [Real-Time Financial Fraud Detection](https://github.com/angadkumar9128/Real-Time-Financial-Fraud-Detection-Monitoring-System)

**Streaming analytics and anomaly detection**

A project demonstrating a streaming-oriented fraud-monitoring pipeline from transaction data to anomaly scores and business-facing metrics.

**Highlights**
- Bronze, Silver and Gold data layers.
- Transaction cleaning, enrichment and feature preparation.
- Isolation Forest scoring with MLflow tracking.
- Gold outputs for fraud predictions, time-based metrics and high-risk entities.
- Databricks SQL dashboard use cases.

**Stack:** Databricks · Structured Streaming · Delta Lake · PySpark · Isolation Forest · MLflow

[Repository →](https://github.com/angadkumar9128/Real-Time-Financial-Fraud-Detection-Monitoring-System)

</td>
<td width="50%" valign="top">

### ⚖️ [LexAI — Legal RAG Platform v2](https://github.com/angadkumar9128/lexai-legal-rag-platform-v2)

**Retrieval-grounded legal research assistant**

A dual-profile RAG application with a Databricks notebook pipeline and a local Streamlit experience for legal-document retrieval and question answering.

**Highlights**
- PDF-to-lakehouse workflow: Bronze → Silver → Gold.
- Embedding generation and legal QA notebooks.
- Local FAISS and lexical retrieval with optional cross-encoder reranking.
- Optional local GGUF model generation and extractive fallback.
- FastAPI adapter and Streamlit UI components.

**Stack:** Python · Databricks · PySpark · FAISS · Embeddings · Reranking · Streamlit · FastAPI

[Repository →](https://github.com/angadkumar9128/lexai-legal-rag-platform-v2)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎬 [CreatorFlow AI](https://github.com/angadkumar9128/CreatorFlow-AI)

**AI-assisted short-form content studio**

A web app that generates scripts, captions and hashtags, creates scene images through configurable providers, and renders vertical video in the browser.

**Highlights**
- LLM-provider fallback for text generation.
- Image-provider fallback for scene artwork.
- Canvas and MediaRecorder-based video rendering.
- 9:16 output workflow, captions and social-post metadata.
- Vercel-oriented deployment instructions.

**Stack:** JavaScript · Next.js · LLM APIs · Image APIs · Canvas · MediaRecorder · Vercel

[Repository →](https://github.com/angadkumar9128/CreatorFlow-AI)

</td>
<td width="50%" valign="top">

### 🛒 [Retail Analytics Transformation Pipeline](https://github.com/angadkumar9128/Enterprise-Retail-Analytics-Transformation-Pipeline)

**Modern ELT and analytics engineering**

A retail analytics project organized around a modern data stack and Medallion Architecture, with orchestration and transformation patterns documented in the repository.

**Areas covered**
- Raw-to-curated data pipeline design.
- Apache Airflow orchestration concepts.
- dbt transformation workflows.
- Databricks and Delta Lake compute.
- Data-quality and analytics use cases for retail operations.

**Stack:** Python · Airflow · dbt · Databricks · Delta Lake

[Repository →](https://github.com/angadkumar9128/Enterprise-Retail-Analytics-Transformation-Pipeline)

</td>
</tr>
</table>

---

## 🧰 Technical Skills

<div align="center">

### Data Engineering & Platforms

<img src="https://skillicons.dev/icons?i=python,postgres,mysql,mongodb,kafka,docker,aws,azure" alt="Python, databases, Kafka, Docker, AWS and Azure"/>

**PySpark · Spark SQL · Delta Lake · Medallion Architecture · Structured Streaming · ELT/ETL · Databricks · Unity Catalog · Airflow · Snowflake · Azure Data Factory**

### AI & GenAI

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,fastapi" alt="PyTorch, TensorFlow and FastAPI"/>

**RAG · LLM applications · Embeddings · Semantic Search · Vector Retrieval · Reranking · Prompt Engineering · LangChain · LangGraph · Hugging Face**

### Software & Tooling

<img src="https://skillicons.dev/icons?i=git,github,linux, javascript,react,nodejs,django" alt="Development tools and frameworks"/>

**Python · SQL · Java · JavaScript · FastAPI · Django · REST APIs · Git · GitHub · Docker**

</div>

---

## 🏅 Certifications

- **Oracle Cloud Infrastructure 2025 Certified AI Foundations Associate** — issued October 2025.
- **Oracle Cloud Database Services 2025 Certified Professional** — issued October 2025.
- **Databricks Fundamentals accreditation** — issued November 2025; verify current validity before presenting as active.

> I prefer to keep certification details specific and verifiable. I have not included unverified performance figures, customer counts or adoption claims in this portfolio.

---

## 📊 GitHub Activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=angadkumar9128&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=angadkumar9128&layout=compact&theme=tokyonight&hide_border=true" alt="Most-used languages"/>

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=angadkumar9128&theme=tokyo-night&hide_border=true" alt="GitHub contribution activity"/>

</div>

---

## 🤝 Let's Connect

I'm open to conversations about **data engineering, lakehouse architecture, streaming systems, applied GenAI and AI platform engineering**.

<div align="center">

<a href="https://www.linkedin.com/in/angadkumar54/"><img src="https://img.shields.io/badge/LinkedIn-Angad%20Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile"/></a>
<a href="mailto:angadkumar9128@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Angad"/></a>

</div>

<div align="center">
<sub>Build reliable data foundations. Turn data into useful intelligence.</sub>
</div>
