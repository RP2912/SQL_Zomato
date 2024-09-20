Zomato Database Project
Overview
This project is a simulation of a database system for tracking customer transactions, product sales, and Zomato Gold membership data using SQL. The goal is to provide an efficient way to store and query data related to customer activities, products, and membership status, with a focus on generating insights such as total spending, product popularity, and customer behavior.
**
Features**

Database Design: The project consists of four key tables – USERS, GOLD_SIGNUP, SALES, and PRODUCT – to manage user information, product details, sales records, and membership data.
Transaction Tracking: Sales data is recorded for each user, enabling detailed analysis of purchasing behavior and the popularity of products.
Membership Management: Users can sign up for Zomato Gold, and the database tracks their membership status and purchases before and after joining the program.
Reward Points System: Implements logic to calculate rewards points based on purchases, with different products offering varying point systems.

Advanced SQL Queries: The project includes a variety of complex SQL queries, such as:
Calculating the total spending of each customer.
Determining the first and most popular product purchased by each customer.
Analyzing customer transactions before and after joining Zomato Gold.
Ranking transactions by time and identifying popular products.
**
Database Tables**

USERS: Stores customer information, including their unique ID and signup date.
GOLD_SIGNUP: Tracks when a user becomes a Zomato Gold member.
SALES: Contains data on customer purchases, including sales date and the product purchased.
PRODUCT: Holds product details such as product ID, name, and price.
**
Key SQL Queries**
The project includes several advanced queries to generate valuable business insights:

Total Amount Spent by Each Customer: Shows how much each user has spent based on their purchases.
Customer Visits: Calculates the number of transactions per customer.
First Product Purchased: Determines the first item each customer bought.
Most Popular Product: Finds out which product was purchased the most overall and per user.
Pre- and Post-Membership Analysis: Tracks the first product bought after a customer becomes a Gold member and the last product before they joined.
Points System: Implements a reward system where customers earn points based on product prices, simulating a loyalty program.
**
Usage**
Clone this repository.
Run the SQL file in any SQL-based relational database management system (e.g., MySQL, PostgreSQL, SQL Server).
Use the provided queries to interact with the database and retrieve insights.
**
Conclusion**
This project demonstrates essential database management practices and advanced SQL querying techniques for e-commerce applications. It provides valuable business insights and can be adapted to similar database systems for tracking sales, membership, and user activity.
