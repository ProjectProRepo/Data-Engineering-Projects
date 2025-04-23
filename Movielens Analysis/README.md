# Movielens Dataset Analysis on Azure

In this project, you will build a movie recommendation system using Spark SQL and PySpark on Microsoft Azure. You'll work with the popular Movielens dataset, setting up an end-to-end cloud-based data pipeline that leverages Azure Data Factory, Azure Databricks, and Azure Storage services to extract, transform, and analyze the data, and finally generate actionable movie recommendations.

---

## Project Objectives

- Set up and configure an Azure subscription with essential data services
- Upload and organize raw data in Azure Blob and Data Lake Storage
- Create and execute copy data pipelines in Azure Data Factory
- Launch Databricks workspace and clusters for scalable data analysis
- Clean and transform data using PySpark and Spark SQL
- Perform data analysis and generate movie recommendations
- Visualize movie ratings and tag distributions

---

## Prerequisites

- Active Microsoft Azure subscription
- Basic knowledge of Spark, SQL, and Python
- Familiarity with Azure Storage, ADF, and Databricks interface

---

## Tech Stack

**Languages**: Python, SQL, Spark  
**Packages**: PySpark, Spark SQL  
**Services**: Azure Blob Storage, Azure Data Lake Storage, Azure Data Factory, Azure Databricks  
**Dataset**: [Movielens](https://grouplens.org/datasets/movielens/)

---

## Expected Outcomes

- Implement an end-to-end movie recommender system on Azure
- Understand data pipeline design from ingestion to transformation
- Learn to use Spark SQL and PySpark for large-scale data analysis
- Visualize KPIs like movie ratings and tag distributions
- Apply collaborative filtering and content-based recommendation techniques

---

## Key Features

- Upload raw Movielens ZIP files to Azure Blob Storage containers
- Use ADF to build a copy data pipeline that transfers data to ADLS
- Set up and configure Databricks workspace and Spark clusters
- Mount storage accounts and extract CSV files from ZIP in Databricks
- Load data into Spark DataFrames and perform cleansing and exploration
- Analyze movie ratings, tags, and generate personalized recommendations
- Create visualizations using PySpark DataFrames and bar charts

---

## Important Notes

- While traditional DBFS mounts are still common in tutorials, Databricks **now recommends Unity Catalog** for secure, governed data access across workspaces.
- When accessing external data, use direct paths such as `wasbs://` instead of mounting.
- Always organize Azure resources using **Resource Groups** for easier management.
- Azure Data Factory pipelines help in orchestrating data movement and transformation across storage tiers.

---

## Dataset Overview

The [Movielens dataset](https://grouplens.org/datasets/movielens/) includes:

- `movies.csv`: Movie titles, genres, and IDs  
- `ratings.csv`: User ratings of movies over time  
- `tags.csv`: Tags users have applied to movies  
- `links.csv`: Mapping to external movie databases (IMDb, TMDb)

---

## Project Link

[Movielens Dataset Analysis on Azure](https://www.projectpro.io/project-use-case/analyse-movie-ratings-data)
---

## Next Steps

- Explore recommendation models like ALS (Alternating Least Squares) in Spark MLlib
- Deploy the recommender model using Azure ML or Databricks Jobs
- Connect Power BI for interactive dashboards on movie insights
- Automate ADF pipelines and notebook executions using triggers
- Integrate GitHub for version control and CI/CD in Databricks
