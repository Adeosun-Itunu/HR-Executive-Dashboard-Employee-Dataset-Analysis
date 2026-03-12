# HR-Executive-Dashboard-Employee-Dataset-Analysis

## Project Overview

This project presents an end-to-end HR data analysis built entirely in Microsoft Excel. Starting from a raw employee dataset, I cleaned the data, built structured PivotTables, calculated custom business measures, and assembled a single-page HR Executive Dashboard designed for C-suite and HR leadership consumption.

# The goal was to answer three core business questions:
* Which job roles deliver the most revenue per dollar of salary paid?
* How is workforce headcount and salary cost distributed across global regions?
* Who are the top-performing employees, and how cost-efficient are each region's operations?

  ## Dataset Overview

The dataset contained 1,000 active employee records with these key fields: Employee ID, Employee Name, Job Title, Region, Annual Salary, Total Sales, and Active Status.
The 10 job titles were: Software Engineer, Product Manager, Business Analyst, Accountant, Marketing Manager, Data Analyst, Operations Manager, Sales Executive, Data Scientist, and HR Officer.
The 7 regions were: Australia, Europe, North America, Latin America, South Asia, East Asia, and Middle East.

## Tools & Process

I used Microsoft Excel exclusively PivotTables, Calculated Fields, Conditional Formatting, and embedded charts.

Step 1 — Data Import & Inspection: Loaded the raw CSV into Excel and checked for nulls, duplicate IDs, and data type inconsistencies.
Step 2 — Data Cleaning: Standardized column headers, formatted Salary and Sales as currency, filtered to Active employees only (confirmed 1,000 records), and removed trailing whitespace in text fields.
Step 3 — PivotTable Construction: Built separate PivotTables for salary efficiency by role, top 5 employees by sales, total sales by region, headcount by region, and salary-to-sales ratio by region.
Step 4 — Measure Calculation: Defined calculated fields and formulas for all KPIs.
Step 5 — Dashboard Assembly: Arranged all charts and KPI cards on a dedicated Dashboard sheet with a dark background and green accent palette.

## Measures & Calculated Fields

Total Sales = SUM of all sales values. Result: $251,266,044.
Average Sales per Employee = Total Sales divided by count of active employees. Result: $251,256. This is the productivity benchmark for the workforce.
Total Salary Cost = SUM of all annual salaries. Result: $112,603,352. This is the total annual payroll and underpins all efficiency ratios.
Median Salary = MEDIAN of the salary range. Result: $112,282. The near-identical mean ($112,603) and median confirm a symmetric salary distribution with no extreme outliers.
Salary Efficiency Ratio = Total Sales for a role divided by Total Salary Cost for that role. Example — HR Officer generates $2.48 in revenue for every $1 spent on their salary. This is the most important measure in the dashboard.
Salary-to-Sales Ratio (Regional) = Regional Salary Cost divided by Regional Sales, expressed as a percentage. Example — North America is 47%, Middle East is 43%. Lower percentage means the region is more cost-efficient.

## Key Findings

Salary Efficiency by Job Title, ranked from highest to lowest return per $1 of salary:
HR Officer ($2.48), Data Scientist ($2.44), Sales Executive ($2.38), Operations Manager ($2.37), Data Analyst ($2.22), Marketing Manager ($2.19), Accountant ($2.14), Business Analyst ($2.14), Product Manager ($2.06), Software Engineer ($1.88).
Insight: HR Officers and Data Scientists deliver the highest revenue return per salary dollar. Software Engineers post the lowest ratio, likely because their contribution is infrastructure-oriented rather than directly revenue-generating.
Top 5 Employees by Total Sales:
Olivia White ($24,964,813), Sophia Taylor ($24,653,931), Sara Ahmed ($23,454,211), Michael Brown ($22,242,975), Ali Khan ($21,546,845).
Insight: The gap between #1 and #5 is about $3.4M — a narrow band that suggests balanced productivity among top performers.
Total Sales by Region:
Australia ($39,436,193), Europe ($37,556,687), Latin America ($36,638,814), South Asia ($35,344,315), East Asia ($35,315,168).
Insight: Australia leads in total sales despite not having the largest headcount, pointing to above-average individual productivity in that region.
Employee Count by Region:
Australia (159), Europe (149), North America (147), Latin America (147), South Asia (138), East Asia (137), Middle East (123).
Salary-to-Sales Ratio by Region:
North America (47%), Australia (45%), Europe (45%), South Asia (44%), East Asia (44%), Latin America (44%), Middle East (43%).
Insight: All regions cluster between 43–47%, showing globally consistent cost efficiency. Middle East is the most cost-efficient region.

## Limitations

Sales figures are treated as directly attributable to individuals, but in practice team collaboration may be involved. Salary efficiency ratios don't account for indirect contributions — roles like Software Engineers support revenue without generating it directly. No tenure, performance ratings, or department-level cost data was available. Regional cost-of-living differences are not factored in. All analysis is based on a single fiscal snapshot with no time-series comparison.

## Skills Demonstrated

Data cleaning and type standardization, Excel PivotTables and Calculated Fields, SUM/COUNT/MEDIAN formulas and ratio calculations, data visualization with bar charts and KPI cards, business framing of salary efficiency as an ROI metric, dashboard design with layout hierarchy and color theming, and structured technical documentation.

