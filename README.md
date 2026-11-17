# Hi, I'm Fidelis Addi 👋

**Data Platform Engineer · Calgary, AB**

I build data platforms end to end: ingestion, lakehouse modelling, orchestration, CI/CD, and the dashboards people actually use. I'm currently the sole data engineer at Iron Gate Wine Auctions, where I designed and built the company's data platform from scratch on Azure and Databricks.

## ⭐ Featured project

**[databricks-medallion-pipeline](https://github.com/Fideladdi/databricks-medallion-pipeline)**
A production-style batch platform on Azure Databricks. Files land in ADLS Gen2, a file-arrival trigger starts the job, and Bronze → Silver → Gold notebooks build a star schema for Power BI. A Delta control table tracks every batch, so failed loads retry automatically and reruns never duplicate data. Deployed to dev, test and prod with Databricks Asset Bundles and GitHub Actions.

## 🏗️ What I work on

- **Lakehouse architecture:** medallion pipelines on Databricks with Delta Lake and Unity Catalog
- **Incremental processing:** batch control tables, idempotent `MERGE` and `replaceWhere` loads, automatic retries
- **Dimensional modelling:** star schemas, surrogate keys, schema drift handling
- **Orchestration and ingestion:** Databricks Jobs, Azure Data Factory, file-arrival triggers, ADLS Gen2
- **CI/CD:** GitHub Actions, pytest, Databricks Asset Bundles, service principal deployments across environments
- **Cost and performance:** compute tuning (classic vs. serverless), diagnosing cloud networking costs
- **Analytics delivery:** self-hosted Apache Superset with row-level security, Power BI
- **Automation:** pipeline-driven Slack reporting with Databricks SQL and LLM summaries, n8n workflows

## 🔧 Tech stack

| | |
|---|---|
| **Languages** | Python · SQL · PySpark |
| **Platforms** | Databricks · Delta Lake · Unity Catalog · Azure Data Factory · ADLS Gen2 |
| **Databases** | PostgreSQL · MySQL |
| **BI and analytics** | Power BI · Apache Superset |
| **Backend and automation** | FastAPI · Django · n8n · Docker |
| **DevOps and tools** | GitHub Actions · Databricks Asset Bundles · Git · Linux · Jupyter |

## 📌 Currently

- Exploring industrial and OT data (AVEVA PI, OPC UA, Ignition) for energy-sector use cases
- Writing up data platform patterns from production work

## 📫 Connect

💼 [LinkedIn](https://linkedin.com/in/fidelisaddi) · 🌐 [addifidelis.com](https://addifidelis.com) · 📧 addifidelis@live.com
