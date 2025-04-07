# Databricks Real-Time Streaming with Event Hubs and Snowflake

## Overview

In today’s hyper-connected world, the ability to process and analyze data in real-time is critical for making timely decisions. This project teaches you how to leverage **Azure Databricks**, **Event Hubs**, and **Snowflake** to build a **real-time streaming pipeline** for monitoring **IoT devices**.

You’ll stream data through **Azure Event Hubs**, process it using **structured streaming in Databricks**, and load it into **Snowflake** for further analysis and visualization. This project demonstrates a highly scalable, cloud-native solution ideal for handling large volumes of IoT data.

## Project Objectives

* Understand the advantages of **Azure Databricks** for scalable analytics.
* Learn the core features of **Azure Event Hubs** and how to set up a streaming ingestion pipeline.
* Explore the **Snowflake architecture** and how to load streaming data into it.
* Mount and process data using **Azure Blob Storage**.
* Use **Structured Streaming** with Databricks to process event data.
* Ingest and analyze real-time data from IoT devices.
* Query processed data in **Snowflake** for business intelligence and reporting.

## Prerequisites

Before starting this project, you should have:

* A basic understanding of **Apache Spark** and **streaming concepts**.
* Familiarity with **Azure services** like Databricks, Event Hubs, and Blob Storage.
* Working knowledge of **Python** or **Scala**.
* Access to an **Azure subscription** with permissions to create resources.
* A **Snowflake account** for storing and querying analytics data.

## Tech Stack

* **Languages**: Python, Scala
* **Framework**: Apache Spark (Structured Streaming)
* **Cloud Services**:  
  * Azure Event Hubs  
  * Azure Databricks  
  * Azure Blob Storage  
  * Snowflake

## Expected Outcomes

By completing this project, you will:

* Build a real-time streaming data pipeline using **Azure-native tools**.
* Process IoT device data using **structured streaming in Databricks**.
* Learn how to stream data from **Event Hubs** and persist it to **Snowflake**.
* Explore time-series insights and anomaly detection use cases.
* Design and deploy scalable pipelines for **real-time analytics**.

## Dataset

This project uses a **Microsoft Sample Dataset** simulating IoT device readings with the following fields:

* `Index`: User ID
* `Arrival_Time`: Time when GPS data arrived
* `Creation_Time`: Time the GPS reading was captured
* `x`, `y`, `z`: GPS coordinates
* `User`: Dummy user info
* `Model`: Phone model used
* `Device`: Phone version
* `gt`: Device location type
* `Id`: Reading ID
* `Geolocation`: City and country of reading

The dataset is mounted into **Databricks File System (dbfs)** from Azure Blob Storage and used as input for the streaming pipeline.

## Key Features of the Pipeline

* **Event Ingestion with Event Hubs**: Real-time ingestion of millions of messages per second.
* **Structured Streaming in Databricks**: Easy-to-write, scalable stream processing code.
* **Snowflake for Storage and Analysis**: Cloud-native warehousing and querying of data.
* **Blob Storage Mounting**: Seamless integration of source datasets for pipeline input.
* **Secure and Scalable Architecture**: End-to-end security with scalable cloud resources.

## Important Notes

* **Real-Time Performance**: Be mindful of Event Hub partition counts and throughput units.
* **Security**: Ensure secure credential handling between Databricks and Snowflake.
* **Costs**: Monitor Databricks cluster costs and Event Hubs throughput usage.
* **Azure Permissions**: Verify your Azure account has access to create and configure Event Hubs, Databricks, and Blob storage.
* **Snowflake Setup**: A Snowflake warehouse and schema must be created before loading data.

## Project Link

[Databricks Real-Time Streaming with Event Hubs and Snowflake](https://www.projectpro.io/project-use-case/databricks-real-time-streaming)

## Next Steps

* Add anomaly detection using **ML models in Databricks**.
* Visualize data trends using **Power BI** or **Snowflake dashboards**.
* Extend the pipeline to support **multiple IoT device types**.
* Integrate **alerts and notifications** using Azure Logic Apps or Functions.
