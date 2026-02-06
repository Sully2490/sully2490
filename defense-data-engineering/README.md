# Defense Data Engineering

Data pipelines focused on publicly available defense and government datasets. These projects work with open contract, procurement, and spending data to build analytical pipelines relevant to the defense sector.

**Tech Stack:** Python | SQL | Apache Airflow | Kafka | AWS | Docker | Terraform

---

## Projects

| # | Project | Description | Status |
|---|---------|-------------|--------|
| 01 | [Contract Pipeline](./01-contract-pipeline) | ETL pipeline processing federal contract data from USAspending.gov and FPDS | Planned |
| 02 | [Procurement Analysis](./02-procurement-analysis) | Analytical pipeline for defense procurement trends, vendor analysis, and spending patterns | Planned |

---

## Architecture Pattern

```
Public Data Source → Ingestion (Python) → Staging (S3) → Transform (SQL/dbt) → Warehouse → Dashboard
```

Orchestration via Airflow. Infrastructure defined in Terraform. Containerized with Docker.

---

## About

Built by an Army veteran who understands defense operations firsthand. These projects apply data engineering to the kind of data problems that actually exist in the defense space — contract tracking, procurement analysis, and spending visibility.
