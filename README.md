# For data exploration and preparation 
1. Checking for missing values and inconsistencies (e.g., missing CustomerID in row 4).
2. Identifying data types and ensuring proper formats (e.g., converting TransactionDate to datetime).
3. Normalize categorical values where needed.

# Key Metrics & Insights- below are some key aggregate and drill-down insights we can extract:
A] Overall Sales Performance -
1. Total Revenue: Sum of TransactionAmount.
2. Total Transactions: Count of TransactionID.
3. Average Order Value (AOV): SUM(TransactionAmount) / COUNT(TransactionID).
4. Total Items Sold: Sum of Quantity.
   
B] Customer Demographics Analysis -
1. Sales distribution by Age Groups (e.g., <30, 30-50, >50).
2. Sales by Gender: Total revenue split by CustomerGender.
3. Top Spending Customers: ORDER BY SUM(TransactionAmount) DESC.
   
C] Store Type & Region Breakdown -
1. Online vs. In-Store Sales Contribution.
2. Regional Sales Performance: Grouping by Region.
3. Top Performing Cities & Stores.
   
D] Product & Category Performance -
1. Best-selling Products: Group by ProductName, sum Quantity.
2. Average Discount Impact on Sales.
3. Returned Products Analysis.
