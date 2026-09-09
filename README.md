# 🛢️ SQL Learning Journey - Udemy

Welcome to my learning repository! This project compiles the code, exercises, and queries developed throughout my journey of learning SQL from scratch, based on a specialized course on Udemy.

The goal of this repository is to consolidate SQL fundamentals and serve as evidence of the practical application of data analysis and business intelligence (BI) skills.

---

## 📚 About the Course

* **Course:** The Complete SQL Bootcamp (30 Hours): Go from Zero to Hero
* **Instructor:** Baraa Khatib Salkini
* **Platform:** Udemy
* **Level:** Initial / From Scratch

---

## 🧠 Topics Learned

During this course, I acquired and practiced fundamental concepts of SQL, including:

* **Introduction to SQL:** Learn what SQL is, why it matters, how databases work, and how to set up your full SQL environment.
* **Querying Data (SELECT):** Master SELECT, FROM, WHERE, GROUP BY, HAVING, ORDER BY, DISTINCT, TOP, and query execution order.
* **Data Definition (DDL):** Create, modify, and remove database objects using CREATE, ALTER, and DROP commands.
* **Data Manipulation (DML):** Add, update, and delete records using INSERT, UPDATE, and DELETE with real-world logic.
* **Filtering Data:** Use comparison and logical operators like AND, OR, NOT, BETWEEN, IN, and LIKE to filter data effectively.
* **Combining Data:** Join and merge tables using INNER, LEFT, RIGHT, FULL, CROSS joins and SET operations like UNION, INTERSECT.
* **Row-Level Functions:** Use string, numeric, date, null-handling functions, and CASE expressions to transform your data.
* **Aggregation & Analytics:** Apply aggregate functions and advanced window functions like RANK, DENSE_RANK, LAG, and LEAD.
* **Advanced SQL Techniques:** Work with subqueries, CTEs (recursive and non-recursive), views, temp tables, procedures, and triggers.
* **Performance Optimization:** Improve query speed using indexes, partitions, and practical performance tips.
* **AI & SQL:** Use ChatGPT and GitHub Copilot to generate, explain, optimize, and debug SQL — plus translate and document code.

---

## 🛠️ Final Projects

The following describes the two final exercises—queries created from scratch—that integrate the knowledge acquired during the course:

### 1. SQL for Data Analysis (EDA) 
**Use SQL to perform exploratory data analysis on real datasets, extracting insights and creating reports as a data analyst would.**
  
    01_database_exploration
    02_dimensions_exploration
    03_date_range_exploration
    04_measures_exploration
    05_magnitude_analysis
    06_ranking_analysis

### 2. Advanced Query Optimization
**Tackle complex query challenges and practice performance tuning on large datasets to simulate high-pressure, real-world scenarios.**
  
    07_change_over_time_analysis
    08_cumulative_analysis
    09_performance_analysis
    10_part_to_whole_analysis
    11_data_segmentation
    12_report_customers_view
    13_report_products_view
    14_report_customers_query
    15_report_products_query
---
## 🚀 How to Execute the Script Queries

To test any of the queries locally, make sure you have SQL Server Management Studio 22 installed and follow these steps:

- Download or clone the code: Click the green "Code" button on GitHub and copy the link to use `git clone [URL]` in your terminal, or download the ZIP file.

- Once the files (datasets, docs, scripts) have been downloaded, activate the database as follows to review the query scripts:
  
#1 Option: Creating a new Database  

    In SQL Server Management Studio 22:   
    A) Create a new database.  
    B) Select the new database and execute a new query to create a schema named "gold".  
    C) Import the following flat files located in the datasets folder; make sure to select the "gold" table schema:
    - dim_custumers.csv
    - dim_products.csv
    - fact_sales.csv  
    D) You can now test any of the queries located in the scripts folder (1. SQL for Data Analysis (EDA) / 2. Advanced Query Optimization).

#2 Option: Restoring Database using file.bak  

    In SQL Server Management Studio 22:  
    A) Create a new database
    B) Restore the DataWarehouseAnalytics.bak database, a file located in the datasets folder.
    C) You can now test any of the queries located in the scripts folder (1. SQL for Data Analysis (EDA) / 2. Advanced Query Optimization).
---
## ✉️ Contact

If you would like to connect with me or view more details about my professional profile:

LinkedIn: https://www.linkedin.com/in/alberto-carcache-pallais/

GitHub: @albertocarcache
