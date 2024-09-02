# E-commerce trend in brazil retail store (SQL Case Study)

## Project Overview

This project analyzes e-commerce data from Target Corporation to provide actionable insights into customer behavior, sales trends, and logistics performance. The analysis focuses on understanding order patterns, customer distribution, payment preferences, and delivery efficiency, with the goal of optimizing operations and enhancing customer satisfaction.

## Business Problem

Target Corporation aims to gain a deeper understanding of its e-commerce operations in Brazil. The objectives are to identify trends in order placement, analyze geographic distribution of customers, assess the impact of different payment methods, and evaluate logistics performance to make data-driven decisions for improving overall business efficiency.

## Tools

- **SQL**
- **Google BigQuery** (or any other SQL database)

## Steps Involved

### 1. Data Import and Exploration
- **Dataset Structure**: Analyzed the structure of the dataset, including data types of all columns in the `customers` table.
- **Time Range Analysis**: Determined the time frame of orders using the earliest and latest purchase timestamps.
- **Location-Based Order Count**: Counted the number of orders placed by customers in different cities and states.

### 2. In-Depth Exploration
- **Order Trends**: Analyzed the number of orders placed over the years to identify any growing trends.
- **Seasonality Analysis**: Examined monthly order data to detect any seasonality in order placements.
- **Order Time Analysis**: Investigated the time of day when Brazilian customers mostly place their orders, categorizing them into Dawn, Morning, Afternoon, and Night.

### 3. Customer and Geographic Distribution
- **State-Wise Order Analysis**: Analyzed the month-on-month number of orders placed in each state.
- **Customer Distribution**: Examined how customers are distributed across different states in Brazil.

### 4. Economic Impact Analysis
- **Order Cost Analysis**: Calculated the percentage increase in the cost of orders from 2017 to 2018.
- **State-Wise Spending Analysis**: Determined the total and average order prices for each state.
- **Freight Cost Analysis**: Calculated the total and average freight costs for each state.

### 5. Logistics Performance Analysis
- **Delivery Time Analysis**: Calculated the time taken to deliver each order and the difference between estimated and actual delivery dates.
- **Freight and Delivery Performance**: Identified the top 5 states with the highest and lowest average freight value and delivery time.

### 6. Payment Analysis
- **Payment Method Trends**: Analyzed the number of orders placed using different payment methods on a month-by-month basis.
- **Installment Analysis**: Investigated the distribution of orders based on the number of payment installments.

### 7. Business Insights and Recommendations
- **Focus on Key States**: Prioritize operations and marketing efforts in the top 7 states, which account for 80% of the orders.
- **Logistics Optimization**: Improve logistics in key states to reduce average delivery time, enhancing customer satisfaction.
- **Product Pricing Strategy**: Focus on marketing medium-priced products to increase sales in states with lower average order prices.
- **Credit Card Promotions**: Leverage the popularity of credit cards in Brazil by offering promotions during festive seasons.
- **Resource Planning**: Ensure adequate manpower to handle operations efficiently in high-demand states.

## Conclusion

The insights from this analysis provide Target Corporation with data-driven recommendations to optimize its e-commerce operations in Brazil. By focusing on key states, improving logistics, and tailoring marketing strategies, Target can enhance customer satisfaction and drive growth in the Brazilian market.
