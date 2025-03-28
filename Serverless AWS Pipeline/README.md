# Build Serverless Pipeline using AWS CDK and Lambda in Python  

## Overview  

**Serverless architecture** enables developers to build and deploy applications without managing infrastructure. While applications still run on servers, AWS handles provisioning, scaling, and maintenance. This project leverages **AWS Cloud Development Kit (AWS CDK)** to build a **serverless data pipeline** for analyzing financial data from multiple sources.  

The pipeline processes **historical stock data from Amazon Aurora**, **FOREX data stored in Amazon S3**, and **intraday stock data from the Alpha Vantage API**. AWS **Lambda** and **Glue** transform the data, which is then analyzed using **Amazon Athena** and visualized in **Amazon QuickSight**.  

## Project Objectives  

- Understand **AWS CDK** and how it simplifies infrastructure deployment.  
- Learn about **Alpha Vantage API** for fetching financial market data.  
- Work with **three different financial datasets** stored across **Amazon Aurora, S3, and API streams**.  
- Deploy **serverless data processing pipelines** using **AWS Lambda** and **Glue**.  
- Perform **real-time and batch data analysis** using **Amazon Athena**.  
- Create **interactive financial dashboards** using **Amazon QuickSight**.  

## Prerequisites  

Before starting this project, ensure you have:  

- Basic knowledge of **AWS Cloud Services**, including **S3, Lambda, and Glue**.  
- Experience with **Python and SQL** for data transformation and querying.  
- A working **AWS account** (ensure access to AWS CDK, Glue, and Athena).  
- Familiarity with **GitHub** for cloning repositories and deploying AWS CDK applications.  

## Tech Stack  

- **Language**: Python  
- **AWS Services**: AWS S3, Amazon Lambda, Amazon Aurora, AWS Glue, Amazon Athena, QuickSight, AWS CDK  

## Expected Outcomes  

By completing this project, you will:  

- Learn to **build a fully serverless data pipeline** using **AWS CDK**.  
- Process and store **financial data from multiple sources** in AWS.  
- Use **AWS Glue** for **data transformation and ETL workflows**.  
- Query **financial market data** efficiently using **Amazon Athena**.  
- Build **real-time financial dashboards** in **Amazon QuickSight**.  

## Key Features of the Serverless Pipeline  

✔ **Fully Serverless**: Uses **AWS Lambda, Glue, and S3** for scalable data processing.  
✔ **Financial Market Data Processing**: Ingests data from **Alpha Vantage API, Amazon Aurora, and S3**.  
✔ **Automated ETL Workflows**: Uses **AWS Glue** for efficient data transformation.  
✔ **SQL-Based Querying**: Utilizes **Amazon Athena** to perform analysis on transformed data.  
✔ **Real-Time Data Visualization**: Implements **QuickSight dashboards** for financial insights.  

## Important Notes  

- **AWS Services Costs**: Using **AWS Lambda, Glue, and Athena** may incur **cloud service charges**. Review AWS pricing before deployment.  
- **Cloud9 Deprecation**: AWS has **deprecated Cloud9 for new users**. Consider using **Visual Studio Code** as an alternative for AWS CDK development.  
- **Athena Query Costs**: Amazon Athena charges per **query execution**. Optimize queries to minimize costs.  

## Project Link  

[Build Serverless Pipeline using AWS CDK and Lambda in Python](https://www.projectpro.io/project-use-case/aws-cdk-lambda-pipeline-example)  

## Next Steps  

- Extend the project to **include real-time stock price alerts**.  
- Implement **machine learning models** for **stock trend prediction**.  
- Optimize AWS Lambda functions for **cost efficiency**.  
- Automate **CI/CD deployment** for the AWS CDK application.  
