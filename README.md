# 📊 Customer Shopping Behavior Analysis

## 📌 Overview

This project presents an end-to-end data analytics solution focused on understanding customer purchasing behavior and generating actionable business insights. Using **Python, SQL, and Power BI**, the project follows a structured approach commonly adopted by data teams to transform raw transactional data into meaningful intelligence.

The goal is to enable better decision-making by identifying patterns in customer behavior, product performance, and revenue contribution.

---

## 🎯 Business Objectives

The analysis is designed to address key business questions:

- Which customer segments contribute the most revenue?
- Do subscription-based customers generate higher value?
- Which products receive the highest ratings?
- How do discounts influence purchasing behavior?
- What trends exist across demographics and purchase frequency?

---

## 🧩 Project Workflow

This project follows a clear and industry-relevant analytics pipeline:

### 1. Data Collection
- Source: CSV-based customer transaction dataset  
- Includes demographic, transactional, and product-level data  

### 2. Data Preparation (Python)
- Data cleaning and validation  
- Handling missing and inconsistent values  
- Feature engineering:
  - Age segmentation (Young, Middle-aged, Senior)
  - Conversion of purchase frequency into numeric values  

### 3. Data Analysis (SQL)
- Revenue analysis by customer demographics  
- Customer segmentation:
  - New (1 purchase)  
  - Returning (2–10 purchases)  
  - Loyal (11+ purchases)  
- Evaluation of:
  - Subscription impact  
  - Discount effectiveness  
  - Product performance  
- Use of advanced SQL concepts such as aggregations and CTEs  

### 4. Data Visualization (Power BI)
- Interactive dashboard for business insights  
- Dynamic filtering by:
  - Gender  
  - Category  
  - Subscription status  
  - Shipping type  
- KPI tracking and trend analysis  

---

## 📊 Key Insights

- **Loyal customers drive the majority of revenue**, highlighting strong retention.
- **Subscribers contribute consistent revenue** through frequent purchases.
- **Discounts significantly influence buying decisions**, especially across key categories.
- **Shipping preferences are driven by convenience**, not spending behavior.

---

## 📈 Dashboard Highlights

- Revenue distribution by category and age group  
- Customer segmentation insights  
- Average purchase value and product ratings  
- Sales trends and purchase patterns  
- Interactive filters for deeper exploration  

---

## 💡 Business Recommendations

- Strengthen loyalty programs to retain high-value customers  
- Promote top-rated products to leverage customer satisfaction  
- Apply targeted discount strategies rather than blanket promotions  
- Expand subscription benefits to increase repeat purchases  

---

## 🛠️ Tech Stack

- **Python (Pandas)** – Data cleaning and transformation  
- **SQL (MySQL)** – Data analysis and querying  
- **Power BI** – Visualization and dashboard development  

---

## 📂 Repository Structure

```bash
├── data/
│   └── customer_shopping_behavior.csv
├── sql/
│   └── analysis_queries.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
├── report/
│   └── project_report.pdf
└── README.md
```

---

## 🚀 Conclusion

This project demonstrates how a structured analytics approach can convert raw data into valuable insights that support strategic business decisions. By integrating data preprocessing, analytical querying, and visualization, it highlights the importance of data-driven thinking in improving customer engagement and overall business performance.
