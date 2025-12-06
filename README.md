# CUSTOMER_BEHAVIOR_ANALYTICS
Customer Behavior Analysis using Python 🐍 (Pandas), PostgreSQL 🐘, and Power BI 📊. Cleaned data, engineered features, answered business questions with SQL, and built an interactive dashboard. Final insights and presentation created using Gamma AI 💡 for clear storytelling.

Customer Shopping Behavior Analysis – README
📌 Overview

This project analyzes 3,900+ customer purchase records to understand shopping behavior, spending patterns, product preferences, and subscription trends. The goal is to uncover insights that support better marketing strategies, product decisions, and customer retention efforts. The workflow includes Python (Pandas), PostgreSQL SQL analysis, Power BI dashboarding, and reporting with Gamma AI.

📁 Dataset

Rows: 3,900

Columns: 18

Includes:

Customer demographics (Age, Gender, Location, Subscription Status)

Product & purchase details (Item, Category, Amount, Season, Size, Color)

Behavioral data (Discounts, Promo Code, Review Rating, Shipping Type, Frequency)

Missing Data: 37 missing values in Review Rating → imputed using median rating per category

🛠 Tools & Technologies

Python (Pandas) – Data cleaning, preprocessing, feature engineering

PostgreSQL – SQL analysis & business insights

Power BI – Dashboard creation

Gamma AI – Final reporting & presentation

Jupyter Notebook / VS Code – Development environment

🔧 Steps Performed
1. Data Cleaning & Feature Engineering (Python)

Loaded and explored dataset

Standardized column names

Imputed missing ratings

Created age_group and purchase_frequency_days

Removed redundant fields (promo_code_used)

Loaded cleaned data into PostgreSQL

2. Business Analysis (SQL in PostgreSQL)

Answered key business questions including:

Revenue by gender

High-spending discount users

Top 5 highest-rated products

Standard vs Express shipping spend

Subscriber vs non-subscriber revenue

Discount-dependent products

Customer segmentation (New, Returning, Loyal)

Top products per category

Repeat buyers & subscription patterns

Revenue by age group

3. Dashboard (Power BI)

Interactive visuals including:

KPIs (Total Revenue, Avg Spend, Subscriber Revenue)

Best products & categories

Age-group and region-wise revenue

Shipping type comparison

Customer segments (New, Returning, Loyal)

📈 Results

Identified high-value customer groups

Highlighted bestselling and top-rated products

Found strong links between loyalty & subscriptions

Identified discount-heavy categories

Revealed spending differences across gender, age, and shipping type

▶️ How to Run

Clone the repository

Open notebook and run Python script for cleaning & feature engineering

Load cleaned data into PostgreSQL

Execute SQL queries for insights

Open Power BI file to view interactive dashboard

Refer to Gamma AI report for final summary & recommendations
