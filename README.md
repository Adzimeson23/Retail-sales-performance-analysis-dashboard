# Retail-sales-performance-analysis
##📌 Project Overview
This project involves a comprehensive analysis of retail sales data to identify trends, understand customer behavior, and evaluate product performance. The goal was to transform raw sales records into an interactive dashboard that provides actionable insights for stakeholders.

## 📊 Key Features
• Total Revenue Tracking: Real-time calculation of total sales (₦456,000).
• Demographic Profiling: Breakdown of sales by Gender and Age groups (18-67).
• Product Analytics: Comparison of "Most Bought" vs. "Highest Revenue" products.
• Time-Series Analysis: Monthly sales trends to identify seasonal fluctuations.

## 🛠️ Tools & Functions Used
• Data Cleaning: Used Power Query (or Filter/Sort) to handle missing values and standardize currency formats.
• Pivot Tables & Charts: The backbone of the dashboard, used to aggregate sales by category, month, and demographics.
• Advanced Formulas:
• SUMIFS / COUNTIFS: For dynamic data segmentation.
• VLOOKUP / XLOOKUP: For merging customer data with sales records.
• TEXT(): To extract months from date strings for the trend line.
• Data Visualization: Implementation of Slicers, Line Charts, and Clustered Bar Charts for an interactive UX.

## 📈 Key Insights (Based on your data)
1.	Revenue Leader: Electronics is the primary revenue driver (exceeding ₦155k), despite "Clothing" being highly competitive in volume.
2.	Gender Balance: The customer base is nearly an equal split (~51% Female vs 49% Male), suggesting a broad market appeal.
3.	Top Volume Category: While Electronics makes the most money, Clothing is the "Most Bought" category for both Male and Female segments.
4.	Core Demographic: The 48–57 age group represents the highest purchasing frequency, particularly in the Electronics and Clothing categories.
5.	Downward Trend: Sales peaked in May (approx. ₦55k) but show a steady, significant decline through the year, hitting a low point toward September.

 ##  Recommendations
1.	Address the Seasonal Slump: Investigate the consistent month-over-month decline from May to September. A "Back to School" or mid-year clearance sale in July/August could stabilize revenue.
2.	Target the "Silver Spenders": Since the 48-57 and 58-67 age groups are highly active, marketing campaigns should be tailored to their preferences rather than focusing solely on younger demographics.
3.	Upsell in Beauty: The Beauty category has the lowest revenue and volume. Bundle Beauty products with "Most Bought" Clothing items to increase the Average Order Value (AOV).

 ##  Talking Points
• The "Why": "I built this because high-level revenue numbers often hide the 'who' and 'when.' I wanted to see if our most frequent buyers were also our most profitable ones."
• Data Integrity: "Before building the charts, I ensured the 'Age' column was grouped into logical buckets (18-27, etc.) using IF statements/VLOOKUP to make the distribution chart readable."
• Actionable Design: "I chose a dark-themed UI to make the ₦456k Total Amount pop, ensuring that a manager looking at this for 5 seconds immediately knows the bottom line."
• Handling the Trend: "If asked about the declining line chart, I’d explain that identifying a negative trend is just as valuable as a positive one, as it signals a need for a change in marketing strategy."
