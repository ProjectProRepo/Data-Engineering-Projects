# AWS Project: Build an ETL Data Pipeline in Python on YouTube Data

## Overview

In this project, you will build a **serverless ETL pipeline on AWS** to process and analyze **YouTube trending video data** using **Python**. This project mirrors real-world data engineering tasks, such as data ingestion, transformation, schema discovery, and querying across a scalable cloud-native architecture. It’s ideal for anyone looking to strengthen their AWS and ETL development skills using popular services like S3, Lambda, Glue, and Athena.

You’ll use tools like **AWS Lambda**, **Glue Studio**, **Athena**, and **QuickSight** to automate data transformations, run analytical queries, and visualize trends in video performance across regions.

## Project Objectives

- Set up an **S3-based data lake** to store raw and transformed YouTube data.  
- Use **AWS Lambda** to convert raw JSON files into **Parquet** format using Python and **awswrangler**.  
- Configure **AWS Glue Crawlers** to infer schema and update the **Glue Data Catalog**.  
- Build and run **ETL jobs in AWS Glue Studio** using Spark and Python.  
- Use **Athena** to run SQL queries on transformed data stored in S3.  
- Create **interactive dashboards in QuickSight** for visual analysis.  
- Understand the **permissions and role configurations** needed for each AWS service.

## Prerequisites

Before you begin, ensure the following:

- An **AWS Free Tier account** with access to S3, Lambda, Glue, Athena, and QuickSight.  
- Installed **Python 3** (for testing and packaging Lambda code).  
- Familiarity with basic **SQL syntax** and **Python scripting**.  
- Some understanding of **cloud storage formats** (CSV, JSON, Parquet).  
- Basic knowledge of **IAM roles**, **permissions**, and AWS regions.

## Tech Stack

- **Languages**: Python, SQL  
- **Cloud Services**: AWS S3, Lambda, Glue, Athena, QuickSight  
- **Libraries**: AWS Data Wrangler, Boto3, Pandas  
- **Data**: YouTube Trending Video Dataset (multi-region CSV/JSON)

## Expected Outcomes

By completing this project, you will:

- Gain hands-on experience with **cloud-native ETL development** on AWS.  
- Understand how to **transform and optimize data** using Parquet and Spark.  
- Learn how to **query large datasets** efficiently using AWS Athena.  
- Build and schedule **Glue jobs** for scalable and automated ETL.  
- Create **visual dashboards** to analyze YouTube video trends.  
- Be prepared for roles involving **data pipelines**, **cloud analytics**, or **data lake architectures**.

## Key Features of the Project

- **Event-Driven ETL**: Trigger Lambda on data upload to start transformations.  
- **Schema Management**: Automate schema discovery using Glue Crawlers.  
- **Optimized File Format**: Convert to columnar Parquet format for Athena querying.  
- **Distributed SQL Queries**: Analyze data directly on S3 with Athena.  
- **BI Visualization**: Build charts in QuickSight from Athena datasets.  
- **Role-Based Access Control**: Secure each AWS service with IAM roles.

## Important Notes

- **AWS Region Consistency**: Use the same region for all services to avoid cross-region costs or errors.  
- **Lambda Deployment**: Use a deployment package or Lambda layer for the awswrangler library.  
- **Crawler Frequency**: Set Glue Crawlers to run only when new data arrives or schema changes.  
- **QuickSight Setup**: You may need to manually grant access to S3 and Athena during setup.  
- **Data Cost**: Athena charges per query scanned—optimize with partitioning and Parquet format.

## Dataset Overview

The project uses multi-region YouTube trending data with the following attributes:

- `video_id`  
- `title`  
- `channel_title`  
- `category_id`  
- `views`  
- `likes`  
- `dislikes`  
- `comment_count`  
- `tags`  
- `description`  
- `publish_time`  
- `country`  

You’ll upload these files to S3, transform them to Parquet, and analyze performance metrics across different regions and categories.

## Project Link

[AWS Project: Build an ETL Data Pipeline in Python on YouTube Data](https://www.projectpro.io/project-use-case/aws-etl-data-pipeline-python-example)

## Next Steps

- Extend the pipeline with **S3 Event Notifications** and **Lambda Triggers**.  
- Orchestrate complex workflows using **Step Functions** or **EventBridge**.  
- Add **error handling**, **logging**, and **alerts** using CloudWatch.  
- Partition data in Athena for faster querying and cost efficiency.  
- Explore **data governance** with Lake Formation or **multi-account** setups for security.
