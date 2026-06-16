# 📊 Retenza — Telecom Customer Churn Analytics

> A 6-page interactive Power BI report for analyzing telecom customer churn across India, built under the **Retenza Analytics Suite** brand.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blueviolet?style=for-the-badge)
![Pages](https://img.shields.io/badge/Report%20Pages-6-9B59B6?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🚨 The Problem

> **India's telecom sector loses billions annually to customer churn — and most operators can't see it coming.**

With four major players — Reliance Jio, Airtel, Vodafone, and BSNL — competing for 244K+ customers across every Indian state, even a 1% shift in churn rate translates to thousands of lost customers per month. Most telecom managers lack a unified, visual tool to understand *who* is churning, *where*, *when*, and *why*.

**Retenza** solves this by combining **demographic analysis**, **geographic intelligence**, **provider benchmarking**, and **predictive risk scoring** into a single, beautiful 6-page Power BI dashboard that decision-makers can explore interactively.

---

## 🌐 Live Demo

Explore the fully interactive dashboard here — no sign-in required:

🔗 **Live Power BI Report:** [Click to Open Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjc0Mzk2MTUtODBhYi00OTJkLTg1NDEtMGMyZWJkNzczNmEwIiwidCI6ImUxNGU3M2ViLTUyNTEtNDM4OC04ZDY3LThmOWYyZTJkNWE0NiIsImMiOjEwfQ%3D%3D)

> Use the **left sidebar navigation** to switch between pages (Dashboard → Customers → Churn → Telecom → Geography → Predictions) and the **top slicers** to filter by Telecom Partner, Gender, or State.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📊 **KPI Cards** | Total Customers, Churned Customers, Churn Rate %, Avg Data Usage at a glance |
| 📅 **Trend Analysis** | Monthly churn rate trends broken down by telecom partner across the full year |
| 🗺️ **India Map Visuals** | State-level customer distribution and churn risk across all Indian states |
| 🌳 **Treemaps** | Churned customers and churn by telecom partner — spot the outliers instantly |
| 🎀 **Ribbon Chart** | Telecom partner ranking shifts month-over-month |
| 📉 **Anomaly Flagging** | Visual identification of months with spike-level churn rates |
| 🔮 **Churn Predictions** | Year-over-year churn prediction trend (2020–2023) with risk categorization |
| 🎮 **Cross-Page Slicers** | Filter everything by Telecom Partner, Gender, State, or Risk level |
| 🌙 **Polished UI** | Retenza-branded purple/pink gradient theme with icon-based sidebar navigation |

---

## 📁 Report Pages

### 1. 🏠 Dashboard
The executive summary — KPIs and the most important visuals in one view.

| KPI | Value |
|-----|-------|
| Total Customers | 244K |
| Churned Customers | 49K |
| Churn Rate % | 20% |
| Avg Data Usage | 4.99K |

**Visuals:** Churn Rate % by Year & Month (area chart) · Churned Customers by State (treemap) · Telecom Partner Ranking by Month (ribbon chart) · Churn by Telecom Partner (donut) · Customer Count by Gender (pie) · Geographic Distribution (India map) · Churn Rate by Age Group (bar)

**Slicers:** Telecom Partner · Gender · State

---

### 2. 👥 Customers
Customer acquisition trends and demographic breakdown.

**Visuals:** Monthly Acquisition Trend (multi-line) · Total Customers gauge (244K vs 220K target) · Distribution by Gender (146K Male · 98K Female) · Distribution by Age Group · Customers by Telecom Partner (donut)

**Slicers:** Telecom Partner · Gender

---

### 3. 📉 Churn Analysis
Deep-dive into who churns, when, and which provider loses the most.

**Visuals:** Monthly Churn Rate by Telecom Partner (multi-line, 19–22% range) · Overall Churn Rate gauge (20.05%) · Churn by Age Group (bar: 46–60 highest) · Churn by Gender (29K Male · 20K Female) · Churn by Telecom Partner (treemap)

**Slicers:** Telecom Partner · Gender

---

### 4. 📡 Telecom Analytics
Provider-level benchmarking across data, calls, and SMS engagement.

**Visuals:** Monthly Data Usage Trend by Partner (line) · Avg Calls Made (Reliance Jio 49.20 · BSNL 49.04 · Airtel 49.02 · Vodafone 48.78) · Market Share (donut) · Avg SMS Sent by Partner (column) · Data Usage vs Calls Made (bubble chart)

**Slicers:** Telecom Partner · State

---

### 5. 🗺️ Geography
State-level churn intelligence across India.

**Visuals:** Customer Distribution Map (India filled map) · Customer Count by State (bar: West Bengal · Uttarakhand top) · Churn Rate % by State (Jharkhand · Karnataka highest) · Overall Market Share (donut) · Churned Customers by State (treemap)

**Slicers:** Telecom Partner · Gender

---

### 6. 🔮 Predictions
Forward-looking churn risk scoring with year-over-year trends.

**Visuals:** Monthly Churn Prediction Trend 2020–2023 (multi-line) · Overall Churn Risk gauge (20.0%) · Customer Count by Risk Category (195K Low Risk · 49K High Risk) · State-wise Churn Risk Map · Predicted Churn by Telecom Partner (donut)

**Slicers:** Telecom Partner · Risk

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------| 
| **Power BI Desktop** | Report development, layout, and publishing |
| **Power Query (M)** | Data transformation, type casting, column shaping |
| **DAX** | KPI measures (churn rate %, risk scoring, MoM trends) |
| **Power BI Service** | Publishing & public embed via Publish to Web |

---

## 📂 Dataset Details

- **Domain:** Indian Telecom (synthetic dataset)
- **Records:** ~244,000 customer rows
- **Telecom Partners:** Reliance Jio · Airtel · Vodafone · BSNL
- **Geographic Scope:** Pan-India — all major states with churn granularity
- **Time Range:** 2020–2023 (monthly)
- **Key Fields:** `customer_id` · `gender` · `age_group` · `state` · `telecom_partner` · `churn_flag` · `data_usage_mb` · `calls_made` · `sms_sent` · `join_date` · `churn_risk_category`

---

## 🚀 How to Use

### View Online (Recommended)
Click the live demo link above — no Power BI account needed.

### Run Locally

1. Clone this repository
   ```bash
   git clone https://github.com/KunalAnand7222/Telecom-Customer-Churn-Analytics.git
   cd Telecom-Customer-Churn-Analytics
   ```

2. Open the `.pbix` file in **Power BI Desktop**
   ```
   Retenza_Churn_Analysis.pbix
   ```

3. If prompted, update the data source path under:
   **Home → Transform Data → Data Source Settings**

4. Click **Refresh** and explore all 6 pages using the left sidebar

---

## 📸 Screenshots

### 📊 Dashboard
![Dashboard](screenshots/01_dashboard.png)

---

### 👥 Customers
![Customers](screenshots/02_customers.png)

---

### 📉 Churn Analysis
![Churn Analysis](screenshots/03_churn.png)

---

### 📡 Telecom Analytics
![Telecom Analytics](screenshots/04_telecom.png)

---

### 🗺️ Geography
![Geography](screenshots/05_geography.png)

---

### 🔮 Predictions
![Predictions](screenshots/06_predictions.png)

> 📁 Add your screenshots to a `/screenshots` folder and the images will appear above automatically.

---

## 📈 Key Insights

- The overall churn rate is **~20%**, consistent across all four telecom partners — pointing to structural industry-wide issues rather than provider-specific failures
- **Age group 46–60** has the highest churn volume, suggesting older customers are more price-sensitive or service-quality-driven
- **Jharkhand and Karnataka** lead in state-level churn rate, indicating regional retention campaigns are needed
- All four providers maintain nearly identical average call volumes (~49 calls/month), meaning churn is **not driven by usage** — plan pricing and customer service are likely the real drivers
- **49K customers (20%)** fall into the high-risk churn category, giving retention teams a clear, actionable target segment

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change or improve.

---

## 📄 License

This project is for educational and portfolio purposes. The dataset used is synthetic.

---

<p align="center">
  📊 <strong>Retenza Analytics Suite</strong> — Turning telecom churn data into retention strategy. 🇮🇳
</p>
