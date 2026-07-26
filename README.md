<div align="center">

<h1>Hi, I'm Franz Monzales 👋</h1>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00FF9D&center=true&vCenter=true&width=700&lines=Data+Engineer+%7C+ETL+%26+Pipeline+Developer;Data+Warehouse+%26+Analytics+Platform+Builder;Building+Scalable%2C+Deterministic+Data+Infrastructure;Python+%7C+SQL+%7C+Modern+Data+Stack" alt="Typing SVG" />

<p><b>Software Engineer turned Data Engineer</b>, with 5+ years of professional dev experience now focused on building reliable, production-grade data platforms — from ingestion and orchestration to dimensional modeling, data quality, governance, and analytics-ready warehouses.</p>

<p>🟢 <b>Open to:</b> Data Engineer · ETL Developer · Data Warehouse Engineer roles (Remote / Philippines)</p>

<a href="https://www.linkedin.com/in/franz-monzales" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://twitter.com/ikigamidevs" target="_blank"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<a href="mailto:ikigamidevs@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/ikidevz" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

</div>

## 🧭 Background

I spent 5+ years as a **full-stack web developer**, building and shipping production systems end-to-end — REST APIs, database design, deployment pipelines, and systems that had to hold up under real users and real data. That work is what pulled me toward data engineering in the first place: I kept finding myself more interested in *how data moved and stayed correct* than in the UI sitting on top of it.

What carries over directly:
- **API & backend design** → building resilient ingestion layers and integration points (see `ikiapikit`)
- **Database schema design** → dimensional modeling, Data Vault 2.0, and warehouse design
- **CI/CD & deployment discipline** → orchestration, idempotent pipelines, and production-grade tooling instead of one-off scripts
- **Debugging distributed, stateful systems** → the same muscle used for data quality issues, CDC, and pipeline failures at scale

The projects below are self-directed — mostly built on synthetic data by design, so I could safely model realistic scale and edge cases (multi-subsidiary finance, regulatory reporting, PII) without needing access to a company's real production data. They're meant to demonstrate architectural judgment, not just tool familiarity.

<br/>

## ⭐ Start Here: Flagship Project

