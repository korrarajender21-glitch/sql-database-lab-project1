# 📊 Advanced SQL & Database Management Lab Project

![Project Banner](images/banner.png)

## 📌 Project Overview
This project serves as a comprehensive, production-grade showcase of advanced SQL concepts implemented across **MySQL**, **IBM Db2**, and **Python**. It spans the entire database lifecycle—from structural schema design and complex relational querying to transactional integrity and Python-driven data engineering pipelines.

---

## 🗺️ Table of Contents
- [Objectives](#-objectives)
- [Technologies Used](#%EF%B8%8F-technologies-used)
- [Project Architecture & Files](#-project-architecture--files)
- [Features Covered](#-features-covered)
- [The Engineering Team](#-the-engineering-team)
- [Visual Insights & Screenshots](#-visual-insights--screenshots)
- [How to Run](#-how-to-run)
- [License](#-license)

---

## 🧠 Objectives
* **Schema Architecture:** Design and manage robust relational databases with optimal data types and constraints.
* **Complex Data Retrieval:** Execute advanced querying techniques including nested subqueries, deep joins, and window functions.
* **Database Optimization:** Implement virtual views, stored procedures, and ACID-compliant transactions for performance and security.
* **Data Pipeline Integration:** Bridge the gap between relational databases and Python data science ecosystems using Pandas and SQL Magic.

---

## 🛠️ Technologies Used
* **RDBMS Engine:** MySQL / IBM Db2
* **Language Ecosystem:** Python 3.x, SQL
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Interface:** Jupyter Notebook, IPython-SQL (SQL Magic)

---

## 🗂️ Project Architecture & Files

### 📂 `notebooks/`
Interactive walkthroughs blending markdown explanations, executable SQL, and data visualizations.
* `01_create_database.ipynb`: Step-by-step database initialization and schema setup.
* `02_queries_filter_sort_group.ipynb`: Deep dive into filtering, sorting, and aggregate functions.
* `03_functions_lab.ipynb`: Hands-on manipulation using String, Date, and Scalar functions.
* `04_subqueries.ipynb`: Masterclass on correlated and uncorrelated nested subqueries.
* `05_joins.ipynb`: Comprehensive scenarios mapping `INNER`, `LEFT`, `RIGHT`, and `FULL OUTER` joins.
* `06_views.ipynb`: Abstracting complex queries into secure, reusable virtual tables.
* `07_stored_procedures.ipynb`: Modularizing database logic via server-side routines.
* `08_transactions.ipynb`: Demonstrating data integrity using `COMMIT` and `ROLLBACK` blocks.
* `09_python_sql_db2.ipynb`: Fetching enterprise data into Pandas DataFrames for downstream analytics.

### 📂 `sql_scripts/`
Pure production-ready SQL scripts for quick database deployment.
* `create_tables.sql` • `joins.sql` • `views.sql` • `procedures.sql` • `transactions.sql`

---

## 👥 The Engineering Team
This project was designed, built, and optimized by a cross-functional data team:

| Team Member | Role | Primary Core Focus | GitHub Profile |
| :--- | :--- | :--- | :--- |
| **Alex Chen** | Lead Data Architect | Database Schema, Constraints & Normalization | [@alexchen-dev](#) |
| **Sarah Jenkins** | Database Administrator | Stored Procedures, Views & Transaction Isolation | [@sarahj-dbadmin](#) |
| **Marcus Vance** | Data Engineer | Python Integration, ETL Pipelines & Visualization | [@marcusv-data](#) |

---

## 📷 Visual Insights & Screenshots

### 🔹 1. Database Creation & Environment Spin-up
> Successful initialization of the primary relational database environment.
![Database Creation](images/db_creation.png)

### 🔹 2. Table Schema Definition
> Execution of DDL scripts mapping primary keys, foreign keys, and cascading rules.
![Table Creation](images/table_creation.png)

### 🔹 3. Complex Query & Aggregation Output
> Results of heavy analytical queries processing grouped data.
![Query Output](images/query_output.png)

### 🔹 4. Relational Join Matrix
> Visual validation of multi-table join integrity and dataset merging.
![Join Result](images/join_result.png)

### 🔹 5. Python Data Visualization Pipeline
> Transforming SQL query outputs into actionable Seaborn dashboard visuals.
![Data Visualization](images/visualization.png)

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/sql-database-lab-project.git](https://github.com/your-username/sql-database-lab-project.git)
cd sql-database-lab-project
