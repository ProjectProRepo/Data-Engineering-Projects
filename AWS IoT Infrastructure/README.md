# AWS Project: Real-Time IoT Infrastructure with AWS CDK and MQTT

## Overview

In this AWS cloud infrastructure project, you will learn how to build a **real-time IoT architecture** using **AWS Cloud Development Kit (CDK)** in **Python** to simulate, stream, and process IoT data. This project enables Infrastructure as Code (IaC) deployment of services like **AWS IoT Core**, **Kinesis Firehose**, **Lambda**, **S3**, and **Secrets Manager** for seamless data ingestion and cloud migration.

You’ll replicate a simulated **on-premise MySQL environment** using EC2 and IoT device data, representing a **smart city sensor system** near London’s O2 Arena. The entire infrastructure is provisioned and deployed using AWS CDK constructs, making it a production-grade, scalable setup for edge-to-cloud streaming analytics.

## Project Objectives

- Understand the end-to-end **IoT architecture and its cloud migration** strategy.  
- Create an **AWS account** and follow setup and security best practices.  
- Install and configure the **AWS CLI** for secure programmatic access.  
- Use the **AWS IoT Device Simulator** to emit geo-location data.  
- Create a **Kinesis Firehose** stream for near real-time delivery to S3.  
- Launch and configure an **EC2 instance** to simulate on-premise MySQL DB.  
- Ingest data from EC2 using **IoT Core and MQTT protocol**.  
- Install and bootstrap the **AWS CDK** CLI on a local machine.  
- Understand **L1, L2, and L3 CDK constructs** and their use cases.  
- Build and deploy **S3 and Lambda stacks** with CDK using Python.  
- Set up **Secrets Manager** and a **VPC Endpoint** for secure DB access.  
- Use CDK to **deploy and destroy infrastructure stacks** programmatically.

## Prerequisites

Before starting this project, make sure you have:

- An active **AWS account** with admin access to IAM, S3, EC2, IoT Core, Lambda, Secrets Manager, and Kinesis.  
- Basic understanding of **Python**, **cloud networking**, and **MQTT protocol**.  
- Familiarity with **Infrastructure as Code (IaC)** and **CloudFormation** concepts.  
- Working knowledge of **AWS CLI**, **IAM policies**, and EC2 provisioning.  
- A local development environment set up with **Node.js, Python 3, and AWS CDK CLI**.  

## Tech Stack

- **Languages**: Python 3, SQL, MQTT  
- **AWS Services**: AWS CDK, IoT Core, Kinesis Firehose, Lambda, Amazon S3, EC2, Secrets Manager, VPC  
- **Libraries & Tools**: AWS CDK, AWS CLI, MariaDB (on EC2), AWS IoT Device Simulator  

## Expected Outcomes

By completing this project, you will:

- Learn to **provision complete IoT architecture using AWS CDK**.  
- Simulate and stream **real-time geo-location data** from IoT devices.  
- Understand how to **deploy EC2-based systems** as part of a hybrid cloud setup.  
- Use **Kinesis Firehose** to deliver streaming data directly to S3.  
- Build **event-driven serverless pipelines** using AWS Lambda.  
- Define infrastructure with **Python CDK constructs** and manage deployments.  
- Apply **secure secrets handling** using AWS Secrets Manager.  
- Prepare for roles in **DevOps, IoT cloud architecture, and Infrastructure Engineering**.

## Key Features of the Project

- **Infrastructure as Code with CDK**: Full automation using declarative Python-based stacks.  
- **IoT Simulation & MQTT Integration**: Emulate edge devices in a realistic smart city use case.  
- **Real-Time Data Delivery**: Use Kinesis Firehose for low-latency data streaming to cloud storage.  
- **On-Premise Emulation**: Simulate an existing data center using EC2 and MariaDB.  
- **Lambda Triggers**: Build real-time data processors with serverless functions.  
- **CDK Construct Levels**: Learn the differences between L1, L2, and L3 CDK constructs.  
- **Secrets Management**: Securely store and access database credentials.  
- **Clean Resource Lifecycle**: Deploy and destroy stacks cleanly using CDK CLI.

## Important Notes

- **IoT Device Simulator**: Use AWS-provided tools to simulate edge environments before scaling.  
- **MQTT and SQL Fusion**: Leverage the power of rules engine to transform incoming MQTT messages using SQL.  
- **Secrets Handling**: Always use AWS Secrets Manager instead of hardcoding credentials.  
- **VPC Endpoints**: Ensure secure and private connection to cloud services without traversing the internet.  
- **Stack Destruction**: Remember to run `cdk destroy` to avoid recurring charges post-demo.  

## Dataset Overview

The project simulates **live geo-location data** for smart devices positioned around The O2 Arena in London. Fields include:

- `device_id`  
- `timestamp`  
- `latitude`  
- `longitude`  
- `sensor_type`  
- `temperature`  
- `humidity`  
- `status`  

This simulated dataset is ingested into AWS services and used for real-time processing and analytics.

## Project Link

[AWS Project: Real-Time IoT Infrastructure with AWS CDK and MQTT](https://www.projectpro.io/project-use-case/aws-cdk-project-example-for-building-real-time-iot-infrastructure)

## Next Steps

- Extend the pipeline to store IoT data into **Amazon Timestream** for time-series analytics.  
- Build a **QuickSight dashboard** for real-time visualization of IoT metrics.  
- Migrate EC2-based MariaDB to **Amazon RDS or Aurora** with DMS.  
- Implement **alerts and monitoring** using CloudWatch and SNS.  
- Integrate **AWS IoT Analytics** or **Kinesis Data Analytics** for advanced stream processing.  
