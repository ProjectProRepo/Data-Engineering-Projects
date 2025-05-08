# GCP Project – Build Data Pipeline using Dataflow and Apache Beam in Python  
In this GCP project, you will design and implement a real-time and batch data pipeline using **Apache Beam with the Dataflow runner**. You’ll use **Pub/Sub for event ingestion**, **Cloud Storage for input data**, and **BigQuery for downstream analytics**.

---

## Project Objectives  
- Understand the core concepts of Apache Beam’s unified programming model  
- Explore the features and benefits of Google Cloud Dataflow for data processing  
- Create and test a sample Beam pipeline using Python  
- Simulate real-time flight event data via Pub/Sub and ingest it into Dataflow  
- Configure and manage pipeline execution parameters  
- Perform clustering and table partitioning in BigQuery for optimization  
- Execute Dataflow jobs in both streaming and batch modes  
- Load transformed and cleaned data into BigQuery for analytics  

---

## Prerequisites  
- Intermediate knowledge of Python  
- Familiarity with Google Cloud services and the GCP Console  
- Basic experience with BigQuery and SQL  
- Google Cloud SDK (gcloud) installed and configured  
- Billing-enabled GCP project and appropriate IAM permissions  

---

## Tech Stack  
- **Language**: Python 3  
- **Services**:  
  - Google Cloud Storage  
  - Google Cloud Dataflow  
  - Apache Beam (Python SDK)  
  - Google BigQuery  
  - Google Cloud Pub/Sub  
  - GCloud CLI  

---

## Expected Outcomes  
- Build and deploy both batch and real-time pipelines using Apache Beam  
- Publish and consume JSON flight events using Pub/Sub topics and subscriptions  
- Transform raw data using Beam DoFns and apply filters, mappings, and type casting  
- Output structured data to partitioned BigQuery tables for downstream reporting  
- Cluster BigQuery tables to optimize query costs and performance  
- Visualize and query cleaned data directly using SQL on BigQuery  
- Handle streaming vs. batch workloads using the same Beam codebase  
- Monitor pipeline health, job metrics, and logs using the Dataflow UI  

---

## Key Features  
- Unified streaming and batch pipelines with Apache Beam  
- GCP-native pipeline orchestration using Dataflow  
- Pub/Sub for real-time ingestion simulation  
- Use of schema-aware `BigQueryIO` sink in Beam for structured data insertion  
- Parameterized pipelines to control runtime behavior  
- End-to-end monitoring with Dataflow metrics and Cloud Logging  
- Efficient BigQuery table management with clustering and partitioning  

---

## Important Notes  
- Be cautious with long-running streaming pipelines—they may incur higher GCP charges  
- Ensure Pub/Sub topics and subscriptions have proper retention periods configured  
- Use a regional location when deploying Dataflow jobs for performance optimization  
- Validate the Beam pipeline locally before deploying it to Dataflow  
- BigQuery charges per query and per data scanned—partition wisely  

---

## Dataset Overview  
You will use a dataset containing **flight event information**, where each record is in JSON format and includes:  
- `flight_id` – Unique identifier for a flight  
- `event_type` – Type of event (scheduled, departed, delayed, etc.)  
- `event_timestamp` – Event occurrence time  
- `airline`, `origin`, `destination`, `status` – Additional flight details  

The dataset is published to Pub/Sub and/or stored in Cloud Storage for different pipeline modes.

---

## Project Link  
[GCP Project: Build a Streaming and Batch Data Pipeline using Dataflow and Apache Beam in Python](https://www.projectpro.io/project-use-case/gcp-dataflow-apache-beam-python)

---

## Next Steps  
- Integrate Cloud Functions for real-time alerts based on events  
- Add schema validation using Apache Avro or JSON schemas  
- Automate deployment using Terraform or Cloud Deployment Manager  
- Incorporate machine learning models into the pipeline using Vertex AI  
- Schedule periodic batch pipelines with Cloud Composer (Airflow)
