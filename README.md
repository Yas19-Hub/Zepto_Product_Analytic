# 🛒 Zepto Product, Pricing & Inventory Analytics

<p align="center">
  
![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

</p>

<p align="center">
  <b>End-to-End Product Analytics Project using Python & Power BI</b>
</p>
---

## 📌 Project Overview

This project analyzes a Zepto product dataset to understand **product performance, pricing strategies, discount patterns, estimated sales value, and inventory availability**.

The project combines **Python-based data analysis and Power BI visualization** to transform raw product-level data into meaningful business insights.
The final Power BI dashboard provides an interactive view of:

- Product performance
- Category-level analysis
- Pricing and discounts
- Estimated sales value
- Product availability
- Out-of-stock products
- Inventory distribution

---

## 🎯 Business Problem

Quick-commerce platforms such as Zepto manage thousands of products across multiple categories.

Understanding which products and categories generate higher sales value, receive larger discounts, and experience inventory shortages can help businesses improve:

- Inventory planning
- Pricing strategies
- Promotional decisions
- Product availability
- Category management
- Revenue optimization

### Key Business Questions
1. Which product categories have the highest estimated sales value?
2. Which categories offer the highest average discounts?
3. Which products contribute the most estimated sales value?
4. What percentage of products are out of stock?
5. Which categories have the highest number of out-of-stock products?
6. How does MRP compare with average selling price across categories?
7. Which categories have the highest product availability?
8. Which products require better inventory management?

---

## 📊 Dataset

The analysis uses a Zepto product dataset containing product-level information.

### Important Columns

| Column | Description |
|---|---|
| `Category` | Product category |
| `name` | Product name |
| `mrp` | Maximum Retail Price |
| `discountPercent` | Discount percentage |
| `availableQuantity` | Available quantity |
| `discountedSellingPrice` | Selling price after discount |
| `weightInGms` | Product weight in grams |
| `outOfStock` | Product stock availability |
| `quantity` | Product quantity |

---

## 🛠️ Tech Stack

### Data Analysis

- Python
- Pandas
- NumPy
- Jupyter Notebook

### Data Visualization

- Power BI
- Matplotlib
- Seaborn

### Data Source

- Microsoft Excel

---

## 🔄 Project Workflow

```text
Raw Excel Dataset
       ↓
Data Loading
       ↓
Data Cleaning & Preparation
       ↓
Exploratory Data Analysis
       ↓
Business Metrics & KPIs
       ↓
Power BI Data Modeling
       ↓
Interactive Dashboard
       ↓
Business Insights
