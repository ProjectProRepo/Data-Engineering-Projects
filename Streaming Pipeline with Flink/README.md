# AWS Project: Real-Time Streaming Data Pipeline Using Flink and Kinesis

## Overview

In this big data project on AWS, you will learn how to build a **real-time streaming data pipeline** using **Apache Flink** and **Amazon Kinesis** to process simulated accident event data. This project mirrors enterprise-grade streaming ETL solutions where perishable data must be processed and acted upon instantly to make smarter decisions. It’s ideal for those looking to gain hands-on experience with real-time analytics, stream processing, and event-driven architectures.

You’ll use tools like **Apache Flink**, **Kinesis Data Streams**, **AWS Lambda**, **Glue**, **Athena**, and **Grafana** to develop a fault-tolerant, scalable, and insight-driven data streaming system on AWS.

## Project Objectives

- Understand the concept of **perishable data** and its business value.  
- Simulate **real-time accidents data** from edge devices to Kinesis Streams.  
- Create **IAM roles and policies** required for stream analytics.  
- Set up the AWS CLI and manage resources programmatically.  
- Use **Apache Flink** to process real-time events from Amazon Kinesis.  
- Visualize metrics and KPIs using **Grafana** and **CloudWatch Dashboards**.  
- Create **Glue Crawlers** and build **Athena tables** from the data lake.  
- Trigger **SNS notifications** using AWS Lambda for alerting.  
- Work with **Apache Zeppelin notebooks** for real-time analytics.

## Prerequisites

Before you begin, ensure the following:

- An active **AWS Free Tier account** with permissions to use Kinesis, Flink, Lambda, SNS, Glue, Athena, and CloudWatch.  
- Basic knowledge of **Python**, **SQL**, and **real-time data concepts**.  
- Familiarity with **streaming architectures**, **S3**, and **IAM roles**.  
- **AWS CLI configured** locally for managing services via terminal.  
- Some exposure to **data visualization platforms** like Grafana.

## Tech Stack

- **Languages**: Python 3, SQL  
- **Cloud Services**: AWS S3, AWS Glue, AWS Lambda, Amazon Kinesis, Amazon SNS, AWS Athena, AWS CloudWatch, Grafana, Apache Flink, Apache Zeppelin  
- **Libraries**: Boto3, Pandas, PyFlink, SQLAlchemy

## Expected Outcomes

By completing this project, you will:

- Understand how to build a **low-latency streaming architecture** on AWS.  
- Learn to deploy **Apache Flink applications** for processing event data.  
- Gain practical experience using **Kinesis Data Streams and Firehose**.  
- Automate data crawling and querying using **Glue Crawlers and Athena**.  
- Set up alerting systems with **SNS and Lambda** for critical event detection.  
- Build **real-time dashboards** to monitor accident events using Grafana.  
- Prepare for **big data engineer roles** focused on streaming and IoT data.

## Key Features of the Project

- **Streaming Pipeline Architecture**: End-to-end system from ingestion to analytics.  
- **Real-Time Data Processing**: Use Flink to process event data with low latency.  
- **Serverless Notifications**: Trigger SNS alerts from Lambda on critical events.  
- **Athena Integration**: Run distributed SQL queries directly on S3.  
- **Zeppelin Notebook Integration**: Use PyFlink for exploratory stream analytics.  
- **Monitoring & Visualization**: Leverage Grafana and CloudWatch for insights.

## Important Notes

- **Cloud9 Deprecation**: This project includes alternate steps using **VS Code** to upload files and configure Lambda since **Cloud9 is deprecated for new users**.  
- **Cookbook Access**: A **text-based execution guide** is available as an alternative to video walkthroughs.  
- **Cost Awareness**: Regularly monitor your AWS usage and services to avoid unexpected charges.  
- **Kinesis Limits**: Be aware of shard limits, throughput quotas, and record size limitations.  
- **IAM Permissions**: Ensure fine-grained roles are assigned to Lambda, Glue, and Flink for secure access.

## Dataset Overview

The project uses a simulated US accidents dataset containing the following fields:

- `severity`  
- `start_time`  
- `end_time`  
- `location`  
- `description`  
- `city`  
- `state`  

This dataset is streamed into Kinesis and processed in real-time to detect patterns, visualize trends, and trigger alerts.

## Project Link

[AWS Project: Real-Time Streaming Data Pipeline Using Flink and Kinesis](https://www.projectpro.io/project-use-case/real-time-streaming-data-pipeline-using-apache-flink-python-and-amazon-kinesis)

## Next Steps

- Implement **sliding window aggregations** in Flink for rolling metrics.  
- Add **checkpointing** and **state management** to improve Flink fault tolerance.  
- Explore **multi-region streaming** and **data replication** patterns.  
- Integrate **Redshift or OpenSearch** for long-term storage and analytics.  
- Use **AWS Step Functions** to orchestrate multi-step workflows in the pipeline.
