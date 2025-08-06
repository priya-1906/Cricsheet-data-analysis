Cricsheet Match Data Analysis Project

A sports analytics project that processes cricket match data from Cricsheet in JSON format, stores it in a SQL database, and provides analytical insights using SQL, Python (EDA), and Power BI.

 Project Overview

This project focuses on analyzing historical cricket match data for four major international formats: Test, ODI, T20, IPL . The data is sourced from [Cricsheet](https://cricsheet.org/) and includes both match-level and delivery-level information.


- Parse JSON files (Test, ODI, T20, IPL)
- Insert them into structured MySQL tables
- Analyze using 20+ SQL queries
- Perform EDA using Python (Matplotlib, Seaborn, Plotly)
- Build Power BI dashboards for interactive insights

Technologies used:

- **Languages:** Python, SQL
- **Database:** MySQL / TiDB
- **Libraries:** Pandas, JSON, Matplotlib, Seaborn, Plotly
- **Tools:** MySQL Workbench, Power BI, Visual Studio


Match-Level Data Insertion
`insert_test_matches.py`
`insert_odi_matches.py`
`insert_t20_matches.py`
`insert_ipl_matches.py`

 Extracts `info` section  
 Handles optional fields like `city`, `event`, `match_number`  
 Skips already inserted matches using `match_id`

 Delivery-Level Data Insertion
- `insert_deliveries.py`  
✔️ Inserts ball-by-ball records  
✔️ Supports all formats  
✔️ Skips duplicates  
✔️ Graceful error handling with reconnection logic

SQL Queries (20+)

Queries include:
- Top run-scorers per format
- Bowlers with most wickets
- Matches with highest scores
- Toss impact on winning
- Win margins analysis
- Team performance across formats
- Batsman vs bowler insights



Python EDA:
- Run: `eda/eda_analysis.ipynb`
- Tools: Matplotlib, Seaborn, Plotly
- Plots: Run distribution, dismissal types, win margins, team comparison

 Power BI:
- File: `powerbi/cricsheet_dashboard.pbix`
- Interactive: Filters for format, team, year
- Graphs: Bar, line, pie charts for KPIs

