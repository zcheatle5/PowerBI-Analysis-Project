# PowerBI-Project

## Project Proposal
Utilize PowerQuery, DAX, and powerful visualizations in PowerBI to analyze the AdventureWorks Bike Rental Business and provide and executive summary for business owners.

## Tools Used
- PowerBI

## Methodology

### PowerQuery
1. Import the following AdvenutreWorks data tables into PowerBI using PowerQuery:
  - Calendar_Lookup
  - Customer_Lookup
  - Product_Category_Lookup
  - Product_Subcategory_Lookup
  - Territory_Lookup
  - Returns
  - Sales
  
2. Clean up and verify column names and data types

3. Create a Rolling Calendar table

### DAX
1. Create the following DAX measures for the Sales table:
- Order Calculations
  - Order Target
  - Quantity Sold
  - % of All Orders
  - ALL Orders
  - Bulk Orders
  - High Ticket Orders
  - Weekend Orders
  - Prev Month Orders
  
- Sales Calculations
  - Revenue Target
  - Total Cost
  - Total Profit
  - Total Revenue
  - YTD Revenue
  - 10 Day Rolling Revenue
  - 90 Day Rolling Revenue
  - Prev Month Revenue

2. Create the following DAX measures for the Returns table:
  - % of All Returns
  - ALL Returns
  - Bike Returns
  - Prev Month Returns
  - Quantity Returned
  - Return Rate
  - Total Returns
  
### Visualizations
1. Executive Summary: high level breakdown of order and sales data
  - Top product (orders): Water Bottle - 30oz
  - Top product (profit): Mountain Bike - 200 black, 46
  - Total orders by category:
    - Accessories 17,000
    - Bikes 11,000
    - Clothing 7,000
    
2. Key Influencer of Customer Ordering Behavior
  - The liklihood of a customer ordering multiple items per order increases by 1.18x if they are from Canada and 1.08x if they are from the Northwestern region of USA. 
