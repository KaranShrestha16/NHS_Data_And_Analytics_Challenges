
# 🧠 NHS Step Up Challenge – Mental Health Prescribing Analysis (Python Path)

> A real-world healthcare data project using Python & NHS open data to explore trends in antidepressant prescriptions across England.

---

## 🟠 Project Overview

This project was part of the **NHS Step Up Career Challenge**, where participants acted as public health analysts to explore **4 years of longitudinal antidepressant prescribing data** using Python. The goal was to derive meaningful insights that can support NHS policy decisions and improve patient care.

---

## 🧠 Concept Overview

The challenge focused on understanding:
- **Volume vs. Cost** of antidepressants
- **Regional disparities** in prescribing behavior
- **Monthly & yearly prescribing trends**
- Identifying potential **cost-efficiency opportunities** for NHS decision-makers

Key concepts applied:
- Exploratory Data Analysis (EDA)  
- Time-series analysis  
- Data visualization  
- Insight generation for public health  

---

## 🧾Data Overview & Preparation

Data Source:  
📂 `BSA_ODP_PCA_REGIONAL_SUMMARY.csv` – provided by NHS England via the [NHS Open Data Portal](https://opendata.nhsbsa.net/dataset/prescription-cost-analysis-pca-monthly-data)

Columns:
- `YEAR`: Year of prescription
- `YEAR_MONTH`: Period in YYYYMM format
- `REGION`: NHS region
- `DRUG`: Antidepressant name
- `ITEMS`: Number of prescribed items
- `COST`: Total cost of prescriptions

Steps:
- Loaded data from GitHub repo
- Converted dates, handled nulls, and normalized column types
- Aggregated data by region, drug, and date for trend analysis

---

## 💻 Application

Libraries Used:
- `pandas` for data wrangling
- `matplotlib`, `seaborn` for visualizations
- `Jupyter Notebook` for documentation and exploration

Key Techniques:
- Grouping and aggregating prescriptions by region/drug
- Calculating total cost and volume
- Visualizing top 10 drugs by cost and items
- Time-series plotting of prescription trends

---

## 📊 Analyzing The Results

### 🔍 Key Insights:
- **Sertraline**: Most prescribed drug across all regions.
- **Duloxetine & Vortioxetine**: High-cost drugs with relatively low volume.
- **Midlands** and **North West**: Highest in overall prescription volume.
- **Post-2021 trend**: Significant increase in prescribing, reflecting rising mental health needs.

### 📈 Visuals Included:
- Top 10 drugs by volume and cost
- Regional prescribing heatmaps
- Monthly trend line charts
- Cost-volume mismatch comparisons

---

## 📈 Growth & Next Steps

If given more time, I would:
- Apply ARIMA/Prophet for **forecasting future prescription trends**
- Create a **dashboard** using Plotly/Dash or Power BI
- Explore **demographic-level data** (if available) for deeper segmentation
- Integrate **NHS policy interventions** to assess impact

---

## 🤝 Let's Connect


📧 karanxhrestha@gmail.com
