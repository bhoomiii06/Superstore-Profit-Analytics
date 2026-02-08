# Superstore Profit Analytics & Business Intelligence System

## 📌 Project Overview
This project is an end-to-end data analytics solution designed to diagnose profit stagnation for a Global Superstore. By integrating **SQL**, **Python**, and **Power BI**, we moved from static reporting to a dynamic decision-support environment.

## 📊 Business Insights (Research Results)
- **The Discount Trap:** Analysis proves that discounts exceeding **20%** lead to net losses.
- **Problem Areas:** Identified **Texas, Ohio, and Pennsylvania** as high-sales but negative-profit states.
- **Operational Efficiency:** Validated a **5.25% Same-Day Shipping rate** using SQL window functions.
- **Seasonality:** Confirmed a consistent **Q4 Sales Surge** (Sept-Dec), accounting for nearly 40% of annual revenue.

## 🛠️ Technical Stack
- **Database:** MS SQL Server (Backend Validation & KPI Extraction)
- **Programming:** Python 3.9+ (Pandas, Seaborn, Matplotlib)
- **Visualization:** Power BI Desktop
- **Environment:** Jupyter Notebook

## 📂 File Descriptions
- **`Scripts/sales.ipynb`**: Core analytical engine handling data cleaning, feature engineering (Margin calculation), and EDA.
- **`Scripts/sqlQuery.sql`**: Comprehensive SQL script containing 14+ business queries including consecutive order tracking and shipping percentages.
- **`Data/Final_Analysis.csv`**: The refined dataset with engineered features like 'Order Year' and 'Profit Margin (%)'.
- **`Visuals/`**: Direct screenshots of the interactive dashboard and statistical charts.

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/bhoomiii06/Superstore-Profit-Analytics.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Execute the `sales.ipynb` notebook to generate the cleaned data and plots.
