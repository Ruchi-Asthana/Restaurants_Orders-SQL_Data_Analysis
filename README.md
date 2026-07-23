# Restaurants, Orders and Customers - Data Analysis Project | SQL

## Project Overview:
This project focuses on analyzing raw data from three core business entities — Customers, Restaurants and Orders — to generate
actionable insights for improving business performance, customer engagement and operational efficiency.
Using SQL as the primary analytical tool, customer behaviour, restaurant performance, order trends and 
revenue patterns were explored. The analysis answers key business questions that help stakeholders make informed decisions.

## Dataset Description:

1. Customers Table: Contains customer profile and onboarding details.
   * customer_id — Unique identifier for each customer
   * customer_name — Full name of the customer
   * city — Customer’s city
   * signup_date — Date the customer registered
2. Restaurants Table: Contains restaurant information and ratings.
   * restaurant_id — Unique identifier for each restaurant
   * restaurant_name — Name of the restaurant
   * city — City where the restaurant operates
   * rating — Customer rating (1–5 scale)  
3. Orders Table: Captures transactional order-level details.
   * order_id — Unique order identifier
   * customer_id — Customer who placed the order
   * restaurant_id — Restaurant fulfilling the order
   * order_date — Date of the order
   * order_amount — Total bill amount
   * payment_method — Mode of payment (Cash, Credit Card, Debit Card, UPI)
   * order_status — Status (Completed, Cancelled)

## Project Objective:

The primary goals of this analysis were:

* Understand customer ordering patterns.
* Evaluate restaurant performance and revenue contribution.
* Identify high-value customers.
* Analyze payment preferences.
* Study city-wise and month-wise revenue trends.
* Build ranking, categorization and segmentation logic.
* Provide insights that support marketing, operations and strategic planning.

## Business Questions Answered:

The following SQL-driven insights were delivered to the client:

1. Completed Orders with Customer & Restaurant Details: Joined customers, restaurants and orders to display all successfully completed transactions.
2. Total Revenue by Restaurant: Calculated total earnings per restaurant to identify top revenue contributors.
3. Total Orders per Customer: Measured customer engagement by counting orders placed by each customer.
4. Average Order Amount per City: Provided city-level spending trends to support regional strategy.
5. Order Categorization (Low, Medium, High): Segmented orders based on amount thresholds for better pricing and marketing insights.
6. Restaurants with Above-Average Order Value: Identified restaurants outperforming the overall average order value.
7. Customers with No Orders: Detected inactive or newly onboarded customers for targeted engagement.
8. Top 5 Customers by Total Spending: Ranked customers based on lifetime value.
9. Most Frequently Used Payment Method: Analyzed payment preferences to optimize checkout experience.
10. Running Total of Revenue by Order Date: Built a cumulative revenue trend to understand business growth over time.
11. Ranking Restaurants by Revenue: Ranked restaurants using SQL window functions to highlight top performers.
12. Second Highest Order Amount: Extracted the second-highest transaction value using advanced SQL techniques.
13. Customers Above Average Order Count: Identified highly active customers for loyalty programs.
14. Top 3 Restaurants per City by Order Volume:Ranked restaurants within each city to understand regional competition.
15. Month-wise Revenue with Previous Month Comparison: Provided time-series revenue insights with month-over-month performance.

## Key Insights and Finding:

Revenue & Restaurant Performance:
* Certain restaurants consistently generated higher revenue due to strong customer loyalty or high average order values.
* City-wise revenue differences highlighted regional demand patterns.
* Month-wise revenue trends helped identify seasonal peaks and dips.

Customer Behaviour:
* A small group of customers contributed significantly to total spending.
* Several customers had never placed an order, indicating potential onboarding or marketing gaps.
* Customers with above-average order frequency represent strong retention opportunities.
  
Payment Trends:
* One payment method emerged as the most preferred, guiding future payment gateway optimizations.
Order Patterns:
* Categorizing orders revealed the distribution of low, medium and high-value purchases.
* Running totals and rankings helped visualize business growth and competitive positioning.

## Conclusion

This project provides a comprehensive analytical foundation for understanding customer behaviour, restaurant performance and order trends. The insights generated can directly support:
* Marketing campaigns
* Customer retention strategies
* Restaurant partnerships
* Operational improvements
* Revenue optimization
  
The SQL analysis ensures accuracy, scalability and clarity — making it easy to extend or integrate into future data initiatives.

