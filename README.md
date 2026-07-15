# 📊 E-Commerce Sales Dashboard | Power BI

## 📌 Project Overview

This project is an interactive **Power BI dashboard** built using an E-Commerce Sales dataset to analyze sales performance, profitability, customer behavior, product categories, and payment methods.

The dashboard enables business users to monitor KPIs, identify high-performing categories, analyze customer purchasing trends, and make data-driven decisions using interactive visualizations.

---

## 📷 Dashboard Preview

> Add your dashboard screenshot here

![Dashboard](Dashboard.png)

---

## 🎯 Business Objective

The objective of this dashboard is to help business stakeholders:

- Track Sales Performance
- Monitor Profitability
- Analyze Customer Purchase Trends
- Identify Best Selling Categories
- Understand State-wise Sales Distribution
- Monitor Monthly Profit Trends
- Analyze Payment Preferences

---

## 📂 Dataset

The project uses two related tables.

### Table 1: Details

Contains transactional information.

Columns:

- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- Payment Mode
- AOV (Average Order Value)

---

### Table 2: Orders

Contains customer and location information.

Columns:

- Order ID
- Customer Name
- City
- State

---

## 🔗 Data Model

The two tables are connected using:

```
Orders[Order ID]
      │
      │
      ▼
Details[Order ID]
```

Relationship:

- One-to-Many
- Order ID used as Primary Key

---

## 📈 Dashboard KPIs

The dashboard displays:

- 💰 Total Sales Amount
- 💵 Total Profit
- 📦 Total Quantity Sold
- 🛒 Average Order Value (AOV)

---

## 📊 Visualizations Used

- KPI Cards
- Clustered Bar Chart
- Horizontal Bar Chart
- Donut Chart
- Column Chart
- Slicers
- Interactive Filters

Dashboard includes analysis for:

- Sales by State
- Profit by Month
- Quantity by Category
- Quantity by Payment Mode
- Profit by Sub-Category
- Sales by Customer

---

## 🎛 Interactive Features

- Quarter Slicer
- State Filter
- Cross Filtering
- Interactive Drill-down
- Dynamic Visual Updates

---

## 🛠 Power BI Features Used

- Data Modeling
- Relationships
- Power Query
- DAX Measures
- Slicers
- Cards
- Custom Formatting
- Conditional Formatting
- Interactive Visualizations

---

## 📚 Project Learnings

- Created an interactive dashboard to track and analyze online sales performance.
- Built relationships between multiple tables using a common key (Order ID).
- Performed data cleaning and transformation using Power Query.
- Used DAX measures to calculate KPIs such as Total Sales, Profit, Quantity, and Average Order Value (AOV).
- Implemented interactive slicers and filters for Quarter and State-based analysis.
- Designed user-friendly dashboard layouts with customized themes and formatting.
- Created dynamic visualizations to support business decision-making.
- Improved storytelling through data visualization and KPI tracking.

---

## 💡 Business Insights

### Sales Performance

- Total Sales Amount reached **21K**.
- Overall Profit generated was approximately **3K**.
- Total Quantity Sold was **328** units.
- Average Order Value (AOV) was around **6K**.

### Customer Insights

- Gaurav and Shreyshi contributed the highest purchase amounts.
- Customer-wise sales comparison helps identify valuable customers.

### Product Insights

- Bookcases generated the highest profit among all sub-categories.
- Chairs were the second most profitable product category.
- Accessories, Trousers, and Handkerchief contributed comparatively lower profits.

### Payment Analysis

- Majority of orders were placed using the most preferred payment mode (largest donut segment).
- Payment distribution helps understand customer payment preferences.

### Category Analysis

- One product category contributed nearly 73% of the total quantity sold.
- Remaining categories contributed significantly less, indicating strong product concentration.

### Monthly Trend

- Highest profits were recorded during January and August.
- Some months experienced negative profits, highlighting opportunities for operational improvement.

### Geographic Analysis

- Gujarat generated the highest sales among the available states.
- State-level analysis helps identify strong-performing regions.

---

## 🚀 Skills Demonstrated

- Business Intelligence
- Power BI
- Data Visualization
- Data Modeling
- Power Query
- DAX
- Dashboard Design
- KPI Reporting
- Business Analytics
- Interactive Reporting
- Data Analysis

---

## 🧰 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Microsoft Excel (Dataset)

---

## 📁 Repository Structure

```
Ecommerce-Sales-Dashboard/
│
├── Dashboard.pbix
├── Dataset.xlsx
├── Dashboard.png
└── README.md
```

---

## ⭐ Future Enhancements

- Add Year and Month slicers.
- Create Top N Customers analysis.
- Include Profit Margin KPI.
- Add Forecasting using Power BI Analytics.
- Build Customer Segmentation.
- Add Drill-through pages.
- Create Executive Summary page.
- Publish dashboard to Power BI Service.

---

## 👤 Author

**Ajay Kumar**

Aspiring Business Analyst | Product Owner | Data Analyst

Skills:
- Power BI
- SQL
- Excel
- Python
- Data Analysis
- Business Analysis
- Agile
- DAX
- Power Query

---

⭐ If you found this project useful, don't forget to star this repository.
