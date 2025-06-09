# Bike Rental Data Analysis

## Project Overview
This project delivers a comprehensive analysis of bike rental customer behavior, revenue streams, and pricing strategies 
using advanced SQL techniques on a PostgreSQL database. It is designed to provide actionable business insights for optimizing 
customer engagement and maximizing revenue.

## Database Schema
-Customer: Stores customer details.
![Screenshot 2025-06-09 151941](https://github.com/user-attachments/assets/8eab9922-1f0f-4318-83af-042da3798f5a)

-Bike: Contains bike information including categories, prices, and availability status.
<img width="650" alt="image" src="https://github.com/user-attachments/assets/944c3e1d-e743-44dd-85c9-043cd696502c" />

-Rental: Tracks rental transactions with timestamps and payment details.

-Membership & Membership Type: Holds membership plans and their purchase records.

## Technology
-PostgreSQL for database management and advanced SQL querying.

- [Project Overview](#project-overview)
- [Business Problems Addressed](#business-problem-addressed)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Dashboard Highlights](#dashboard-highlights)
- [Dashboard Preview](#dashboard-preview)
- [Key Insights](#key-insights)
- [Recommendatons](#recommendations)
- [Let's Connect](#let's-connect)



## Project Overview
Hotels often struggle with high cancellation rates, unclear revenue patterns, and underperforming guest segments or channels. This dashboard was built to address those challenges and answer key business questions such as:

- What is the total revenue and average booking value?
- Which guest types and countries contribute the most revenue?
- What’s the impact of cancellations across booking channels and days?
- How do revenue and cancellation rates vary by room type?

## Business Problems Addressed
**High Cancellation Rates**  
→ Identify which days, guest types, and channels experience more cancellations and why

**Unclear Revenue Contributors**  
→ Pinpoint which guest types, countries, and room categories are driving the most revenue.

**Ineffective Channel Strategy**  
→ Compare booking volume and cancellation rates across Direct, Online, Corporate, and Travel Agent channels.

**Missed Revenue Opportunities by Day**  
→ Optimize pricing and marketing based on day-wise revenue and cancellation trends.

## Data Source
The dataset was simulated using ChatGPT to reflect real-world hotel booking scenarios. It contained missing values and inconsistent data types, 
which were addressed during the data cleaning process.

## Tools Used

- **Power BI** for interactive data visualization  
- **Python** for data preprocessing  
- **DAX** for custom measures (Total Revenue, Cancellation Rate, etc.)

## Dashboard Highlights

- **Revenue Trends by Day**
- **Performance by Room Type**
- **Revenue Distribution by Country**
- **Guest Type vs. Revenue & Cancellation**
- **Cancellation Trends Over Days**
- **Confirmed vs. Cancelled Bookings**

All visuals are dynamically filterable by **room type, country, month, week, and channel**.

## Dashboard Preview
<img width="462" alt="image" src="https://github.com/user-attachments/assets/d344a3b8-846f-401b-99d8-905bd39347ee" />

## Key Insights
- The overall cancellation rate stands at 50.4%, meaning half of all bookings are not converting into stays, despite a total of 2,000 bookings and a $1M total revenue.
- Monday records the highest revenue, while Sunday sees the lowest, showing uneven distribution of earnings across the week. However, cancellation rates gradually increase throughout the week, peaking on Wednesday.
- Among room types, Double rooms generate the highest revenue ($280K), followed by Deluxe, Single, and Suite, but cancellation rates are unevenly spread, with Suite rooms showing higher cancellation risk.
- Direct and Online channels are responsible for the most bookings (526 and 518 respectively), but Online has the lowest cancellation rate, while Corporate and Direct channels experience over 50% cancellations.
- Data indicates "Family" bookings as the top revenue generator ($0.79M), necessitating a strategic approach centered on understanding and catering to this segment.
- France, the UK, and India are the top revenue-generating countries, with values of $190K, $187K, and $184K respectively, indicating a geographic concentration of customer value.
- Thursday records the highest number of confirmed bookings (160), while Wednesday shows the most cancellations (119), reflecting a shift in booking reliability midweek.
- The average booking value is $523, and cancellation rates trend upward through the week, indicating that later-week bookings are more likely to be cancelled compared to those earlier in the week.

## Recommendations
- To reduce cancellations that usually happen between Monday and Wednesday, the hotel can offer special discounts or non-refundable booking options during these days.
- Since most bookings come from online and direct channels, it’s a good idea to improve the experience for direct bookings and give more rewards for online ones to keep customers interested.
- Double rooms bring in the most money, so promoting them more in ads or combining them with other offers could increase revenue. At the same time, the hotel should check why suite bookings are not performing well and make adjustments to pricing or features.
- Corporate and travel agent bookings have a higher cancellation rate. It may help to talk to these partners, understand the reasons, and find ways to reduce cancellations. 
- Countries like France, the UK, and India bring in high revenue, so focusing marketing efforts on these regions could help attract even more guests.
- Since Monday brings the most revenue and Thursday has the most bookings, the hotel can run special campaigns or promotions on these days to fill more rooms.
- Encouraging guests to book in advance with non-refundable options might reduce the overall cancellation rate, especially from people booking midweek or with less commitment.

## Let’s Connect!
If you find this project valuable or would like a customized version for your hospitality business, feel free to connect with me on https://www.linkedin.com/in/biya-rocky-dataanalyst/.

