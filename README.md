# 📊 Business Analytics on E-commerce Sales (Jordan & Lebanon, 2021–2025)

## 📌Project Overview
This project analyzes multi-national e-commerce sales data (2021–2025) for Jordan and Lebanon, focusing on **electronics and office furniture**.  
The analysis covers sales trends, customer segmentation, product performance, sales channel effectiveness, and promotional impact.  
Findings are supported with **visualizations and actionable recommendations**.


## 📂 Dataset Information
- **Files**: `sales_data_part1.csv`, `sales_data_part2.csv`, `customers.csv`
- **Main Columns**:  
  `order_id`, `date`, `customer_id`, `country_code`, `channel`,  
  `sales_person`, `units_sold`, `unit_price`, `product_code`,  
  `product`, `promotion_flag`, `commission_percent`


  ## 🧹 Data Preparation & Cleaning
- Concatenated datasets into one DataFrame  
- Renamed all column names to `snake_case`  
- Standardized country codes (`JO`, `JOR`, `Jrdn` → `Jordan`)  
- Removed duplicates and stored them in a separate DataFrame for review  
- Filled missing values with `unknown`  
- Converted datatypes (`date` → datetime, numeric columns → float/int)  
- Created new calculated columns:
  - `country`
  - `unit_price_usd`
  - `discount_pct`
  - `total_amount`
  - `commission_amount`
  - `year`, `month`, `weekday_name`
  - `sales_volume_category`
  - `customer_segment`
 


📊 Results Achieved
Understand Customer Behavior and Market Segmentation More Accurately

By analyzing customer segments (Loyal, Premium, Standard, One-time) and identifying the most active sectors and cities.

Evaluate Channel, Product, and Sales Performance Over Time

The goal is to identify the best-performing channels, the most profitable products, and any channels or products that may need closure or improvement.



##Recommendations:
The dataset did not include details about inventory or shipping costs, which limits the accuracy of some recommendations.


## ⚙️ How to Run the Project

To run the analysis, first clone the repository and navigate into the project folder:

###Clone repository

git clone https://github.com/sanad-almadi/-Business-Analytics-on-E-commerce-Sales-.git
cd Business-Analytics-on-E-commerce-Sales-

###Install requirements

pip install -r requirements.txt

###Run notebooks

jupyter notebook






    