**[Enterprise Holdings Multi-Subsidiary Data Platform](https://github.com/ikidevz/Enterprise-Holdings-Multi-Subsidiary-Data-Platform)**

A fully idempotent, end-to-end data platform modeled on a 10-subsidiary conglomerate — the project I'd point to first if you only have time to look at one.

- Synthetic source data generation → orchestrated ingestion → integration layer → conformed marts → executive dashboards
- Designed to be re-run safely at any point without duplicating or corrupting data (idempotency by design, not an afterthought)
- Covers the full breadth of the stack: Airflow orchestration, dbt transformations, dimensional modeling, and BI-ready outputs across finance, operations, and group reporting

<br/>

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge&logo=delta&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-003B77?style=for-the-badge&logo=timescale&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-FF4C4C?style=for-the-badge&logo=polars&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

</div>

| Category | Tools | Level |
|---|---|---|
| **Core** | Python, SQL | Advanced |
| **Orchestration** | Apache Airflow, dbt, Docker | Experienced |
| **Data Platforms** | Spark, Kafka, Delta Lake, PostgreSQL, TimescaleDB | Experienced |
| **Data Quality & Governance** | Great Expectations, Iki_DQ_Check, PII handling | Experienced |
| **APIs & Ingestion** | ikiapikit, FastAPI, async scraping | Experienced |
| **Analytics** | Pandas, Polars, Streamlit, Plotly, Superset/Metabase | Intermediate |
| **Web / DevOps** | React/Next.js, Git, CI/CD, Heroku, Vercel, DigitalOcean | Intermediate |

<br/>

## 🚀 Featured Tools & Utilities

Production-ready, open-source tools built to solve real pain points for data professionals.

<table>
<tr>
<td width="50%" valign="top">

**[IkiDataGenerator](https://github.com/ikidevz/IkiDataGenerator)**
<img src="https://raw.githubusercontent.com/ikidevz/IkiDataGenerator/refs/heads/main/assets/cover.png" width="100%"/>
Generate realistic synthetic data with **700+ fields** across 22 categories. Supports CSV, Parquet, JSON, SQL, Excel, DuckDB, and more. Perfect for testing, demos, and privacy-safe development.

</td>
<td width="50%" valign="top">

**[ikiapikit](https://github.com/ikidevz/ikiapikit)**
<img src="https://raw.githubusercontent.com/ikidevz/ikiapikit/main/assets/cover.png" width="100%"/>
The Swiss-army knife for REST & GraphQL APIs. One elegant interface for pagination, retries, DataFrames (Polars/Pandas), streaming, and file exports (Parquet/NDJSON). Built for data ingestion at scale.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[IkiProtect](https://github.com/ikidevz/IkiProtect)**
<img src="https://raw.githubusercontent.com/ikidevz/IkiProtect/main/assets/image.png" width="100%"/>
One tool. Every data-protection primitive you'll ever need.

</td>
<td width="50%" valign="top">

**[Iki_PII_Masker](https://github.com/ikidevz/Iki_PII_Masker)**
<img src="https://raw.githubusercontent.com/ikidevz/Iki_PII_Masker/main/assets/image.png" width="100%"/>
Fast, pipe-friendly CLI + library for sanitizing PII. 10+ strategies (fake, redact, hash, reversible AES, etc.), auto-detection, multi-format support, and dry-run capabilities.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[IkiSchema](https://github.com/ikidevz/IkiSchema)**
<img src="https://raw.githubusercontent.com/ikidevz/IkiSchema/main/assets/image.png" width="100%"/>
Infer, compare, and validate data schemas.

</td>
<td width="50%" valign="top">

**[IkiChunk](https://github.com/ikidevz/IkiChunk)**
<img src="https://raw.githubusercontent.com/ikidevz/IkiChunk/main/assets/image.png" width="100%"/>
One facade, zero required dependencies — tackle common data engineering tasks with minimal code.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Iki Data Governance](https://github.com/ikidevz/ikidgov-Iki-Data-Goverance)**
<img src="https://raw.githubusercontent.com/ikidevz/ikidgov-Iki-Data-Goverance/main/assets/image.png" width="100%"/>
A lightweight, composable data governance toolkit for scanning data sources, classifying columns, and evaluating role-based access policies — without requiring a large platform migration.

</td>
<td width="50%" valign="top">

**[Iki_Scraper](https://github.com/ikidevz/Iki_Scraper)**
<img src="https://tdhghaslnufgtzjybhhf.supabase.co/storage/v1/object/public/content/Data%20Tools%20Scripts/Iki-Scraper/img_cover.png" width="100%"/>
Advanced asynchronous web scraping framework powered by Playwright. Clean verb-first API with structured extraction, table parsing, change detection, resumable runs, and sitemap discovery.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Iki_DQ_Check](https://github.com/ikidevz/Iki_DQ_Check)**
<img src="https://tdhghaslnufgtzjybhhf.supabase.co/storage/v1/object/public/content/Data%20Tools%20Scripts/Iki-DQ-Check/cover.png" width="100%"/>
Production-grade data quality validation with 25+ checks across Lite/Standard/Advanced tiers. Python-native config, CLI, and universal facade for Pandas, Polars, DuckDB, SQL, etc.

</td>
<td width="50%" valign="top">

**[Iki-ETL-Table-Driven](https://github.com/ikidevz/Iki-ETL-Table-Driven)**
<img src="https://raw.githubusercontent.com/ikidevz/Iki-ETL-Table-Driven/main/assets/image.png" width="100%"/>
A single, table-driven ETL Swiss-army-knife.

</td>
</tr>
</table>

<br/>

## 📊 More Data Engineering Projects

| Project | What it demonstrates |
|---|---|
| **[ETL PH Banking AML](https://github.com/ikidevz/ETL_ph_banking_aml)** | BSP-compliant AML system using **Data Vault 2.0**, Snowflake Streams CDC, PII masking, fuzzy matching, and regulatory reporting marts |
| **[PH Logistics Port Congestion](https://github.com/ikidevz/ETL_ph_logistics_port_congestion)** | Port monitoring using **Kimball modeling + Snowflake Dynamic Tables** for near-real-time insight without external streaming |
| **[PH Multi-Subsidiary Enterprise DW](https://github.com/ikidevz/ETL_PH-Multi-Subsidiary-Enterprise-Data-Warehouse)** | Enterprise warehouse unifying 5 subsidiaries via a **3NF integration layer** and conformed marts for finance, ops, and reporting |
| **[PH Corporate Finance FP&A](https://github.com/ikidevz/ETL_PH-Corporate-Finance-FP-A)** | Kimball warehouse on Snowflake + dbt + Airflow for budget variance, consolidated P&L, rolling forecasts, and cash flow across a multi-subsidiary group |

<details>
<summary><b>More pipelines & platforms</b></summary>
<br/>

- **[Landed Cost Calculator](https://github.com/ikidevz/Landed-Cost-Calculator-Logistic-Data-Pipeline)** — Kafka + Airflow + dbt + Metabase for PH import logistics
- **[PH Port Congestion Monitor](https://github.com/ikidevz/PH-Port-Congestion-Monitor-Data-Pipeline)** — Real-time & batch monitoring, Medallion architecture
- **[Retail Medallion Data Pipeline](https://github.com/ikidevz/Retail-Medallion-Data-Pipeline)** — Bronze → Silver → Gold with Polars and a Star Schema
- **[BSP-AMLA Compliance Pipeline](https://github.com/ikidevz/BSP-AMLA-Compliance-Suspicious-Transaction-Reporting-Pipeline)** — Synthetic banking data with AML detection & reporting
- **[PH Multi-Subsidiary Data Lakehouse](https://github.com/ikidevz/PH-Multi-Subsidiary-Data-Lakehouse)** — CDC via Debezium + Kafka + Airflow + Superset
- **[RemitFlowPH](https://github.com/ikidevz/RemitFlowPH)** — Microservices remittance pipeline, TimescaleDB + Streamlit
- **[ETL-Table-Driven](https://github.com/ikidevz/ETL-Table-Driven)** — Metadata-driven framework for zero-code pipeline additions
- Multiple production-grade **Streamlit + Plotly** dashboards covering supply chain, retail sales, customer cohorts, churn, and marketing analytics

</details>

<br/>

## 🎓 Certifications

- [Data Engineer Professional Certificate](https://learn.365datascience.com/certificates/DD-0FA99845A0/) — 365 Data Science
- [Data Engineering Professional](https://www.coursera.org/account/accomplishments/professional-cert/1AT47XEDRYSM) — DeepLearning.AI (Coursera)
- [Data Scientist Certificate](https://www.coursera.org/account/accomplishments/specialization/2QEGUBE3VTFZ) — 365 Data Science
- [Data Analyst Certificate](https://www.coursera.org/account/accomplishments/specialization/7SNWN9YKGZVR) — 365 Data Science
- [IBM Data Science Specialization](https://learn.365datascience.com/certificates/DD-DFAA0CDAE2/) — IBM (Coursera)
- [IBM Data Analyst Specialization](https://learn.365datascience.com/certificates/DD-46F49544DE/) — IBM (Coursera)

<br/>

## 📈 GitHub Stats

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=ikidevz&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ikidevz&theme=radical&hide_border=true" alt="GitHub Streak" height="165"/>

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=ikidevz&layout=compact&theme=radical&hide_border=true" alt="Top Languages" height="165"/>

</div>

<div align="center">
<br/>
<i>💬 Open to collaborating on data platform, ETL, or open-source data-tooling projects — feel free to reach out.</i>
</div>
