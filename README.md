# Data Analytics & SQL Projects – Alex Bootcamp  

This repository contains a collection of projects I completed as part of **Alex Bootcamp**, focusing on real-world applications of **data analysis, cleaning, and visualization**. Each project highlights how I transformed raw datasets into meaningful insights using **SQL, Python, and Excel**.  

---

## Projects  

### 1. **Correlation Analysis – Python (Jupyter Notebook)**  
- **Techniques Used:**  
  - Data preprocessing with Pandas.  
  - Correlation matrix to identify relationships between numerical variables.  
  - Heatmaps and scatterplots using Matplotlib and Seaborn for visual interpretation.  
- **Insights Gained:**  
  - Identified variables that had the strongest linear correlations (e.g., positive correlations where one variable increased along with another).  
  - Highlighted weak or negligible correlations, helping filter out features that may not add predictive value in a model.  
- **Impact:** Improved feature selection approach for further predictive modeling tasks.  

---

### 2. **COVID-19 Data Exploration – SQL**  
- **Techniques Used:**  
  - Aggregate functions (SUM, MAX, CAST) to measure infection and death counts.  
  - Window functions and **CTEs** to calculate rolling vaccination percentages.  
  - Temp tables and Views for modular, reusable queries.  
- **Insights Gained:**  
  - Death rates varied drastically across countries; the U.S. maintained a death-to-case ratio between 1–3% at peak periods.  
  - Countries with high populations (e.g., India, Brazil, U.S.) showed disproportionate infection percentages compared to smaller nations.  
  - Vaccination rollouts had clear correlations with reduced growth in new cases over time.  
  - Continent-level analysis revealed that Europe and North America carried the highest cumulative death counts.  
- **Impact:** This analysis simulated how health organizations could monitor infection trends, prioritize vaccine distribution, and measure effectiveness over time:contentReference[oaicite:0]{index=0}.  

---

### 3. **COVID-19 Excel Dashboard – Excel**  
- **Techniques Used:**  
  - Data transformation with Excel functions (IF, VLOOKUP).  
  - Pivot tables and slicers for interactive filtering.  
  - Charts (line, bar, pie) for comparative visuals.  
- **Insights Gained:**  
  - Visualized infection peaks during specific pandemic waves.  
  - Tracked country-level vaccination rates and compared them to infection outcomes.  
  - Identified lag times between vaccination efforts and observed declines in mortality.  
- **Impact:** Created a dashboard that a non-technical healthcare operations team could use for daily monitoring and presentations.  

---

### 4. **Nashville Housing Data Cleaning – SQL**  
- **Techniques Used:**  
  - Standardization of dates with `CONVERT()`.  
  - Address parsing with `SUBSTRING()`, `CHARINDEX()`, and `PARSENAME()`.  
  - Data normalization by fixing inconsistent entries (`Y/N` → `Yes/No`).  
  - Duplicate removal using **ROW_NUMBER()** within CTEs.  
  - Column pruning to eliminate redundant fields:contentReference[oaicite:1]{index=1}.  
- **Insights Gained (Post-Cleaning):**  
  - Cleaner dataset enabled more reliable trend analysis on house sales.  
  - Duplicate removal ensured accurate aggregation for pricing trends.  
  - Address normalization allowed deeper geographic insights (city-level breakdowns).  
- **Impact:** Produced an analytics-ready housing dataset that could feed into BI dashboards and appraisal models.  

---

### 5. **SQL Data Cleaning & Exploration Scripts**  
- **Data Cleaning.sql:**  
  - Focused on removing duplicates, standardizing inconsistent entries, and ensuring referential data integrity.  
- **Data Exploration.sql:**  
  - Applied advanced queries with joins, aggregations, and conditional filters.  
  - Designed queries to uncover anomalies and detect mismatches across datasets.  
- **Impact:** Demonstrated how SQL can be used not just for reporting but also for **data engineering and quality assurance**.  

---

## Skills Demonstrated  
- **SQL:** Aggregations, Joins, CTEs, Window Functions, Temp Tables, Views, Data Cleaning.  
- **Python:** Pandas for preprocessing, Seaborn/Matplotlib for visualization, correlation analysis.  
- **Excel:** Pivot Tables, Slicers, Charting, Data Transformation.  
- **Data Cleaning & Transformation:** Handling missing values, normalizing categorical values, removing duplicates, structuring semi-clean datasets.  

---

## Project Files  
- `Correlation Project (1).ipynb` – Python correlation analysis.  
- `CovidDeathsinfo.xlsx`, `CovidVaccinationsinfo.xlsx` – Excel datasets for COVID-19 analysis.  
- `Nashville Housing Data for Data Cleaning.xlsx` – Housing dataset.  
- `Data Exploration.sql` – SQL queries for COVID-19 analysis.  
- `Data Cleaning.sql` – SQL queries for housing dataset cleaning.  

---

## Learning Outcome  
Through these projects, I built end-to-end experience in:  
- Cleaning messy, real-world datasets.  
- Writing complex SQL queries for exploration and reporting.  
- Using Python and Excel to visualize patterns and correlations.  
- Translating raw data into actionable insights that could drive real business or public health decisions.  

These projects represent the foundation of my **data analytics skill set**, preparing me for **data analyst, business intelligence, and data engineering roles**.  

---
