**Cricsheet Match Data Analysis Project**
A sports analytics project that processes cricket match data from Cricsheet in JSON format, stores it in a SQL database, and provides analytical insights using SQL, Python (EDA), and Power BI.

**Project Overview**

This project is based on cricket match data collected from the Cricsheet website.
The aim is to download match data for Test, ODI, T20, and IPL formats, store it in a SQL database, and perform analysis using SQL queries, Python EDA, and Power BI dashboards.

**Objectives**

Collect cricket match data in JSON format from Cricsheet.
Convert the data into structured Pandas DataFrames.
Store the data in MySQL/TiDB database tables.
Write SQL queries to get meaningful insights.
Perform EDA using Python visualization libraries.
Create interactive dashboards in Power BI.

**Technologies used:**

- **Languages:** Python, SQL
- **Database:** MySQL / TiDB
- **Libraries:** Pandas, JSON, Matplotlib, Seaborn, Plotly
- **Tools:** MySQL Workbench, Power BI, Visual Studio

**Project Steps:**
-Data Collection
Download JSON files for Test, ODI, T20, and IPL matches from Cricsheet.

-Data Processing
Convert JSON data to Pandas DataFrames and handle missing values.

-Database Creation
Create separate tables in SQL for each match format and other required entities.

-Data Insertion
Insert processed data into the database using Python scripts.

-SQL Analysis
Write 20 analytical queries for different insights.

-EDA using Python
Use Matplotlib, Seaborn, and Plotly to create visual charts.

-Power BI Dashboard
Connect SQL database to Power BI and create an interactive dashboard.

-Deliverables
SQL database with match and delivery-level data

-20 SQL queries with results

-Python EDA with multiple charts

-Power BI dashboard

-Project documentation

**Python EDA:**

- Run: `eda/eda_analysis.ipynb`
- Tools: Matplotlib, Seaborn, Plotly
- Plots: Run distribution, dismissal types, win margins, team comparison

**Power BI**

- File: `powerbi/cricsheet_dashboard.pbix`
- Interactive: Filters for format, team, year
- Graphs: Bar, line, pie charts for KPIs

