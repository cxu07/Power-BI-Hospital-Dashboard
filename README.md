# 🏥 Healthcare Encounters – Power BI Dashboard
  -- A healthcare analytics case study demonstrating SQL-validated metrics and Power BI dashboard design.
  
-This Power BI dashboard analyzes **healthcare encounter data** from Maven Analytics to address key business questions related to encounter trends, costs, insurance coverage, and patient readmissions.
Readmission and length-of-stay (LOS) logic were validated using **SQL (CTEs and window functions)** prior to implementation in **DAX**.

---

## 📊 Dashboard Structure

The report is organized into **three pages**, each aligned with a specific analytical objective.

---

### 1. Encounters Overview
- Total encounters by year  
- Distribution of encounter classes (%)  
- Encounters lasting over vs. under 24 hours  
- 📷 [Encounter Overview](./Encounter%20Overview.jpg)

---

### 2. Cost & Coverage Insights
- Zero vs. non-zero payer coverage  
- Top procedures by encounter frequency and average cost  
- Procedures with the highest average base cost  
- Average total claim cost by payer  
- 📷 [Cost & Coverage Analysis](./Cost_coverage.jpg)

---

### 3. Patient Behavior Analysis
- Unique patients admitted by quarter  
- Patients readmitted within 30 days  
- Top patients by number of readmissions  
- 📷 [Patient Behavior Analysis](./patients_behavior.jpg)

---

## ⬇️ Download Dashboard
- 📥 [Download Power BI Dashboard (.pbix)](https://github.com/cxu07/Power-BI-Hospital-Dashboard/raw/main/Hospital_Analysis_Dashboard.pbix)
- Open the `.pbix` file using **Power BI Desktop** to explore interactive visuals, slicers, and drill-down functionality.

---

## 🗂️ Data Source
The dataset used in this project is **synthetic healthcare data** provided by **Maven Analytics**, including patient encounters, procedures, healthcare organizations, and payer information.

- 🔗 [Maven Analytics – Healthcare Sample Data](https://www.mavenanalytics.io/data-playground)

---

## 🛠️ Tools & Skills Demonstrated
- Power BI (data modeling, DAX, visual design)  
- SQL-based data preparation and validation  
- KPI design and healthcare analytics insights  
