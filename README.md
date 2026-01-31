# GCP Dataproc Serverless Data Pipelines

This project demonstrates how to build **serverless data pipelines** on Google Cloud using **Dataproc Serverless Templates**, enabling scalable data processing without managing Spark clusters.

## Project Overview

The goal of this project is to showcase how Dataproc Serverless can be used to:
- Process large datasets using Apache Spark
- Move data between BigQuery and Cloud Storage
- Run batch analytics jobs without cluster provisioning
- Reduce operational overhead and cost

This project focuses on **architecture design and pipeline patterns**, not on running production workloads.

## Architecture

The pipeline follows a serverless batch-processing model:

1. Data is sourced from **BigQuery** or **Cloud Storage**
2. **Dataproc Serverless** runs Spark jobs using predefined templates
3. Transformed data is written back to **BigQuery** or **Cloud Storage**
4. No persistent clusters are created or managed

![Architecture Diagram](architecture.png)

## Example Pipelines

- BigQuery → Cloud Storage (export & transform)
- Cloud Storage → BigQuery (ingestion & enrichment)
- Batch ETL using Spark SQL

## Why Dataproc Serverless?

- No cluster management
- Auto-scaling Spark execution
- Pay only for job runtime
- Native integration with BigQuery and GCS

## Skills Demonstrated

- GCP Dataproc Serverless
- Apache Spark (serverless execution)
- Cloud data pipeline design
- Batch ETL architecture
- Cost-efficient cloud analytics

## Notes

This repository is intended for **learning, architecture demonstration, and portfolio showcase** purposes.
