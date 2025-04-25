# GCP Project: GCP Data Ingestion with SQL using Google Cloud Dataflow

## Overview

In this GCP project, you'll build a real-time and batch-based **data processing pipeline** using **Apache Beam**, **Google Cloud Dataflow**, and **BigQuery** on **Google Cloud Platform (GCP)**. The pipeline ingests and transforms data from the **Yelp dataset**, delivered in both stream and batch formats via **Google Pub/Sub** and **Google Cloud Storage**, respectively.

This end-to-end project helps you master GCP-native tools like **Cloud Composer**, **Pub/Sub**, and **Dataflow** for orchestrating robust data pipelines. You'll also gain hands-on experience with **Google BigQuery** for analytics and **Google Data Studio** for visualization.

## Project Objectives

- Understand the overall project architecture and data flow.  
- Learn how to use **Google Cloud Storage (GCS)** to stage batch data.  
- Visualize a complete ingestion-to-visualization architecture.  
- Set up and use the **Google Cloud SDK**.  
- Connect SDK to a service account for secure API access.  
- Explore and parse the **Yelp dataset** in JSON file and stream formats.  
- Create and configure **Cloud Storage buckets**.  
- Understand and implement **Google Pub/Sub** for streaming ingestion.  
- Learn **Apache Beam** and write streaming and batch pipelines.  
- Deploy and monitor **streaming Dataflow jobs**.  
- Deploy and monitor **batch Dataflow jobs**.  
- Use **Cloud Composer (Apache Airflow)** to orchestrate batch workflows.  
- Create and configure a **Cloud Composer environment**.  
- Track DAG runs and configurations in **Airflow UI**.  
- Integrate **Pub/Sub and Cloud Composer** with Apache Beam.  
- Load processed data into **Google BigQuery**.  
- Perform SQL analytics and visualize with **Google Data Studio**.

## Prerequisites

Before beginning this project, you should have:

- A **Google Cloud Platform (GCP)** account with billing enabled.  
- Basic knowledge of **Python** and **SQL**.  
- Familiarity with cloud concepts like **buckets, jobs, and IAM**.  
- Installed **Google Cloud SDK (gcloud CLI)**.  
- Enabled APIs for **Pub/Sub**, **Dataflow**, **Composer**, and **BigQuery**.

## Tech Stack

- **Languages**: Python, SQL  
- **GCP Services**:  
  - Google Cloud Storage (GCS)  
  - Google Cloud Pub/Sub  
  - Google Cloud Dataflow  
  - Google BigQuery  
  - Google Cloud Composer  
  - Google Data Studio  
- **Libraries**: Apache Beam, Google Cloud SDK

## Expected Outcomes

By completing this project, you will:

- Create a working real-time and batch-based **ETL pipeline** on GCP.  
- Learn to work with **streaming ingestion via Pub/Sub**.  
- Use **Cloud Composer** to schedule and orchestrate workflows.  
- Transform and load data using **Apache Beam and Dataflow**.  
- Query structured data in **BigQuery**.  
- Create live dashboards using **Data Studio**.

## Key Features of the Project

- **Hybrid Ingestion**: Support for both real-time (stream) and batch processing pipelines.  
- **Cloud-Native Stack**: Uses fully managed GCP services for scalability and ease of maintenance.  
- **Apache Beam Flexibility**: Unified model for stream and batch job creation.  
- **Airflow Orchestration**: Automate DAGs with Google Cloud Composer.  
- **Data Visualization**: Build dashboards with real-time insights in Google Data Studio.  
- **Scalable and Modular**: Easily extendable for larger datasets or new ingestion sources.

## Project Description

### What is Data Ingestion?

**Data Ingestion** is the process of collecting and transporting data from multiple sources into a destination where it can be analyzed and stored—such as a **data warehouse**, **data mart**, or **cloud storage**. Sources may include **RDBMS**, **CSV files**, **APIs**, or **streaming services** like Pub/Sub.

### What is a Data Pipeline?

A **data pipeline** is an end-to-end system that captures, processes, and delivers data from source to destination. It typically includes stages such as extraction, validation, transformation, and loading (ETL), with orchestration and monitoring built-in.

### Agenda of the Project

- Build a hybrid **data ingestion and processing pipeline** on GCP.  
- Use the **Yelp dataset (JSON format)** for real-time and batch input.  
- Set up a **GCP service account** and install the **Google Cloud SDK**.  
- Configure **Python** and required libraries locally.  
- Stream Yelp JSON data to **Google Pub/Sub**.  
- Orchestrate batch ingestion using **Cloud Composer (Airflow)**.  
- Process data with **Apache Beam**, deployed via **Dataflow**.  
- Load transformed data into **Google BigQuery**.  
- Visualize the final dataset in **Google Data Studio**.

## Dataset Overview

We use the publicly available **Yelp dataset**, which contains business, user, and review information in JSON format.

### Usage of the Dataset Includes:

- **Batch Pipeline**:  
  - Push Yelp JSON files to **Google Cloud Storage (GCS)**.  
  - Use **Cloud Composer** to schedule Apache Beam batch processing jobs.  

- **Streaming Pipeline**:  
  - Stream Yelp data in real-time to a **Pub/Sub topic**.  
  - Use **Apache Beam streaming jobs** deployed on **Dataflow** to process messages.  

## Data Analysis Flow

1. Download the **Yelp dataset** in JSON format.  
2. Upload batch data to **GCS** using the SDK or GCSFuse.  
3. Stream JSON lines to a **Pub/Sub topic** for real-time processing.  
4. Write **Apache Beam pipelines** for both stream and batch processing.  
5. Deploy these pipelines to **Dataflow** and monitor execution.  
6. Write transformed output to **BigQuery** tables.  
7. Visualize results using **Google Data Studio** or **Looker**.

## Important Notes

- **IAM Configuration**: Ensure all required roles are granted for accessing Dataflow, Pub/Sub, Composer, and BigQuery.  
- **Code Versioning**: Use Git to manage your Beam pipeline code and DAGs.  
- **Resource Management**: Stop streaming jobs and delete Composer environments after use to avoid charges.  
- **Modular Pipeline**: Apache Beam allows code reuse between batch and streaming jobs.  
- **Airflow DAG Monitoring**: Monitor DAG run statuses, logs, and retry attempts using the Composer Airflow UI.

## Project Link

[GCP Project: GCP Data Ingestion with SQL using Google Cloud Dataflow](dataflow)

## Next Steps

- Add **BigQuery partitioning and clustering** to improve performance.  
- Explore **Dataflow templates** to deploy reusable Beam pipelines.  
- Integrate **Cloud Functions** to trigger Dataflow jobs on GCS file events.  
- Experiment with **BigQuery ML** to analyze trends and build predictions.  
- Extend the pipeline to include ingestion from **external APIs** or **Kafka**.  
- Implement **logging and monitoring** using GCP’s Operations Suite.
