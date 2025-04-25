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


## Dataset Overview

We use the publicly available **Yelp dataset**, which contains business, user, and review information in JSON format.


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
