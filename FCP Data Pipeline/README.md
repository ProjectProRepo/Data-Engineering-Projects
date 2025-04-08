# Build a Scalable Event-Based GCP Data Pipeline Using DataFlow

## Overview

In a modern data-driven organization, teams often need access to large volumes of data in real-time to make informed decisions. Event-Driven Architecture (EDA) provides the scalability and flexibility required for these high-throughput environments. In this project, you will learn to build and deploy a **fully-managed, serverless, event-driven data pipeline on Google Cloud Platform (GCP)**.

You’ll use GCP services such as **Pub/Sub**, **Cloud Functions**, **Cloud Composer (Airflow)**, **BigQuery**, **BigTable**, and **Dataflow with Apache Beam** to ingest, process, orchestrate, and analyze real-time COVID-19 data efficiently.

## Project Objectives

- Understand the **problem statement** and **event-driven architecture (EDA)**.  
- Explore the **COVID-19 dataset** and its structure.  
- Set up and configure the **Cloud SDK** and **project dependencies**.  
- Create and publish messages to **Pub/Sub topics**.  
- Use **Cloud Functions** to ingest and transform data.  
- Set up **Cloud Composer** and configure Airflow DAGs.  
- Establish **SSH and SFTP connections** to pull data from VM to GCS.  
- Implement **Apache Beam pipelines** using **Dataflow runner**.  
- Analyze data using **BigQuery** and **BigTable**.  
- Visualize metrics and trends using **Cloud Studio Dashboards**.  

## Prerequisites

Before you begin, make sure you have:

- A **Google Cloud Platform (GCP)** account with billing enabled.  
- Basic understanding of **Python** and **SQL**.  
- Familiarity with **GCP services** like Pub/Sub, Cloud Functions, BigQuery, and BigTable.  
- Installed and configured the **Google Cloud SDK**.  
- Prior exposure to **workflow orchestration** tools like Apache Airflow (optional).  

## Tech Stack

- **Language**: Python 3.7  
- **Framework**: Apache Beam (Dataflow Runner)  
- **Data Source**: COVID-19 Cases.csv from data.world  
- **Services**:  
  - Google Cloud Storage (GCS)  
  - Pub/Sub  
  - Cloud Functions  
  - Cloud Composer  
  - BigQuery  
  - BigTable  
  - Dataflow  

## Expected Outcomes

By completing this project, you will:

- Build a fully serverless, scalable, event-driven data pipeline on GCP.  
- Gain hands-on experience with **Pub/Sub**, **Cloud Functions**, and **Cloud Composer**.  
- Learn how to process streaming data using **Dataflow and Apache Beam**.  
- Store, analyze, and query processed data in **BigQuery and BigTable**.  
- Visualize pipeline metrics and dashboards using **Cloud Studio**.  

## Key Features of the Pipeline

- **Event-Based Ingestion**: Real-time data collection using Pub/Sub  
- **Serverless Transformation**: Trigger-based processing with Cloud Functions  
- **Orchestration**: Workflow automation using Cloud Composer and Airflow  
- **Streaming Analytics**: Large-scale processing with Dataflow (Apache Beam)  
- **Hybrid Storage**: Structured and semi-structured data stored in BigQuery and BigTable  
- **Monitoring and Visualization**: Dashboarding and logs through Cloud Studio  

## Important Notes

- **API Rate Limits**: Ensure data ingestion respects API and quota limits.  
- **IAM and Security**: Apply least-privilege principles when setting up permissions.  
- **Cost Optimization**: Monitor resource usage and set up billing alerts.  
- **Dataflow Templates**: Consider using templates for reusable job definitions.  

## Dataset Description

The dataset used in this project is a COVID-19 dataset with fields such as:

- `people_positive_cases_count`  
- `county_name`  
- `case_type`  
- `data_source`  

The dataset is stored in CSV format and will be streamed and processed through the pipeline.

## Project Link

[Build a Scalable Event-Based GCP Data Pipeline Using DataFlow](https://www.projectpro.io/project-use-case/build-production-ready-data-pipeline-using-dataflow)

## Next Steps

- Add **support for multi-region ingestion** and data replication.  
- Integrate **ML models** for predictive analytics or anomaly detection.  
- Implement **data validation** using tools like Cloud Data Loss Prevention (DLP).  
- Automate deployment using **Terraform** or **Deployment Manager**.  
