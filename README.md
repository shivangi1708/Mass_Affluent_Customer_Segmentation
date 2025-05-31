# 🧠 Mass Affluent Customer Segmentation & Strategy Dashboard

This project demonstrates a full-cycle customer segmentation and insight generation workflow using **Python for data preparation** and **Power BI for dashboard development**, simulating a **Mass Affluent strategy** used in financial services.

---

## 🔍 Project Overview

The goal of this project is to identify and analyze customer segments—particularly high-value "Mass Affluent" groups—based on demographic, behavioral, and financial attributes. The dashboard enables dynamic filtering and strategy simulation, providing actionable insights for customer targeting, product positioning, and growth potential.

---

## 📊 Tools & Technologies

- **Python (Pandas)** – Data cleaning, feature engineering
- **Power BI** – Interactive dashboard creation
- **K Means Algorithm (ML)** – Groups customer into different clusters
- **DAX** – Custom KPIs and dynamic calculations
- **Power Query** – Data modeling and transformation

---

## Data Preparation and Clustering (Python)

- Cleaned customer records (e.g., missing values, date formats, type casting)
- Filtered out deceased customers
- Engineered features:
  - `Is_Mass_Affluent_Custom` flag
  - Age buckets (`Age_Group`)
  - `High_Potential_Flag` for young + wealthy customers

---

## Dashboard Creation (Power BI)

### 📄 **Page 1: Customer Segment Overview**
- Pie chart: % of customers by Cluster
- Bar charts: Avg. property valuation & purchases by Cluster
- KPI cards: Total customers, Total Mass Affluent
- Slicers: State, Job Industry

### 📄 **Page 2: Segment Demographics**
- Boxplot: AGE by Cluster
- Treemap: Job Industry by Cluster
- Stacked chart: Car ownership by Cluster
- Slicers: Age group, Mass Affluent flag

### 📄 **Page 3: Mass Affluent Strategy Insights**
- Map: Customer distribution by State/Postcode
- Scatter plot: AGE vs Property Valuation by Cluster
- KPI cards: % Mass Affluent per Cluster, Avg. tenure

---

## 📈 Key Insights

- Identified high-potential customer segments combining age, valuation, and tenure
- Enabled dynamic exploration of customer behavior by location, wealth, and industry
- Simulated real-world business intelligence use case aligned with financial sector strategy

---

## 📁 Files Included

- `Mass_Affluent_Customer_Dashboard.pbix` – Power BI visualization file
- `customer_data_cleaned.csv` – Cleaned dataset (optional)
- `data_preprocessing.py` – Python script for data cleaning & feature engineering

---

