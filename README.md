# 📊 SQL Capstone: HR Attrition Analysis

This capstone project analyzes employee attrition data using **SQL** with **SQLite3** in Python. The project simulates a real-world data engineering scenario where raw HR data is cleaned, structured into a relational database, and queried to derive insights into employee turnover patterns.

---

## 🧾 Project Overview

**Objective**: To understand patterns and drivers of employee attrition through structured SQL queries and exploratory analysis on HR data.

**Key Deliverables**:
- Create and populate a normalized relational database using SQLite
- Write SQL queries to extract meaningful attrition trends
- Perform grouped analysis (by Department, Job Role, Age, etc.)
- Document analytical insights in Markdown within Jupyter notebooks

---

## 🧰 Tools & Technologies

- **SQL** (SQLite3)
- **Python** (for automation and integration)
- **Pandas** (for data loading and formatting)
- **Jupyter Notebook** (for analysis and explanation)

---

## 📁 Files Included

| File Name                     | Description                                  |
|------------------------------|----------------------------------------------|
| `SQL_Capstone_1_Part_1.ipynb` | Data ingestion, table creation, normalization |
| `SQL_Capstone_1_Part_2.ipynb` | SQL queries for grouped analysis & insights  |

---

## 🔧 Project Breakdown

### ✅ Part 1: Database Creation
- Loaded raw HR dataset
- Created a normalized relational schema
- Defined primary/foreign keys
- Inserted data using Python & SQLite

### ✅ Part 2: Attrition Analysis
- Queried attrition rates by:
  - Job Role
  - Department
  - Age group
  - Education field
- Calculated and visualized aggregate statistics
- Used SQL joins, group-by, and filters

---

## 📊 Key Insights

- Certain job roles like **Sales Representative** and **Laboratory Technician** showed higher attrition.
- **Younger employees** (under 30) had noticeably higher turnover.
- Attrition varied significantly across **Departments** and **Education Fields**.

---

## 🧠 Skills Demonstrated

- SQL table design and schema normalization
- Writing complex SQL queries with GROUP BY, JOIN, and filtering
- Automating SQL workflows using Python
- Communicating insights clearly via Markdown and visualization

---

## 🏷 Tags

`sql` `sqlite3` `data-engineering` `hr-analytics` `attrition-analysis`  
`python-sql` `relational-database` `data-analysis` `capstone-project`

---

## 📌 Future Enhancements

- Integrate visualizations via matplotlib or seaborn
- Export SQL results to dashboards (e.g., Tableau, Power BI)
- Build automated reports using Python scripts
