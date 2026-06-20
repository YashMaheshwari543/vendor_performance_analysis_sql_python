# Vendor Performance Analysis

## Project Overview

This project analyzes vendor performance using Python, SQL, and Streamlit.
---

## Table of Contents
<a href="#overview">Overview</a>
<a href="#business-problem">Business Problem</a>
<a href="#dataset">Dataset</a>
<a href="#tools--technologies">Tools & Technologies</a>
<a href="#project-structure">Project Structure</a>
<a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
<a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
<a href="#research-questions--key-findings">Research Questions & Key Findings</a>
<a href="#dashboard">Dashboard</a>
<a href="#how-to-run-this-project">How to Run This Project</a>
<a href="#final-recommendations">Final Recommendations</a>
<a href="#author--contact">Author & Contact</a>
---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project evaluates vendor performance and retail inventory dynamics to drive strategic insights for purchasing, pricing, and inventory optimization. A complete data pipeline was built using SQL for ETL, Python for analysis and hypothesis testing, and Power BI for visualization.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Effective inventory and sales management are critical in the retail sector. This project aims to:

- Identify underperforming brands needing pricing or promotional adjustments
- Determine vendor contributions to sales and profits
- Analyze the cost-benefit of bulk purchasing
- Investigate inventory turnover inefficiencies
- Statistically validate differences in vendor profitability

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Multiple CSV files located in `/data/` folder (sales, vendors, inventory)
- Summary table created from ingested data and used for analysis

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- SQL (Common Table Expressions, Joins, Filtering)
- Python (Pandas, Matplotlib, Seaborn, SciPy)

- GitHub
---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```text
vendor_analysis2/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── notebooks/                 # Jupyter notebooks
│   ├── exploratory_data_analysis.ipynb
│   └── vendor_performance_analysis.ipynb
│
├── scripts/                   # Python scripts
│   ├── ingestion_db.py
│   └── get_vendor_summary.py
│
│
├── data/                      # Raw datasets
│
└── inventory.db              # SQLite database
---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Removed duplicate records
- Handled missing values
- Standardized column names and data types
- Merged vendor, sales, and inventory datasets
- Created summary tables with vendor-level metrics
- Converted data types and handled outliers

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Negative or Zero Values Detected

- Gross Profit: Negative values indicating loss-making sales
- Profit Margin: Sales at or below cost
- Unsold Inventory: Indicates slow-moving stock

**Outliers Identified

- High freight costs
- Large purchase and actual price differences

**Correlation Analysis

- Weak relationship between Purchase Price and Profit
- Strong relationship between Purchase Quantity and Sales Quantity
- Negative relationship between Profit Margin and Sales Price

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. Which vendors generate the highest revenue?
2. Which vendors contribute the most profit?
3. Are there vendors with high sales but low profitability?
4. What products experience inventory turnover issues?
5. Which vendors should be prioritized for future purchasing?

### Findings

- Top vendors contributed the majority of total revenue
- Several vendors showed high sales volume but low margins
- Inventory inefficiencies were found in slow-moving products
- Vendor profitability varied significantly across categories

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>


---

<h2><a class="anchor" id="how-to-run-this-project"></a>How To Run This Project</h2>

1. Clone the repository

```bash
git clone https://github.com/yourusername/vendor_analysis2.git
<h2><a class="anchor" id="how-to-run-this-project"></a>How To Run This Project</h2>

python scripts/ingestion_db.py