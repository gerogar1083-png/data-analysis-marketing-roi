# 📊 Data Analysis – Marketing ROI

## 📌 Project Overview

This project focuses on analyzing marketing performance data to evaluate the return on investment (ROI) of different traffic sources and campaigns. Using Python and data analysis techniques, the goal is to identify which channels generate the highest value, which underperform, and how marketing budget allocation could be optimized based on data-driven insights.

The analysis is oriented toward **business decision-making**, not just data exploration, and reflects a typical real-world marketing analytics scenario.

---

## 🎯 Business Objective

* Evaluate the effectiveness of different marketing sources
* Understand user behavior from visit to purchase
* Identify high- and low-performing channels using ROI-related metrics
* Provide actionable recommendations for marketing budget allocation

---

## 🧩 Data Description

The analysis is based on three core datasets:

* **Visits** – user sessions, traffic sources, and visit dates
* **Orders** – purchase data linked to users and dates
* **Costs** – marketing spend by source and date

📁 The original datasets are stored in `data/raw/` and represent the unmodified input data used for the analysis.

> Note: Intermediate datasets are generated dynamically during the analysis and are not stored as separate files.

---

## 🛠️ Tools & Technologies

* **Python**
* **pandas** – data manipulation
* **NumPy** – numerical operations
* **Matplotlib / Seaborn** – data visualization
* **SciPy** – statistical analysis
* **Jupyter Notebook** – analysis environment

---

## 📈 Key Metrics & KPIs

The analysis focuses on metrics commonly used in marketing and growth analytics:

* Conversion Rate
* Customer Acquisition Cost (CAC)
* Revenue per User
* Return on Marketing Investment (ROMI / ROI)
* Cohort-based performance metrics

These metrics were chosen to directly support budget and strategy decisions.

---

## 🔍 Key Findings

* Not all traffic sources contribute equally to revenue
* Some channels show strong conversion but poor ROI due to high acquisition costs
* A smaller subset of sources generates a disproportionate share of profit
* Cohort analysis reveals differences in long-term user value across channels

*(Detailed results and supporting visualizations are available in the notebook.)*

---

## ✅ Conclusions & Recommendations

* Reallocate marketing budget toward sources with consistently positive ROI
* Optimize or reduce spend on channels with negative or marginal returns
* Use cohort-level insights to evaluate long-term channel performance
* Combine ROI metrics with conversion and retention for more balanced decisions

---

## 📂 Repository Structure

```text
data-analysis-marketing-roi/
├── README.md
├── notebooks/
│   └── showz_marketing_analysis.ipynb
├── data/
│   └── raw/
│       ├── visits.csv
│       ├── orders.csv
│       └── costs.csv
├── images/
│   ├── roi_by_source.png
│   ├── cac_by_source.png
│   └── conversion_by_source.png
├── requirements.txt
└── .gitignore
```

---

## 🎓 Academic Context

This project was originally developed as part of the **TripleTen Data Analytics Program**. The analysis approach, code, and conclusions presented here are my own and have been adapted for professional portfolio use.

---

## 👤 Author

**Gerardo Rosas**
Data Analyst

