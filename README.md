# 📊 Lead Scoring Data Analysis & Interactive Dashboard (Power BI)

## 📌 Project Overview
An end-to-end data analytics portfolio project built in **Power BI Desktop** analyzing **9,240 customer lead records**[cite: 3]. This project evaluates acquisition channel performance, candidate demographics, conversion rates, and course motivators to assist sales and marketing optimization[cite: 3].

---

## 🔑 Key Analytical Insights
* **Primary Acquisition Channels:** **Google** leads channel volume with **2.87K leads (31.04%)**[cite: 3], followed by **Direct Traffic** (**2.54K leads / 27.52%**)[cite: 3] and **Olark Chat** (**1.755K leads / 18.99%**).
* **High-Converting Referral Channel:** While **Reference leads** account for 534 total leads[cite: 3], they deliver an exceptional **91.76% conversion rate**.
* **Demographic Target Group:** **85.94% of categorized leads (5,600 leads)** are **Unemployed** candidates seeking career transition[cite: 3], followed by **Working Professionals (10.83% / 706 leads)**[cite: 3].
* **High-Intent Working Professionals:** **Working Professionals** show a **91.64% conversion rate**, highlighting them as the most qualified segment for premium enrollments.
* **Core Motivator:** Over **99.9% of responsive candidates** select **"Better Career Prospects"** as their primary reason for choosing a course[cite: 3].

---

## 🛠️ Data Engineering & Power Query Pipeline
* **Data Cleaning & Standardization:** Used **Power Query (M Engine)** to map missing (`null`), blank, and placeholder inputs (`"Select"`) to standardized `"N/A"` labels[cite: 3].
* **Data Modeling & Calculations:** Modeled relationship schemas and created calculated measures for lead counts and conversion rates across categories[cite: 3].
* **Visual Interface:** Built single-metric **Card visual callouts**[cite: 3], clustered bar charts, demographic pie charts[cite: 3], and responsive slicers for dynamic filtering.

---

## 📁 Repository Structure
```text
├── Lead_Scoring.csv                    # Raw dataset (9,240 rows × 37 columns)
├── Lead_Scoring_Analysis.pbix          # Master Power BI Desktop report
├── Lead_Scoring_Template.pbit          # Lightweight Power BI template file
├── Lead_Scoring_Data_Analysis_Final.pdf # Exported PDF analysis report
└── README.md                           # Project documentation
