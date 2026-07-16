# MetricMind - Data Dictionary

## Project Name

MetricMind: Agentic Semantic BI Engine

## Dataset Name

sales_data.csv

## Description

The dataset contains transactional sales data for a fictional global electronics company during the year 2024.

It is designed for business intelligence, SQL analysis, Power BI dashboards, machine learning, and conversational AI analytics.

---

# Dataset Information

| Property | Value |
|----------|-------|
| Dataset Name | sales_data.csv |
| Total Records | 25,000 |
| Total Columns | 16 |
| Time Period | January 2024 – December 2024 |
| Industry | Electronics Sales |
| Regions | 6 |
| Countries | 20 |
| Products | 10 |

---

# Column Definitions

| Column Name | Data Type | Description | Example |
|--------------|-----------|-------------|---------|
| Order_ID | String | Unique identifier for each order | ORD000001 |
| Order_Date | Date | Date when the order was placed | 2024-05-14 |
| Region | String | Sales region | Europe |
| Country | String | Country where the sale occurred | Germany |
| Product | String | Product sold | Laptop |
| Category | String | Product category | Computers |
| Customer_Type | String | Customer segment | Retail |
| Quantity | Integer | Number of units sold | 8 |
| Unit_Price | Decimal | Price of one product | 850.00 |
| Revenue | Decimal | Total sales amount | 6800.00 |
| Material_Cost | Decimal | Manufacturing cost | 2900.00 |
| Shipping_Cost | Decimal | Delivery expense | 420.00 |
| Operational_Cost | Decimal | Business operating cost | 560.00 |
| Total_Cost | Decimal | Sum of all costs | 3880.00 |
| Profit | Decimal | Revenue minus Total Cost | 2920.00 |
| Margin | Decimal | Profit percentage | 42.94 |

---

# Business Rules

Revenue

Revenue = Quantity × Unit Price

---

Total Cost

Total Cost = Material Cost + Shipping Cost + Operational Cost

---

Profit

Profit = Revenue − Total Cost

---

Margin

Margin (%) = (Profit / Revenue) × 100

---

# Business Scenario

The dataset simulates a multinational electronics company operating across multiple regions.

A special business condition has been intentionally introduced:

• During Quarter 3 (July–September), shipping costs increase significantly in Europe.

As a result:

- Total Cost increases
- Profit decreases
- Margin decreases

This scenario enables the AI assistant to perform root cause analysis for questions such as:

"Why did European margins drop in Q3?"

---

# Supported Business Analysis

The dataset supports:

- Revenue Analysis
- Cost Analysis
- Profit Analysis
- Margin Analysis
- Product Analysis
- Regional Analysis
- Quarterly Analysis
- Trend Analysis
- Root Cause Analysis
- Business Intelligence Dashboards

---

# Intended Usage

This dataset is designed for:

- SQL Queries
- Python Data Analysis
- Pandas
- Power BI
- Machine Learning
- Streamlit Applications
- MetricMind Conversational BI Engine

---

# Author

Project: MetricMind

Prepared for Internship Project