# 📊 Vendor Performance Analysis (Python + SQL)

## 📌 Project Overview
This project analyzes vendor performance using **Python, SQL, and data visualization techniques**.  
The objective is to optimize inventory management, improve profitability, and reduce risks caused by vendor dependency.

The analysis was performed on raw sales, purchase, and inventory data to uncover patterns in **sales, gross profit, unit costs, stock turnover, and vendor efficiency**.

---

## 🚀 Business Problem
Retail and wholesale companies often face challenges in:
- Inefficient pricing and low sales volume.
- High inventory holding costs due to unsold stock.
- Vendor dependency creating supply chain risks.
- Difficulty identifying profitable vs. underperforming vendors.

This project addresses these issues by answering:
1. Which brands/vendors need promotional or pricing adjustments?  
2. Who are the top vendors contributing to sales and gross profit?  
3. How does bulk purchasing impact unit costs?  
4. Which vendors have low inventory turnover?  
5. What are the profitability differences between high vs. low-performing vendors?  

---

## 🔍 Key Insights
- **198 brands** have high margins but low sales → require marketing/promotions.  
- **Top 10 vendors** contribute **65.7% of total purchases** → supplier diversification needed.  
- **Bulk purchasing** reduces unit cost by **72%** (avg. $10.78/unit).  
- **Unsold inventory** tied up **$2.71M** in capital → needs clearance or stock optimization.  
- **Profit margin comparison**:  
  - Top vendors: ~31% mean margin  
  - Low vendors: ~41% mean margin (but low sales volumes).  
- **Statistical testing** confirmed significant differences in profitability models.  

---

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib/Seaborn)  
- **SQL** (for querying and data aggregation)  
- **Jupyter Notebooks** (Exploratory Data Analysis & Vendor Insights)  

---

## 📂 Repository Structure
"""
├── data/ # Raw CSVs (ignored in .gitignore)
├── Notebooks/
│ ├── Exploratory Data Analysis.ipynb
│ ├── Vendor performance analysis.ipynb
├── scripts/
│ ├── get_vendor_summary.py
│ ├── inventory_db.py
├── reports/
│ └── Vendor Performance Report.pdf
├── README.md
└── .gitignore
"""

## ✅ Recommendations
- Adjust pricing for **low-sales, high-margin brands**.  
- Diversify vendor base to avoid over-reliance on a few suppliers.  
- Leverage **bulk purchasing** for cost efficiency.  
- Optimize **slow-moving inventory** via clearance sales and purchase planning.  
- Enhance marketing and distribution strategies for **low-performing vendors**.  

---
