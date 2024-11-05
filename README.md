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

## Powerbi Ans.
### Step 1: Prepare Your Data
- Create a Table: Ensure your data is formatted as a table in Excel for easy manipulation. Go to Insert > Table and select your data range.
- Add Calculated Columns: Add a Total Sales column using the formula =Quantity * UnitPrice if not already done.
- Convert Order Date to Month & Year Columns: This will make it easier to group data by month and year in PivotTables.
Use Excel formulas like =TEXT(OrderDate, "YYYY-MM") in a new column called OrderMonth.


### Step 2: Set Up the Dashboard Layout
- Create a new worksheet and name it Dashboard.
- Organize the layout with separate sections for the Sales Overview, Top-Performing Products, and Regional Breakdown.
- Leave space for charts and slicers for interactivity.

### Step 3: Sales Overview Section
A. Monthly Sales Trend Chart
- Create a PivotTable:
- Rows: OrderMonth (group by month and year).
- Values: Sum of Total Sales.
- Insert a line chart based on the PivotTable to show the monthly trend of total sales.
- Place the chart in the Sales Overview section and add titles, labels, and data points as needed.

## Example Dashboard Layout
Here’s a suggested layout for your Dashboard sheet:
- Section	Contents
- Sales Overview	Monthly Sales Trend Chart, Total Sales KPI
- Top-Performing Products	Bar Chart of Total Sales by Product
- Regional Breakdown	Pie Chart of Sales by Region
- Additional Insights	Top 5 Customers Chart, Year-over-Year Comparison Chart
- Slicers	Year, Region, Product slicers for filtering









