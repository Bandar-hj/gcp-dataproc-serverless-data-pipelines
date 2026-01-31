# GCP Dataproc Serverless Data Pipelines

This project demonstrates how to build **serverless data pipelines** on Google Cloud using **Dataproc Serverless Templates**, enabling scalable data processing without managing Spark clusters.

---

## Project Overview

The goal of this project is to showcase how Dataproc Serverless can be used to:

- Process large datasets using Apache Spark
- Move data between BigQuery and Cloud Storage
- Run batch analytics jobs without cluster provisioning
- Reduce operational overhead and operational cost

This project focuses on **architecture design and pipeline patterns**, not on running production workloads.

---

## Architecture

The pipeline follows a **serverless batch-processing model**:

1. Data is sourced from **BigQuery** or **Cloud Storage**
2. **Dataproc Serverless** runs Spark jobs using predefined templates
3. Transformed data is written back to **BigQuery** or **Cloud Storage**
4. No persistent Spark clusters are created or managed

![Dataproc Templates Architecture](https://github.com/GoogleCloudPlatform/dataproc-templates/blob/main/dp-templates.png)

---

## Example Pipelines

- BigQuery → Cloud Storage (export & transform)
- Cloud Storage → BigQuery (ingestion & enrichment)
- Batch ETL using Spark SQL

---

## Why Dataproc Serverless?

- No cluster management required
- Automatic Spark scaling based on workload
- Pay only for job execution time
- Native integration with BigQuery and Cloud Storage
- Simplified Spark-based data processing

---

## Technologies Used

- Google Cloud Dataproc Serverless
- Apache Spark
- BigQuery
- Google Cloud Storage (GCS)
- Dataproc Templates
- Serverless batch processing architecture

---

## Use Cases

- Large-scale batch data processing without infrastructure management
- Cost-optimized ETL pipelines for analytics workloads
- Data movement between BigQuery and Cloud Storage
- Scheduled or event-driven Spark batch jobs
- Reference architecture for serverless data platforms

---

## How This Project Adds Value

This project demonstrates how modern cloud-native data platforms can:

- Eliminate infrastructure provisioning and maintenance
- Scale automatically based on workload size
- Reduce costs by charging only for execution time
- Simplify Spark-based data engineering workflows
- Serve as a reference architecture for enterprise analytics teams

---

## Skills Demonstrated

- GCP Dataproc Serverless
- Apache Spark (serverless execution)
- Cloud data pipeline architecture
- Batch ETL design patterns
- Cost-efficient cloud analytics solutions

---

## Future Enhancements

- Add CI/CD pipelines for automated job deployment
- Integrate with Cloud Composer (Airflow) for orchestration
- Add monitoring and logging dashboards using Cloud Monitoring
- Extend pipelines to support streaming workloads

---

## Notes

This repository is intended for **learning, architecture demonstration, and portfolio showcase** purposes.
