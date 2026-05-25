# Hi, I'm Jashwanth Reddy Earla

**Senior Data Engineer** — Cloud Data Platforms · ETL/ELT · Analytics Engineering | Mississauga, Canada
- [jashwanthreddyearla@gmail.com](mailto:jashwanthreddyearla@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jashwanthreddye/) · [Portfolio](https://jashwanthreddye.github.io)

---

## About

Senior Data Engineer with 4+ years building enterprise-grade data platforms on **Microsoft Azure** and **AWS** across banking, retail, and healthcare. I take ownership end-to-end — raw ingestion through business-ready analytics — and I ship to SLA.

What I work on, day to day:

- **Streaming + batch lakehouses** — PySpark on Databricks / EMR, Delta Lake medallion on ADLS Gen2, near-real-time event scoring via Event Hub, Kafka, and Structured Streaming.
- **Warehouses that hold up under audit** — star-schema models on Snowflake, Redshift, and Azure Synapse with SCD Type 2, CDC merge logic, and dbt tests as deployment gates.
- **Pipeline orchestration** — Airflow DAGs on AKS/EC2, ADF, AWS Glue + Step Functions, all wired through Azure DevOps and Jenkins CI/CD with Terraform IaC.
- **Governance + data quality** — Great Expectations, dbt tests, Python reconciliation, Purview / Glue Data Catalog lineage, column-level masking, RLS.
- **LLM-assisted engineering** — Azure OpenAI, Claude, and Copilot for prompt-engineered NL → SQL assistants, dbt model scaffolds, and auto-generated pipeline documentation.

---

## Tech I reach for

**Cloud** — Azure (ADF, Synapse, ADLS Gen2, Databricks, Event Hub, Functions, Purview, AKS) · AWS (S3, Redshift, Glue, EMR, Athena, Step Functions, Lambda, Bedrock)
**Warehousing** — Snowflake · Synapse · Redshift · SQL Server · Oracle · star/snowflake schema · SCD Type 1/2
**Pipelines** — Azure Data Factory · AWS Glue · dbt · Apache Airflow · PySpark · Databricks Structured Streaming
**Streaming** — Azure Event Hub · Kafka · AWS Step Functions · event-driven triggers
**DevOps / IaC** — Azure DevOps · Jenkins · Terraform · Docker · Kubernetes (AKS) · Git · GitHub Actions
**Quality + governance** — Great Expectations · dbt tests · Azure Purview · AWS Glue Data Catalog
**Visualization** — Power BI (DAX, RLS, semantic models) · Tableau · Streamlit · Plotly
**Languages** — Python (PySpark, Pandas, Boto3) · SQL (CTEs, window functions, tuning) · DAX · Shell
**AI / Prompt Engineering** — Azure OpenAI (GPT-4) · AWS Bedrock (Claude) · GitHub Copilot · LangChain · NL → SQL

---

## What I've shipped

**Senior Data Engineer · CGI · Aug 2024 – Present** *(Tier-1 Canadian bank)*
Real-time fraud detection on Azure — Event Hub + Kafka → Databricks Structured Streaming → Snowflake gold. Replaced T+1 batch fraud scoring with sub-8-second event-to-alert. Brought a 5-hour overnight feature refresh to under 90 minutes. Built a Purview lineage + Power BI quality console used by both engineering and OSFI compliance. Stood up an Azure OpenAI NL → SQL assistant on Snowflake fraud data for risk analysts.

**Data Engineer · Hexagon Capability Centre · Aug 2022 – Aug 2023** *(global retail client)*
Customer 360 platform on AWS as a federated data mesh — S3 + Glue Data Catalog, EMR PySpark identity stitching, Redshift star schema with conformed dimensions, dbt + Jenkins CI/CD. Migrated 16 legacy Informatica mappings and cut monthly segmentation cycles from 6 hours to ~90 minutes.

**Data Engineer · Quality Theorem · May 2020 – Jul 2022** *(hospital network)*
Azure Synapse data-warehouse modernization for clinical operations, claims, and provider analytics. Metadata-driven ADF templates replaced 19 legacy SSIS packages; dbt on Synapse with SCD Type 2 macros; Purview lineage with PHI classification; Power BI DirectQuery semantic models replacing 11 SSRS reports.

---

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**crypto-sentinel**](https://github.com/JashwanthReddyE/crypto-sentinel) · [live ↗](https://crypto-sentinel-dashboard.vercel.app/) | Azure Functions pipeline scoring 24 crypto assets daily into **BUY / WATCH / AVOID** picks. 6-signal weighted engine — news sentiment (CryptoPanic) + 3 momentum windows + volume ratio + trending bonus — exposed via HTTP endpoints and a Vercel dashboard. Runs at ~$0.03/month. 144 pytest cases. | Python 3.11 · Azure Functions v4 · CoinGecko · CryptoPanic · LRS Storage · Vercel |
| [**aws-stock-sentiment-pipeline**](https://github.com/JashwanthReddyE/aws-stock-sentiment-pipeline) | End-to-end AWS pipeline: Lambda news ingest → S3 medallion → Bedrock Claude Haiku sentiment → Athena → 5-day forecast → Streamlit dashboard. IaC with Terraform, CI on GitHub Actions, hermetic tests via moto. | Python · AWS Lambda · S3 · Athena · Bedrock · Terraform · Streamlit · Plotly |
| [**sql-data-warehouse-project**](https://github.com/JashwanthReddyE/sql-data-warehouse-project) | SQL Server data warehouse with a bronze / silver / gold medallion architecture. CRM + ERP source integration, SCD logic, quality checks, and gold-layer star-schema views (`dim_customers`, `dim_products`, `fact_sales`). | T-SQL · SQL Server · Medallion architecture · Dimensional modeling |
| [**Gen-AI**](https://github.com/JashwanthReddyE/Gen-AI) | LangChain *Ice Breaker* agent — given a person's name, finds their LinkedIn profile via Tavily search, scrapes it, and returns a structured Pydantic summary from Gemini. ReAct agent + prompt engineering. | Python · LangChain · Gemini · Tavily · Pydantic |
| [**IBM**](https://github.com/JashwanthReddyE/IBM) | IBM Data Science capstone — SpaceX Falcon 9 first-stage landing prediction. API + web scraping ingestion, EDA, label engineering, classification. Plus King County house-price regression. | Python · Pandas · scikit-learn · seaborn |
| [**JashwanthReddyE.github.io**](https://github.com/JashwanthReddyE/JashwanthReddyE.github.io) | Current portfolio site — architecture diagrams, wins-with-numbers, and deep-dives on the Crypto Sentinel and AWS stock-sentiment pipelines. | HTML · CSS · Vanilla JS |

---

## Coursework & earlier work

- [**Portfolio**](https://github.com/JashwanthReddyE/Portfolio) — first-iteration personal site (HTML / CSS / JS).
- [**double-pendulum**](https://github.com/JashwanthReddyE/double-pendulum) — MATLAB simulation of a chaotic double-pendulum system.
- [**INSE-6220**](https://github.com/JashwanthReddyE/INSE-6220) — Concordia advanced statistical methods project (Jupyter).
- [**INSE-6230**](https://github.com/JashwanthReddyE/INSE-6230) · [**INSE-6210-Data**](https://github.com/JashwanthReddyE/INSE-6210-Data) — Concordia project data and analysis sets.
- [**INSE-6250-Phonebook**](https://github.com/JashwanthReddyE/INSE-6250-Phonebook) — Java phonebook app, software-quality coursework.
- [**freecodecamp**](https://github.com/JashwanthReddyE/freecodecamp) — freeCodeCamp exercises.

---

## Education

- **M.Eng., Quality Systems Engineering** — Concordia University, Montreal · 2023 – 2025 · GPA 3.73/4.0
- **B.E., Mechanical Engineering** — Chaithanya Bharathi Institute of Technology, Hyderabad · 2017 – 2021 · GPA 7.96/10

---

## Get in touch

- [jashwanthreddyearla@gmail.com](mailto:jashwanthreddyearla@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/jashwanthreddye/)
- [Portfolio](https://jashwanthreddye.github.io)
