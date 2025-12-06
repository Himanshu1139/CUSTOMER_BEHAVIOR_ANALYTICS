# CUSTOMER_BEHAVIOR_ANALYTICS
Customer Behavior Analysis using Python 🐍 (Pandas), PostgreSQL 🐘, and Power BI 📊. Cleaned data, engineered features, answered business questions with SQL, and built an interactive dashboard. Final insights and presentation created using Gamma AI 💡 for clear storytelling.


📌**Overview**

This project analyzes 3,900+ customer shopping transactions to uncover insights related to spending behavior, product preferences, subscription patterns, and customer segmentation.
It uses Python (Pandas) for data cleaning, PostgreSQL for business queries, and Power BI for dashboard creation. A final report was built using Gamma AI.

📁**Dataset**

Rows: 3,900

Columns: 18

Includes:

Demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item, Category, Amount, Season, Size, Color)

Behavior fields (Discount, Review Rating, Shipping Type, Previous Purchases)

Missing Values: 37 review ratings → imputed using median by category

🛠️ Tools & Technologies

Python: Pandas, NumPy

SQL: PostgreSQL

Visualization: Power BI

Reporting: Gamma AI

Environment: Jupyter Notebook / VS Code

🔧 **Steps Performed**

1️⃣ **Data Cleaning & Feature Engineering (Python)**

Loaded and inspected dataset

Standardized column names

Handled missing values

Engineered features:

age_group

purchase_frequency_days

Dropped redundant fields

Loaded cleaned data into PostgreSQL

2️⃣**SQL Business Analysis (PostgreSQL)**

Answered key questions:

Revenue by gender

High-spending discount users

Top-rated products

Standard vs Express shipping revenue

Subscribers vs non-subscribers

Discount-heavy products

Customer segmentation (New, Returning, Loyal)

Top 3 products per category

Repeat buyers vs subscription

Revenue contribution by age group

3️⃣ **Dashboard (Power BI)**

Dashboard includes:

Revenue KPIs

Age & gender analysis

Product & category insights

Customer segments

Shipping comparison

Interactive filters/slicers

📈 Results & Insights

Identified top-performing products and categories

Found strong relationship between loyalty and subscription behavior

Highlighted discount-dependent categories

Discovered spending differences across age and gender

Identified high-value customer segments for targeting

▶️ **How to Run**

Clone the repository

Run the Python notebook for data cleaning

Load cleaned data into PostgreSQL

Execute SQL scripts for insights

Open the Power BI dashboard

View final insights in Gamma AI report
