# 🗄️ SQL Retail & Sales Data Analysis Project

This project was completed during a **Data Technician Bootcamp** and focuses on analysing structured datasets using **SQL and relational databases**. The objective was to extract meaningful insights from **retail and sales data** by writing queries that filter, sort, aggregate, and combine information from multiple tables.

The project demonstrates how SQL can be used to transform raw data stored in relational databases into **actionable business insights** through structured queries.

---

## 🚀 Project Overview

In this project, SQL was used to:

- Query and explore relational databases
- Filter and organise datasets to answer business questions
- Combine multiple tables using **JOIN operations**
- Aggregate data to generate summaries and reports
- Analyse customer, product, and sales information

These queries support typical **data analysis workflows** used in business environments such as retail analytics and reporting.

---

## 🛠️ SQL Skills Demonstrated

### Data Retrieval

Used `SELECT` statements to retrieve specific data from database tables.

Examples include:

- Retrieving full datasets for reporting
- Selecting specific columns for targeted analysis
- Extracting unique values from datasets

Example query:

```sql
SELECT CustomerName, City
FROM Customers;
```

---

### Data Filtering

Used the `WHERE` clause to filter datasets based on specific conditions, such as:

- Product price thresholds
- Customer locations
- Date-based filtering for orders

Example:

```sql
SELECT *
FROM Products
WHERE Price > 50;
```

---

### Sorting and Organising Data

Used `ORDER BY` to organise query results for easier analysis and reporting.

Example:

```sql
SELECT *
FROM Orders
ORDER BY OrderDate DESC;
```

This allows analysts to quickly identify **recent activity or top-performing records**.

---

### Aggregation and Grouping

Used `GROUP BY` with aggregate functions to summarise datasets.

Examples include:

- Counting products within categories
- Summarising sales quantities
- Calculating totals and averages

Example:

```sql
SELECT CategoryName, COUNT(ProductID) AS TotalProducts
FROM Products
GROUP BY CategoryName;
```

---

### Table Relationships and JOINs

Combined data from multiple related tables using **JOIN operations** to create comprehensive reports.

Types of joins used include:

- **INNER JOIN** – retrieve matching records between tables
- **LEFT JOIN** – include all records from one table and matched records from another
- Understanding of **RIGHT JOIN, FULL JOIN, and CROSS JOIN** concepts

Example:

```sql
SELECT p.ProductName, c.CategoryName, s.SupplierName
FROM Products p
JOIN Categories c ON p.CategoryID = c.CategoryID
JOIN Suppliers s ON p.SupplierID = s.SupplierID;
```

This query combines product, category, and supplier data into a single report.

---

## 📊 Data Analysis Applications

SQL queries were used to analyse datasets such as:

- Customer information
- Product catalogues
- Order history
- Supplier and category relationships

Example analysis tasks included:

- Identifying **high-value products**
- Reviewing **recent orders**
- Counting products by category
- Analysing **sales volumes and product demand**
- Combining multiple tables to generate detailed reports

---

## 📁 Databases Used

The project used sample relational databases including:

- **Northwind database** (sales and retail dataset)
- **World database** for additional query practice
- Custom relational database design exercises

These datasets simulate real-world scenarios involving **customers, orders, products, suppliers, and geographic data**.

---

## 🎯 Learning Outcomes

Through this project I developed practical skills in:

- Writing SQL queries for data analysis
- Filtering and sorting data using SQL clauses
- Aggregating data using grouping functions
- Combining datasets with JOIN operations
- Understanding relational database structures and relationships

---

## 🧠 Tools Used

- **MySQL Workbench**
- **SQL (Structured Query Language)**
- Relational database design concepts

---

## 💡 Project Purpose

This project demonstrates how SQL is used to extract insights from relational databases. It highlights foundational **data analysis and database querying skills** that are essential for roles such as:

- Data Technician  
- Data Analyst  
- Business Intelligence Analyst  

The project showcases the ability to **retrieve, analyse, and combine structured data to support business decision-making**.

---

## Examples of Codes ran

### City with the Lowest Population
<img width="459" height="283" alt="image" src="https://github.com/user-attachments/assets/b2d981f2-8fa7-433d-9d49-90f81d38962d" />

### Capital of Spain
<img width="459" height="227" alt="image" src="https://github.com/user-attachments/assets/06639103-d394-42f4-b521-bfb498be8cc3" />

### Average Population by Country
<img width="459" height="324" alt="image" src="https://github.com/user-attachments/assets/88dd1f6e-a043-486f-a5cf-a5efdb907ef9" />

### Countries with Low Population Density
<img width="459" height="264" alt="image" src="https://github.com/user-attachments/assets/313b5f46-e607-4649-b0f6-eb1bc6907e1c" />

---





