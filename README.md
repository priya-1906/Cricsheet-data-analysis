**Project Overview**
This project uses cricket match data collected from the Cricsheet website.
The goal is to download match data for Test, ODI, T20, and IPL formats, store it in a SQL database, and perform analysis through SQL queries, Python EDA, and interactive dashboards in Power BI.

**Objectives**
>Collect cricket match data in JSON format from Cricsheet.
>Convert the data into structured Pandas DataFrames.
>Store the data in MySQL/TiDB database tables.
>Write SQL queries to generate meaningful insights.
>Perform Exploratory Data Analysis (EDA) using Python visualization libraries.
>Build interactive Power BI dashboards for visual storytelling and decision-making.

**Technologies Used**
Languages: Python, SQL
Database: MySQL / TiDB
Libraries: Pandas, JSON, Matplotlib, Seaborn, Plotly
Tools: MySQL Workbench, Power BI, Visual Studio

**Project Workflow**
>Data Collection
Download JSON files for Test, ODI, T20, and IPL matches from Cricsheet.

>Data Processing
Convert JSON data to Pandas DataFrames.
Handle missing/null values.

>Database Creation
Create separate SQL tables for each match format (test_matches, odi_matches, t20_matches, ipl_matches) and a deliveries table for ball-by-ball data.

>Data Insertion
Insert processed data into the database using Python scripts.

>SQL Analysis
Write and execute 20 analytical queries for cricket statistics and trends.

>EDA using Python
Use Matplotlib, Seaborn, and Plotly for visual insights such as run distribution, dismissal types, win margins, and team comparisons.

>Power BI Dashboard
Connect SQL database / exported CSV files to Power BI.
Create interactive dashboards with filters for Format, Team, and Year.
Visuals include:
  -Total Matches by Format & Year
  -Top Run Scorers
  -Top Wicket Takers
  -Venue Analysis
  -Toss Decision vs Match Result

**Python EDA**
Run: eda/eda_analysis.ipynb
Tools: Matplotlib, Seaborn, Plotly
Plots: Run distribution, dismissal types, win margins, team performance comparisons.

**Power BI Dashboard**
File: powerbi/cricsheet_dashboard.pbix
Export: PDF version for sharing: powerbi/cricsheet_dashboard.pdf
Features:
  -Filters: Format, Team, Year
  -Graph Types: Bar, Line, Pie, KPI Cards
  -Interactive drill-down by format and player
  -Relationship between matches and deliveries for detailed ball-by-ball insights
