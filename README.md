# Excel-Capstone-Project-E-Commerce-Analysis
# Excel Capstone Project – E-Commerce Analysis

## 📌 Project Overview
An end-to-end Excel analytics project involving data cleaning, transformation, and analysis of an e-commerce dataset with four related tables: Sales, Customer, Product, and Store. Built pivot tables, charts, and an interactive dashboard to uncover revenue trends, sales distribution, and payment patterns.

## 📂 Dataset
The dataset consists of 4 linked sheets:
- **Customer_Dim** (500+ records) – Customer ID, Name, Age, Gender, City, State, Country, Loyalty Level
- **Product_Dim** (100 records) – Product ID, Name, Category, Sub-Category, Brand, Cost, Stock
- **Store_Dim** (20 records) – Store ID, Name, Region, City, Store Type
- **Sales_Fact** (2,000+ records) – Sales ID, Order Date, Customer/Product/Store references, Quantity, Unit Price, Discount, Payment Type, Total Amount

## 🧹 Data Cleaning & Transformation
- Removed duplicate IDs across Customer, Product, and Store tables
- Standardized text formatting using `PROPER` and `TRIM` functions
- Handled missing values: blank discounts set to 0, blank unit prices filled via `XLOOKUP` from Product table, missing totals calculated as Quantity × Unit Price
- Corrected date and numeric formatting issues
- Removed irrelevant/unnecessary columns to improve data clarity

## 🛠️ Tools & Techniques Used
- **Microsoft Excel** – Data cleaning, PROPER/TRIM, XLOOKUP
- **XLOOKUP** – Connected Sales_Fact with Customer, Product, and Store dimension tables
- **Pivot Tables** – Sales summaries by region, category, payment type, and month
- **Charts** – Column, pie, and line charts for trend visualization
- **Descriptive Statistics** – Mean, median, mode, and standard deviation to understand sales variability

## 📊 Analysis Performed
- Region-wise, category-wise, and payment-type-wise revenue breakdown
- Month-wise sales trend analysis
- Customer and product-level insights via cross-table lookups

## 💡 Key Insights
- Identified top-performing regions and product categories by revenue
- Determined most-used payment methods and their contribution to total sales
- Surfaced monthly sales trends to support demand forecasting
- Delivered a clean, dashboard-ready dataset for ongoing business reporting

## 📁 Files in this Repository
- `Excel_Capstone_Project_-_E-Commerce_Analysis.xlsx` – Cleaned dataset, pivot tables, charts, and dashboard

## 🚀 How to View
Open the `.xlsx` file in Microsoft Excel. Explore the **Dashboard** sheet for the visual summary, the **Pivot table** sheet for breakdowns, and the **Summary** sheet for the full analysis write-up.

---
**Author:** A. Mathew Ebineshya
**LinkedIn:** [linkedin.com/in/mathew-ebineshya-941286281](https://www.linkedin.com/in/mathew-ebineshya-941286281)
