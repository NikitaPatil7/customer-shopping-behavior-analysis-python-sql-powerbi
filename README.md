# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior for a retail company to uncover purchasing patterns, revenue drivers, and customer engagement insights.  
The goal is to help businesses improve sales performance, customer satisfaction, and long-term loyalty using data-driven decision-making.

The analysis follows an **end-to-end analytics workflow**, leveraging **Python for data preprocessing**, **PostgreSQL for advanced SQL analysis**, and **Power BI for interactive visualization**.

---

## Business Problem
A retail company wants to understand:
- How customer demographics influence purchasing behavior
- Which product categories and customer segments drive the most revenue
- Whether discounts and subscriptions impact spending and loyalty
- How customer engagement varies across age groups and categories

**Key Question:**  
*How can customer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?*

---

## Dataset Overview
- **Rows:** 3,901  
- **Columns:** 14 (after cleaning and feature engineering)
- **Format:** CSV  
- **Data Includes:**
  - Customer demographics (age, gender, location)
  - Product details (category, item, size, color)
  - Purchase behavior (amount, frequency, discounts)
  - Engagement metrics (review ratings, subscription status)
  - Shipping and payment preferences

---

## Tools & Technologies
- **Python** (Pandas, NumPy)
- **PostgreSQL** (SQL, CTEs, Window Functions)
- **Power BI**
- **Jupyter Notebook**
- **Git & GitHub**

---

## Project Workflow

### 1️. Data Cleaning & EDA (Python)
- Loaded and explored the dataset using Pandas
- Handled missing values using **category-wise median imputation**
- Standardized column names using snake_case
- Performed feature engineering:
  - Created age groups using quantile-based binning
  - Converted textual purchase frequency into numeric days
- Identified and removed redundant columns

---

### 2️. Advanced SQL Analysis (PostgreSQL)
- Connected Python to PostgreSQL using SQLAlchemy and psycopg2
- Loaded cleaned data into a relational database
- Answered real business questions using:
  - Aggregations
  - Subqueries
  - CTEs
  - Window functions
  - Conditional logic

**Sample Business Questions:**
- Do subscribed customers spend more than non-subscribers?
- Which products have the highest average review ratings?
- How does revenue vary across age groups and categories?
- What is the impact of discounts on high-value purchases?

---

### 3️. Data Visualization (Power BI)
- Built an interactive executive dashboard with:
  - KPIs: Total Customers, Avg Purchase Amount, Avg Rating
  - Revenue and sales breakdown by category and age group
  - Subscription distribution
  - Dynamic filters for deeper insights
- Connected Power BI directly to PostgreSQL for live analysis

---

## Key Insights
- Clothing is the highest revenue-generating category
- Only ~27% of customers are subscribed, indicating strong growth potential
- Young adults and middle-aged customers contribute the most revenue
- Discounts are frequently used by high-spending customers, not just low spenders
- Subscribers show higher engagement and purchase value

---

## Business Recommendations
- Increase focus on subscription-based customer retention
- Target young adult and middle-aged segments with personalized campaigns
- Optimize discount strategies for high-value customers
- Improve performance of underperforming categories through bundling or seasonal promotions

---
