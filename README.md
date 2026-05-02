# Beverage Sales Analysis

An interactive Business Intelligence dashboard built using **Power BI**, **SQL**, and **DAX** to analyze beverage sales across multiple business dimensions. The dashboard enables users to monitor sales performance, identify trends, evaluate product performance, and gain actionable business insights through dynamic visualizations.

---

## Dashboard Preview

<img width="1258" height="812" alt="image" src="https://github.com/user-attachments/assets/67e632ac-6d78-4f19-a1a9-c130853f93db" />


---

# Project Overview

This project focuses on transforming raw transactional beverage sales data into meaningful business insights through interactive reporting. The objective was to design a comprehensive Power BI dashboard that allows stakeholders to monitor key performance indicators, explore sales trends, and evaluate business performance across products, stores, and time periods.

The project includes SQL-based data preparation, Power Query transformations, DAX calculations, and interactive dashboard development.

---

# Business Objectives

The dashboard was designed to answer several important business questions:

- How are overall beverage sales performing?
- How many orders and products are sold over time?
- What are the month-over-month growth trends?
- Which stores generate the highest revenue?
- Which beverage categories and products contribute the most to total sales?
- Which hours and days experience peak customer activity?
- How does daily performance compare against the average sales trend?

---

# Tech Stack

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard Development & Data Visualization |
| **MySQL** | Data Cleaning, Transformation & Analysis |
| **Excel** | Initial Dataset Validation |
| **Power Query** | Data Transformation |
| **DAX** | KPI Calculations & Business Logic |

---

## Dataset

This project uses a publicly available beverage sales dataset from Kaggle. The dataset contains transactional records including:

- Transaction Date & Time
- Transaction ID
- Store Location
- Product Category
- Product Type
- Unit Price
- Quantity Sold

The data was cleaned, transformed, and modeled using MySQL, Power Query, and DAX before building the interactive Power BI dashboard.

---

# Data Preparation

Before building the dashboard, the dataset was cleaned and transformed to ensure consistency and accuracy.

### Excel

- Verified missing values
- Corrected inconsistent formatting
- Standardized date values
- Validated numeric columns
- Performed initial quality checks

### MySQL

The transactional data was processed using SQL to prepare it for reporting.

Operations included:

- Date & Time Conversion
- Data Type Modification
- KPI Queries
- Sales Aggregations
- Window Functions
- Monthly Sales Analysis
- Product & Store Analysis

### Power Query

Within Power BI, additional transformations included:

- Removing duplicate records
- Changing column data types
- Filtering unnecessary records
- Building the data model
- Creating relationships between tables

---

# Data Modeling

A dedicated **Date Table** was created and linked with the Transactions table to enable efficient time intelligence calculations.

The model supports:

- Monthly Analysis
- Daily Analysis
- Calendar Heatmap
- Time-Based Filtering
- Dynamic Slicers

---

# DAX Measures

Several custom DAX measures were implemented to power the dashboard.

Key measures include:

- Total Sales
- Total Orders
- Total Quantity Sold
- Current Month Sales
- Previous Month Sales
- Month-over-Month Growth
- Daily Average Sales
- Store Performance
- Category Performance
- Product Performance
- Calendar Heatmap Metrics

---

# Dashboard Features

The dashboard includes interactive visualizations such as:

- KPI Cards
- Monthly Sales Trend
- Total Orders Trend
- Quantity Sold Trend
- Calendar Heatmap
- Store Location Analysis
- Beverage Category Analysis
- Beverage Type Analysis
- Top Products
- Daily Sales vs Average Sales
- Sales by Day & Hour Matrix
- Interactive Tooltips
- Dynamic Slicers

---

# Business Insights

The dashboard enables users to:

- Monitor overall business performance
- Identify seasonal and monthly sales trends
- Compare store-level performance
- Evaluate high-performing beverage categories
- Discover peak business hours
- Analyze customer purchasing behavior
- Track month-over-month business growth

---

# Recommendations

Based on the analysis, the following improvements can be considered:

- Prioritize inventory for top-performing beverages.
- Schedule promotions during lower sales periods.
- Optimize staffing based on hourly demand patterns.
- Focus marketing efforts on underperforming store locations.
- Expand successful product categories while reviewing low-performing items.

---

# Conclusion

This project demonstrates how SQL, DAX, and Power BI can be combined to convert raw transactional data into meaningful business intelligence. The dashboard provides decision-makers with an interactive platform to monitor KPIs, identify trends, and support data-driven business decisions.
