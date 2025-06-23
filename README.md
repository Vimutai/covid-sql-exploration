# 🧪 COVID-19 Data Exploration with SQL

**Project Type:** SQL Querying · Data Exploration · Analysis  
**Tools Used:** Microsoft SQL Server Management Studio (SSMS)  
**Dataset:** COVID deaths and vaccinations data (global)

## 🔍 Overview

This project explores global COVID-19 trends using SQL. I used SQL Server to write queries for exploring infection rates, death rates, and vaccination rollouts by country, continent, and globally.

## 🧠 Key Analysis Tasks

- Total cases vs deaths by country (death likelihood)
- Infection % by population
- Death % by continent
- Highest infection/death regions
- Rolling total vaccinations using `OVER(PARTITION BY...)`
- CTEs and temporary tables for population vs vaccination
- View creation for dashboard-ready outputs

## 🧰 SQL Concepts Used

- Filtering with `WHERE`, `LIKE`, `IS NULL`  
- Aggregation: `SUM()`, `MAX()`, `GROUP BY`, `ORDER BY`  
- Calculated fields with percentages  
- Common Table Expressions (CTEs)  
- Temp tables: `CREATE TABLE`, `DROP TABLE IF EXISTS`  
- Views for reusability  
- Joins on `location` and `date`

## 📁 Files Included

- `covid_data_exploration.sql` – Full cleaned SQL script  
- `README.md` – Project description  
- `screenshots/` *(optional)* – Visuals from SSMS (charts or query output)

## ✅ Key Learnings

- Hands-on practice in transforming raw COVID data using SQL  
- Real-world use of JOINs, window functions, and table creation  
- Writing reusable, readable queries for data analysis

## 🖼️ SQL Highlights

**1. Kenya Death Percentage Calculation**  
![Kenya Death %](screenshots/death_percentage_kenya.png)

**2. Highest Infection % by Country**  
![Infection %](screenshots/infection_rate_population.png)

**3. CTE – Rolling Vaccination Count**  
![Vaccination CTE](screenshots/cte_rolling_vaccinations.png)

**4. Temporary Table for Vaccinations**  
![Temp Table](screenshots/temp_table_vaccinations.png)

**5. Global Summary Metrics**  
![Global Summary](screenshots/global_summary.png)




---

📌 *Dataset sourced from publicly available COVID-19 repositories. Project built for learning and portfolio purposes.*
