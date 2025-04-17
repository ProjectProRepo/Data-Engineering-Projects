# GCP Project: Build an ETL Pipeline for Financial Data Analytics using GCP-IaC

## Overview

This GCP cloud infrastructure project focuses on creating an efficient **ETL (Extract, Transform, Load) pipeline** for financial data analytics using **Infrastructure as Code (IaC)**. You'll use **GCP Deployment Manager** to provision and manage cloud resources while automating the ETL flow from an **on-premise SQL Server** (hosted on AWS RDS) to **Google BigQuery** for analytics.

Automated deployable infrastructure brings consistency, scalability, and version control to cloud development. It reduces human error, improves collaboration, and simplifies disaster recovery. With **Deployment Manager**, you'll define templates to provision GCP services reproducibly, speeding up development and improving cost efficiency. This end-to-end project highlights the importance of modern IaC principles in cloud-native financial data engineering.

## Project Objectives

- Understand the project architecture and IaC design principles.  
- Set up a **SQL Server instance on AWS RDS** to simulate on-premise data.  
- Import and structure the **financial equity dataset** in the SQL Server.  
- Learn the fundamentals of **GCP Deployment Manager** for IaC.  
- Deploy GCP infrastructure including **Cloud Storage**, **VM**, and **BigQuery**.  
- Install and configure **Apache NiFi** on a **Compute Engine VM**.  
- Extract data from the SQL Server and load into **GCP Cloud Storage**.  
- Deploy **Cloud Functions** to monitor storage and trigger workflows.  
- Launch **Dataproc clusters** using workflow templates to run **Spark jobs**.  
- Transform raw financial data using **PySpark**.  
- Load clean data into **BigQuery** for analytics and reporting.  
- Perform exploratory and aggregate stock data analysis in **BigQuery SQL**.  
- Use **Cloud Shell** to destroy resources post-project for cost management.

## Prerequisites

Before starting this project, ensure you have:

- An **active GCP account** with billing enabled.  
- **Basic understanding of SQL, Spark, and Python**.  
- Familiarity with **cloud storage, virtual machines**, and **ETL concepts**.  
- Prior exposure to **Apache NiFi** and **Infrastructure as Code (IaC)** is helpful.  
- Access to **AWS account** to launch SQL Server on **AWS RDS**.  
- Installed tools: **gcloud CLI**, **Cloud Shell**, and optionally **Terraform/NiFi toolkit**.  

## Tech Stack

- **Languages**: Python, SQL  
- **Cloud Services**:  
  - AWS RDS (SQL Server)  
  - GCP Compute Engine  
  - GCP Cloud Storage  
  - GCP Cloud Functions  
  - GCP Dataproc  
  - GCP BigQuery  
  - GCP Deployment Manager  
- **Tools**: Apache NiFi, PySpark, Cloud Shell, Google Cloud Console  

## Expected Outcomes

By completing this project, you will:

- Build a complete **IaC-based ETL pipeline** for financial data.  
- Understand **Deployment Manager** templates and automated provisioning.  
- Set up **NiFi flows** for data ingestion from external sources.  
- Use **Cloud Functions and Dataproc** for serverless transformation.  
- Apply **PySpark transformations** to clean and standardize equity data.  
- Load transformed datasets into **BigQuery** and run analytical queries.  
- Gain confidence in **cross-cloud orchestration** between AWS and GCP.  
- Prepare for real-world roles in **data engineering, cloud analytics, and DevOps**.

## Key Features of the Project

- **Infrastructure as Code (IaC)**: Automate GCP deployments using YAML templates with Deployment Manager.  
- **Cross-Cloud Setup**: Simulate on-premise SQL Server using AWS RDS and connect it to GCP workflows.  
- **Apache NiFi on GCE**: Build NiFi flows to extract SQL data and load into GCS.  
- **Event-Driven Processing**: Trigger Spark jobs automatically using Cloud Functions on GCS bucket events.  
- **Dataproc Automation**: Use PySpark for batch transformation on dynamically created clusters.  
- **BigQuery Analytics**: Load clean financial data into BigQuery and run SQL analytics for reporting.  
- **Cloud Shell Cleanup**: Terminate all resources post-run to minimize costs using gcloud commands.  
- **End-to-End ETL Flow**: Streamline extraction, transformation, and loading using fully managed GCP services.

## Important Notes

- **Deployment Manager Templates**: Use declarative YAML templates for reproducible GCP provisioning.  
- **NiFi Setup**: Secure your VM and configure NiFi with persistent storage and SSL if used in production.  
- **IAM Permissions**: Ensure correct IAM roles for Compute Engine, Cloud Functions, and Dataproc access.  
- **Cloud Function Triggers**: Define triggers based on GCS file creation or modification events.  
- **Cost Management**: Always destroy resources after use to avoid unexpected GCP billing.  
- **PySpark Workflow**: Parameterize PySpark scripts to handle various stock data transformations.  
- **Data Security**: Mask sensitive financial attributes during transformation if required.  

## Dataset Overview

This project uses **equity financial data** sourced from **BSE India**, which includes historical stock performance and trading information. Sample fields include:

- `open_price`  
- `high_price`  
- `low_price`  
- `close_price`  
- `no_of_shares`  
- `no_of_trades`  
- `total_turnover`  

The dataset simulates typical stock trading data and is used to build transformation logic and perform stock analytics in BigQuery.

## Project Link

[GCP Project: Build an ETL Pipeline for Financial Data Analytics using GCP-IaC](https://www.projectpro.io/project-use-case/gcp-iac-project-to-build-etl-pipeline-for-financial-data-analytics)

## Next Steps

- Add **Data Loss Prevention (DLP)** features to redact sensitive information before analytics.  
- Extend transformation to detect **anomalies or volatility patterns** in stock price movement.  
- Use **BigQuery ML** to build predictive models on top of transformed financial data.  
- Replace AWS RDS with **on-premise connectors** like VPN or Cloud Interconnect for hybrid use cases.  
- Integrate **Looker or Data Studio** for dashboarding and executive reporting.  
- Implement **audit logging and monitoring** using GCP’s Operations Suite (formerly Stackdriver).  
