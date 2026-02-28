 Vendor Performance Analytics Platform

## 📌 Overview

This project analyzes large-scale vendor transactional data to evaluate profitability, identify underperforming vendors, and support data-driven decision-making.

The solution integrates **SQL for data engineering**, **Python for statistical analysis and machine learning**, and **Power BI for interactive visualization**.

Total data processed: **15+ million records**

---

## 🎯 Business Objective

Retail and wholesale businesses must optimize vendor relationships to improve profitability.

This project aims to:

* Identify high and low-performing vendors
* Analyze sales vs purchase profitability
* Detect margin inefficiencies
* Predict vendor performance categories
* Support operational decision-making

---

## 🛠️ Tech Stack

* **MySQL** – Data cleaning, indexing, aggregation
* **Python** – Pandas, NumPy, Matplotlib, Seaborn
* **Scikit-learn** – Random Forest Classification
* **Power BI** – Interactive dashboard

---

## ⚙️ Project Workflow

### 1️⃣ Data Engineering (MySQL)

* Imported 15M+ sales and purchase records
* Created indexed tables for optimized performance
* Built summary tables:

  * `sales_summary`
  * `purchase_summary`
  * `vendor_performance`

### KPIs Generated:

* Total Sales
* Total Purchase
* Gross Profit
* Profit Margin

---

### 2️⃣ Exploratory Data Analysis (Python)

* Distribution analysis of vendor sales
* Profitability comparison
* Correlation analysis
* Sales vs Profit scatter visualization

---

### 3️⃣ Hypothesis Testing

Performed statistical t-test to evaluate:

> Whether high-sales vendors have significantly different profit margins compared to low-sales vendors.

---

### 4️⃣ Machine Learning Model

Implemented a **Random Forest Classifier** to predict vendor performance category:

* High Performer
* Medium Performer
* Low Performer

Model Accuracy: **~71%**

The model showed strong performance in identifying low-performing vendors.

---

### 5️⃣ Power BI Dashboard

The interactive dashboard includes:

* KPI cards (Sales, Purchase, Profit, Margin)
* Top Vendors by Sales
* Purchase Contribution %
* Low Performing Vendors
* Sales vs Profit Analysis
* Performance Category Filtering

---

## 📈 Key Insights

* A small group of vendors drives majority of revenue
* Some vendors generate high sales but low margins
* Predictive modeling helps proactively identify risk vendors
* Profitability strongly correlates with purchase cost control

---

## 🚀 Business Impact

This solution enables:

* Vendor prioritization
* Risk detection
* Cost optimization
* Predictive performance monitoring

---

## 📂 Repository Structure

```
VENDOR_ANALYTICS/
│
├── notebooks/
├── scripts/
├── DASHBOARD.pbix
├── dashboard.png
├── README.md
└── .gitignore
```

---

## 👩‍💻 Author

**Kanika**
BCA – Artificial Intelligence & Data Science
Focused on Data Analytics, Machine Learning & Business Intelligence

---

