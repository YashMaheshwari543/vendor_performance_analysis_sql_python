# 🚀 Vendor Performance Analysis | SQL + Python + Data Analytics

## 📌 Executive Summary

This project delivers an end-to-end Vendor Performance Analytics solution designed to evaluate supplier profitability, inventory efficiency, purchasing patterns, and sales performance.

Using SQL-based ETL pipelines, Python-driven exploratory analysis, statistical testing, and business intelligence techniques, the project transforms raw transactional data into actionable business insights that can support strategic purchasing and inventory decisions.

The objective is to help organizations identify high-performing vendors, optimize procurement strategies, reduce inventory holding costs, and maximize profitability.

---

## 🎯 Business Problem

Retail businesses often struggle to answer critical questions such as:

* Which vendors generate the highest revenue?
* Which vendors contribute the highest profit?
* Are bulk purchases actually reducing costs?
* Which products are causing inventory inefficiencies?
* Which vendors should be prioritized for future procurement?
* Which brands are underperforming despite strong sales volume?

This project addresses these challenges through data-driven analysis and statistical validation.

---

## 🏗️ Project Architecture

```text
Raw CSV Files
      │
      ▼
Data Ingestion Pipeline
      │
      ▼
SQLite Database
      │
      ▼
Vendor Summary Generation
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Statistical Testing
      │
      ▼
Business Insights & Recommendations
```

---

## 📂 Dataset Overview

The project integrates multiple business datasets:

### Vendor Data

* Vendor Information
* Purchase Records
* Purchase Prices

### Inventory Data

* Beginning Inventory
* Ending Inventory
* Unsold Stock Analysis

### Sales Data

* Product Sales
* Sales Quantity
* Revenue Metrics

### Invoice Data

* Vendor Invoices
* Freight Cost Information

These datasets are combined into a consolidated vendor performance model for analysis.

---

## ⚙️ Technologies Used

### Programming & Analytics

* Python
* SQL
* SQLite

### Python Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* SQLAlchemy

### Development Tools

* Jupyter Notebook
* Git
* GitHub

---

## 🔄 ETL Pipeline

A complete ETL workflow was implemented:

### Extract

* Imported multiple CSV files

### Transform

* Data Cleaning
* Null Value Handling
* Duplicate Removal
* Data Type Conversion
* Vendor-Level Aggregation

### Load

* Loaded processed datasets into SQLite database
* Generated analytical summary tables

---

## 📊 Exploratory Data Analysis

The project performs comprehensive analysis including:

### Revenue Analysis

* Top Revenue Generating Vendors
* Vendor Revenue Distribution

### Profitability Analysis

* Gross Profit Analysis
* Profit Margin Evaluation
* Vendor Profit Ranking

### Inventory Analysis

* Unsold Inventory Assessment
* Inventory Turnover Analysis
* Stock Optimization Opportunities

### Purchasing Analysis

* Purchase Cost Evaluation
* Bulk Purchase Impact Analysis
* Freight Cost Assessment

### Correlation Analysis

* Purchase Quantity vs Sales Quantity
* Purchase Price vs Profitability
* Sales Performance Relationships

---

## 📈 Key Business Insights

### 💰 Revenue Concentration

A small group of vendors contributes a significant portion of total revenue, indicating supplier concentration.

### 📦 Inventory Optimization Opportunity

Several products showed high unsold inventory levels, highlighting opportunities for inventory reduction and better demand planning.

### 📉 Margin Leakage

Certain vendors generated strong sales volume but produced relatively low profit margins.

### 🚚 Freight Cost Impact

Freight expenses significantly influenced overall profitability for some vendor groups.

### 📊 Purchasing Efficiency

Bulk purchasing demonstrated measurable cost advantages for selected products and vendors.

---

## 🧪 Statistical Analysis

Hypothesis testing was performed to validate business assumptions rather than relying solely on descriptive analytics.

Key objectives included:

* Vendor profitability comparison
* Margin performance validation
* Statistical significance testing
* Data-driven business recommendations

This strengthens decision-making confidence for stakeholders.

---

## 📋 Business Recommendations

Based on the analysis:

✅ Prioritize high-margin vendors

✅ Review low-profit, high-volume suppliers

✅ Optimize slow-moving inventory

✅ Negotiate freight-intensive vendor contracts

✅ Expand relationships with high-performing vendors

✅ Improve inventory planning using sales trends

---

## 📁 Project Structure

```text
vendor_analysis2/
│
├── data/
│   ├── sales.csv
│   ├── purchases.csv
│   ├── purchase_prices.csv
│   ├── begin_inventory.csv
│   ├── end_inventory.csv
│   └── vendor_invoice.csv
│
├── notebook/
│   ├── Exploratory_Data_Analysis.ipynb
│   └── Vendor_Performance_Analysis.ipynb
│
├── scripts/
│   ├── ingestion_db.py
│   └── get_vendor_summary.py
│
├── logs/
├── README.md
└── .gitignore
```

---

## 🎓 Skills Demonstrated

* SQL Query Writing
* Data Cleaning
* Data Wrangling
* ETL Development
* Exploratory Data Analysis
* Statistical Testing
* Data Visualization
* Business Analytics
* Inventory Analytics
* Vendor Performance Evaluation

---

## 📌 Project Outcome

This project demonstrates how raw retail transaction data can be transformed into strategic business intelligence through SQL, Python, and statistical analysis.

The final solution enables organizations to make informed procurement, inventory, and vendor management decisions using data rather than intuition.

---

## 👨‍💻 Author

**Yash Maheshwari**

Aspiring Data Analyst | SQL | Python | Data Visualization | Statistics | Machine Learning

📧 Open to Data Analyst, Business Analyst, and Data Science opportunities.

⭐ If you found this project valuable, consider giving the repository a star.
