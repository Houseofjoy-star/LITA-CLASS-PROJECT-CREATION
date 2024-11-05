# LITA-CLASS-PROJECT-CREATION
This is where i want to keep my first project while learning Data Analysis with the Incubator Hub

# Sales Overview
## Total Sales
- Visual Type: Card
- Measure: Total Sales = SUM(Sales[Quantity] * Sales[UnitPrice])
- Insight: Displays the overall sales value, providing a quick view of revenue performance.
- Design Tip: Position this card at the top for visibility. Use bold fonts and a large size to make it prominent.

## Average Order Value (AOV)
- Visual Type: Card
- Measure: AOV = DIVIDE([Total Sales], [Total Orders])
- Insight: Shows the average revenue per order, which is a key performance metric for sales.
- Design Tip: Position this alongside the Total Sales and Total Orders cards. Use a unique color to differentiate it as a calculated metric.

 ## Sales Trends Over Time
### Monthly Sales Trend
- Visual Type: Line Chart
- Axis Setup:
- X-axis: OrderDate (set to month/year format)
- Y-axis: Total Sales
- Insight: This line chart shows sales trends over time, helping you observe peaks and dips in sales.
- Design Tip: Enable data markers to clearly show each month’s data point. Include tooltips with exact sales numbers and order counts for more detailed insights.

