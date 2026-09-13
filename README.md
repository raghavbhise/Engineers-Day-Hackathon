# Interactive Retail Sales & Profitability Analytics Dashboard

## 📌 Project Overview

The **Interactive Retail Sales & Profitability Analytics Dashboard** is an Excel-based data analytics solution designed to transform raw retail transaction data into clear, actionable business insights.

The dashboard provides an interactive view of sales, profit, profitability, customer segments, product performance, regional performance, shipping modes, and discounting patterns. It enables decision-makers to identify major profit drivers, detect loss-making products and regions, and understand how discounting affects overall profitability.

---

## 🎯 Problem Statement

While retail sales are growing across multiple cities, leadership often lacks a consolidated and interactive view of what is actually driving net profit and what is eroding margins.

Issues such as:

- Excessive discounting
- Loss-making products
- Underperforming sub-categories
- Regional profitability gaps
- Differences in customer segment performance
- Fluctuations in monthly sales and profit

can remain hidden within large volumes of transactional data.

Without a centralized and filterable dashboard, decision-makers may struggle to quickly identify profitability risks and prioritize areas that generate the highest returns.

---

## 🎯 Project Objective

The primary objective is to build an **interactive and dynamic retail performance dashboard in Microsoft Excel** that consolidates sales data into meaningful business insights.

The dashboard aims to help management:

- Monitor revenue and profitability
- Identify major sales and profit drivers
- Detect loss-making products and sub-categories
- Analyze the impact of discounting
- Compare customer segments
- Evaluate regional performance
- Understand shipping-mode distribution
- Identify trends and fluctuations over time
- Support data-driven pricing and business decisions

---

## 📊 Key Business Questions

The analysis is designed to answer the following questions:

1. Which categories and sub-categories drive the majority of revenue, and which consistently generate negative profit?

2. Which are the top 10 most profitable products and bottom 10 loss-making products that require management attention?

3. How does revenue contribution compare with profit contribution across product categories?

4. At what discount level does profitability begin to deteriorate?

5. Does aggressive discounting increase sales and transaction volume, or does it primarily erode profit margins?

6. How does profitability vary across product sub-categories under different discount levels?

7. Which regions, states, and cities generate the strongest profitability, and which operate at a loss?

8. Are geographic profitability differences related to demand, product mix, or discounting?

9. Which cities generate high sales but negative profitability?

10. How do AOV, sales, and profitability differ across Consumer, Corporate, and Home Office segments?

11. Which shipping modes provide the best balance between order volume and profitability?

12. What are the monthly and quarterly sales and profit trends, and are there identifiable seasonal patterns?


---

## 📈 Dashboard Features

### KPI Section

The dashboard provides key performance indicators including:

- **Total Revenue**
- **Total Profit**
- **Profit Margin (%)**
- **Total Units Sold**
- **Total Orders**
- **Average Order Value (AOV)**
- **Average Discount (%)**
- **Loss-Making Orders (%)**
- **Profit per Order**

These KPIs provide a quick overview of the overall health of the business.

---

## 📊 Dashboard Analysis

### 1. Sales & Profit Trend

Analyzes yearly and monthly sales and profit performance to identify growth patterns, fluctuations, and periods of strong or weak performance.

### 2. Sales & Profit by Customer Segment

Compares Consumer, Corporate, and Home Office segments to identify the primary revenue and profitability contributors.

### 3. Category Performance

Compares sales and profit across:

- Furniture
- Office Supplies
- Technology

This helps identify categories that generate high revenue but comparatively weak profitability.

### 4. Sub-Category Performance

Provides a detailed comparison of sales and profit across individual sub-categories and identifies loss-making areas such as Tables and Bookcases.

### 5. Top 10 Products by Profit

Identifies products that contribute the most to overall profitability and highlights high-value products that should be prioritized.

### 6. Bottom 10 Products by Profit

Identifies products generating the largest losses despite their sales contribution, helping management identify candidates for repricing, discount optimization, supplier negotiation, or discontinuation.

### 7. Regional Performance

Compares sales and profit across regions to identify high-performing and underperforming geographic markets.

### 8. Discount Analysis

Analyzes the relationship between discount levels, sales, profit, and order volume to determine whether higher discounts generate sufficient additional demand to justify the margin reduction.

### 9. Shipping Mode Analysis

Evaluates order distribution and profitability across:

- Standard Class
- Second Class
- First Class
- Same Day

### 10. Monthly Segment Analysis

Analyzes monthly sales and profitability across customer segments to identify periods of strong or weak segment performance.

---

## 🔍 Key Insights

The dashboard provides several important business insights:

- **Technology** is the strongest overall category in terms of both sales and profit.
- **Furniture** generates substantial sales but significantly lower profit, indicating margin-efficiency issues.
- **Tables and Bookcases** are important loss-making sub-categories requiring further investigation.
- **Consumer** is the dominant customer segment and the primary contributor to overall sales and profit.
- **West** is the strongest-performing region in terms of both sales and profit.
- Several high-sales products generate negative profit, demonstrating that **high revenue does not necessarily indicate strong profitability**.
- Higher discount levels do not consistently generate proportional increases in sales or orders and can significantly reduce profitability.
- **Standard Class** dominates shipping volume and contributes the largest share of shipping-mode profitability.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- **Power Query**
- **PivotTables**
- **PivotCharts**
- **Excel Formulas**
- **Slicers**
- **Interactive Dashboard Design**

---

## 📂 Dataset

The project uses a retail **Superstore transactional dataset** containing sales, profit, product, customer, geographic, shipping, quantity, and discount information.

### Important Fields

- Order ID
- Order Date
- Category
- Sub-Category
- Product Name
- Region
- State
- City
- Sales
- Profit
- Discount
- Quantity

---

## 🔄 Methodology

The project follows the following analytical workflow:

```text
Raw Transaction Data
        ↓
Data Cleaning & Preparation
        ↓
Power Query / Excel Transformation
        ↓
PivotTables & Calculations
        ↓
KPI Development
        ↓
PivotCharts & Visualizations
        ↓
Interactive Slicers
        ↓
Business Analysis
        ↓
Insights & Recommendations
