# SQL Project – Advanced Data Analysis using Oracle Database (Part 4)

In this advanced SQL data analysis project, you will use **Oracle SQL Developer** to explore and manipulate structured data using SQL’s **WITH clause**, **CASE statements**, **inline views**, and **aggregate functions**. This project builds on foundational concepts from previous projects and takes your SQL proficiency to the next level by solving real-life business problems with efficient queries and logical operators.

---

## Project Objectives

- Get comfortable with the **Oracle SQL Developer IDE**
- Explore the distinction between `COUNT(*)` and `COUNT(column_name)`
- Use **CTEs (Common Table Expressions)** via the `WITH` clause for cleaner query structure
- Apply **CASE statements** for dynamic value categorization
- Use **HAVING** and **EXISTS** clauses to filter grouped and conditional data
- Understand and implement **inline views** to simplify complex subqueries
- Learn how and when to use **ROWNUM** to limit rows and filter results efficiently
- Solve practical business problems using optimized SQL queries

---

## Prerequisites

- Basic knowledge of SQL syntax and relational database concepts  
- Familiarity with SELECT, WHERE, GROUP BY, and JOIN operations  
- Access to **Oracle SQL Developer** (or an online lab environment for macOS users)  
- An Oracle-compatible dataset loaded into the database  

---

## Tech Stack

- **Language**: SQL  
- **Tool**: Oracle SQL Developer  

---

## Expected Outcomes

- Ability to write complex queries using **WITH clause** and **inline views**
- Group and filter data effectively using **aggregate functions** like MIN, MAX, AVG, COUNT
- Dynamically label or bucket values using **CASE**
- Understand the performance and syntactical differences between `COUNT(*)` and `COUNT(column)`
- Apply **EXISTS** and **HAVING** clauses for refined filtering
- Gain confidence in handling real-world analytical tasks through SQL

---

## Key Features

- Hands-on practice using **Oracle SQL Developer** for interactive query building  
- Reusable subqueries via **WITH clause** for modular and readable SQL  
- Use of **ROWNUM** to return top N results or paginated data  
- Scenario-based learning through structured exercises and datasets  
- Experience with logic-based query structures using **CASE** and **EXISTS**  
- Simplify nested queries using **inline views**

---

## Important Notes

- **COUNT(*)** counts all rows including NULLs, whereas **COUNT(column)** skips NULL values  
- `WITH` clause (CTEs) improves readability and modularity of large queries  
- **ROWNUM** is Oracle-specific and useful for fetching the top records in sorted order  
- Mac users are recommended to use the provided cloud-based lab environment, as Oracle SQL Developer is not natively supported on macOS  

---

## Dataset Overview

The dataset used in this project contains transactional records from a fictional business domain, which may include fields such as:

- `customer_id`
- `transaction_date`
- `purchase_amount`
- `product_category`
- `location`
- `payment_method`

This structured dataset enables in-depth analysis of trends, categorizations, and performance indicators.

---

## Agenda of the Project

This is the **fourth project** in the SQL series. While the previous project focused on subqueries, `GROUP BY`, and `EXISTS`, this project emphasizes **advanced query techniques** such as:

- **WITH clause** for modular query building  
- **CASE statements** for flexible data labeling  
- Difference between `COUNT(*)` vs `COUNT(column)`  
- Use of **HAVING** to filter aggregated results  
- Implementing **inline views** to simplify deeply nested logic  
- Limiting results using **ROWNUM**  

Each concept is grounded in **real-world business scenarios** like customer segmentation, sales performance ranking, and product trend analysis.

---

## Sample Use Cases

- Categorize purchases into "Low", "Medium", and "High" spenders using `CASE`  
- Use `WITH` clause to create temporary grouped data before final filtering  
- Filter categories with average purchases above a certain threshold using `HAVING`  
- Use `EXISTS` to check customer activity across multiple tables  
- Apply `ROWNUM` to identify top 10 most frequent buyers  

---

## Project Link

[SQL Project Part 4: Advanced Data Analysis with Oracle SQL Developer](https://www.projectpro.io/project-use-case/sql-project-for-beginners-to-practice-using-oracle-db-using-sql-functions)

---

## Next Steps

- Extend the project by introducing **window functions** and **analytical SQL**
- Explore **stored procedures and functions** for reusable logic
- Create **views and materialized views** for report generation
- Integrate SQL queries with Python or BI tools for visualization
