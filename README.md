# Gabriel's Data Engineering Portfolio

Building reliable, scalable data pipelines using modern tools and best practices.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apache-airflow&logoColor=white)](https://airflow.apache.org/)
[![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white)](https://www.getdbt.com/)
[![Spark](https://img.shields.io/badge/Spark-E25A1C?logo=apache-spark&logoColor=white)](https://spark.apache.org/)
[![Azure](https://img.shields.io/badge/Azure-0089D6?logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?logo=google-cloud&logoColor=white)](https://cloud.google.com/)
[![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)](https://www.databricks.com/)

## Overview

This repository showcases my hands-on data engineering work, starting from ingestion and orchestration up to production-grade batch and streaming pipelines. 
Projects are inspired by structured learning (e.g., Data Engineering Zoomcamp) but extended with my own experiments, production considerations, and optimizations.

Key themes:
- Containerized workflows (Docker & Compose)
- Data ingestion & transformation
- Workflow orchestration & scheduling
- Analytics engineering & modeling
- Data warehousing & ELT
- Batch & stream processing
- Testing, monitoring, & observability

## Portfolio Structure

Here's how the repo is organized for clarity and scalability:
```
gabriel-data-engineering-portfolio/
├── README.md                     # ← This file: portfolio landing page
├── LICENSE                       # MIT
├── .gitignore                    # Python + data + env
├── .github/                      # (future: CI/CD workflows)
│   └── workflows/
├── docs/                         # Diagrams, architecture overviews, Medium assets
│   ├── architecture-overview.png
│   ├── data-flow-diagrams/
│   └── medium-assets/            # Screenshots for articles
├── utils/                        # Reusable helpers (scripts, monitoring)
│   ├── scripts/
│   └── monitoring/
├── modules/                      # Core work from Zoomcamp modules
│   ├── 01-containerization-infra/     # Docker, Terraform, Postgres, ingestion
│   │   ├── docker/
│   │   ├── terraform/
│   │   ├── ingestion/
│   │   ├── sql/
│   │   ├── notebooks/
│   │   ├── homework/
│   │   └── README.md
│   ├── 02-workflow-orchestration/     # Airflow DAGs, etc.
│   │   ├── dags/
│   │   ├── plugins/
│   │   ├── docker/
│   │   ├── homework/
│   │   └── README.md
│   ├── 03-data-warehouse/
│   ├── 04-analytics-engineering/      # dbt project
│   ├── 05-batch-processing/           # Spark jobs
│   └── 06-streaming/                  # Kafka, streaming
├── final-project/                    # Capstone end-to-end pipeline
│   ├── pipeline/
│   ├── data/                         # (gitignore large files)
│   ├── docs/
│   ├── README.md
│   └── presentation/
├── cloud-migrations/                 # Future: ports to cloud platforms
│   ├── azure/
│   ├── gcp/
│   ├── aws/
│   └── databricks/
└── personal-projects/                # Extra non-Zoomcamp work later
├── project-name-1/
└── project-name-2/

```

Each module folder contains its own README.md explaining:
- What was built
- Key decisions & trade-offs
- Challenges faced & solutions
- Production hardening ideas
- Link to the related Medium article (once published)
