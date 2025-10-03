# Amazon_Sales_Report


## Introduction
This project analyzes a dummy Amazon sales dataset sourced from Kaggle to derive insights into sales performance, product trends, and customer behavior in the Indian market. The dataset, comprising *128,943 transaction records, includes details on product categories, order statuses, shipping details, and regional sales. Using **Microsoft Excel*, the analysis involves data cleaning, exploratory data analysis (EDA), and the calculation of key performance indicators (KPIs) such as total revenue (₹1,625,797), total quantity sold (2,654 units), and average transaction amount (₹591.18). Relationships were established among multiple tables (Fact Sales, DimProducts, DimDate, DimLocation, DimShipping, DimChannel) to enable multidimensional analysis. The results provide valuable insights for optimizing sales strategies, inventory management, and logistics.

This repository contains the dataset, Excel workbook, and documentation to replicate the analysis and understand the findings.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Project Overview](#project-overview)
4. [Objectives](#objectives)
5. [Dataset](#dataset)
6. [Tools Used](#tools-used)
7. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
8. [Analysis Results](#analysis-results)
9. [Recommendations](#recommendations)
10. [Conclusions](#conclusions)
11. [Installation and Usage](#installation-and-usage)
12. [Contributing](#contributing)
13. [License](#license)

---

## Problem Statement
Amazon's e-commerce platform in India generates vast amounts of transaction data across diverse product categories and regions. Without detailed analysis, it is challenging to identify top-performing products, understand customer preferences, optimize shipping processes, or detect seasonal sales trends. Using a dummy dataset from Kaggle, this project aims to analyze sales data to uncover patterns, measure performance through KPIs, and provide data-driven recommendations to enhance sales, inventory management, and customer satisfaction.

---

## Project Overview
The Amazon Sales Report Analysis project processes a dummy dataset of *128,943 sales records* from Kaggle to extract insights into sales performance, product categories, order statuses, shipping efficiency, and regional trends. Key analyses include:
- Calculating KPIs: Total revenue (₹1,625,797), total quantity sold (2,654 units), average transaction amount (₹591.18), and product category count (2,865).
- Analyzing sales by product category, order status, shipping service level, and geographic region.
- Identifying seasonal sales trends (e.g., peak sales in April, May, June; lowest in February).
- Establishing relationships among tables (Fact Sales, DimProducts, DimDate, DimLocation, DimShipping, DimChannel) for multidimensional analysis.

The analysis was conducted using *Microsoft Excel*, leveraging pivot tables, charts, and Power Pivot for data processing and visualization.

---

## Objectives
The primary objectives of this project are:
1. Calculate and analyze key performance indicators (KPIs) such as total revenue, quantity sold, and average transaction amount.
2. Evaluate sales performance by product category, order status, shipping service level, and geographic region.
3. Identify seasonal sales trends to inform inventory and marketing strategies.
4. Establish relationships among tables to enable comprehensive, multidimensional analysis.
5. Provide actionable recommendations to improve sales, logistics, and customer experience.

---

## Dataset
The dataset is a *dummy dataset* downloaded from Kaggle, simulating Amazon's sales transactions in the Indian marketplace. It contains *128,943 transaction records* and is structured into the following tables:
- *Fact Sales*: Core transaction data, including order IDs, revenue, quantities, and status.
- *DimProducts*: Product details, including categories (e.g., Set, Kurta, Top).
- *DimDate*: Date-related information, including month and year for trend analysis.
- *DimLocation*: Geographic data, including state information (e.g., Maharashtra, Tamil Nadu).
- *DimShipping*: Shipping details, including courier status (e.g., Shipped, Cancelled) and service level (Expedited, Standard).
- *DimChannel*: Sales channel information.

### Key Data Points:
- *Total Rows*: 128,943
- *Total Revenue*: ₹1,625,797 (Indian Rupees)
- *Total Quantity Sold*: 2,654 units
- *Average Transaction Amount*: ₹591.18
- *Product Categories*: 2,865 unique products
- *Time Period*: Covers sales data with monthly trends (e.g., April, May, June, February)
- *Source*: [Kaggle Amazon Sales Dataset](https://www.kaggle.com) (Note: Replace with the specific Kaggle dataset URL if available)

---

## Tools Used
- *Microsoft Excel*: Primary tool for data cleaning, transformation, analysis, and visualization.
  - *Pivot Tables*: Summarized sales by category, status, region, and shipping metrics.
  - *Charts*: Visualized sales trends, category distributions, and regional performance.
  - *Power Pivot*: Established relationships among tables (Fact Sales, DimProducts, DimDate, DimLocation, DimShipping, DimChannel).
  - *Excel Functions*: Used VLOOKUP, SUM, AVERAGE, and date extraction functions for calculations and data transformation.

---

## Data Cleaning and Preparation
The dummy dataset was cleaned and prepared to ensure accuracy and consistency:
1. *Removed Duplicates*: Identified and eliminated duplicate records to prevent skewed results.
2. *Handled Inconsistent Data*: Standardized formats for dates, product categories, and statuses.
3. *Calculated Total Revenue*: Aggregated revenue across transactions.
4. *Extracted Month*: Derived month from date fields for trend analysis.
5. *Established Table Relationships*: Linked Fact Sales with DimProducts, DimDate, DimLocation, DimShipping, and DimChannel using Power Pivot to enable multidimensional analysis.

---

## Analysis Results
The analysis yielded the following key findings:

### Key Performance Indicators (KPIs)
- *Total Revenue*: ₹1,625,797
- *Total Quantity Sold*: 2,654 units
- *Average Transaction Amount*: ₹591.18
- *Total Product Categories*: 2,865

### Sales by Product Category
- *Set*: ₹811,969 (highest revenue)
- *Kurta*: ₹493,060 (second highest)
- *Top*: ₹127,722 (third highest)

### Order Status Breakdown
- *Shipped*: 1,699 orders
- *Shipped - Delivered to Buyer*: 798 orders
- *Cancelled*: 288 orders
- *Shipped - Returned to Seller*: 51 orders
- *Shipped - Picked Up*: 13 orders
- *Pending*: 9 orders
- *Pending - Waiting for Pickup*: 7 orders
- *Shipped - Returned to Seller (Other)*: 2 orders

### Courier Status
- *Shipped*: 2,559 orders
- *Cancelled*: 233 orders
- *Unshipped*: 73 orders

### Sales by Shipping Service Level
- *Expedited*: Highest sales volume
- *Standard*: Second highest

### Top 10 States by Total Revenue
1. Maharashtra (highest)
2. Tamil Nadu
3. Karnataka
4. Kerala
5. Uttar Pradesh
6. West Bengal
7. Telangana
8. Andhra Pradesh
9. Gujarat
10. Delhi

### Sales Trends
- *Peak Sales*: April (highest), followed by May and June.
- *Lowest Sales*: February.

### Visualizations
- Pivot tables and charts were created to visualize:
  - Revenue distribution by product category.
  - Order status and courier status breakdowns.
  - Regional sales performance.
  - Monthly sales trends.

---

## Recommendations
Based on the analysis, the following recommendations are proposed:
1. *Focus on High-Performing Categories*: Prioritize inventory and marketing for "Set" and "Kurta" categories, which contribute significantly to revenue (₹811,969 and ₹493,060, respectively).
2. *Reduce Cancellations*: Investigate the reasons behind 288 cancelled orders and 233 cancelled shipments to improve customer satisfaction and operational efficiency.
3. *Optimize Shipping*: Promote Expedited shipping, which outperforms Standard, to enhance delivery speed and customer experience.
4. *Target Top Regions*: Increase marketing efforts in Maharashtra, Tamil Nadu, and Karnataka, which are the top revenue-generating states.
5. *Seasonal Strategy*: Stock inventory and plan promotions for April, May, and June to capitalize on peak sales periods, while analyzing reasons for low sales in February.
6. *Improve Data Quality*: Standardize data entry processes to minimize inconsistencies and duplicates in future datasets.

---

## Conclusions
The Amazon Sales Report Analysis, based on a dummy dataset from Kaggle, provides a comprehensive view of simulated sales performance in the Indian market. Key findings highlight the dominance of the "Set" and "Kurta" product categories, the efficiency of Expedited shipping, and strong sales in Maharashtra and Tamil Nadu. Seasonal trends show peak sales in April, May, and June, with February being the slowest month. By establishing relationships among tables, the analysis enabled a multidimensional understanding of sales dynamics. The insights and recommendations can guide hypothetical strategies for optimizing inventory, improving logistics, and targeting high-potential regions and seasons to drive growth.

---

## Installation and Usage
### Prerequisites
- *Microsoft Excel*: Version 2016 or later (with Power Pivot enabled).
- *Dataset*: Download the dummy dataset from the data/ folder in this repository or from the original Kaggle source.

### Steps to Replicate the Analysis
1. *Clone the Repository*:
   ```bash
   git clone https://github.com/your-username/amazon-sales-report.git
