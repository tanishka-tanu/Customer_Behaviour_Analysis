📊 Customer Shopping Behavior Analysis
📌 Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product performance, discounts, and subscription behavior.
The goal is to support data-driven business decisions through Python-based analysis, SQL querying, and interactive Power BI dashboards.

The dataset contains 3,900 purchase records across multiple product categories and customer demographics.

📁 Dataset

Total Records: 3,900

Total Columns: 18

Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency

Customer Feedback & Logistics: Review Rating, Shipping Type

Data Quality:

Missing values detected in the Review Rating column

Missing values were handled during data cleaning

🛠 Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

SQL: PostgreSQL (queries compatible with MySQL & SQL Server)

Power BI: Interactive dashboard & visual analytics

Gamma: Presentation (PPT) creation

pgAdmin: Database management

GitHub: Version control & project hosting

🔄 Project Workflow / Steps
1️⃣ Data Loading & Cleaning (Python)

Loaded dataset using pandas

Checked data structure using df.info() and df.describe()

Handled missing values in Review Rating using median values per product category

Standardized column names to snake_case

Removed redundant column (promo_code_used)

Performed feature engineering:

Created age_group

Derived purchase frequency metrics

Exported cleaned data to PostgreSQL database

2️⃣ Exploratory Data Analysis (EDA)

Analyzed customer demographics and purchase trends

Studied distribution of purchase amounts

Examined discount usage and subscription behavior

Identified high-performing products and categories

3️⃣ SQL Analysis (PostgreSQL)

Business-focused queries were written to answer key questions:

Revenue contribution by Gender

High-spending customers who used discounts

Top-rated products by average review rating

Purchase comparison by Shipping Type

Spending behavior of Subscribers vs Non-Subscribers

Products most dependent on discounts

Customer segmentation (New, Returning, Loyal)

Top products within each category

Relationship between repeat purchases and subscriptions

Revenue contribution by Age Group

📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize insights:

Key Visuals:

Revenue by Gender & Age Group

Subscriber vs Non-Subscriber spending

Top products and categories

Discount impact analysis

Customer segmentation overview

Shipping type comparison

Features:

Filters & slicers for dynamic analysis

Business-friendly KPIs

Clean and intuitive layout

📈 Results & Insights

Subscribers contribute higher average revenue

Certain products rely heavily on discounts

Loyal customers generate consistent revenue

Express shipping users tend to spend more

Specific age groups drive maximum revenue

💡 Business Recommendations

Promote subscription plans with exclusive benefits

Introduce loyalty programs for repeat customers

Optimize discount strategies to protect margins

Highlight top-rated & best-selling products

Focus marketing on high-revenue age groups
