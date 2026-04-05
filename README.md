# 🛍️ Customer Shopping Behavior Analysis (SQL + Python + Power BI)
## 📌 Overview

This project analyzes customer shopping behavior using transactional retail data to uncover patterns in purchasing decisions, customer segments, and revenue drivers.

The goal is to answer the business question:
**How can a retail company leverage customer data to improve engagement, optimize marketing strategies, and increase sales?**

## 🎯 Business Problem

A retail company observed shifts in purchasing patterns across:

* Customer demographics
* Product categories
* Sales channels (online vs. offline)

This project explores how factors like **discounts, reviews, seasonality, and subscription status** influence customer behavior and repeat purchases.

## 📂 Dataset
* ~3,900 transactions
* 18 features including:
  * Demographics (Age, Gender, Location)
  * Purchase data (Category, Amount, Season)
  * Behavior (Discounts, Reviews, Frequency, Subscription)

⚠️ **Note:** Dataset and problem statement are sourced from the tutorial linked below and are not originally created by me.

## 🛠️ Project Workflow
### 1. 🐍 Data Preparation (Python)
* Cleaned and transformed raw data using `pandas` 
* Handled missing values (e.g., review ratings imputed using median)
* Standardized column names (snake_case)
* Created new features:
  * `age_group`
  * `purchase_frequency_days`
* Loaded cleaned data into MySQL

### 2. 🗄️ Data Analysis (SQL)

Performed business-driven queries to extract insights:

* Revenue by gender
* High-spending customers using discounts
* Top-rated products
* Shipping type vs purchase amount
* Subscriber vs non-subscriber behavior
* Discount dependency by product
* Customer segmentation (New / Returning / Loyal)
* Revenue by age group
* Repeat purchase behavior

### 3. 📊 Data Visualization (Power BI)

Built an interactive dashboard to visualize:

* Customer segments
* Revenue trends
* Product performance
* Purchase behavior patterns

## 📈 Key Insights
* Certain customer segments contribute disproportionately to revenue
* Discounts influence purchases but may not always correlate with higher value
* Loyal customers show stronger subscription tendencies
* Product ratings and reviews significantly impact purchasing decisions

## 🚀 Tools & Technologies
* Python (Pandas)
* SQL (PostgreSQL)
* Power BI
* Data Modeling & Visualization

## ⚠️ Disclaimer
* This project is for educational and portfolio purposes only
* Dataset and project idea are sourced from an external tutorial
* No original data collection was performed

## 🙌 Acknowledgment

This project is based on the following tutorial:
👉 https://www.youtube.com/watch?v=5PrZvPeUw60

All datasets and guidance were provided in the video description.
