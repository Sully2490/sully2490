# Defense Space Command Center

Capstone project that ties together the full stack — space data pipelines, defense data integration, and production infrastructure into a unified command center application.

**Tech Stack:** Python | SQL | Apache Airflow | Kafka | AWS | Docker | Terraform

---

## Structure

```
defense-space-command-center/
├── src/                  # Application source code
├── infrastructure/       # Terraform, Docker, deployment configs
└── docs/                 # Architecture decisions, diagrams, runbooks
```

---

## Vision

A unified data platform that combines:
- **Space situational awareness** — satellite tracking, launch monitoring, NEO alerts
- **Defense contract intelligence** — procurement trends, vendor analysis, spending data
- **Real-time streaming** — live data feeds processed through Kafka
- **Production infrastructure** — deployed on AWS with IaC, CI/CD, and monitoring

This project pulls from every other repo in the portfolio. It's the integration point where individual pipelines become a working system.

---

## Components

| Component | Source Repo | Role |
|-----------|------------|------|
| Space Data Feeds | [space-data-engineering](https://github.com/sully2490/space-data-engineering) | Satellite, launch, and NEO data pipelines |
| Defense Data Feeds | [defense-data-engineering](https://github.com/sully2490/defense-data-engineering) | Contract and procurement pipelines |
| Infrastructure | [data-infrastructure-labs](https://github.com/sully2490/data-infrastructure-labs) | Streaming, storage, CI/CD, and quality patterns |

---

## About

Built by an Army veteran who has seen what operational command centers look like — and what the data behind them should look like. This is the full-stack proof of concept.
