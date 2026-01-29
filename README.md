# Sales Analytics
1. What Is Sales Analytics?
- Sales analytics is the process of using historical and current sales data to understand sales performance, customer behavior, and revenue trends, and to support business decisions related to growth and efficiency.
- In practical terms, sales analytics answers questions such as:
    - How are we performing against our revenue targets?
    - Which products, regions, or sales reps are driving results?
    - Where are deals getting stuck or lost?
    - What can we expect in future revenue?
- Sales analytics turns raw transactional and CRM data into structured insights that sales leaders, operations teams, and executives rely on to make informed decisions.
- Why this matters: Without sales analytics, organizations rely on intuition or incomplete views of performance, which can lead to poor forecasting, inefficient sales processes, and missed revenue opportunities.

## Example 1  
This project analyzes e-commerce sales and profitability across time, region, and product mix. The pipeline is simple: a flat sales dataset → Tableau visuals → executive KPIs. The dashboard answers: How are sales and profit trending, which states and categories drive results, where are losses concentrated, and which products lead revenue.

## Dataset
- Scope: U.S. retail orders with product, customer, geography, and financials.
- Typical fields: Order ID, Order Date, Ship Date, Customer ID, Segment, State, Region, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit.
- File: Ecommerce Sales Analysis.xlsx 
- Grain: One row per order line item.

## Dasboard
  <img width="2048" height="1267" alt="image" src="https://github.com/user-attachments/assets/342c05dc-4f16-46bb-aae6-d3bd85ff3620" />
  
**KPIs and insights**\
  Top KPIs: 
  - Profit Margin
  - Customer Count
  - Total Sales
  - Total Profit

**What the visuals show**

1. Sales & Profit trend : Sales are generally rising through the year with a noticeable late-year spike. Profit tracks sales but with sharper dips, suggesting discounting or cost spikes in some months.
2. Profit by region : Western and Northeastern states contribute sizable profit; a few states show negative profit pockets (likely heavy discounting, high returns, or unprofitable SKUs).
3. Category → Sub-category performance : Technology and Office Supplies lift overall profit; some Furniture sub-categories swing negative. Sub-category granularity is key for pruning low-margin items.
4. Category sales share : Sales are fairly balanced across the three top-level categories, with Technology slightly leading. Balanced mix reduces concentration risk.
5. Top 10 products : Phones, Chairs, Storage, Tables, and Binders dominate sales. Track their price sensitivity and return rates; small changes here move the needle the most.\

