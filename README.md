# 📊 Zepto SQL Data Analysis Project

## 🎯 Project Objective
The goal is to simulate how actual data analysts in the e-commerce or retail industries work behind the scenes to use SQL to:
- Set up a messy, real-world e-commerce inventory database
- Perform Exploratory Data Analysis (EDA) to explore product categories, availability, and pricing inconsistencies
- Implement Data Cleaning to handle null values, remove invalid entries, and convert pricing from paise to rupees
- Write business-driven SQL queries to derive insights around pricing, inventory, stock availability, revenue, and more

## 📁 Dataset Source
[Dataset](https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv)

## 📌 Key Performance Indicators (KPIs)
The following KPIs were derived using SQL to extract actionable insights from the Zepto inventory dataset:
- Found top 10 best-value products based on discount percentage
- Identified high-MRP products that are currently out of stock
- Estimated potential revenue for each product category
- Filtered expensive products (MRP > ₹500) with minimal discount
- Ranked top 5 categories offering highest average discounts
- Calculated price per gram to identify value-for-money products
- Grouped products based on weight into Low, Medium, and Bulk categories
- Measured total inventory weight per product category

## 🛠️  Project Tasks
1.Data Exploration
- Count total records
- View sample entries
- Check for missing/null values
- List unique product categories
- Identify out-of-stock vs in-stock items
- Detect duplicate product names
2. Data Cleaning

Remove products with MRP = 0

Convert values from paise to rupees

Ensure price fields are in valid format

Data Analysis (KPIs & Insights)

Top 10 best-value products by discount %

High MRP products that are out of stock

Estimated revenue by product category

Products with high MRP but low discounts

Top 5 categories with highest average discounts

Price per gram for items above 100g

Categorization of items into Low, Medium, and Bulk

Total inventory weight per category





  
