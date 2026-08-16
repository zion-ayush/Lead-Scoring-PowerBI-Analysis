# 📊 Lead Scoring Data Analysis & Interactive Dashboard (Power BI)

## 📌 Project Overview
An end-to-end data analytics project using **Power BI Desktop** and **Power Query** to analyze **9,240 lead records**. This interactive dashboard provides actionable insights into customer acquisition channels, target demographics, missing data handling, and conversion dynamics to help optimize marketing funnel performance[cite: 3].

---

## 🔑 Key Analytical Insights
* **Lead Acquisition Channels:** Out of **9.24K total leads**[cite: 3], **Google** leads channel volume with **2.87K leads (48.3% of primary web channels)**[cite: 3], followed by **Direct Traffic** with **2.54K leads (42.7%)**[cite: 3] and **Reference** with **534 leads (9.0%)**[cite: 3].
* **High-Converting Referral Leads:** While direct web channels generate the bulk of top-of-funnel traffic[cite: 3], **Reference leads** demonstrate an exceptional conversion rate of **91.76%**.
* **Demographic Segmentation:** **85.94% of categorized leads (5,600 leads)** are **Unemployed** individuals seeking career upskilling[cite: 3], followed by **Working Professionals (10.83% / 706 leads)**[cite: 3] and **Students (3.23% / 210 leads)**[cite: 3].
* **Working Professional High Intent:** **Working Professionals** show a conversion rate of **91.64%**, making them the most valuable target group for premium course conversions.
* **Primary Motivator:** Over **99.9% of candidates** specifying a motivation select **"Better Career Prospects"** as their main reason for enrolling[cite: 3].

---

## 🛠️ Data Engineering & Power Query Pipeline
* **Data Hygiene & Standardization:** Applied **Power Query (M Engine)** transformation rules to handle missing (`null`), blank, and default form values (`"Select"`) by categorizing them cleanly as `"N/A"` to prevent visual aggregation skew[cite: 3].
* **Data Modeling:** Modeled field relationships and optimized column data types for dynamic slicer cross-filtering across channels and occupation segments[cite: 3].
* **Visual Interface:** Designed standard single-metric **Card visuals** for clean summary headlines[cite: 3], paired with styled column charts, pie charts, and interactive slicers[cite: 3].

---

## 📁 Repository Structure
```text
├── Lead_Scoring.csv                 # Raw dataset (9,240 rows × 37 attributes)
├── Lead_Scoring_Analysis.pbix       # Master Power BI Desktop report file
├── Lead_Scoring_Data_Analysis_2.pdf # PDF export of the interactive dashboard
└── README.md                        # Comprehensive project documentation
