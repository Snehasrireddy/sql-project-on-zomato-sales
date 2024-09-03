# Zomato Sales SQL Project 
## Project Overview

This project is a comprehensive case study on a dataset containing information about Zomato sales. The dataset consists of four primary tables: `users`, `sales`, `product`, and `goldusers_signup`. The main objective was to analyze customer behavior, product popularity, and the impact of the Zomato Gold membership program.

## Dataset Information

The dataset includes the following tables:

1. **users**:
   - `userid` (Primary Key)
   - `signup_date`

2. **sales**:
   - `userid` (Foreign Key)
   - `created_date`
   - `product_id` (Foreign Key)

3. **product**:
   - `product_id` (Primary Key)
   - `product_name`
   - `price`

4. **goldusers_signup**:
   - `userid` (Foreign Key)
   - `gold_signup_date`

## Questions Explored

1. **Total Amount Each Customer Spent on Zomato**:
   - Calculated the total expenditure of each customer by summing up the price of all products they purchased.

2. **How Many Days Each Customer Visited Zomato**:
   - Determined the number of unique days each customer placed an order on Zomato.

3. **First Product Purchased by Each Customer**:
   - Identified the first product each customer bought based on the earliest `created_date`.

4. **Most Purchased Item on the Menu and How Many Times It Was Purchased**:
   - Analyzed the most frequently purchased product and counted the total purchases.

5. **Most Popular Item for Each Customer**:
   - Found the most purchased product for each customer individually.

6. **Item Purchased by the Customer After Becoming a Member**:
   - Tracked the products each customer bought after joining the Zomato Gold program.

7. **Item Purchased by the Customer Before Becoming a Member**:
   - Identified the products each customer bought before joining the Zomato Gold program.

8. **Total Orders and Amount Spent by Each Member Before Becoming a Member**:
   - Calculated the total number of orders and the total amount spent by each customer before they became a Zomato Gold member.

9. **Zomato Points Calculation Based on Product Purchases**:
   - Implemented a custom points system based on product prices and calculated the total Zomato points collected by each customer. Also determined which product generated the most points.

10. **Zomato Points Earnings in the First Year of Gold Membership**:
    - Calculated the Zomato points earned by customers in their first year after joining the Gold program. Compared the points earnings of two specific customers to see who earned more.

11. **Ranking of All Transactions by Customers**:
    - Ranked all transactions made by customers chronologically.

12. **Ranking of Transactions for Gold Members**:
    - Ranked the transactions made by customers during their Gold membership. Non-Gold member transactions were marked as 'NA'.

## Tools and Technologies Used

- **SQL**: For data extraction, transformation, and analysis.

## Conclusion

This project provided valuable insights into customer behavior on Zomato, including spending patterns, product popularity, and the impact of the Zomato Gold membership program. The analysis answered key business questions that could help in strategic decision-making.

