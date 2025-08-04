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

1Top 10 Best-Value Products
Products with the highest discount percentages.

2High MRP but Out of Stock Products
Identified premium products that are not available for sale.

3Estimated Revenue per Category
Calculated by multiplying discounted price with available quantity.

4Low Discount on High MRP Products
Products priced above ₹500 but offering less than 10% discount.

5Top 5 Categories by Average Discount
Highlighted product categories giving the best average discounts.

6Price Per Gram Analysis
Compared value-for-money by calculating ₹ per gram for items above 100g.

7Weight-Based Product Segmentation
Categorized products as Low, Medium, or Bulk based on weight.

8Total Inventory Weight by Category
Useful for logistics and stock planning.

## 🛠️ Tools Used
- PostgreSQL
- SQL Queries
- Data Cleaning & Exploration Techniques

  
