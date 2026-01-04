# -Healthcare-Visitor-Analytics-Dashboard-Power-BI-
This project presents an interactive Power BI dashboard designed to analyze hospital visitor data and uncover meaningful trends that support data-driven decision-making in healthcare environments.By leveraging Power Query, DAX, and SQL, the dashboard provides actionable insights .
# 🏥 Healthcare Visitor Analytics Dashboard (Power BI)

Introduction

This project presents an interactive Power BI dashboard designed to analyze hospital visitor data and uncover meaningful trends that support data-driven decision-making in healthcare environments.

By leveraging Power BI, Power Query, DAX, and SQL, the dashboard provides actionable insights into visitor demographics, visit patterns, wait times, satisfaction levels, and departmental engagement. These insights help healthcare professionals optimize resources, improve operational efficiency, and enhance patient care quality through business intelligence.

---

Project Objectives

- Analyze hospital visitor trends across time (daily, monthly, quarterly, yearly)
- Identify peak visiting periods and operational bottlenecks
- Explore demographic patterns (age, gender, race)
- Evaluate patient satisfaction and waiting times
- Support healthcare management with KPI-driven insights

---

Key Technologies and Skills

- Power BI
- Power Query Editor (ETL and Data Transformation)
- Data Analysis Expressions (DAX)
- SQL (KPI and Aggregation Queries)
- Excel
- Data Modeling and Visualization

---

Dataset Description

The healthcare dataset includes the following key fields:

| Column Name | Description |
|------------|-------------|
| Date | Visit date |
| ID | Unique visitor identifier |
| Gender | Visitor gender |
| Age | Visitor age |
| Race | Visitor race |
| Moment | AM / PM visit time |
| Weekday/Weekend | Day type |
| Admin Flag | Patient / Non-Patient |
| Department Referral | Medical department |
| Wait Time | Waiting time in minutes |
| Satisfaction Score | Patient satisfaction rating |

These features enable comprehensive analysis of visitor behavior, service usage, and operational performance.

---

Data Preprocessing (ETL)

Data preparation was performed using the Power Query Editor, following best practices in ETL:

- Data Normalization  
  Tables were split to improve structure, clarity, and relational modeling

- Missing Value Imputation  
  Missing or inconsistent values were handled to maintain data integrity

- Data Cleaning  
  Standardized formats for dates, categories, and numerical fields

This ensured the dataset was reliable, consistent, and analysis-ready.

---

Data Modeling and DAX Calculations

- Relationships were established between dimension and fact tables
- DAX measures were created for:
  - Total Visitors
  - Average Wait Time
  - Satisfaction Score
  - Visit Growth Rates
  - Demographic Percentages
- These calculations enabled flexible filtering and drill-down analysis across visuals

---

Key Insights and Features

Visit Trends

- Daily Visits show a gradual increase throughout the month, peaking in the final week
- Monthly Visits increase significantly from April to October, indicating seasonal impact
- Yearly Visits show a 5.8 percent growth from 2019 to 2020
- Quarterly Visits indicate that Q2 and Q3 are 53.9 percent busier than Q1 and Q4

---

Time-Based Distribution

- AM vs PM visits are nearly equal, with a slight 0.6 percent preference for AM
- Visits peak on Mondays and Wednesdays and are lowest on Fridays
- Weekday visits are 148.83 percent higher than weekend visits

---

Wait Time Analysis

- The average wait time is approximately 35 minutes
- 90.9 percent of visitors wait between 20 and 60 minutes
- Only 9.1 percent experience short waits of 10 to 20 minutes, highlighting opportunities for service improvement

---

Demographic Insights

- Age groups from 0 to 75 show balanced visit frequencies, while visitors aged 75 and above account for only 5.04 percent
- White and African American visitors form the majority, reflecting a diverse patient population
- Male visitors outnumber female visitors by 4.86 percent

---

Satisfaction and Departmental Insights

- The average satisfaction score is 5 out of 10, indicating a neutral overall perception
- General Practice and Orthopedics account for 30.75 percent of referrals
- Non-referred visitors represent 58.67 percent of total visits
- Registered patients make up 50.04 percent of visitors, while non-patients account for 49.96 percent

---

Dashboard Features

- Interactive slicers for date, department, and demographics
- KPI cards for high-level performance monitoring
- Line, bar, donut, and trend visuals
- Drill-down capabilities for detailed analysis

---

How to Use

1. Download or clone this repository  
2. Open the PBIX file using Power BI Desktop  
3. Refresh the data if needed  
4. Explore insights using interactive filters and visuals  

---

Contributing

Contributions are welcome.  
If you would like to improve visuals, optimize DAX measures, or add predictive analytics, feel free to fork the repository and submit a pull request.

---

License

This project is licensed under the MIT License and is free to use, modify, and distribute with attribution.

---

Contact

Author: Mehrnaz Mostafavi  
Email: your email here  
LinkedIn: your LinkedIn profile  
Portfolio: optional  

If you have questions, feedback, or collaboration ideas, feel free to reach out.
