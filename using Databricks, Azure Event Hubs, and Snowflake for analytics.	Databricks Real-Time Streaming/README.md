
# Databricks Real-Time Streaming with Event Hubs and Snowflake

## Overview

In today's IoT-driven world, businesses rely on **real-time data processing** to respond instantly to changing conditions. This project demonstrates how to integrate **Azure Databricks**, **Event Hubs**, and **Snowflake** to build a real-time analytics pipeline for monitoring IoT devices.

By leveraging **cloud-native services**, you’ll stream, process, and store sensor data at scale while learning key concepts in distributed systems, stream processing, and modern data warehousing.

## Azure Project Template Outcomes

- Understanding Databricks advantages  
- Understanding Event Hubs advantages  
- Understanding Snowflake Architecture  
- Pros and Cons of Blob Storage  
- Create Resource Groups  
- Configure Compute Cluster in Databricks  
- Mount dataset in Blob using Scala in Databricks  
- Understanding Structured Streaming  
- Create Event Hub  
- Setup Snowflake Account  
- Stream data into Event Hub using Databricks  
- Consume data from Event Hub  
- Load data in Snowflake  

## Project Description

### Business Overview

Real-time analytics using **Azure Event Hubs**, **Databricks**, and **Snowflake** enables organizations to ingest, process, and analyze vast volumes of data as it arrives, providing near-instant insights and actionable intelligence.

These cloud-based services offer a powerful, scalable, and secure ecosystem for building modern streaming data platforms:

- **Azure Event Hubs** can process millions of events per second and integrate seamlessly with real-time analytics engines.  
- **Azure Databricks**, built on Apache Spark, excels at stream processing and offers collaborative development environments.  
- **Snowflake** provides scalable, pay-as-you-go cloud storage and powerful SQL-based analytics.  

Together, they create a robust pipeline for streaming data from sources such as IoT sensors, enabling immediate visibility into operational metrics, predictive insights, and alerting systems.

In this project, we’ll demonstrate a real-world scenario of **IoT device monitoring**, where data is streamed through **Event Hubs**, processed in **Databricks**, and stored and queried in **Snowflake**. This setup ensures low-latency processing and high scalability while maintaining flexibility in analysis and reporting.

## Dataset Description

This project uses a **Microsoft sample dataset** that simulates GPS readings from mobile phones. Each record captures a snapshot of device sensor data:

- `Index`: User ID  
- `Arrival_Time`: Time the GPS tracker received data  
- `Creation_Time`: Time the GPS tracker captured data  
- `x`, `y`, `z`: GPS coordinates  
- `User`: Dummy column  
- `Model`: Phone model  
- `Device`: Phone version  
- `gt`: IoT device location  
- `Id`: Reading ID  
- `Geolocation`: City, Country of the reading  

The dataset is mounted in **Databricks File System (DBFS)** from **Azure Blob Storage** using a Scala notebook.

## Tech Stack

- **Framework**: Apache Spark  
- **Languages**: Scala, Python  
- **Services**:  
  - Azure Databricks  
  - Azure Blob Storage  
  - Azure Event Hubs  
  - Snowflake  

## Azure Event Hubs

Azure Event Hubs is a high-throughput event ingestion service capable of handling millions of events per second. It’s ideal for real-time analytics scenarios such as telemetry ingestion, clickstream processing, and application logging.

## Databricks

Databricks is a cloud-native platform that brings together **data engineering**, **machine learning**, and **analytics** on top of Apache Spark. It provides collaborative notebooks, managed Spark clusters, and integration with a wide array of cloud services, making it ideal for scalable stream processing.

## Snowflake

Snowflake is a fully managed, cloud-native data platform for SQL analytics. With features like **virtual warehouses**, **Snowpipe**, **Streams**, and **Tasks**, it supports near-real-time data ingestion and transformation at scale.

**Key Snowflake Components:**

- **Warehouse** / Virtual Warehouse  
- **Database & Schema**  
- **Tables & Views**  
- **Stored Procedures**  
- **Streams & Tasks**  
- **Snowpipe** for real-time ingestion  

## Notes

- A Microsoft IoT GPS dataset is used and mounted via Databricks Scala notebook.  
- Event Hubs and Databricks allow for **low-latency streaming**, while Snowflake provides **powerful SQL analytics**.  
- Sample datasets used are available in Azure Databricks for hands-on practice.  
- Visualizations and dashboards can be built using Snowflake or external BI tools like **Power BI**.
