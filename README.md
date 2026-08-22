# 🛍️ E-Commerce Customer Analytics

## 📋 Project Overview

This project analyzes e-commerce customer transaction data to understand **customer behavior, purchasing patterns, customer value, and revenue concentration**.

Using Python and customer-level analytics, the project applies **RFM segmentation, Customer Lifetime Value (CLV), and Pareto analysis** to identify valuable, loyal, at-risk, and high-potential customers.

The goal is to transform transactional data into **actionable business insights** that can support customer retention, targeted marketing, and revenue growth.

## 🎯 Business Problem

E-commerce businesses generate large volumes of transaction data, but raw transaction records do not clearly show **which customers are most valuable, which customers are at risk, or where revenue is concentrated**.

This project addresses the following business questions:

- 👥 Which customers are repeat buyers versus one-time customers?
- 💰 Which customers generate the most revenue?
- 🎯 Which customer segments are the most valuable?
- ⚠️ Which customers are at risk of becoming inactive?
- 🚀 Which customers have high potential for future growth?
- 📈 How concentrated is revenue across the customer base?
- 💡 What strategies can improve customer retention and revenue?

The objective is to provide **data-driven insights that support customer retention, targeted marketing, and revenue optimization**.

## 🧹 Data Preparation & Cleaning

The raw e-commerce transaction data was cleaned and prepared to ensure reliable customer-level analysis.

Key cleaning steps included:

- 🧹 Removing duplicate records
- ❌ Removing invalid or negative quantities
- 💰 Removing zero or negative unit prices
- 🚫 Identifying and handling cancelled transactions
- 🔍 Handling missing customer information
- 📦 Removing non-product transactions
- 📅 Standardizing date-related fields
- ✅ Validating the final dataset for analysis

After cleaning, the dataset contained **392,693 valid transactions** used for the analysis.

## ⚙️ Feature Engineering

To support customer-level analysis, new features were created from the cleaned transactional data. These features provide the foundation for customer behavior analysis, RFM segmentation, and Customer Lifetime Value (CLV) estimation.

The following features were created:

- 💰 **Revenue** = Quantity × Unit Price
- 📅 **Invoice Year**
- 📆 **Invoice Month**
- 📊 **Invoice Quarter**
- 🗓️ **Invoice Day**
- 📅 **Invoice Weekday**
- ⏳ **Customer Tenure**
- 🔄 **Purchase Frequency**
- 🛒 **Average Order Value**
- 💵 **Revenue Band**
- 👥 **Customer Type**

## 👥 Customer Dataset Creation

The cleaned transaction data was aggregated at the customer level to create a dedicated dataset for customer analytics.

The resulting customer dataset contains **4,338 unique customers** and includes key metrics such as:

- 💰 **Total Revenue**
- 🛒 **Total Orders**
- 📦 **Total Quantity**
- 📅 **First Purchase**
- 📅 **Last Purchase**
- 💵 **Average Order Value**
- ⏳ **Customer Tenure**
- 🔄 **Purchase Frequency**
- 📊 **Revenue Band**
- 👥 **Customer Type**
- 🎯 **Recency**
- ⭐ **RFM Scores**
- 💎 **Estimated CLV**

## 📈 Customer Behavior Analysis

Customer purchasing behavior was analyzed to understand how frequently customers purchase and how much value they generate.

The analysis focused on:

- 👥 Customer purchasing patterns
- 🔄 Repeat vs. one-time customers
- 💰 Customer spending behavior
- 🛒 Purchase frequency
- 📊 Average customer revenue
- 🌍 Customer distribution by country

### 🔑 Key Findings

- 👥 **4,338 unique customers** were identified.
- 🔄 **2,845 customers (65.58%)** were repeat buyers.
- 🛒 **1,493 customers (34.42%)** made only one purchase.
- 💰 Average customer revenue was approximately **£2,048.69**.

## 🎯 RFM Customer Segmentation

RFM analysis was used to segment customers based on three key dimensions:

