# Healthcare Encounters – Power BI Dashboard

This Power BI dashboard analyzes healthcare encounter data (Maven Analytics) to answer defined business questions related to encounter trends, costs, coverage, and patient readmissions.

## Dashboard Structure

The report is organized into three pages, each aligned to a specific analytical objective.

### 1. Encounters Overview
- Total encounters by year
- Encounter class distribution (%)
- Encounters over vs under 24 hours
- [Encounter Overview](./Encounter%20Overview.jpg)


### 2. Cost & Coverage Insights
- Zero vs non-zero payer coverage
- Top procedures by frequency and average cost
- Procedures with highest average base cost
- Average total claim cost by payer
- [Payer Cost Analysis](./Cost_coverage.jpg)



### 3. Patient Behavior Analysis
- Unique patients admitted by quarter
- Patients readmitted within 30 days
- Top patients by number of readmissions
- [Patient Behavior Analysis](./patients_behavior.jpg)


## Download Dashboard
- [Download Power BI Dashboard (.pbix)](https://github.com/cxu07/Power-BI-Hospital-Dashboard/raw/main/Hospital_Analysis_Dashboard.pbix)
>Open the `.pbix` file using **Power BI Desktop** to explore interactive visuals, slicers, and drill-down capabilities.

## Data Source
The dataset used in this project is **synthetic healthcare data** provided by Maven Analytics and includes patient encounters, procedures, organizations, and payer information.

- [Maven Analytics – Healthcare Sample Data](https://www.mavenanalytics.io/data-playground)

## Tools & Skills Demonstrated
- Power BI (Data Modeling, DAX, Visual Design)
- SQL-based data preparation concepts
- KPI design, analysis insights for executive and operational stakeholders
