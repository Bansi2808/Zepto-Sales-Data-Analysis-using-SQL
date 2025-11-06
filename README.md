 ## 🛒 Zepto Sales Data Analysis using SQL

## 📘 Project Overview

This project focuses on analyzing Zepto product and inventory data using SQL to derive meaningful business insights. The analysis explores product pricing, discounts, stock availability, and category-wise revenue to support data-driven decision-making.

The dataset contains detailed product information such as MRP, discount percentage, stock levels, and weights. SQL queries are used for data cleaning, exploration, and business analysis.

🧰 Tools & Technologies
Database: MySQL / PostgreSQL
Language: SQL
Environment: Any SQL IDE (MySQL Workbench, DBeaver, or pgAdmin)


## 📂 Dataset Structure

The dataset (zepto_v2) contains the following columns:

| Column Name           | Description |
|------------------------|-------------|
| sku_id                | Unique product identifier |
| category              | Product category |
| name                  | Product name |
| mrp                   | Maximum Retail Price |
| discountPercent       | Discount offered on product |
| availableQuantity     | Number of items available in stock |
| discountedSellingPrice| Final price after discount |
| weightInGms           | Product weight in grams |
| outOfStock            | Stock availability status (True/False) |
| quantity              | Units sold or available |


## 🧹 Data Cleaning Steps

Checked for missing/null values in important columns.
Removed products with zero prices.
Converted price units from paise to rupees.
Ensured unique SKUs and standardized product categories.

## 📊 Business Analysis & Key Queries
1️⃣ Top 10 Best-Value Products
Identify products offering the highest discounts.

2️⃣ High-MRP Products Out of Stock
Find premium products currently unavailable for purchase.

3️⃣ Estimated Revenue per Category
Calculate total category revenue = discountedSellingPrice × availableQuantity.

4️⃣ High-MRP & Low-Discount Products
List expensive items offering minimal discounts.

5️⃣ Top 5 Categories with Highest Average Discount
Determine which product categories provide the best deals.

6️⃣ Price per Gram Analysis
Measure product value based on price-to-weight ratio.

7️⃣ Weight-Based Product Classification
Classify products as Low, Medium, or Bulk based on total weight.

8️⃣ Total Inventory Weight per Category
Calculate overall inventory weight distribution across categories.

💡 Insights & Observations

Certain categories offer high discounts, driving better customer value.

Out-of-stock premium items highlight potential restocking priorities.

Revenue contribution varies heavily across product categories.

Bulk products tend to have lower price-per-gram ratios, indicating better pricing efficiency.



👩‍💻 Author
Bansi Shah

