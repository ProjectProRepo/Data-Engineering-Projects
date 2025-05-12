# Azure Project – Build Streaming Data Pipeline using Azure Stream Analytics  
In this Azure Data Engineering project, you will build a **real-time streaming data pipeline** using **Azure Stream Analytics**, **Azure Event Hub**, and **Azure SQL Database**. This project will walk you through the full process of ingesting live data, processing it with SQL-like queries, storing it in a relational database, and visualizing it through **Power BI**.

---

## Project Objectives  
- Understand how to work with **transportation data** for real-time processing  
- Learn the differences between **big data** and traditional batch processing  
- Gain practical experience with **Azure Stream Analytics**, **Event Hub**, and **SQL Database**  
- Write and run a Python script to simulate real-time event ingestion  
- Filter and transform data using **Stream Analytics queries**  
- Store processed data in **Azure SQL Database**  
- Connect Power BI to the database and create an interactive dashboard  

---

## Prerequisites  
- Basic knowledge of Azure services and Python  
- Familiarity with SQL syntax  
- An active **Azure account** and **Power BI Desktop** installed  
- Understanding of data ingestion and real-time data concepts  

---

## Tech Stack  
- **Languages**: Python, SQL  
- **Services**: Azure Event Hub, Azure Stream Analytics, Azure SQL Database, Power BI  

---

## Expected Outcomes  
- Real-time data ingestion from a simulated event stream  
- Custom Stream Analytics jobs to process data on the fly  
- Filtered data stored securely in a cloud SQL database  
- Live dashboards showing transportation insights via Power BI  
- Hands-on understanding of **streaming pipelines** for use cases such as IoT, transportation, and operational analytics  

---

## Key Features  
- Setup and manage an **Azure Event Hub** for real-time event ingestion  
- Build an **Azure Stream Analytics** job to process and transform streaming data  
- Write SQL-like queries in Stream Analytics to filter relevant insights  
- Create and configure an **Azure SQL Database** to persist the results  
- Use a **Python script** to simulate and send streaming messages to Event Hub  
- Load and visualize insights using **Power BI dashboards**  
- End-to-end real-time analytics pipeline using Azure cloud tools  

---

## Important Notes  
- Azure Stream Analytics supports both **real-time** and **windowed queries** for data analysis  
- Ensure **firewall rules** and **connection strings** are correctly configured for SQL and Event Hub  
- Use the **Azure Portal** to monitor the health of your Stream Analytics job  
- For Power BI, ensure that the SQL Database is reachable via the **on-premises data gateway** (if needed)  

---

## Dataset Overview  
The project uses a **transportation dataset** containing real-time vehicle and traffic data such as:  
- `vehicle_id` – Unique identifier for each vehicle  
- `route` – Assigned route  
- `speed` – Current speed  
- `timestamp` – Time of the event  
- `location` – Latitude and longitude coordinates  

This data simulates a real-world streaming use case to track transportation performance.

---

## Azure Service Overview  

### Azure Stream Analytics  
A real-time analytics service designed for mission-critical workloads with millisecond-level latency. It can ingest data from multiple sources like **IoT devices**, **event hubs**, or **blobs**, apply transformation logic using SQL-like syntax, and route data to a variety of outputs such as **databases**, **storage**, or **dashboards**.

### Azure Event Hub  
A **big data streaming platform** and event ingestion service that can receive and process millions of events per second. It acts as the front door for an event streaming pipeline, decoupling the producers (like devices or apps) from the consumers (like analytics services or databases).

### Azure SQL Database  
A **fully managed relational database** in the cloud that offers scalability, security, and integration with other Azure services. Used in this project to persist cleaned and filtered streaming data for further analysis.

---

## Sample Insights  
- Identify routes with high congestion based on real-time speed analysis  
- Monitor vehicle flow per location in near real-time  
- Detect anomalies in travel patterns or speed violations  
- Build transport performance dashboards for operational decision-making  

---

## Project Link  
[Azure Streaming Project: Real-Time Transportation Analytics using Stream Analytics, Event Hub, and SQL ](https://www.projectpro.io/project-use-case/data-pipeline-using-azure-stream-analytics)

---

## Next Steps  
- Integrate **Azure Functions** to trigger alerts based on thresholds  
- Use **Azure Blob Storage** to store raw unprocessed events for auditing  
- Build a **scheduled data refresh** pipeline in Power BI  
- Incorporate **machine learning models** to predict delays or optimize routing  
