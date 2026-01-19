# Amazon-Sales-Performance
**1. Project Overview**

This project analyses 100,000 Amazon retail transaction records to evaluate sales performance, customer purchasing behaviour, discount effectiveness, and operational outcomes across multiple years.
The analysis was conducted entirely in Microsoft Excel, using cleaned and prepared data from Kaggle,  creating Pivot Tables for analysis, and a one-page executive dashboard for data storytelling.
The goal is to provide decision-makers with a clear, refreshable, and interactive view of business performance.

**2. Business Objectives**

This analysis was designed to answer the following key business questions:
How has net sales evolved over time (2020–2024)?
Which product categories and brands drive the most revenue?
How does sales performance vary by state and geography?
What is the distribution of order statuses (Delivered, Returned, Cancelled, Pending, Shipped)?
How do discount levels impact cancellations and returns?
Which payment methods contribute most to sales volume?

**3. Data Preparation**
Key Preparation Steps:
Standardised data types for dates and numeric fields
Created calculated fields:
Gross Sales = Quantity × Unit Price
Discount Amount = Gross Sales x Discount rate
Net Sales = Gross Sales - Discount Amount
Created Discount Bands (0–5%, 6–10%, 11–15%, etc.) by Nestedif

4. Pivot Table Analysis
4.1 Sales Performance by Category & Year

Categories analysed: Books, Clothing, Electronics, Home & Kitchen, Sports & Outdoors, Toys & Games
Each category shows:
Net Sales
Quantity Sold
Year-over-Year growth (%)
<img width="661" height="690" alt="image" src="https://github.com/user-attachments/assets/5da5d08a-27b4-4922-a63f-326742758aad" />

Insight:
Sales are relatively balanced across categories, but growth patterns vary by year, indicating shifting consumer demand.
