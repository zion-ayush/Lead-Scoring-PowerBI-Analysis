# 📊 Lead Scoring Data Analysis & Interactive Dashboard (Power BI)

## 📌 Project Overview
An end-to-end data analytics portfolio project built in **Power BI Desktop** analyzing **9,240 customer lead records**[cite: 3]. This analysis focuses specifically on core acquisition channels: **Google**, **Reference**, and **Direct Traffic** to evaluate channel efficiency, candidate demographics, and high-conversion segments[cite: 3].

---

## 🔑 Key Analytical Insights
* **Google Acquisition Volume:** **Google** is the leading acquisition channel overall, accounting for **2.87K leads (31.04% share)** with **1,147 conversions (39.99% conversion rate)**[cite: 3].
* **Direct Traffic Channel:** **Direct Traffic** represents **2.54K leads (27.52% share)** and yields **818 conversions (32.17% conversion rate)**[cite: 3].
* **High-Converting Reference Channel:** **Reference leads** deliver the highest conversion performance by far, generating **490 conversions out of 534 leads (91.76% conversion rate)**[cite: 3].
* **Core Channel Comparison:** While **Google** and **Direct Traffic** drive the bulk of inbound lead volume (~58.5% combined)[cite: 3], **Reference leads** convert at nearly 3x the rate of organic/direct channels[cite: 3].

---

## 🛠️ Data Engineering & Power Query Pipeline
* **Data Cleaning & Standardization:** Standardized raw inputs, missing values (`null`), and `"Select"` placeholders across Google, Direct, and Reference channel records using **Power Query (M Engine)**[cite: 3].
* **Channel Metrics Calculation:** Modeled DAX measures to isolate volume, conversion counts, and conversion percentages across target channels[cite: 3].
* **Visual Dashboards:** Constructed comparative bar charts and card callouts dedicated to core acquisition streams[cite: 3].

---

## 📁 Repository Structure
```text
├── Lead_Scoring.csv                     # Raw dataset (9,240 rows × 37 columns)
├── Lead_Scoring_Analysis_v3.pdf         # Channel analysis report (Google, Reference, Direct)
├── Lead_Scoring_Template.pbit           # Lightweight Power BI template file
├── Lead_Scoring_Data_Analysis_Final.pdf # Technical dashboard preview PDF
└── README.md                            # Project documentation
