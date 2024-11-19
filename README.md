# AtliQ Hospital Analysis
![image](https://github.com/user-attachments/assets/bdc2dad3-0f59-4ae5-ac8f-298181d5f20b)

## Project Overview
This project utilizes comprehensive datasets from the hospitality industry, providing detailed information on hotel properties, room categories, bookings, and guest interactions. The data is meticulously cleaned and transformed to ensure accuracy and relevance.
![image](https://github.com/user-attachments/assets/35ffb171-aa20-4ac8-a3f9-afb11ca1a140)

## Executive Summary
The AtliQ Hospital Analysis project provides a comprehensive examination of the hospitality industry's performance, utilizing detailed datasets to uncover key trends and insights. Leveraging Power BI for visualization, the analysis reveals significant performance metrics, revenue patterns, booking behaviors, and customer satisfaction indicators. Key findings include Week 19's peak performance with the highest average rating, significant revenue surges starting late January 2022, and RT2's dominance in revenue contributions. Booking trends show a notable decline in January 2022, with makeyourtrip leading in total bookings. High cancellation rates in May and consistent ratings across properties underscore the importance of strategic decision-making. The project highlights the transformative potential of data in driving business strategies and optimizing performance, positioning AtliQ for sustained growth and success.
## Data model
![Hospitality analysis](https://github.com/user-attachments/assets/1ec14b17-df48-4bd2-bed0-cb137a9df493)

dim_rooms: Contains room classification and unique identifiers.

dim_hotels: Details on hotel categories, cities, and properties.

dim_date: Specific dates, day types, and month-year formats.

fact_aggregated_bookings: Aggregated data on capacity, check-in dates, and successful bookings.

fact_bookings: Comprehensive booking details, including dates, platforms, statuses, ratings, and revenue.


## Key Insights & Analysis
![image](https://github.com/user-attachments/assets/e29de477-b731-4edd-b967-ec6d2f2f278e)

### Overall Analysis
Top Performance in Week 19: Week 19 stood out with the highest Average Rating of 3.65, which was 1.57% higher than Week 22's lowest rating of 3.59.

Significant Divergence in Week 23: The most notable divergence between Average Rating and Occupancy % (decimal) occurred in Week 23, where ratings were 3.27 points higher.

Consistent Performance Metrics: Average Ratings were consistent, ranging from 3.59 to 3.65, while Occupancy % (decimal) ranged from 0.36 to 0.44 across all weeks.

Revenue Leaders: The Elite room class achieved the highest total revenue_realized at 191,179,584, followed by Premium, Presidential, and Standard classes.

Mumbai's Contribution: The Elite room class in Mumbai accounted for 13.55% of the total revenue_realized.

Highest Average Revenue: Elite had the highest average revenue_realized at 47,794,896.

![image](https://github.com/user-attachments/assets/620ed1f5-4484-42ea-abff-af1bd834147c)

### Revenue Analysis
Overall Revenue Growth: There was a 19.94% increase in revenue between January 1, 2022, and January 31, 2022.

Rapid Revenue Surge: From January 29, 2022, revenue surged by 40.96% in just 2 days.

Top Performing Segment - RT2: RT2 achieved the highest revenue_realized at 187,937,424, which was 80.88% higher than RT1.

Key Revenue Contributors: RT2 accounted for 32.80% of the total revenue_realized.

Revenue Range Across Properties: Revenue varied significantly across properties, ranging from 22,155,029 to 107,542,555.

Mumbai's Impact in July: On July 01, 2022, Mumbai contributed 39.23% of the revenue_realized.

![image](https://github.com/user-attachments/assets/752eddeb-804d-46c7-b14a-0e40a3dae539)

### Booking Wise Analysis
Decline in Bookings: Total Bookings and Total Cancelled Bookings decreased by 38.30% and 41.38% respectively between January 1, 2022, and January 31, 2022.

Steep Booking Decline: Total Bookings fell by 28.29% (1106) between January 27, 2022, and January 31, 2022.

Leading Booking Platform - makeyourtrip: makeyourtrip had the highest Total Bookings at 26,898, significantly surpassing direct offline bookings.

Significant Contribution in May: Mumbai in May contributed 10.98% of Total Successful Bookings.

High Cancellation Counts: May recorded the highest total Count of Cancellation Rate1 at 45,882.

![image](https://github.com/user-attachments/assets/85e016fb-afd0-4fd8-8f45-92ab71db91d7)

### Rating Analysis
Top Rating Periods: Sunday, May 01, 2022, had the highest average rating of 3.63.

Highest Rated Property: Atliq Blu had the highest Average Rating of 3.96, 72.54% higher than Atliq Seasons.

Consistent Ratings: Average Ratings across properties ranged from 2.29 to 3.96.

Booking Contributions: RT2 accounted for 36.78% of Total Bookings.
## Recommendations
#### Optimize Booking Platforms:

 Focus on High-Performing Platforms: Given makeyourtrip's leading contribution to total bookings, enhancing partnerships and marketing strategies with this platform could further boost bookings.

Reduce Cancellation Rates: Implement measures to reduce the high cancellation counts observed in May. This could include flexible booking options, better communication, and incentives for guests to keep their bookings.

#### Enhance Revenue Management:

Target High Revenue Periods: Focus marketing efforts on periods with historically high revenue increases, such as the late January surge. Special promotions and discounts during these times can capitalize on natural upticks in demand.

Leverage High-Performing Room Classes: Elite and Premium room classes contribute significantly to revenue. Offer targeted promotions and premium packages to further boost revenue from these segments.

#### Improve Customer Satisfaction:

Maintain High Standards in Top-Performing Properties: Properties like Atliq Blu, which received the highest average rating, should be used as benchmarks to improve service quality across other properties.

Address Low-Rating Areas: Focus on improving aspects of properties with lower ratings like Atliq Seasons to ensure a more consistent customer experience.

#### Strategic Pricing Adjustments:

Dynamic Pricing Models: Implement dynamic pricing strategies based on occupancy rates and booking trends to maximize revenue. This could involve adjusting prices during peak and off-peak times to optimize occupancy and revenue.

Promotional Offers for Low Occupancy Periods: Introduce special rates or packages during weeks with lower occupancy rates to attract more guests and balance occupancy levels.

#### Data-Driven Decision Making:

Utilize Predictive Analytics: Leverage predictive analytics to forecast booking trends, revenue, and customer preferences. This will enable more proactive and informed decision-making.

Regular Performance Monitoring: Continuously monitor key performance metrics to identify emerging trends and adjust strategies accordingly.
