# PySpark Project – Airline Dataset Analysis using GraphFrames in Python  
In this PySpark project, you will analyze airline performance data using **GraphFrames** in a **Databricks** environment. You will construct and query graph structures to uncover meaningful patterns such as shortest paths, flight delay motifs, and airport influence using **PageRank**.

---

## Project Objectives  
- Learn how to set up and use **Databricks** for PySpark-based analysis  
- Install and use **GraphFrames** in a Databricks notebook  
- Explore and understand **Spark SQL**, cluster architecture, and Spark UI components  
- Perform **graph-based analysis** of airline data  
- Use **motif finding**, **PageRank**, and **Breadth-First Search (BFS)** algorithms  
- Understand directed vs. undirected graph behavior in real-world flight data  
- Identify key insights related to airport performance and travel patterns  

---

## Prerequisites  
- Basic understanding of Python and PySpark  
- Familiarity with Spark DataFrames and SQL  
- A Databricks account (community edition or enterprise)  
- Working knowledge of graph theory concepts (optional but helpful)  

---

## Tech Stack  
- **Language**: Python  
- **Libraries**: PySpark, GraphFrames  
- **Platform/Service**: Databricks  

---

## Expected Outcomes  
- Ability to model relational airline data as a graph structure  
- Discover patterns such as:
  - Airports with the most delays
  - Most popular and connected routes
  - Top transfer hubs in the flight network  
- Run and interpret results from **PageRank** and **Triangle Count**  
- Use **motif finding** to detect complex relationships in delay propagation  
- Understand graph analytics fundamentals applied to real-world datasets  

---

## Key Features  
- Use of **GraphFrames** to represent flights and airports as vertices and edges  
- Integration with **Databricks** for cluster management and notebook-based development  
- Structured queries with Spark SQL to filter and transform the dataset  
- Graph-based exploration for topological insights:
  - **BFS** for shortest path detection  
  - **PageRank** for airport influence ranking  
  - **Motif finding** for complex structure patterns  
- Visualization and performance monitoring with Spark UI, Driver Logs, and Event Logs  

---

## Important Notes  
- GraphFrames requires installation via Maven coordinates or library utility within Databricks  
- Always cache your DataFrames when reused across multiple transformations to boost performance  
- Graph analytics can be computationally expensive – optimize Spark configurations for large data  
- Use sample subsets during development to avoid unnecessary cluster strain  

---

## Dataset Overview  
The dataset consists of over **1 million records** detailing airline flight performance. Key fields include:  
- `Date` – Date of the flight  
- `Delay` – Delay time in minutes  
- `Distance` – Distance flown  
- `Origin` – Departure airport code  
- `Destination` – Arrival airport code  

This structured dataset allows the modeling of airports as **vertices** and flights as **edges** in a graph.

---

## Project Link  
[PySpark Project: Airline Network and Delay Analysis using GraphFrames on Databricks](https://www.projectpro.io/project-use-case/airline-dataset-analysis-using-graphframes-in-python) 

---

## Next Steps  
- Integrate **flight schedule prediction models** using MLlib  
- Extend graph analysis to **seasonal data** (e.g., holiday travel patterns)  
- Visualize flight graphs using network visualization tools like Neo4j or Graphistry  
- Schedule this analysis pipeline using **Databricks Jobs** or **Apache Airflow**  
