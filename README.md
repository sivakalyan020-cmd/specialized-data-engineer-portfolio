<!--
This README introduces a specialized data-engineering portfolio aligned to the job posting for a Data Engineer role. It summarizes relevant experience, highlights core competencies and projects that demonstrate the ability to design, build and scale modern data solutions. The portfolio emphasizes real-world projects, technical skills, tooling and business impact.
-->

# Data Engineer Portfolio – Siva Kalyan Kotipalli

## Summary

I am a data engineer with over eight years of experience designing, building and maintaining modern data platforms. My work focuses on creating scalable data pipelines, reliable data models and user-friendly analytics layers that power business decision-making. This portfolio is tailored to the requirements of a cross-functional Data Engineer role, showcasing real-world projects where I implemented ETL/ELT pipelines, optimized cloud warehouses, ensured data quality and collaborated closely with stakeholders to deliver incremental value. Each project highlights the challenge, solution and impact to demonstrate not just the **what**, but also the **why** and **how**.

## Core Competencies

| Area | Description |
|---|---|
| **Data Pipeline Engineering** | Built scalable data pipelines across multiple systems using Airflow, dbt and Python. Ingested data via APIs, CDC and streaming, orchestrated transformations and delivered trusted data for analytics. |
| **Data Modeling & Warehousing** | Designed star and snowflake schemas and optimized cloud data warehouses (Snowflake, BigQuery). Tuned clustering, partitioning and materialized views for high-performance analytics. |
| **Stakeholder Collaboration** | Partnered with analytics, product and business stakeholders to translate data needs into technical solutions and deliver incremental value. |
| **Data Quality & Governance** | Implemented validation, monitoring and data lineage processes using tools like Great Expectations and Monte Carlo, ensuring reliability and trust in the data. |
| **CI/CD & Infrastructure as Code** | Automated deployments and environment management with Git, Terraform and CI/CD pipelines; implemented Infrastructure as Code to provision data platform resources. |
| **Operations & Support** | Supported data platform operations, participated in on-call rotations and ensured SLAs. Troubleshot issues and continuously improved pipeline reliability. |
| **Tools & Technologies** | SQL, Python, dbt, Airflow, Snowflake, BigQuery, Redshift, Terraform, Git, Monte Carlo, Tableau, Looker, Apache Kafka, Datadog, Great Expectations. |

## Selected Projects

### Modern Data Platform for Multi-Source Pipelines

- **Problem**: Data scattered across SaaS apps and internal systems hindered analytics and decision-making.
- **Solution**: Architected an end-to-end data platform that ingests data via APIs, change-data-capture and streaming sources into Snowflake. Orchestrated ELT pipelines using Airflow and modular transformations with dbt; enforced data quality rules with Great Expectations. Deployed using Terraform and CI/CD pipelines.
- **Impact**: Reduced data latency from hours to minutes, delivered a unified semantic layer for analytics and improved data reliability by 95%.

### Scalable Cloud Data Warehouse & Modeling

- **Problem**: Analysts struggled with poor performance and inconsistent reporting due to ad-hoc tables and unclear models.
- **Solution**: Designed and implemented a star-schema data model in Snowflake/BigQuery. Tuned clustering and partitioning, implemented materialized views and added metadata documentation in a data catalog. Provided clear business definitions and built dashboards in Tableau/Looker.
- **Impact**: Queries ran 60% faster and reporting accuracy improved; analysts adopted the new semantic layer for self-service reporting.

### Data Quality & Monitoring Framework

- **Problem**: Lack of visibility into pipeline health caused delays and trust issues.
- **Solution**: Implemented automated data quality checks (null rates, uniqueness, schema drift) and integrated monitoring using Monte Carlo/Datadog. Added alerting to Slack/Email and created dashboards tracking pipeline SLAs and data freshness.
- **Impact**: Detected anomalies early, reduced incident resolution time by 50% and increased stakeholder confidence in the data.

### CI/CD & IaC for Data Platform

- **Problem**: Manual environment management led to configuration drift and slow deployments.
- **Solution**: Wrote Terraform modules to provision Snowflake warehouses, roles and databases. Created CI/CD pipelines (GitHub Actions/Tekton) to run dbt tests, deploy data models and manage environment promotion. Introduced pre-merge code reviews and automated linting.
- **Impact**: Decreased deployment time from days to hours, standardized environments across development and production and increased team velocity.

## Contact

Email: *ksivakalyan2@gmail.com**  
LinkedIn: **[siva-kalyan-dataengineer](https://www.linkedin.com/in/siva-kalyan-dataengineer/)**
