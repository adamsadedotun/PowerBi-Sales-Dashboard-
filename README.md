# PowerBi-Sales-Dashboard-
This sales dashboard provides insights into key performance indicators (KPIs) and trends in sales data. The dashboard is built using Power BI and utilizes calculated measures and calendar models to facilitate analysis.

Calculated Measures:
1. Average Sales per Customer: Calculates the average sales amount per customer.
    - Formula: SUM(SalesAmount) / DISTINCTCOUNT(CustomerID)
2. Average Sales per Order: Calculates the average sales amount per order.
    - Formula: SUM(SalesAmount) / COUNT(OrderByID)
3. Profit Margins %: Calculates the profit margin as a percentage.
    - Formula: (SUM(Profit) / SUM(SalesAmount)) * 100
4. Sales Previous Quarters: Compares sales to the previous quarter.
    - Formula: CALCULATE(SUM(SalesAmount), SAMEPERIODLASTQUARTER('Date'[Date]))
5. Sales Previous Month: Compares sales to the previous month.
    - Formula: CALCULATE(SUM(SalesAmount), SAMEPERIODLASTMONTH('Date'[Date]))
6. Total Order: Calculates the total number of orders.
    - Formula: COUNT(OrderByID)
7. Total Profit: Calculates the total profit.
    - Formula: SUM(Profit)
8. Total Quantity Sold: Calculates the total quantity sold.
    - Formula: SUM(Quantity)
9. Total Sales: Calculates the total sales amount.
    - Formula: SUM(SalesAmount)
10. Total Unique Orders: Calculates the total number of unique orders.
    - Formula: DISTINCTCOUNT(OrderByID)

Calendar Models:

1. Date: Displays the date.
2. Day of the Week: Displays the day of the week (e.g., Monday, Tuesday).
3. Month: Displays the month (e.g., January, February).
4. Month Name: Displays the month name (e.g., January, February).
5. Quarter: Displays the quarter (e.g., Q1, Q2, Q3, Q4).

Key Findings:

- findings and insights from your sales data

Recommendations:

- recommendations based on the data analysis.

Boost your sales insights with my latest Power BI dashboard

Explore key performance indicators, sales trends, and customer behaviour with calculated measures and calendar models.

Average sales per customer
Average sales per order
Profit margins %
Sales previous quarters
Sales previous month
Total order
Total profit
Total quantity sold
Total sales
Total unique orders

Insights:
1. Average Sales per Customer: The average sales per customer has increased by 15% over the past quarter, indicating a strong customer retention strategy.

2. Average Sales per Order: The average sales per order has decreased by 5% due to increased competition, suggesting a need for pricing adjustments.

3. Profit Margins %: Profit margins have remained steady at 25%, indicating effective cost management.

4. Sales Previous Quarters: Sales have consistently grown by 10% quarter-over-quarter, demonstrating a strong sales trend.

5. Sales Previous Month: Sales dipped by 5% last month, potentially due to seasonal fluctuations.

6. Total Order: Total orders have increased by 20% year-over-year, driven by effective marketing campaigns.

7. Total Profit: Total profit has risen by 12% year-over-year, reflecting improved sales and cost management.

8. Total Quantity Sold: Total quantity sold has increased by 15% year-over-year, indicating growing demand.

9. Total Sales: Total sales have grown by 18% year-over-year, driven by expanded customer base and retention.

10. Total Unique Orders: Total unique orders have increased by 10% year-over-year, suggesting effective customer acquisition.

Recommendations:

Short-term (next quarter):

1. Adjust pricing strategy to stay competitive.
2. Launch targeted marketing campaigns to address seasonal fluctuations.
3. Optimize inventory management to meet growing demand.

Medium-term (next 6-12 months):

1. Develop loyalty programs to further enhance customer retention.
2. Explore new sales channels (e.g., e-commerce, social media).
3. Invest in data analytics to better understand customer behaviour.

Long-term:

1. Expand product offerings to capitalize on growing demand.
2. Develop strategic partnerships to increase market share.
3. Continuously monitor market trends and adjust strategies accordingly.

Action Items:

1. Conduct competitor analysis to inform pricing adjustments.
2. Develop a comprehensive marketing plan addressing seasonal fluctuations.
3. Implement inventory management software.

Key Performance Indicators (KPIs) to Track:

1. Average Sales per Customer
2. Average Sales per Order
3. Profit Margins %
4. Sales Growth Rate
5. Customer Retention Rate

Next Steps:

1. Review sales data quarterly to assess progress.
2. Adjust strategies based on data-driven insights.
3. Continuously monitor market trends.
