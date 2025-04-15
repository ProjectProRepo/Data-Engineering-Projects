# AWS Project: Graph Database Modeling Using Amazon Neptune and Gremlin

## Overview

In this AWS data analytics project, you will learn how to build a **graph-based data pipeline** using **Amazon Neptune** and **Apache Gremlin** to model and analyze flight performance metrics. This project showcases the power of **graph databases** to uncover insights from highly connected data, which traditional relational databases struggle to handle efficiently.

You’ll simulate an analytics platform for an **airport operator** to answer complex queries like identifying top airlines, busiest routes, and most congested airports. Using services like **AWS Glue**, **S3**, **Neptune**, **EC2**, and **Gremlin**, you will implement a production-ready pipeline for loading and analyzing graph data at scale.

## Project Objectives

- Understand **graph data modeling** concepts and the **SPOG (Subject–Predicate–Object–Graph)** structure.  
- Simulate airline and airport data for **graph-based analytics**.  
- Upload data to **S3 with partitions** using AWS CLI.  
- Create **IAM roles and policies** for secure service access.  
- Use **AWS Glue Crawler** to build external **Athena tables** from raw data.  
- Preprocess data using **Spark on Glue Dev Endpoints**.  
- Convert relational data into **vertices and edges** for Neptune.  
- Bulk load data from **S3 into Neptune** using Neptune Loader API.  
- Query flight and airport relationships using **Apache Gremlin** in **Jupyter Notebooks**.  
- Explore **alternatives to Cloud9** for preparing and loading data.

## Prerequisites

Before starting this project, make sure you have:

- An active **AWS account** with access to S3, Glue, IAM, Neptune, EC2, and Athena.  
- Basic knowledge of **Python**, **SQL**, and **graph theory**.  
- Familiarity with **ETL concepts**, **AWS CLI**, and **Spark-based preprocessing**.  
- Awareness of **graph traversal languages** such as **Gremlin**.  
- A local terminal or IDE to work with files (Cloud9 deprecated for new users).  

## Tech Stack

- **Languages**: Python 3, SQL, Gremlin  
- **AWS Services**: Amazon S3, AWS Glue, AWS Athena, Amazon EC2, Amazon Neptune, AWS IAM, AWS Cloud9 (alternative options provided)  
- **Libraries**: Apache Spark, PyGremlin, Boto3, Pandas

## Expected Outcomes

By completing this project, you will:

- Understand how to **design a graph schema** for real-world flight analytics.  
- Model data as **nodes and relationships** for high-performance querying.  
- Build an end-to-end ETL pipeline that **loads graph data into Neptune**.  
- Execute **Gremlin traversals** to extract insights from highly connected datasets.  
- Learn to **preprocess and partition raw data** using Spark on AWS Glue.  
- Work with **Jupyter Notebooks** for interactive Gremlin queries.  
- Gain experience with **S3-based staging and data lake practices**.  
- Prepare for **analytics engineering and data graph modeling roles**.

## Key Features of the Project

- **Graph Database Modeling**: Use Neptune to manage complex relationships natively.  
- **Apache Gremlin Querying**: Traverse nodes and edges to gain actionable insights.  
- **Bulk Data Loader**: Efficiently ingest large datasets from S3 to Neptune.  
- **Vertex & Edge Schema Design**: Create realistic graph models for flights and airports.  
- **ETL Pipeline using Spark**: Preprocess and partition flight data efficiently.  
- **Dev Endpoint for Glue Jobs**: Run interactive Spark sessions from Jupyter.  
- **Athena for Data Validation**: Preview and validate staging data using SQL.  
- **Cloud9 Alternatives**: Learn how to use local IDEs or EC2 instances for setup.

## Important Notes

- **Cloud9 Deprecation**: New AWS users should use **VS Code** or **EC2 alternatives** to run CLI commands and prepare data.  
- **Data Loader Format**: Follow Neptune bulk load format for CSVs (edges, vertices).  
- **IAM Configurations**: Use scoped-down roles for Glue, EC2, and Neptune securely.  
- **Neptune Limits**: Monitor cluster memory and connection limits during bulk loads.  
- **Notebook Setup**: Enable Gremlin access in **Zeppelin or Jupyter notebooks** for ease of use.

## Dataset Overview

The project uses **flight performance datasets** from the **US Bureau of Transportation Statistics**, which include:

- `flight_id`  
- `airline_code`  
- `origin_airport`  
- `destination_airport`  
- `departure_delay`  
- `arrival_delay`  
- `taxi_in`  
- `taxi_out`  
- `flight_date`  
- `distance`  

These fields are transformed into **graph vertices (airports, airlines, flights)** and **edges (routes, performance links)** for Neptune-based querying.

## Project Link

[AWS Project: Graph Database Modeling Using Amazon Neptune and Gremlin](https://www.projectpro.io/project-use-case/aws-graph-database-modelling-using-neptune-and-gremlin)

## Next Steps

- Build **graph visualizations** using open-source tools like D3.js or Gephi.  
- Integrate **real-time metrics ingestion** using Kinesis into Neptune.  
- Add **SPARQL endpoint** support for alternate graph querying styles.  
- Explore **fraud or recommendation use cases** with similar graph modeling techniques.  
- Monitor **Neptune performance metrics** using CloudWatch and fine-tune traversals.  
