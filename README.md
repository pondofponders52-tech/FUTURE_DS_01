# FUTURE_DS_01
# Repository created for Task 1 of the Data Science & Analytics Internship at Future Interns
---------------------------------------------------------------------------------------------
# Superstore Sales Analysis (Power BI Report) - Executive Summary (Indian Format)
# Business Objective
This analysis evaluates Superstore's sales performance across products, categories, regions, and time periods (2011-2014). The dashboard helps identify top products, seasonal trends, and profitability drivers for MIS reporting and business decisions.

# Data Overview
Based on Superstore order data with Sales (₹29.2L total), Profit (₹2.8L), Orders (5,009), Quantity (3,783), Discounts, Categories, Regions, and Dates. Data cleaned with proper Date Table relationships and Indian ₹ Lakh formatting.

# Key Performance Indicators (KPIs)
# 1. Category Performance
Technology: Highest sales (₹8.36L) + profit (₹1.45L) - 18-22% margins
Furniture: High sales but low profit (₹0.18L) due to 20%+ discounts
Office Supplies: Steady performer with Storage (₹2.24L) + Binders (₹2.03L)​
# 2. Product Leaders
Phones: ₹3.3L sales (Top revenue driver)
Chairs: ₹3.28L sales (Furniture volume leader despite low margins)
Copiers/Accessories: High-profit Technology sub-categories
# 3. Regional Analysis
Top States: New York (₹3.83L) → California (₹2.94L) → Florida (₹2.68L)
West Region: 46% sales share | Central: Lowest profitability
# 4. Discount Impact
Scatter plot reveals Furniture cluster (high discount → low/negative profit). Higher discounts directly erode margins across categories.​
# 5. Time Trends
Seasonality: Nov-Dec peak (holiday demand)
YoY Growth: 18% Sales growth in 2014 | Steady profit trajectory
Ship Mode: Standard Class dominates (efficiency indicator)
------------------------------------------------------------------------------------------------
# Dashboard Structure
# Page 1: Current Year Overview (2014)
Multi-row Cards (5 KPIs) → Sales Trend Line → Category Bars 
→ State Map → Region Stacked Bars → Customer Donut

# Page 2: Yearly Performance
Yearly Table (7 measures + Growth %) → Discount vs Profit Scatter 
→ Profit Trend → Top 5 Products → Ship Mode Donut → Region Cards

# Technical Highlights
DAX Measures: Sales LY, Profit Growth %, Avg Order Value, Profit Margin
Data Model: Date Table + Mark as Date Table
Formatting: ₹ Lakhs (K), Conditional Formatting (Red/Green growth)
Slicers: Year, Category, Region, State

# Business Recommendations 
Pricing Strategy: Reduce Furniture discounts >15% to improve margins
Inventory Focus: Prioritize Technology (Phones/Copiers) + West region
Q4 Planning: Scale operations for Nov-Dec peak demand
Regional Strategy: Target NY/CA/FL (75% top states sales)
Discount Control: Implement category-specific discount caps
Cross-sell: Diversify beyond top 5 products (reduce risk)
Complete portfolio dashboard demonstrates DAX, data modeling, visualization, and actionable insights.
