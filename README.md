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

**4. Pivot Table Analysis**
***4.1 Sales Performance by Category & Year***

Categories analysed: Books, Clothing, Electronics, Home & Kitchen, Sports & Outdoors, Toys & Games
Each category shows:
Net Sales
Quantity Sold
Year-over-Year growth (%)
<img width="661" height="690" alt="image" src="https://github.com/user-attachments/assets/5da5d08a-27b4-4922-a63f-326742758aad" />

Insight:
Sales are relatively balanced across categories, but growth patterns vary by year, indicating shifting consumer demand.

***4.2 Overall Sales Performance by Year***

Total Net Sales (2020–2024): $84.24M
Total Orders: 100,000
Average Order Value (AOV): $842
<img width="464" height="148" alt="image" src="https://github.com/user-attachments/assets/c485a0a7-e4ac-4872-a0b1-208ecd8bc449" />

Insight:
Sales peak around 2022–2023, followed by a slight decline in 2024, suggesting euphoric shopping sentiment after the pandemic. The decline could be due to depleted savings and economic fluctuations affecting income and purchasing power.
----More insights will be provided in dashboard section-----
**5. Dashboard Overview (Executive View)**

The Dashboard sheet consolidates all insights into a single, interactive page. 
**Dashboard Components:**
**KPI Cards**
Total Net Sales
Total Orders
Average Order Value
**Trend Analysis**
Sales performance over years
Quantity sold trend
**Performance Breakdown**
Sales by Category
Sales by Brand
Sales by State (map)
**Operational Risk**
Order Status distribution
Discount impact on Returns and Cancellations
**Interactive Filters**
Category
Brand
Year
<img width="1461" height="717" alt="image" src="https://github.com/user-attachments/assets/2cf4d02e-17de-4f75-9ecf-8343faba5bb9" />

**5.1 Key Business Insights**
Sales performance is stable but plateauing, indicating the need for growth initiatives.
Revenue is driven by a small group of strong brands, creating both opportunity and dependency risk.
Geographic performance is uneven, with clear high-value regions.
Low discounting increases returns and cancellations, reducing net benefit.
Digital payment methods dominate and should remain a strategic focus.

**5.2 Business Recommendations**
***Refine Discount Strategy***
Replace broad discounts with targeted, category-specific promotions, also flexibly provide big sale campaign to attract buyers
***Strengthen Top Brand Partnerships***
Prioritise inventory and marketing support for consistently high-performing brands.
***Reduce Return Risk***
Review high-return categories and promote marketing strategy to flexibly apply discount campaign to improve orders and sales.
***Regional Optimisation***
Allocate marketing and logistics resources toward high-performing states.


