# Amazon_Sales_Ananlysis_Excel
An end-to-end Excel project that cleans, enriches and analyses Amazon order data to find which products and regions drive revenue and where delivery performance falls short.

# What's inside:

Data: AmazonSales (100 orders) linked to ProductMaster, CustomerMaster and RegionGoals sheets.
Data prep: XLOOKUP pulls product category, product name and customer name into the sales table. Calculated columns flag cancelled orders, delivery time and Fast/Slow delivery (Fast is 2 days or less).
Analysis: Pivot tables for sales by region, category, month and delivery status, plus KPI pivots.
Dashboard: An interactive dashboard with slicers.
Brainstorming Reflection: Written answers to the business questions.

# Key findings:

Total revenue is $35,258. Electronics leads at $15,209, and Smartphone is the top product ($9,644).
North is the top region by revenue ($10,491) and also has the highest cancellation rate (40%).
30% of orders were cancelled, and effective sales (delivered orders only) are $13,656.
Only 11 of 34 delivered orders (about 32%) arrived within 2 days, and average delivery time is 3.76 days.

# Recommendations:

Focus on North and Central, which have both high cancellations and slow deliveries.
Improve the share of fast deliveries.
Fix service quality in North first, since it's both the top-revenue and top-cancellation region.

# Tools: 
Excel (XLOOKUP, structured tables, pivot tables, slicers, dashboard)