- 🕐 **Recency (R):** How recently a customer made a purchase
- 🔄 **Frequency (F):** How often a customer made purchases
- 💰 **Monetary (M):** How much a customer spent

Customers were scored across these dimensions and grouped into actionable customer segments.

### 👥 Customer Segments

| Segment | Customers |
|---|---:|
| 🏆 Champions | 957 |
| 💎 Loyal Customers | 453 |
| 🚀 Potential Loyalists | 284 |
| 🆕 New Customers | 99 |
| ⚠️ At-Risk Customers | 453 |
| 💤 Hibernating Customers | 1,050 |
| 🛒 Occasional Customers | 559 |
| 👥 Other Customers | 483 |

This segmentation helps the business develop **targeted strategies for customer retention, engagement, and growth**.

## 💰 Customer Value Analysis

Customer value was analyzed using **Customer Lifetime Value (CLV), Pareto analysis, revenue contribution, and high-value customer identification**.

### 💎 Customer Lifetime Value (CLV)

Estimated CLV was used to identify customers with stronger potential to generate revenue over their relationship with the business.

### 📈 Pareto Analysis

Pareto analysis was used to examine **revenue concentration** and determine how much of the business's revenue is generated by its highest-value customers.

### 🏆 High-Value Customers

The analysis identified the customers generating the highest revenue, allowing the business to prioritize them for retention and personalized engagement.

### 💰 Revenue Contribution

The **Champions segment**, consisting of 957 customers, generated approximately **65.17% of total revenue**, making it the most valuable customer segment.

### 🚀 High-Potential Customers

Customers with strong potential to increase their purchasing activity were identified for targeted engagement, cross-selling, and retention strategies.

## 📊 Data Visualization & Insights

Visualizations were created to communicate key customer and revenue insights clearly and support data-driven decision-making.

### 📌 Visualizations Included

- 👥 One-Time vs. Repeat Customers
- 🎯 Customer Distribution by Segment
- 💰 Revenue Contribution by Segment
- 💎 Customer Lifetime Value (CLV) Distribution
- 📈 Pareto Revenue Analysis
- 🏆 Top 10 High-Value Customers

The visualizations highlight **customer composition, revenue concentration, customer value, and opportunities for targeted retention and growth strategies**.

## 💡 Executive Business Recommendations

Based on the customer segmentation and value analysis, the following strategies are recommended:

- 🏆 **Protect Champions:** Prioritize retention and personalized experiences for Champions, who generate the largest share of revenue.
- 💎 **Strengthen Loyal Customers:** Use loyalty programs, personalized offers, and cross-selling to increase customer value.
- 🚀 **Convert Potential Loyalists:** Encourage more frequent purchases through targeted promotions and product recommendations.
- ⚠️ **Re-engage At-Risk Customers:** Launch targeted win-back campaigns to prevent valuable customers from becoming inactive.
- 💤 **Reactivate Hibernating Customers:** Use personalized incentives and re-engagement campaigns to bring inactive customers back.
- 🆕 **Nurture New Customers:** Develop onboarding and follow-up campaigns to convert first-time buyers into repeat customers.
- 📊 **Focus on High-Value Customers:** Use customer value insights to prioritize marketing and retention resources where they can generate the greatest return.

## 🔗 Project Links

- 📓 **Kaggle Notebook:** [E-Commerce Customer Analytics](https://www.kaggle.com/code/ugwuonudennis/e-commerce-customer-analytics)
- 🐙 **GitHub Repository:** [E-Commerce Customer Analytics](https://github.com/ugwuonudennis/e-commerce-customer-analytics)

## 👤 Author

### Dennis Chinonso Ugwuonu

**Mathematics Graduate | Data Analyst | Business Intelligence | Data Science**

**Technical Skills:** Python • SQL • Excel • Power BI • Data Analysis • Data Visualization

## 🌐 Connect With Me

- 🐙 **GitHub:** [@ugwuonudennis](https://github.com/ugwuonudennis)
- 💼 **LinkedIn:** [Dennis Chinonso Ugwuonu](https://www.linkedin.com/in/dennis-chinonso-ugwuonu-6b121624b/)
