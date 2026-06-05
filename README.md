# SGK Labor Market Analysis

This project analyzes SGK labor market data using Excel, Power Query, SQL Server, Power BI, and Python/Pandas.

The project includes an end-to-end data analysis workflow covering data preparation, Excel dashboarding, SQL database modeling, SQL analysis queries, Power BI reporting, and Python/Pandas-based exploratory analysis.

---

## Tools Used

- Excel
- Power Query
- Pivot Tables
- SQL Server
- SQL Server Management Studio
- Power BI
- Python
- Pandas
- Jupyter Notebook
- Git & GitHub

---

## Project Structure

```text
sgk-labor-market-analysis
│
├── data
│   └── Quarterly SGK reports
│
├── excel
│   ├── images
│   ├── video
│   └── sgk_labor_market_excel_dashboard.xlsx
│
├── powerbi
│   └── SGK Power BI report files
│
├── sql
│   ├── relationship_table
│   ├── 01_create_tables.sql
│   └── 02_analysis_queries.sql
│
├── python_pandas
│   ├── 01_quarterly_baseline_analysis.ipynb
│   ├── 02_employment_by_sector_analysis.ipynb
│   ├── 03_service_production_by_sector_analysis.ipynb
│   └── 04_skill_analysis.ipynb
│
└── README.md
```

---

## Excel Dashboard

The Excel dashboard was created using Power Query and Pivot Tables.

It includes:

- Employee count analysis
- Open job count analysis
- Open job rate analysis
- Sector-based comparison
- Quarterly labor market indicators

[Watch Dashboard Demo](excel/video/dashboard-demo.mp4)

---

## SQL Analysis

The SQL part includes database modeling and analysis queries.

Main tables:

- `PERIODS`
- `SECTORS`
- `QUARTERLY_CORE_METRICS`
- `EMPLOYMENT_EXPECTATIONS`
- `PRODUCTION_EXPECTATIONS`
- `OCCUPATION_SKILL_ANALYSIS`

![SQL Relationship Diagram](sql/relationship_table/relationship_table.png)

---

## SQL Analysis Topics

The SQL queries cover:

- Sector count by period
- Duplicate record check
- Total record count by table
- Top sectors by open job count
- Top sectors by open job rate
- Employee count change by period
- Open job count change by period
- Employment expectation analysis
- Production/service expectation analysis
- Employment vs production expectation comparison
- Occupation skill analysis

---

## Key SQL Concepts Used

- `JOIN`
- `GROUP BY`
- `HAVING`
- `COUNT`
- `COUNT DISTINCT`
- `SUM`
- `AVG`
- `ABS`
- `ORDER BY`
- `TOP`
- Primary Key / Foreign Key relationships

---

## Power BI Report

The Power BI report was created to visualize SGK labor market indicators and provide an interactive reporting layer.

It includes:

- KPI cards
- Sector-based comparisons
- Period filters
- Open job indicators
- Employment expectation visuals
- Production/service expectation visuals
- Skill-related analysis pages
- Navigation and interactive report structure

---

## Python & Pandas Analysis

A Python/Pandas analysis layer was added to extend the project with notebook-based exploratory data analysis.

The following notebooks were created:

- `01_quarterly_baseline_analysis.ipynb`  
  Analyzes employee count, open job count, open job rate, open job distribution, and open jobs per 1,000 employees.

- `02_employment_by_sector_analysis.ipynb`  
  Analyzes employment expectations by sector and creates an employment outlook score.

- `03_service_production_by_sector_analysis.ipynb`  
  Analyzes service/production expectations by sector and creates a service/production outlook score.

- `04_skill_analysis.ipynb`  
  Analyzes skill scores by occupation group and identifies dominant skill categories.

The Python/Pandas analysis includes:

- Excel data loading
- Column preparation and renaming
- Data quality checks
- Missing value checks
- Duplicate row checks
- Period-level summaries
- Sector and occupation group comparisons
- Custom metrics such as outlook scores and dominant skill analysis

---

## Project Status

Completed:

- Excel dashboard
- SQL database schema
- SQL relationship model
- SQL analysis queries
- Power BI report
- Python/Pandas analysis notebooks

---

## Goal

The goal of this project is to demonstrate an end-to-end data analysis workflow:

```text
Raw Reports → Excel / Power Query → SQL Server → SQL Analysis → Power BI → Python/Pandas Analysis
```

This project was created as a portfolio project for junior data analyst and reporting analyst roles.

---

## Author

**Emre Erol**