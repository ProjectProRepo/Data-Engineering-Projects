# Real-time Data Pipeline with Azure Data Factory and Logic Apps

In this Azure Data Engineering project, you will build a **real-time ingestion and transformation pipeline** using **Azure Data Factory (ADF)**, **Azure Logic Apps**, and **Azure Databricks**, processing newly added records from an Azure SQL Database. The system is designed to automatically detect and process incremental updates, enabling **cost-effective, real-time analytics** with seamless Power BI integration.

---

## Project Objectives

- Implement auto-increment logic in Azure SQL Database
- Understand the role of Logic Apps in event-driven data orchestration
- Develop a Logic Apps workflow using a low-code designer interface
- Create and optimize **Azure Data Factory copy pipelines**
- Trigger pipelines based on Azure Blob Storage events
- Develop a **Notebook Activity Pipeline** in ADF to run Databricks notebooks
- Implement **Medallion Architecture** (Bronze → Silver → Gold) in Azure Databricks
- Automate end-to-end real-time processing from SQL to Power BI
- Load real-time data into Power BI dashboards via Databricks integration

---

## Prerequisites

- Basic understanding of Azure services like ADF, Logic Apps, Databricks, and SQL DB  
- Azure subscription with permissions to create and manage resources  
- Familiarity with SQL and basic ETL/ELT concepts  

---

## Tech Stack

- **Programming**: SQL, Scala  
- **Services**:  
  - Azure SQL Database  
  - Azure Logic Apps  
  - Azure Blob Storage  
  - Azure Data Lake Storage Gen2  
  - Azure Data Factory  
  - Azure Databricks  
  - Power BI  

---

## Expected Outcomes

- Build a fully automated **real-time ingestion pipeline** using Azure services  
- Filter and ingest **only newly added records** based on auto-increment logic  
- Use Logic Apps to trigger data extraction workflows  
- Create and manage ADF pipelines with **event-based triggers**  
- Develop and orchestrate medallion-tiered notebooks (Bronze, Silver, Gold) in Databricks  
- Automatically update Power BI reports with only fresh data during each run  

---

## Key Features

- **Real-time Data Extraction**: Pipeline captures and processes only new data based on auto-increment logic from Azure SQL Database  
- **Automation**: Entire workflow—from ingestion to transformation to visualization—is fully automated using triggers and scheduled Logic Apps  
- **Cost Efficiency**: Avoids redundant processing of old records and minimizes storage/computation costs  
- **Medallion Architecture**: Follows industry best practices by transforming raw data through progressive stages (Bronze → Silver → Gold)  
- **Power BI Integration**: Final curated data is loaded into Power BI in real-time for instant visualization  

---

## Project Description

### Business Overview

Real-time data processing is essential for organizations aiming to respond quickly to environmental or operational signals. In this project, we focus on processing **live water quality sensor data** from multiple European countries. The system ensures that **only new records** are processed, helping avoid duplication, reduce cloud costs, and improve processing efficiency.

This project is the **third installment** in our Azure project series. While the first project focused on medallion architecture pipelines and the second on CI/CD with Azure DevOps, this project brings everything together in a **real-time pipeline** designed for **high-volume, incremental data processing** without manual intervention.

---

## Dataset Overview

The dataset includes over 1 million rows of **water quality sensor data** collected across Europe. Key attributes include:

- Country & Monitoring Site  
- Water body category  
- Determinands (measured parameters)  
- Minimum, Maximum, Average concentrations  
- Number of valid samples per reading  
- Timestamp for each observation  

This project uses only **newly ingested rows** (based on timestamp or ID) from Azure SQL Database for real-time processing.

---

## Series Overview

- **Part 1**: Build Data Pipeline using Azure Medallion Architecture  
- **Part 2**: DevOps Project to Build and Deploy Azure CI/CD Pipelines  
- **Part 3 (This Project)**: Real-time Ingestion using ADF + Logic Apps  

---

## Notes

- If you encounter `"Microsoft.ACE.OLEDB.12.0" provider is not registered` error, install the compatible **SQL Server Engine** locally  
- To avoid unexpected Azure charges, configure resources in **local regions** and regularly delete unused services  
- A detailed **text-based CookBook** is provided as an alternative to video instructions  

---

## Project Link

[Real-time Azure ADF + Logic Apps Pipeline for Water Sensor Data](https://www.projectpro.io/project-use-case/azure-data-factory-pipeline-example-with-logicapps)

---

## Next Steps

- Extend the pipeline to integrate anomaly detection models in Databricks  
- Add alerting via Azure Monitor or Logic Apps when certain thresholds are crossed  
- Scale the solution to handle multiple datasets concurrently  
