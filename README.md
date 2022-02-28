# SCD_2_Implementation

![database](https://user-images.githubusercontent.com/100192347/155979704-6660e240-7bb8-4082-98df-d980194123bc.jpg)


**Introduction**: 

A company X wants to keep its employee data up to date in their central database.  
Since, over the time, many employees prefer to change their base location, it is essential to update the employee information in the company's central database. 
 
**Problem Statement:**

The field 'Location' is a Slowly changing Dimension (  a dimension whose attribute or attributes for a record (row) change slowly over time). We will be using SCD-2 type implementation to keep a full history of dimension data in the table. The Type 2 Dimension mapping filters source rows based on user-defined comparisons and inserts both new and changed dimensions into the target. Changes are tracked in the target table by looking up the primary key and creating a version number for each dimension in the table called a surrogate key.  
 
**ETL Process:**

We are sourcing the data from MS SQL Server, transforming it using Informatica and loading it to Oracle server.

**ETL Process:**

We are sourcing the data from MS SQL Server, transforming it using Informatica and loading it to Oracle server.

**Source table in MySQL server:**

![image](https://user-images.githubusercontent.com/100192347/155979863-a3ab2cd5-2df7-4b33-b9d7-6fa41799e1af.png)

**Target table in Oracle:**

![image](https://user-images.githubusercontent.com/100192347/155979889-a728cce3-c5fb-4cff-8b33-5baea4e8be06.png)


