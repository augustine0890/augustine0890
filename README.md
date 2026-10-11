<div align="center">

[![Augustine Nguyen — Senior Data Engineer](https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=E94560&center=true&vCenter=true&width=800&height=80&lines=Augustine+Nguyen;Senior+Data+Engineer;Market+Data+%C2%B7+AI+%C2%B7+Quantitative+Finance;Trustworthy+Financial+Data+Platforms)](https://git.io/typing-svg)

### Data Engineer | Market Data, AI & Quantitative Finance

<br/>

<a href="https://augustine0890.github.io" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Portfolio-1F2937?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/augustine2015/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:augustino0890@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://twitter.com/augusti61988772" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Twitter-1D9BF0?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"></a>
<a href="#credentials"><img src="https://img.shields.io/badge/AWS_Certified_Data_Engineer-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Certified Data Engineer"></a>

<br/>

> *Point-in-time correct, reproducible data for trading, risk, and AI.*

| **5B+** | **10M+** | **+3%** | **🏆 1st** | **7+ yrs** |
|:---:|:---:|:---:|:---:|:---:|
| records on HA clusters | platform users served | credit scoring lift | FPT AI Hackathon 3 · 2025 (global) | industry data & ML engineering |

</div>

---

## ◈ About Me

I'm a **Data Engineer with a quantitative modeling background**, based in the **Republic of Korea**. I build the pipelines and storage that financial, quantitative, and AI workloads rely on, and I design them from the consumer back: the risk model, the analyst's report, the retrieval system.

My background combines **credit risk modeling and causal inference** with **platform engineering**: highly available ClickHouse / MongoDB / Redis clusters holding **5B+ records**, **Spark** pipelines for a platform with **10M+ users**, **Kafka**-based real-time blockchain transaction streams, an **Oracle → PostgreSQL** migration for an investment securities system, and a multimodal RAG pipeline that won **FPT AI Hackathon 3 (2025)**.

Because I've worked as a modeler, I build data the way modelers need it: **versioned, leak-free, and reproducible to the row**.

---

## ◈ Where I Fit

| Target role | What I bring | Evidence |
|:---|:---|:---|
| **Financial Data Engineer** | Highly available storage with disaster recovery · SQL migration that preserves business semantics · traceable, reconcilable financial records | [ABACUS](#abacus) · [Investment Securities](#investment-securities) |
| **Market Data Engineer** | Real-time event ingestion · publish–subscribe fan-out · columnar storage for high-volume time-ordered data · sub-second search | [BlockStream](#blockstream) · ClickHouse clusters |
| **Quantitative Data Engineer** | Model-ready datasets for credit risk · statistical and causal modeling (IV, survival analysis) · Spark at scale | [ABACUS](#abacus) · [Modeling background](#quant-background) |
| **AI Data Engineer** | Unstructured → structured document pipelines · parallel multimodal parsing · vector indexing · LLM/NLP enrichment | [AISOL 🏆](#aisol) · Discord Emotion Tracker |

---

## ◈ How I Build Market & Financial Data

What I prioritize when designing market, quantitative, and financial data systems:

- **Point-in-time correctness.** Keep *event time*, *ingestion time*, and *knowledge time* separate. Use as-of joins and keep revisions so backtests and model training never see data from the future.
- **Reference data first.** Stable instrument and entity identifiers, symbol mapping across sources, corporate actions and price adjustments, trading calendars and time zones. Most market data bugs are reference data bugs.
- **Idempotent, replayable pipelines.** Deduplication keys, late and out-of-order event handling, deterministic reruns, and backfills that can't corrupt history.
- **Data contracts and quality gates.** Explicit schemas and how they evolve, freshness and completeness targets, and reconciliation against the source of record *before* data reaches traders, risk, or models.
- **Lineage and reproducibility.** Any number in a report, signal, or model should trace back to versioned inputs and the transformation that produced it.
- **Storage that fits the access pattern.** Columnar stores for analytical scans over time series, key-value caches for hot lookups, search indexes for exploration, and vector stores for retrieval, each chosen on latency, throughput, and cost.
- **AI-ready data is still data.** Chunks keep their source, structure, and provenance, and retrieval quality gets measured like any other data product.

---

## ◈ Featured Work

<a id="abacus"></a>

### ABACUS — Credit Risk Data Platform

> *AZEN Global · Data Scientist / ML Engineer · 2019–2020*<br/>
> `Financial DE` `Quant DE` · Credit risk & fault detection · **10M+ users · 5B+ records**

A machine learning platform for credit risk scoring and fault detection. The work covered storage, distributed processing, modeling, and operational visibility.

- Architected **highly available ClickHouse, MongoDB, and Redis clusters** managing **5B+ records**, with disaster recovery provisions for data integrity and operational continuity
- Optimized **Apache Spark** fault-detection pipelines, materially increasing throughput for workflows serving **10M+ users**
- Developed credit risk models achieving a **+3% lift in scoring accuracy**, connecting upstream data processing to downstream model performance
- Built **real-time monitoring dashboards and interactive reports** to surface platform signals for operational decisions

`Python` `Apache Spark` `ClickHouse` `MongoDB` `Redis` `Oracle` `Django` `FastAPI`

---

<a id="blockstream"></a>

### BlockStream — Real-Time Blockchain Transaction Pipeline

> *SupperTree · Software Engineer · 2021–2024*<br/>
> `Market DE` · On-chain financial transaction streams · Ethereum & Polygon · Publish–subscribe

A streaming system that ingests, distributes, stores, and indexes high-volume on-chain transaction data, the same problem shape as a market data feed handler.

- Architected real-time collection of **Ethereum and Polygon transaction data**
- Engineered the pipeline **on-chain collection → Kafka → PostgreSQL → OpenSearch / Algolia**, supporting **sub-second search**
- Managed metadata enrichment, persistence, and indexing end to end to keep data consistent and retrieval scalable

`Python` `Golang` `Kafka` `Kinesis` `PostgreSQL` `OpenSearch` `Algolia`

---

<a id="aisol"></a>

### AISOL — Multimodal RAG Data Pipeline · 🏆 Champion

> *FPT Software Korea · FPT AI Hackathon 3 (2025, global) · Track: KT/KB Technical Solutions*<br/>
> `AI DE` · Japanese-language enterprise RAG · Document intelligence

- Designed and delivered a pipeline converting **Excel, Word, PowerPoint, and PDF** documents into structured, retrievable data for enterprise AI
- Parallelized processing of **text, tables, and diagrams**, removing the sequential bottleneck of conventional document loaders
- Preserved **semantic context across document structures** so queries spanning multiple sections resolve correctly
- Integrated **Qdrant** for vector storage, **Gemini** for multimodal understanding, and **Qwen** for Japanese-language generation

`Python` `Qdrant` `Gemini` `Qwen` `RAG` `Vector Search` `Multimodal AI`

---

<a id="investment-securities"></a>

### Investment Securities (Meta) — Oracle → EDB (PostgreSQL) Migration

> *FPT Software Korea · Data Software Engineer · 2024–Present*<br/>
> `Financial DE` · Investment securities workflows · Database portability

- Converted and optimized **Oracle SQL** to **ANSI SQL** for **EDB (PostgreSQL)** compatibility, improving query efficiency and portability
- Translated investment securities business requirements into SQL that stays aligned with financial workflows

`Oracle` `EDB (PostgreSQL)` `ANSI SQL` `SQL Optimization`

---

<details>
<summary><b>More projects</b>: InsightFlow · QA/QC Analytics · Discord Emotion Tracker</summary>

<br/>

#### InsightFlow — Customer Behavior Streaming Analytics

> *FitPetMall · Data Software Engineer · 2020–2021* · E-commerce / fintech event streaming

- Built **Kafka + ELK Stack** event streaming to capture high-volume customer behavior data
- Developed **RFM segmentation, conversion funnel, and propensity-to-purchase scoring** pipelines for campaign targeting
- Architected promotional, delivery, and shipping analytics for revenue and operational decisions

`Kafka` `ELK Stack` `FastAPI` `Python` `Oracle`

#### QA/QC Data Analytics & Visualization Dashboard

> *FPT Software Korea · Data Software Engineer · 2024–Present* · Statistical processing & delivery

- Built **SQL and Java pipelines** to aggregate, preprocess, and analyze large QA/QC datasets
- Applied **Apache Commons Math** for statistical trend and anomaly analysis
- Delivered real-time statistical reports through **Spring Boot REST APIs** and **Chart.js** dashboards

`Java` `Spring Boot` `Oracle` `SQL` `Apache Commons Math` `Chart.js`

#### Discord Emotion Tracker — NLP Enrichment Pipeline

> *SupperTree · Software Engineer · 2021–2024* · Message ingestion, translation & sentiment enrichment

- Captured Discord interactions and built a labeled dataset for **sentiment analysis and emotion classification**
- Enriched messages with **AWS Comprehend**, **HuggingFace Rust-BERT**, and **AWS Translate** (English → Korean)
- Modeled **MongoDB** storage for messages, translations, and sentiment metrics for downstream analysis

`Rust` `Python` `AWS Comprehend` `AWS Translate` `HuggingFace` `MongoDB`

#### Side Projects

- **[discord-playdapp-bot](https://github.com/augustine0890/discord-playdapp-bot)** · Rust, Serenity, MongoDB, Docker. Discord bot for tournament ticket exchange, engagement tracking, and leaderboards
- **[outfit-square](https://github.com/augustine0890/outfit-square)** · Python, Discord.py, MongoDB. Point management bot with dev/prod deployment and OAuth2

</details>

---

<a id="quant-background"></a>

## ◈ Quantitative & Modeling Background

I started in modeling, and I still read pipelines from the modeler's side.

- **Credit risk modeling.** Built scoring models at AZEN Global (+3% accuracy lift) with **scikit-learn, XGBoost, LightGBM**, explained with **SHAP / LIME**
- **Causal inference.** Master's thesis used **Mendelian randomization (instrumental variable analysis)** on genome-wide SNP data. The same identification logic carries over to financial econometrics
- **Statistical methods.** Survival analysis (Kaplan–Meier, Cox PH, AFT), A/B and Bayesian experimentation, DiD, propensity score matching

In practice, this means I anticipate **look-ahead bias, survivorship bias, label leakage, and non-reproducible training sets** before they reach a model.

---

## ◈ Core Engineering Experience

| Domain | Tools & Methods |
|:---|:---|
| **Streaming & Real-Time Ingestion** | Apache Kafka · Kinesis · Publish–Subscribe · ELK Stack |
| **Batch & Distributed Processing** | Apache Spark · Airflow · dbt · ETL/ELT · Pandas |
| **Analytical & Operational Storage** | ClickHouse · PostgreSQL / EDB · Oracle · MongoDB · Redis · HA Clusters · Disaster Recovery |
| **Search & Retrieval** | OpenSearch · Algolia · Qdrant · Vector Search |
| **SQL Engineering** | Query Optimization · Oracle → PostgreSQL Migration · ANSI SQL |
| **AI Data Engineering** | Multimodal Document Processing · RAG · LangChain · Gemini · Qwen · HuggingFace · AWS Comprehend |
| **Quant & ML Modeling** | scikit-learn · XGBoost · LightGBM · Statsmodels · SHAP · Survival Analysis · Causal Inference |
| **Financial Data Domains** | Credit Risk · Investment Securities · On-Chain Transactions · Fault Detection |
| **Delivery & Observability** | FastAPI · Django · Spring Boot · REST APIs · Operational Dashboards |
| **Cloud & Infrastructure** | AWS · Azure · Docker · Kubernetes |
| **Languages** | Python · SQL · Rust · Golang · Java · TypeScript · R · SAS |

---

## ◈ Tech Stack

<div align="center">

**Data Engineering** &nbsp;·&nbsp;
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)

**Databases** &nbsp;·&nbsp;
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Cloud & Infra** &nbsp;·&nbsp;
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**AI & Retrieval** &nbsp;·&nbsp;
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Quant & ML** &nbsp;·&nbsp;
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Languages** &nbsp;·&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

</div>

---

## ◈ Experience

| Period | Company | Role | Focus |
|:---|:---|:---|:---|
| 2024 – Present | **FPT Software Korea** | Data Software Engineer | Investment securities SQL migration · statistical data pipelines · enterprise RAG |
| 2021 – 2024 | **SupperTree** | Software Engineer | Real-time blockchain transaction pipelines · NLP enrichment |
| 2020 – 2021 | **FitPetMall** | Data Software Engineer | Event streaming & customer behavior analytics |
| 2019 – 2020 | **AZEN Global** | Data Scientist / ML Engineer | Credit risk modeling · Spark pipelines · HA database clusters |
| 2016 – 2018 | **National Cancer Center** | Graduate Research Assistant | Causal inference · statistical genetics |

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

<div align="center">

![footer](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

**Open to Senior Data Engineer roles:**<br/>
**AI Data Engineering · Market Data Engineering · Quantitative Data Engineering · Financial Data Engineering**

*I want data that a trader, risk manager, or model can rely on and trace back to its source.*

🌐 Explore the full portfolio → <a href="https://augustine0890.github.io" target="_blank" rel="noopener noreferrer"><strong>augustine0890.github.io</strong></a>

<a href="mailto:augustino0890@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Get_In_Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Get In Touch"></a>

</div>

<!---
augustine0890/augustine0890 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
