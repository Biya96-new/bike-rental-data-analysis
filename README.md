# Bike Rental Data Analysis

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Technology](#technology)
- [Data Analysis and Findings](#data_analysis_and_findings)
- [Key Findings](#key-findings)
- [Recommendatons](#recommendations)
- [Let's Connect](#let's-connect)

## Project Overview
This project delivers a comprehensive analysis of bike rental customer behavior, revenue streams, and pricing strategies 
using advanced SQL techniques on a PostgreSQL database. It is designed to provide actionable business insights for optimizing 
customer engagement and maximizing revenue.

# Project Structure
## Database Schema Setup
-Customer: Stores customer details.
<img width="547" alt="image" src="https://github.com/user-attachments/assets/31bcdb22-0e2e-4d01-862b-0d35961511ed" />

-Bike: Contains bike information including categories, prices, and availability status.
<img width="650" alt="image" src="https://github.com/user-attachments/assets/944c3e1d-e743-44dd-85c9-043cd696502c" />

-Rental: Tracks rental transactions with timestamps and payment details.
<img width="510" alt="image" src="https://github.com/user-attachments/assets/230117bd-78c5-417a-98c1-9c78cc999063" />

-Membership & Membership Type: Holds membership plans and their purchase records.
<img width="645" alt="image" src="https://github.com/user-attachments/assets/b2b2ade4-4637-4dec-a1b7-f9333a18e84b" />
<img width="541" alt="image" src="https://github.com/user-attachments/assets/83dda730-2e19-4a10-9add-d2d94324fe6d" />

## Technology
-PostgreSQL for database management and advanced SQL querying.

## Data Analysis and Findings
The following SQL queries were developed to answer specific business questions:
### Display bike categories with more than 2 bikes owned by the shop, showing category name and bike count (number_of_bikes).
<img width="341" alt="image" src="https://github.com/user-attachments/assets/7c185faa-3086-415b-8ec1-0767b0d69a09" />

###  List each customer’s name with their total memberships purchased (membership_count), sorted by highest count first. 
<img width="308" alt="image" src="https://github.com/user-attachments/assets/caa76bad-ffcd-4576-8d56-9f946837c471" />

### Display each bike’s ID, category, original and discounted prices per hour (old_price_per_hour, new_price_per_hour) and per day (old_price_per_day, new_price_per_day). Apply discounts by category:
-Electric bikes: 10% hourly, 20% daily
-Mountain bikes: 20% hourly, 50% daily
-Others: 50% discount on all rentals
### Round discounted prices to 2 decimals.
<img width="488" alt="image" src="https://github.com/user-attachments/assets/7fc6f83f-eea9-4800-adf1-9a6df1bb282c" />

### Show bike category-wise counts of available (available_bikes_count) and rented bikes (rented_bikes_count).
<img width="474" alt="image" src="https://github.com/user-attachments/assets/26470626-a437-4efc-9efa-093d73d04a06" />

### Display total membership revenue by year, month, and membership type (membership_type_name), sorted by year, month, and type.
<img width="324" alt="image" src="https://github.com/user-attachments/assets/8348bace-c894-409c-84ff-7e48e3cbb9e3" />

### Show total 2023 membership revenue by month and membership type (membership_type_name), including subtotals and grand totals. Sorted by membership type (A-Z) and month.
<img width="467" alt="image" src="https://github.com/user-attachments/assets/e4be8fd4-7c9c-40d9-9c9c-7d5fd1b561e0" />

### Segment customers by rental count:
-More than 10 rentals → 'more than 10'
-Between 5 and 10 rentals → 'between 5 and 10'
-Fewer than 5 rentals → 'fewer than 5'
### Display the count of customers in each category with columns: rental_count_category and customer_count.
<img width="386" alt="image" src="https://github.com/user-attachments/assets/cb806b64-16e9-47bb-a2d5-13a4242f992e" />

## Key Findings
-Only two bike categories (road and mountain bikes) had more than 2 units available.
-The maximum number of memberships purchased by a single customer was 3.
-The highest revenue was generated from the basic monthly membership type.
-Road bikes, which accounted for 30% of customer demand, received a 50% discount—indicating a potential revenue loss and a need to adjust pricing based on demand.
-Most customers fell into the segment with fewer than 5 rentals. 

## Recommendation
-Optimize inventory by focusing on popular bike categories.
-Introduce membership bundles or loyalty programs to boost purchases.
-Promote high-revenue basic monthly memberships and consider tiered options.
-Reevaluate road bike discounts to better match demand and reduce revenue loss.
-Target customers with low rentals through marketing to increase rental frequency.

## Let’s Connect!
If you find this project valuable or would like a customized version for your hospitality business, feel free to connect with me on https://www.linkedin.com/in/biya-rocky-dataanalyst/.

