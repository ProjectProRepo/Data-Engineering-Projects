# Analyse Yelp Dataset with Spark & Parquet Format on Azure Databricks

In this Azure Databricks project, you'll analyze the Yelp reviews dataset using Spark and Parquet file formats. You’ll deploy Azure Data Factory and create scalable pipelines to orchestrate data movement, followed by PySpark transformations and data exploration inside Azure Databricks.

---

## Project Objectives

- Understand the Yelp dataset and define analysis goals
- Learn how Azure services integrate in a modern data pipeline
- Visualize the end-to-end pipeline architecture
- Create and manage Azure Data Lake Storage (ADLS) containers
- Use Azure Data Factory to orchestrate data movement
- Provision and configure Azure Databricks workspace and clusters
- Understand the advantages of file formats like JSON and Parquet
- Learn partitioning, coalesce, and data optimization techniques
- Perform PySpark transformations on semi-structured Yelp data
- Generate actionable insights from business, review, and user data

---

## Prerequisites

- Active Microsoft Azure subscription
- Basic knowledge of PySpark, JSON, and Parquet formats
- Familiarity with Azure portal and Databricks environment

---

## Tech Stack

**Languages**: Python, SQL  
**Libraries**: PySpark  
**Services**: Azure Data Lake Storage Gen2, Azure Data Factory, Azure Databricks  
**File Formats**: JSON (raw), Parquet (processed)

---

## Expected Outcomes

- Build a cloud-scale pipeline to process and analyze Yelp reviews
- Convert JSON data to Parquet and apply transformations using PySpark
- Identify top business categories and most active users
- Analyze review patterns, check-in trends, and user behavior
- Explore advanced Spark operations: partitioning and file format optimization

---

## Key Features

- Create ADLS containers to manage raw and processed data layers
- Upload JSON-based Yelp dataset to the raw container
- Use Azure Data Factory to build and execute a Copy Data pipeline
- Transfer data to a second ADLS container for transformation
- Provision Azure Databricks workspace and compute clusters
- Load JSON data into Spark DataFrames and write to Parquet
- Perform transformation using PySpark on review, user, and business data
- Analyze trends like most reviewed categories, top users, and frequent check-ins
- Use partitioning and coalescing techniques for performance optimization
- Visualize aggregated results using Spark DataFrame operations

---

## Important Notes

- Monitor and manage Azure resources actively to avoid incurring unexpected costs.
- Use Parquet format for optimized storage and faster query performance in Databricks.
- Take advantage of **partitionBy** and **coalesce** to control data distribution and output file sizes.
- Always organize Azure services into resource groups for structured access and governance.

---

## Dataset Overview

The [Yelp dataset](https://www.yelp.com/dataset) includes the following key JSON files:

- **business.json**: Business names, locations, categories, and attributes
- **review.json**: Customer reviews with ratings, text, and timestamps
- **user.json**: User profiles with review history and social connections
- **checkin.json**: Records of business check-in activity by time
- **tip.json**: Short user suggestions and feedback

These components offer a holistic view of local businesses and user interactions across Yelp's ecosystem.

---

## Project Link

[Analyse Yelp Dataset with Spark & Parquet Format on Azure Databricks](https://www.projectpro.io/project-use-case/analyze-yelp-data-spark-parquet-project)

---

## Next Steps

- Explore converting other Yelp JSON files (e.g., check-ins and tips) to Parquet
- Create interactive dashboards using Power BI or Databricks SQL
- Train sentiment analysis or recommendation models on review data
- Use Databricks Jobs and ADF triggers to schedule transformation workflows
- Apply Unity Catalog and role-based access for secure data governance
