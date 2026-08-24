# Maven Toys Sales & Revenue Analysis

## Project Overview

This project analyzes Maven Toys sales data to identify revenue and profit drivers across products, categories, stores, and time periods.

The project follows a complete data analytics workflow:

Raw Data → Data Quality Audit → Data Cleaning → Data Analysis → KPI Tracking → Business Insights

## 🎯 Business Objective

The objective is to analyze sales and revenue performance and identify:

- Top-performing products
- Low-performing products
- Highest-revenue product categories
- Store performance
- Monthly revenue trends
- Overall revenue and profitability

## 📁 Dataset

The project uses the Maven Toys dataset containing:

- Sales transactions
- Products
- Stores
- Inventory
- Calendar
- Data dictionary

The sales table contains 829,262 transaction records.

## 🧹 Data Quality & Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Duplicate identifiers
- Referential integrity
- Data types
- Date formatting
- Monetary formatting

### Results

- Missing values: 0
- Duplicate rows: 0
- Duplicate Sale IDs: 0
- Unmatched Product IDs in Sales: 0
- Unmatched Store IDs in Sales: 0
- Unmatched Product IDs in Inventory: 0
- Unmatched Store IDs in Inventory: 0
- Duplicate Store-Product combinations in Inventory: 0

Product cost and retail price were converted from text currency values into numeric values.

Date fields were converted into proper datetime format.

## 📈 KPIs

The analysis calculates:

- Total Units Sold
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin

## 🔍 Analysis Performed

### Product Analysis
- Revenue by product
- Units sold by product
- Profit by product
- Top and bottom performing products

### Category Analysis
- Revenue by category
- Units sold by category
- Profit by category
- Profit margin by category

### Time Analysis
- Monthly revenue trends
- Monthly units sold
- Monthly profit

### Store Analysis
- Revenue by store
- Units sold by store
- Profit by store
- Store ranking

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Git
- GitHub

## 📂 Project Files

`Maven_Toys_Sales_Analysis.ipynb`  
Main analysis notebook containing data loading, cleaning, analysis, KPIs, and visualizations.

`outputs/`  
Contains processed analytical datasets used for reporting and visualization.

## 💡 Business Insights

Insights are generated from product, category, store, and monthly performance analysis.

The analysis can be used to identify high-revenue products, underperforming products, strong categories, high-performing stores, and important sales trends.

## 🚀 Key Learning Outcomes

This project demonstrates practical skills in:

- Data cleaning
- Exploratory data analysis
- Data transformation
- KPI development
- Business analysis
- Data visualization
- Python/Pandas
- Git/GitHub workflow
