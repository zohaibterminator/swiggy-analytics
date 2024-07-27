# Swiggy Data Analysis Project

This project focuses on analyzing Swiggy's user and order data to derive actionable insights that can help optimize business strategies and enhance customer satisfaction. The analysis involves multiple SQL queries across various datasets, providing a comprehensive understanding of customer behavior, restaurant performance, and overall platform dynamics. This dataset was part of a case study, if you want to participate in it as well, you can do so [here](https://medium.com/@mahnoor88355729)

# Database Schema

**Users Table**
- user_id (int)
- name (varchar(255))
- email (varchar(255))
- password (varchar(20))

**Restaurants Table**
- r_id (int)
- r_name (varchar(255))
- cuisine (varchar(255))

**Food Table**
- f_id (int)
- f_name (varchar(255))
- type (varchar(255))

**Menu Table**
- menu_id (int)
- r_id (int)
- f_id (int)
- price (int)

**Orders Table**
- order_id (int)
- user_id (int)
- r_id (int)
- amount (int)
- date (date)
- partner_id (int)
- delivery_time (int)
- delivery_rating (int)
- restaurant_rating (int)

**Delivery Partners Table**
- partner_id (int)
- partner_name (varchar(50))

**Order Details Table**
- id (int)
- order_id (int)
- f_id (int)


## Analysis Goals
1. Identify customers who have never placed an order.
2. Calculate the average price per dish for each restaurant.
3. Determine the top restaurant in terms of the number of orders for a given month.
4. Identify restaurants with monthly sales greater than Rs 1000.
5. Retrieve detailed order information for a specific customer within a given date range.
6. Find restaurants with the most repeated customers.
7. Analyze month-over-month revenue growth of Swiggy.
8. Determine each customer's favorite food item.
9. Identify the most loyal customer for each restaurant.
10. Analyze month-over-month revenue growth for individual restaurants.

## Conclusion
The analysis provided valuable insights into Swiggy's operations, customer preferences, and restaurant dynamics. Key findings revealed opportunities to engage non-ordering users through targeted marketing campaigns and personalized offers. Dominos emerged as a high-value partner, contributing significantly to revenue despite higher prices, while a gap in budget-friendly restaurant options was identified.
Insights into customer loyalty highlighted the potential of loyalty programs and personalized offers to drive repeat orders and foster long-term relationships. Promoting high-performing restaurants, such as KFC, through dedicated support and promotional campaigns can capitalize on their popularity and contribute to Swiggy's growth.
Overall, the project provided a data-driven foundation for enhancing user engagement, optimizing offerings, and supporting high-performing partners, driving further growth and improving customer satisfaction.

## Getting Started
To explore the analysis and insights, you can refer to the project report which includes detailed queries and their respective insights.

## Prerequisites
- SQL database setup with the provided dataset.

## Acknowledgements
- Thanks to [atomcamp](https://www.atomcamp.com/) for the dataset and the excellent learning experience.
