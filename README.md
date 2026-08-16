# 📊 Lead Scoring Data Analysis & Interactive Dashboard (Power BI)

## 📌 Project Overview
An end-to-end interactive Power BI dashboard designed to analyze lead generation sources, demographic distributions, and candidate motivations. This project provides actionable insights for optimizing marketing strategies and improving lead acquisition targeting.

---

## 🔑 Key Analytical Insights
* **Primary Acquisition Channels:** Google and Direct Traffic serve as the primary growth drivers, accounting for over **91% of total lead volume** (~5.4K out of 9.24K leads).
* **Target Audience Demographics:** **85.94% of total leads** belong to the Unemployed demographic, indicating strong demand for career transitions and skill enhancement programs.
* **Course Selection Motivators:** Slicer filtering reveals that the vast majority of prospective students prioritize courses that offer improved career prospects.

---

## 🛠️ Data Engineering & Pipeline
* **Data Cleaning & Standardization:** Handled missing, blank, and default text values (`null` and `"Select"`) using **Power Query (M Engine)** by mapping them to standardized `"N/A"` labels to prevent aggregation skew.
* **Data Modeling:** Built structured field relationships and customized field data types for seamless dynamic cross-filtering.
* **Interactive Visual Canvas:** Integrated custom summary KPI cards, categorical bar charts, occupation pie charts, and responsive slicers.

---

## 📁 Repository Structure
```text
├── Lead_Scoring_Analysis.pbix       # Master Power BI Desktop report file
├── Lead_Scoring_Data_Analysis.pdf   # Exported executive analysis report
└── README.md                        # Project documentation
