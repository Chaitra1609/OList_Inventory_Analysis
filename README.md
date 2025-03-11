# OList Inventory Analysis

## 📋 Project Overview
This project aims to help **OList**, an e-commerce company, optimize its inventory by:
- Identifying top revenue-generating products using **Pareto analysis**.
- Uncovering frequently purchased product combinations through **Market Basket Analysis**.

---

## ❓ Problem Statement
The project addresses the following key challenges:
- ✅ Identify the top products contributing to the majority of revenue.
- ✅ Highlight slow-moving products that can be phased out to reduce inventory costs.
- ✅ Perform **Market Basket Analysis** to understand customer purchasing patterns and improve marketing strategies.

---

## 📂 Dataset Details
- **Source**: OList e-commerce dataset  
- **Size**: 8,000+ records  
- **Key Columns**: `product_id`, `total_revenue`, `order_status`, etc.

---

## 🧹 Data Cleaning Process
- ✔️ Identified and treated missing values.
- ✔️ Removed duplicate records.
- ✔️ Filtered records to include only `order_status = 'delivered'` for accurate insights.

---

## 📊 Analysis Process

### 1. Pareto Analysis
- ✅ Identified the **Top 20 Products** by revenue and by quantity.
- ✅ Performed Pareto Analysis using SQL to calculate cumulative percentages for both revenue and orders.
- ✅ Visualized results in **Power BI** for effective storytelling.

### 2. Market Basket Analysis
- ✅ Identified frequently purchased product combinations to improve marketing strategies.
- ✅ Recommended product bundling strategies to boost sales.

---

## 🔍 Key Insights
- ✅ Identified top revenue-generating products that contribute to ~80% of revenue.
- ✅ Recommended removing certain product categories with minimal impact on sales.
- ✅ Suggested key product combinations that should be promoted together.

---

## 📂 Project Structure
├── Data/ │ └── Contains cleaned dataset for analysis ├── PowerBI_Dashboard/ │ └── Contains .pbix file and dashboard screenshots ├── Reports/ └── Contains presentation and business recommendations

---

## 🛠️ Tools Used
- **SQL**: For data extraction and transformation.
- **Power BI**: For interactive dashboards and visual storytelling.
- **Excel**: For initial data cleaning.

---

## 🚀 How to Run
1. Clone the repository: https://github.com/Chaitra1609/OList_Inventory_Analysis
2. Open the `.pbix` file in Power BI Desktop.
3. Review the cleaned data in the `Data/` folder.

---

## 📸 Sample Visualizations
Here are some sample visualizations created in Power BI:
- **Matrix** for frequently bought product combinations - ![Market Basket Analysis](Market%20basket%20analysis.png)
- **Pareto Chart** for revenue distribution - ![Pareto Analysis](Pareto%20analysis.png)


For additional insights and detailed recommendations, refer to the `Reports/` folder.




