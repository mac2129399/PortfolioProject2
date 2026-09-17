Clinical Trial Protocol Deviation Analysis (2026)

Overview:
This project looks at protocol deviations from a small, synthetic clinical trial dataset. I used Python, SQL, and Tableau Public to explore patterns in the data and create visual dashboards.

My goal was to practice:
  1. Working with real‑world style clinical data
  2. Running SQL queries
  3. Using pandas for analysis
  4. Creating charts with seaborn
  5. Building a clean Tableau dashboard


Tools Used
  1. Python: pandas, seaborn, matplotlib
  2. SQL: SQLite
  3. Tableau Public: creating my dashboard

Synthetic Dataset
File: Protocol_Deviation_Table.csv  
Rows: 50
Sites: 10
Cities: 10

Each record includes:
Site ID,
Location,
Date,
Deviation Type (Major/Minor),
Category,
Visit,
Notes


Questions I Answered
1. Which locations had the most deviations?
2. How many major vs minor deviations were there?
3. Which categories happened the most?
4. Which sites had the most major deviations?
5. Which visits had the most issues?
6. How did deviations change month‑to‑month?

Key Findings
  1. March 2026 had the most deviations.
  2. Minor deviations were more common than major ones.
  3. Week 8 had the highest number of issues.
  4. Out‑of‑window visits and missing labs were the top categories.
  5. SITE02, SITE05, and SITE08 had the most major deviations
  6. All 10 cities had the same total number of deviations (5 each).

Tableau Dashboard

Page 1 - Overview & Trends
  Monthly deviation trend
  Major vs minor comparison
  Deviations by visit
  Summary KPIs
  Key findings
  Seaborn charts
  
Page 2 - Site Performance
  Major deviations by site
  Total deviations by site
  Category counts
  Filters for deviation type and category
  Tableau charts
