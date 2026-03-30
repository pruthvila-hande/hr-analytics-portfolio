Overview
Interactive Power BI dashboard analysing employee attrition
patterns using the IBM HR Analytics dataset (1,470 employees)

Tools Used
- SQL (window functions, RANK, PARTITION BY, aggregations)
- Power BI (DAX measures, Power Query, dashboard design)
- DB Browser for SQLite

Key Findings
- Overall attrition rate: 16.12%
- Sales had highest attrition at 20.63%
- Sales Representatives had 39.76% attrition
- Employees earning under 3K/month left at 3x the rate
  of those earning over 10K/month
- Low satisfaction score (1) drove 22.2% attrition vs
  11.3% for high satisfaction (4)

DAX Measures Used
- COUNTROWS, CALCULATE, DIVIDE, AVERAGE
- RANKX, ALL, VAR, IF

SQL Queries
- Overall attrition rate calculation
- Attrition by department and job role
- Salary band analysis
- Job satisfaction analysis
- Advanced window functions (RANK, PARTITION BY)

Files
- attrition_queries.sql — all SQL queries
- dashboard_screenshot.png — dashboard preview
- Workforce_Attrition_Dashboard.pbix — Power BI file
