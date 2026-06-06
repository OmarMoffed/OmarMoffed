<div align="center">

# Omar Alfarouk Abbas

**Senior Analytics Engineer · Data Engineer · Finance Data Analyst**

I build data platforms that regulators trust and engineers enjoy maintaining.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omarmoffed)
[![Personal Website](https://img.shields.io/badge/Portfolio-1F4E79?style=for-the-badge&logo=google-chrome&logoColor=white)](https://omaralfarouk.work)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mr.omarmoffed@gmail.com)

</div>

---

### About

Analytics Engineer with **5+ years** in **regulated banking and fintech**. I spend most of my time in the space between raw data and a regulator's inbox — building pipelines that are automated, validated, and boring in the best way (no surprises at 3 AM).

Currently at **Vision Bank** (Saudi Arabia):
- Collaborating in **PostgreSQL/Oracle → Google BigQuery** migration with Google Professional Services
- Automating **SAMA regulatory reporting** end-to-end: schema discovery → dbt models → Airflow orchestration → validation frameworks → submission
- Building a **Self-Service BI layer** on Tableau so analysts stop asking me for ad-hoc queries

Previously shipped BI platforms at **ZATCA** (with Deloitte & PwC), **TETCO**, and **Blueprint Technologies** (Dubai).

**Open to relocation:** 🇬🇧 United Kingdom · 🇳🇱 Netherlands · 🇩🇪 Germany · 🇮🇪 Ireland

---

### How I Think About Data Currently

```
Raw Source  →  Staging  →  Intermediate  →  Marts  →  BI / Regulatory Reports
   │              │              │              │              │
   │         dbt source     dbt models     Star Schema    Tableau / 
   │         freshness      + tests        Kimball        Looker /
   │         checks         + docs         modelling      Power BI
   │              │              │              │              │
   └──────── Airflow orchestrates the whole thing ────────────┘
                              │
                    BigQuery / Snowflake / Databricks
                    (the warehouse layer)
```

**Opinions I hold:**
- dbt tests are not optional — if it doesn't have `not_null` and `unique`, it's not production-ready
- Dimensional modelling (Kimball) still wins for analytics — wide tables are a code smell
- Regulatory pipelines need reconciliation at every hop, not just at the end
- If a dashboard takes more than 10 seconds to load, it's an engineering failure

---

### Impact

```
ETL Runtime            60+ min  →  5–10 min       ██████████████░░  80% faster
Dashboard Refresh      2+ hours →  under 5 min    ████████████████  95% faster
File Size              500 MB   →  under 100 MB   ████████████░░░░  79% smaller
Regulatory Accuracy    ————————————————————————    ████████████████  100%
Executive KPIs         ————————————————————————    ████████████████  100+ shipped
```

---

### Tech Stack

**Data Engineering & Orchestration**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Programming**

![SQL](https://img.shields.io/badge/SQL-Advanced-336791?style=flat-square&logo=amazon-dynamodb&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**BI & Visualisation**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=power-bi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=flat-square&logo=looker&logoColor=white)
![SSRS](https://img.shields.io/badge/SSRS-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

**Cloud & DevOps**

![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab_CI/CD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Regulated Domains**

![Regulatory Reporting](https://img.shields.io/badge/Regulatory_Reporting_(SAMA)-1F4E79?style=flat-square)
![Fraud & Risk](https://img.shields.io/badge/Fraud_&_Risk_Analytics-D32F2F?style=flat-square)
![Data Governance](https://img.shields.io/badge/Data_Governance-5E35B1?style=flat-square)
![Fintech](https://img.shields.io/badge/Fintech-00C853?style=flat-square)
![Digital Banking](https://img.shields.io/badge/Digital_Banking-1565C0?style=flat-square)

---

### Currently Exploring

```python
learning_queue = {
    "deep_dive":    ["Apache Spark / PySpark", "Databricks", "Data Vault 2.0"],
    "leveling_up":  ["MLOps fundamentals", "Great Expectations (data quality)"],
    "studying":     "MSc Data Science — Rome Business School (2025–present)"
}
```

---

### 📌 Featured Projects

| Project | What It Does | Stack |
|---------|-------------|-------|
| 🏦 **[regulatory-reporting-framework](#)** | End-to-end SAMA regulatory reporting: staging → transformation → validation → submission. Reconciliation checks at every hop. | dbt, Airflow, BigQuery, Python |
| 🧱 **[dbt-dimensional-model](#)** | Sample dimensional model (Star Schema / Kimball) with staging, intermediate, and mart layers. Includes dbt tests, docs, and CI. | dbt, BigQuery, GitLab CI |
| 🔄 **[airflow-orchestration-patterns](#)** | Production Airflow DAG patterns: sensor triggers, dynamic task mapping, failure alerting, SLA monitoring. | Python, Airflow, Docker |
| ⚡ **[sql-performance-cookbook](#)** | Advanced SQL optimisation: CTEs vs subqueries, window functions, partition pruning, query plan analysis. Real examples from BigQuery + PostgreSQL. | SQL, BigQuery, PostgreSQL |
| 📊 **[power-bi-optimization-toolkit](#)** | DAX refactoring patterns, data-model compression, incremental refresh configs. Cut dashboard refresh by 70–95%. | Power BI, DAX, SQL |

> *Some repos contain sanitised examples inspired by production patterns — no proprietary data.*

---

### Certifications

![PBI](https://img.shields.io/badge/Microsoft-Power_BI_Data_Analyst_Associate-F2C811?style=flat-square&logo=power-bi&logoColor=black)
![Azure](https://img.shields.io/badge/Microsoft-Azure_Data_Fundamentals-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-Bootcamp_Zero_to_Hero-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-Hands_On_Essentials-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

---

### Education

🎓 **MSc Data Science** — Rome Business School, Italy *(2025 – Present)*

🎓 **BSc Mathematics & Computer Science** — University of Gezira, Sudan *(2014 – 2020)*

---

<div align="center">

**💬 I like talking about:** dimensional modelling · dbt patterns · regulatory data pipelines · cloud migration war stories · why your dashboard is slow

**📬 Reach me:** [mr.omarmoffed@gmail.com](mailto:mr.omarmoffed@gmail.com) · [LinkedIn](https://www.linkedin.com/in/omarmoffed) · [omaralfarouk.work](https://omaralfarouk.work)


</div>
