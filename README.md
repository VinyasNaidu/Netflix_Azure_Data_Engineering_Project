# 🎬 Azure End-to-End Data Engineering Project: **Netflix Data Lakehouse** (Azure + Databricks + Unity Catalog + DLT)

> Modern, parameterized, Medallion-architecture data platform on Azure using Netflix shows/movies data.  


---

## 🔥 Why this project?

- **2025-ready skills**: dynamic/parameterized pipelines, streaming-friendly ingestion, Unity Catalog governance, DLT-based gold curation.
- **Realistic architecture**: Source → Raw → Bronze → Silver → Gold → BI, with **incremental loads**, **quality gates**, and **secure connectivity**.

---

## 🧰 Tech Stack (at a glance)

| Category | Technology/Feature | Details |
|---|---|---|
| Orchestration & Ingestion | **Azure Data Factory (ADF)** | Dynamic, parameterized pipelines; GitHub ingestion via HTTP linked service; validation steps |
| Incremental Landing | **Databricks Auto Loader** | Schema inference/evolution, checkpointing, exactly-once semantics |
| Governance | **Unity Catalog** | Metastore, catalogs/schemas, external locations & storage credentials |
| Transformations | **Databricks Workflows + PySpark** | Parameterized notebooks (widgets), array params, If/Else conditionals |
| Gold Curation | **Delta Live Tables (DLT)** | Declarative ETL, streaming, dependencies, expectations |
| Storage | **ADLS Gen2** | Containers: `raw`, `bronze`, `silver`, `gold` |
| Data Quality | **DLT Expectations** | `expect_all` / `drop` rules, quarantine bad records |
| Security | **Access Connector + RBAC** | Managed identity auth to ADLS; fine-grained UC permissions |
| BI | **Power BI** | Partner Connect to Databricks SQL Warehouse |

---

## 🗺️ Architecture Overview
<img width="1029" height="502" alt="Screenshot 2025-09-22 at 1 01 30 AM" src="https://github.com/user-attachments/assets/7c32d69d-ef47-4547-bb76-5a7a7fa495e1" />

