# UK Study & Work Visa Analysis

**Data-driven analysis of UK study and work visa applications using SQL Server and Power BI**

---

## Project Overview

This project analyzes historical UK visa application data to understand trends, nationality patterns, and visa outcomes for both study and work categories. The goal is to transform raw government data into actionable insights using **SQL Server** for data management and **Power BI** for interactive dashboards.

**Key highlights:**
- Analysis of visa applications between 2010–2024 (study) and 2010–2023 (work)
- Insights on top nationalities, institutions, industries, and visa outcomes
- Interactive dashboards with filters and KPIs for data exploration
- Cleaned and transformed datasets ready for visualization

---

## Folder Structure

```
uk-visa-study-work-analysis/
│
├── research-paper/
│ └── UK_Study_Work_Visa_Analysis.pdf
│
├── dataset/
│ ├── study-visa/
│ │ ├── Study_Sponsorship.xlsx # original raw data
│ │ ├── study_by_institution.xlsx # cleaned dataset
│ │ └── study_by_nationality.xlsx # cleaned dataset
│ └── work-visa/
│ ├── Work_Sponsorship.xlsx # original raw data
│ ├── work_by_industry.xlsx # cleaned dataset
│ └── work_by_nationality.xlsx # cleaned dataset
│
├── sql/
│ └── analysis_queries.sql # SQL queries for cleaning and analysis
│
├── powerbi/
│ ├── uk_visa_dashboard.pbix
│ └── dashboard_screenshots/
│ └── Dashboard.png
```


## Datasets

### Study Visa
- `Study_Sponsorship.xlsx` – original raw dataset  
- `study_by_institution.xlsx` – cleaned dataset aggregated by institution  
- `study_by_nationality.xlsx` – cleaned dataset aggregated by nationality  

### Work Visa
- `Work_Sponsorship.xlsx` – original raw dataset  
- `work_by_industry.xlsx` – cleaned dataset aggregated by industry  
- `work_by_nationality.xlsx` – cleaned dataset aggregated by nationality  

---

## SQL Scripts

- `visa_analysis.sql` – SQL queries for cleaning, transforming, and analyzing the datasets  

---

## Power BI Dashboard

The project dashboard is created in Power BI. The `.pbix` file is available for download:

- `uk_visa_dashboard.pbix` – interactive dashboard  
- `dashboard_screenshots/kpi_overview.png` – snapshot of key KPIs  
- `dashboard_screenshots/nationality_trends.png` – snapshot of nationality trends  

---

## Key Insights

- Study visa applications have increased steadily over the years, with top nationalities being **China** and **India**  
- Work visa applications are most common in **IT, healthcare, professional services, and education**  
- Visa outcome analysis shows **stable approval trends**, with extensions increasing over time  
- Power BI dashboard allows **interactive exploration** of visa trends by year, nationality, institution, and industry  

---

## Technologies Used

- **SQL Server** – data storage, cleaning, and transformation  
- **Power BI** – interactive dashboards and visualization  
- **Excel** – dataset preparation and intermediate cleaning  

---

## How to Use

1. Download the repository or individual files  
2. Open the `.pbix` file in Power BI Desktop to explore the dashboards  
3. Review SQL scripts in the `sql` folder to see data cleaning and analysis steps  
4. Explore the raw and cleaned datasets in the `dataset` folder for additional analysis  
5. Read the research paper in `research-paper/` for detailed methodology and insights  

---

## Authors / Team Members

**Chamali Abeysekara**  
BSc in Applied Data Science Communication  
Advanced SQL and Cloud Databases  

**Team Members / Contributors:**  
- Muhammed Nasir  
- Hussein Ziyard  
- Rajintha Lakshani  

---

## Acknowledgements

Special thanks to all team members for their support and contributions to this project.

