🛍️ Customer Shopping Behaviour Analysis
📌 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective is to uncover insights into:

Customer spending patterns

Product preferences

Subscription behavior

Customer segmentation

Revenue distribution

The project combines Python, SQL, and Power BI to perform end-to-end data analysis and visualization.

📊 Dataset Summary

Total Rows: 3,900

Total Columns: 18

Missing Values: 37 values in review_rating column

Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

🛠️ Tools & Technologies Used

🐍 Python

📊 Pandas

🗄️ MySQL

📈 Power BI

📓 Jupyter Notebook

🚀 Project Workflow
1️⃣ Data Loading & Exploration (Python)

Imported dataset using pandas

Used df.info() and describe() for structure and summary statistics

2️⃣ Data Cleaning

Handled missing values in review_rating using median by category

Renamed columns to snake_case

Removed redundant column (promo_code_used)

Created new features:

age_group

purchase_frequency_days

3️⃣ Database Integration

Connected Python to MySQL server

Loaded cleaned dataset into database

4️⃣ SQL Analysis

Performed structured queries to answer key business questions:

Revenue by Gender

High Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison

Subscribers vs Non-Subscribers Analysis

Discount-Dependent Products

Customer Segmentation (New, Returning, Loyal)

Top 3 Products per Category

Repeat Buyers & Subscription Analysis

Revenue by Age Group

📊 Power BI Dashboard

An interactive dashboard was created to visualize insights.

Dashboard Highlights:

Total Customers: 3.9K

Average Purchase Amount: $59.76

Average Review Rating: 3.75

Revenue by Category

Revenue by Age Group

Subscription Distribution

Sales by Category

Sales by Age Group

The dashboard enables dynamic filtering by:

Gender

Category

Subscription Status

Shipping Type

📈 Key Insights

Loyal customers represent the majority segment

Subscribers contribute significant revenue

Young Adults generate the highest revenue

Certain products are highly discount-dependent

Express shipping users show competitive average spending

💡 Business Recommendations

Boost subscription benefits

Strengthen loyalty programs

Optimize discount strategies

Promote top-rated and best-selling products

Target high-revenue age groups

⚙️ How to Run This Project
Step 1: Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run Python Scripts

Perform EDA and data cleaning

Export cleaned dataset

Step 4: Load Data into MySQL

Import cleaned dataset

Execute SQL queries

Step 5: Open Power BI Dashboard

Open .pbix file

Explore visual insights

📁 Project Structure
├── data/
├── notebooks/
├── sql_queries/
├── powerbi_dashboard/
├── report/
├── presentation/
└── README.md
🎓 Academic Context

This project was developed as part of an academic data analytics project to demonstrate practical skills in:

Data Cleaning

SQL Querying

Business Intelligence

Dashboard Development

Insight Generation
