# Build an Incremental ETL Pipeline with AWS CDK  

## Overview  

The **cryptocurrency market** is dynamic and fast-paced, requiring real-time analytics to uncover trends, build strategies, and make informed decisions. In this project, you’ll learn to **build an Incremental ETL pipeline** using **AWS CDK** and **serverless AWS services**, allowing you to collect, process, analyze, and visualize crypto market data efficiently.  

We’ll use the **Alpha Vantage API** to fetch real-time cryptocurrency data, stream it via **Kinesis**, process it using **Lambda**, **AWS Glue**, and **Apache Flink**, and store the final outputs for querying in **Amazon Athena** and **visualizing in QuickSight**.  

## Project Objectives  

- Understand the **Alpha Vantage API** and the **cryptocurrency dataset** structure.  
- Learn **AWS CDK fundamentals** and deploy infrastructure as code.  
- Create **Lambda Producers and Consumers** to build a serverless pipeline.  
- Stream and process data using **Kinesis Data Streams**.  
- Apply **incremental ETL transformations** using **Apache Flink**, **Glue**, and **Lambda**.  
- Store data in **DynamoDB** and query it using **Amazon Athena**.  
- Visualize insights using **Amazon QuickSight**.  

## Prerequisites  

Before you begin, make sure you have:  

- A basic understanding of **AWS services**, especially **Lambda, Kinesis, Glue, and DynamoDB**.  
- Working knowledge of **Python** and **SQL**.  
- An **AWS account** with necessary permissions to deploy infrastructure.  
- Familiarity with **AWS CLI**, **CDK**, and optionally **Apache Flink**.  

## Tech Stack  

- **Language**: Python  
- **Framework**: AWS CDK  
- **Data Source**: Alpha Vantage API  
- **Services**: AWS Lambda, Kinesis, DynamoDB, S3, Glue, Athena, QuickSight, Apache Flink, Apache Zeppelin  

## Expected Outcomes  

By completing this project, you will:  

- Gain hands-on experience building **incremental ETL pipelines**.  
- Learn how to implement **serverless data ingestion and processing**.  
- Analyze and visualize real-time **cryptocurrency data**.  
- Automate infrastructure deployment using **AWS CDK**.  
- Apply **streaming analytics** using **Apache Flink** and **Zeppelin**.  

## Key Features of the Pipeline  

- **Incremental Data Fetching**: API-driven Lambda Producers
- **Real-time Stream Processing**: Kinesis Streams + Flink + Lambda  
- **Serverless Architecture**: Cost-efficient, event-driven design  
- **Infrastructure as Code**: Provision all AWS resources with CDK  
- **Scalable Storage**: Store time-series crypto data in DynamoDB  
- **Query-Ready Data**: Use Athena and Glue to analyze transformed data  
- **Insightful Visualizations**: Build dashboards with QuickSight  

## Important Notes  

- **Alpha Vantage Rate Limits**: Be mindful of API limits (5 calls/min for free tier).  
- **Cloud9 Deprecation**: Use **Visual Studio Code** or **local IDE** for CDK development.  
- **Security Best Practices**: Secure your API keys and IAM roles properly.  

## Project Link  

[Build an Incremental ETL Pipeline with AWS CDK](<https://www.projectpro.io/project-use-case/building-data-warehouse-using-apache-spark-hive>)  

## Next Steps  

- **Add historical price support** by integrating CSV data from CoinMarketCap.  
- Implement **real-time anomaly detection** using machine learning.  
- Extend to support **multi-source ETL pipelines**.  
- Trigger **alerts via SNS** for sharp market movements.  
