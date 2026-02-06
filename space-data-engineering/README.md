# Space Data Engineering

Data pipelines built around space industry APIs and datasets. Each project ingests, transforms, and serves real-world space data using production-grade tooling.

**Tech Stack:** Python | SQL | Apache Airflow | Kafka | AWS | Docker | Terraform

---

## Projects

| # | Project | Description | Status |
|---|---------|-------------|--------|
| 01 | [SpaceX Launch Tracker](./01-spacex-launch-tracker) | Pipeline ingesting SpaceX launch data via API, transforming and loading into a warehouse for analysis | Planned |
| 02 | [NASA NEO Tracker](./02-nasa-neo-tracker) | Near-Earth Object tracking pipeline using NASA's NeoWs API with alerting and visualization | Planned |
| 03 | [Global Launch Library](./03-global-launch-library) | Aggregated global launch data from Launch Library 2 API with historical trend analysis | Planned |
| 04 | [Satellite Tracker](./04-satellite-tracker) | Real-time satellite position tracking pipeline with orbital data processing | Planned |

---

## Architecture Pattern

Each project follows a consistent pipeline architecture:

```
Source API → Ingestion (Python) → Staging (S3) → Transform (SQL/dbt) → Warehouse → Dashboard
```

Orchestration via Airflow. Infrastructure defined in Terraform. Containerized with Docker.

---

## About

Built by an Army veteran transitioning into data engineering. These projects demonstrate real pipeline skills applied to a domain I'm genuinely interested in — space exploration and the data behind it.
