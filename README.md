<div align="center">

[![Augustine Nguyen — Senior Data Engineer](https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=E94560&center=true&vCenter=true&width=800&height=80&lines=Augustine+Nguyen;Senior+Data+Engineer;Market+%26+Financial+Data+Platforms;Pipeline+Architecture+%7C+Reliability+%7C+AI)](https://git.io/typing-svg)

### Senior Data Engineer | Market & Financial Data Platforms

<br/>

<a href="https://augustine0890.github.io" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Portfolio-1F2937?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/augustine2015/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:augustino0890@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://twitter.com/augusti61988772" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Twitter-1D9BF0?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"></a>
<a href="#credentials"><img src="https://img.shields.io/badge/AWS_Certified-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Certified"></a>

<br/>

> *Reliable data platforms for financial operations, analysis, and AI.*

</div>

---

<div align="center">

### 🏆 &nbsp; Champion · FPT AI Hackathon 3 · 2025 &nbsp; 🏆
**Global Competition** — teams from FPT offices worldwide &nbsp;|&nbsp; Track: Enterprise Document Intelligence

</div>

---

## ◈ About Me

I focus on **data infrastructure for financial applications**, bringing a data science perspective to engineering. Based in the **Republic of Korea**, I connect ingestion, transformation, storage, and delivery to the needs of the people who depend on the data.

My experience spans **credit risk platforms, investment securities SQL migration, blockchain transaction pipelines, streaming analytics, and enterprise AI retrieval**. It includes designing highly available database clusters managing **5B+ records**, optimizing **Spark** processing for a platform serving **10M+ users**, and building a document intelligence pipeline that won **FPT AI Hackathon 3 in 2025**.

I am particularly interested in **market and financial data platforms** where correctness, availability, and explainable data flows matter. Working with customer, product, and financial data has taught me to start with the downstream requirement and carry it through to architecture and operations.

The scope I want to grow into is **Staff-level data engineering**: shaping platform architecture, establishing reusable engineering standards, and aligning data producers and consumers around clear requirements. I value decisions that make a platform easier for teams to operate and extend over time.

---

## ◈ What I Focus On

### Market & Financial Data Integrity

My financial data experience includes credit risk systems, investment securities workflows, and on-chain transactions. For market data, my priorities include **consistent instrument identifiers, event and ingestion timestamps, trading calendars, missing observations, and price adjustments**. I care about preserving the meaning of a financial record as it moves between systems and making corrections understandable to downstream users.

### Reliable Pipelines & Recovery

My project work spans **Kafka event streaming, Spark processing, resilient database clusters, disaster recovery, and operational monitoring**. My design priorities include explicit handling of late or duplicate records, safe retries and backfills, and recovery procedures teams can follow. A useful pipeline delivers data consistently and makes failures diagnosable.

### Platform Architecture & Technical Direction

I approach architecture through **access patterns, latency, throughput, storage cost, and operational complexity**. My experience with database clusters, streaming pipelines, and SQL migration informs those tradeoffs. As I move toward broader platform responsibility, I want to help teams document decisions, reuse ingestion and transformation patterns, and evolve interfaces without breaking downstream workflows.

### Data Quality, Ownership & Traceability

I value **clear dataset definitions, accountable ownership, source reconciliation, and traceable transformations**. The standards I want to help establish cover freshness and completeness expectations, schema changes, and the checks needed before data reaches consumers. These practices help teams investigate discrepancies and understand the inputs behind a financial result.

### Data Delivery for Finance & AI

My work connects processing and storage to **SQL workflows, APIs, search indexes, operational dashboards, and AI retrieval**. I start with what consumers need to query or decide, then work backward to the required structure and delivery path. For AI inputs, that includes preserving source context; for financial analysis, it includes reproducible historical inputs.

---

## ◈ Core Engineering Experience

| Domain | Tools & Methods |
|:---|:---|
| **Batch & Streaming Pipelines** | Apache Spark · Apache Kafka · Airflow · Kinesis · ETL/ELT · ELK Stack |
| **SQL & Data Transformation** | SQL Optimization · Oracle → EDB (PostgreSQL) Migration · ANSI SQL · dbt · Pandas |
| **Storage & Reliability** | PostgreSQL · Oracle · ClickHouse · MongoDB · Redis · Highly Available Clusters · Disaster Recovery |
| **AI Data Engineering** | Multimodal Document Processing · RAG · Vector Search · Qdrant · Gemini · Qwen · LangChain |
| **Financial Data Systems** | Credit Risk Platforms · Fault-Detection Pipelines · Investment Securities Workflows · Blockchain Transaction Data |
| **Data Delivery & Observability** | FastAPI · Django · Spring Boot · REST APIs · OpenSearch · Operational Dashboards |
| **Cloud & Infrastructure** | AWS · Azure · Docker · Kubernetes |
| **Languages** | Python · SQL · Rust · Golang · Java · TypeScript |

---

## ◈ Featured Work

### ABACUS — Advanced Credit Risk Prediction Analysis Tool

> *Financial data infrastructure · Fault detection & credit risk modeling · 10M+ users · 5B+ records*

Work spanning **storage architecture, distributed processing, and operational visibility** for a large financial risk platform.

- Architected **highly available ClickHouse, MongoDB, and Redis clusters** managing **5B+ records**, with disaster recovery provisions to support data integrity and operational continuity
- Optimized **Apache Spark** processing for fault-detection pipelines serving a platform with **10M+ users**
- Built **real-time monitoring dashboards and interactive reports** to make platform signals available for operational decisions
- Developed credit risk models achieving a **+3% lift in scoring accuracy**, connecting data processing to downstream model performance

`Python` `Django` `FastAPI` `Apache Spark` `ClickHouse` `MongoDB` `Oracle` `Redis`

---

### Investment Securities Project (Meta) — Database Migration & SQL Optimization

> *Financial data workflows · Oracle → EDB (PostgreSQL) · ANSI SQL*

Work at the boundary of **financial business requirements and database portability**, keeping SQL aligned with investment securities workflows.

- Converted and optimized **Oracle SQL queries** to **ANSI SQL** for **EDB (PostgreSQL)** compatibility, improving query efficiency and portability
- Translated investment securities business requirements into SQL queries aligned with financial workflows

`Oracle` `EDB (PostgreSQL)` `ANSI SQL` `SQL Optimization`

---

### BlockStream — Real-Time Blockchain Data System

> *On-chain transaction ingestion · Ethereum & Polygon · Publish–subscribe architecture*

An ingestion-to-search architecture connecting **transaction collection, event distribution, persistent storage, and indexing**.

- Architected real-time collection of **Ethereum and Polygon transaction data**
- Engineered the pipeline from **on-chain collection → Kafka → PostgreSQL → OpenSearch / Algolia**, supporting sub-second search
- Managed metadata enrichment, storage, and indexing across the workflow to support data integrity and scalable retrieval

`Python` `Golang` `Kafka` `PostgreSQL` `OpenSearch` `Algolia` `Oracle` `Kinesis`

---

### AISOL — Enterprise AI & Document Data Pipeline

> *Champion, FPT AI Hackathon 3 (2025) · Japanese-language enterprise RAG · Track: KT/KB Technical Solutions*

- Designed and delivered a pipeline converting **Excel, Word, PowerPoint, and PDF documents** into structured data for enterprise AI retrieval
- Parallelized processing of **text, tables, and diagrams**, addressing the sequential bottleneck of conventional document loaders
- Preserved **semantic context across document structures** to support queries spanning multiple sections
- Integrated **Qdrant** for vector storage, **Gemini** for multimodal understanding, and **Qwen** for Japanese-language generation

`Python` `Qdrant` `Gemini` `Qwen` `RAG` `Vector Search` `Multimodal AI`

---

### InsightFlow — Customer Behavior & Growth Analytics

> *Streaming data for e-commerce / fintech · Marketing & product analytics*

- Built **Kafka + ELK Stack** event streaming to capture high-volume customer behavior data
- Developed **RFM segmentation, conversion funnel models, and propensity-to-purchase scoring pipelines** for marketing analysis and campaign targeting
- Architected promotional, delivery, and shipping analytics to support revenue and operational decisions

`Kafka` `ELK Stack` `FastAPI` `Python` `Oracle` `RFM` `Propensity Modeling`

---

### QA/QC Data Analytics & Visualization Dashboard

> *Statistical data processing & delivery · Spring Boot + Java + Oracle*

- Built **SQL and Java pipelines** to aggregate, preprocess, and analyze large QA/QC datasets
- Used **Apache Commons Math** for statistical analysis of trends and anomalies
- Developed **Spring Boot REST APIs** and **Chart.js dashboards** to deliver real-time statistical reports to stakeholders

`Java` `Spring Boot` `Oracle` `Apache Commons Math` `Chart.js` `REST APIs` `SQL`

---

### Discord Emotion Tracker — NLP Data Pipeline

> *Message ingestion, translation & sentiment enrichment · Rust + Python*

- Captured Discord interactions and built a labeled dataset for **sentiment analysis and emotion classification**
- Integrated **AWS Comprehend** and **HuggingFace Rust-BERT** for NLP enrichment, plus **AWS Translate** for English-to-Korean translation
- Structured **MongoDB storage** for messages, translations, and sentiment metrics to support downstream queries and analysis

`Rust` `Serenity` `AWS Comprehend` `AWS Translate` `HuggingFace` `MongoDB` `Python`

---

## ◈ Side Projects

<table>
<tr>
<td width="50%" valign="top">

**[discord-playdapp-bot](https://github.com/augustine0890/discord-playdapp-bot)** &nbsp;·&nbsp; Rust

A high-performance Discord bot built in **Rust** using Serenity for gaming community management. Handles tournament ticket exchange, player engagement tracking, and leaderboard ranking via slash commands.

`Rust` `Serenity` `MongoDB` `Docker`

</td>
<td width="50%" valign="top">

**[outfit-square](https://github.com/augustine0890/outfit-square)** &nbsp;·&nbsp; Python

Python-based Discord bot for user point management in metaverse gaming channels. Integrates MongoDB for persistent storage with multi-stage (dev/prod) deployment and OAuth2 authentication.

`Python` `Discord.py` `MongoDB` `Poetry`

</td>
</tr>
</table>

---

## ◈ Quantitative & Modeling Background

My background in **credit risk modeling, statistical analysis, and causal inference** helps me understand downstream data requirements, including historical consistency and reproducible inputs. I use that perspective to support analysts and model developers when designing financial data pipelines.

---

## ◈ Tech Stack

<div align="center">

**Data Engineering** &nbsp;·&nbsp;
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

**Cloud & Databases** &nbsp;·&nbsp;
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Generative AI & RAG** &nbsp;·&nbsp;
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Languages** &nbsp;·&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

</div>

---

<a id="credentials"></a>

## ◈ Credentials

<div align="center">

| | |
|:---:|:---|
| ☁️ | **AWS Certified Data Engineer – Associate** |
| 🤖 | **AWS Certified AI Practitioner – Foundational** |
| ☁️ | **Microsoft Certified: Azure AI Fundamentals** |
| 📊 | **Nanodegree: Data Engineering with Microsoft Azure** |
| 🔁 | **Astronomer Certification: Apache Airflow Fundamentals** |

</div>

---

## ◈ Education

**Master of Public Health — Health Data Science**
National Cancer Center, Goyang, Republic of Korea · 2016–2018
*Thesis: Causal Effect of BMI on Thyroid Cancer Risk using Mendelian Randomization (Instrumental Variable Analysis)*

**Bachelor of Engineering — Biotechnology**
Industrial University of Ho Chi Minh City, Vietnam · 2008–2013

---

## ◈ Why I Care

I enjoy making data easier to trust and use. An operations team can investigate a discrepancy. An analyst can reproduce a financial report. An engineer can understand a pipeline's dependencies and recover it after a failure.

That is what draws me to broader platform work: building systems that teams can inspect, explain, operate, and depend on as their data needs grow.

---

<div align="center">

![footer](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

**Open to Senior Data Engineer roles in market data, financial services, and financial data platforms, with a path toward Staff-level platform responsibility.**

🌐 Explore the full portfolio → <a href="https://augustine0890.github.io" target="_blank" rel="noopener noreferrer"><strong>augustine0890.github.io</strong></a>

<a href="mailto:augustino0890@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Get_In_Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Get In Touch"></a>

</div>

<!---
augustine0890/augustine0890 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
