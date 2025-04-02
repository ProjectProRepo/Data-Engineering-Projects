# AWS CDK and IoT Core for Migrating IoT-Based Data to AWS  

## Overview  

The **Internet of Things (IoT)** is revolutionizing industries by providing real-time data that enhances decision-making, efficiency, and automation. In this project, we will use **AWS CDK** and various **AWS services** to **simulate an on-premise data center** and migrate real-time IoT data to AWS.  

The project leverages **AWS IoT Core**, **Kinesis Firehose**, **AWS Lambda**, **Amazon S3**, **MariaDB**, and **AWS Secrets Manager** to build a **scalable and secure IoT data ingestion pipeline**. This is the **first part** of a multi-phase **IoT Data Migration series**, setting the foundation for advanced **data analytics and cloud-based transformations** in subsequent projects.  

## Project Objectives  

- Understand **AWS IoT Core** and **AWS IoT Device Simulator** for generating **real-time sensor data**.  
- Build an **AWS CDK-based infrastructure** for **IoT data ingestion and storage**.  
- Deploy an **EC2 instance** to simulate an **on-premise MySQL database**.  
- Stream IoT data to **Amazon Kinesis Firehose** and store it in **Amazon S3**.  
- Implement **AWS Lambda functions** for data processing and transformation.  
- Secure credentials using **AWS Secrets Manager**.  
- Understand and implement **VPC Endpoints for secure communication**.  

## Prerequisites  

Before starting, ensure you have:  

- A basic understanding of **AWS cloud services (S3, EC2, IoT Core, Lambda, CDK)**.  
- Knowledge of **Python** and **SQL** for scripting and querying.  
- An **AWS account** with necessary permissions for **IAM, Kinesis, and IoT Core**.  
- Familiarity with **AWS CLI** and **AWS CDK** for infrastructure deployment.  

## Tech Stack  

- **Framework**: AWS CDK  
- **Language**: Python  
- **Services**: AWS IoT Core, Kinesis Firehose, AWS Lambda, MariaDB, AWS S3, AWS Secrets Manager, AWS CloudFormation  

## Expected Outcomes  

By completing this project, you will:  

- Understand **IoT data ingestion pipelines** using **AWS services**.  
- Deploy **AWS resources** using **AWS CDK** for **Infrastructure as Code (IaC)**.  
- Implement **real-time data streaming** from **IoT devices to AWS**.  
- Create an **on-premise simulation** using **EC2 and MariaDB**.  
- Secure sensitive information using **AWS Secrets Manager**.  

## Key Features of the IoT Data Pipeline  

- **Real-time IoT Data Ingestion**: Uses **AWS IoT Core and Kinesis Firehose**.  
- **On-Premise Database Simulation**: Deploys **MariaDB on EC2** to replicate **legacy systems**.  
- **Serverless Data Processing**: Uses **AWS Lambda** to **transform incoming IoT data**.  
- **Secure Data Storage**: Stores transformed data in **Amazon S3** with **IAM role-based access control**.  
- **Infrastructure as Code**: Deploys **AWS resources using AWS CDK**.  
- **Secrets Management**: Secures credentials using **AWS Secrets Manager**.  

## Important Notes  

- **IoT Device Simulator**: Used to simulate **geo-location data** from **IoT devices near The O2 Arena in London**.  
- **AWS Costs**: Streaming data through **Kinesis Firehose** may incur **AWS charges**.  
- **Security Best Practices**: Ensure **IAM roles** are correctly configured to **limit access to AWS resources**.  

## Project Link  

[AWS CDK and IoT Core for Migrating IoT-Based Data to AWS](<https://www.projectpro.io/project-use-case/aws-cdk-project-for-migrating-iot-based-data>)  

## Next Steps  

- **Extend the project** by integrating **AWS Glue and AWS Timestream** for real-time analytics.  
- **Automate database migration** using **AWS DMS (Database Migration Service)**.  
- **Implement machine learning models** on IoT data for predictive maintenance.  
- **Explore AWS QuickSight** for **advanced data visualization**.  
