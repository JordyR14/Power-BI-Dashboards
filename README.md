# Power-BI-Dashboards
Datasets, Jupyter Notebooks in Python and Power BI Dashboards to show BI Skills

First and foremost, lets start describing the type of data we got. We got a Zomato dataset which is a restaurant in Bangalore India. It contains more than 40k records. I used power query in power bi to transform the data.
*Few things to mention they were an specific amount of null and incomplete values. We address this issue using python through jupyter notebooks to handlin missing data.
We perform Imputation to fill values with the mean of that particular column and some of the really incomplete data that did not represent more than the 5% was dropped.
After creating a few more columns we get the following dashboard:



1.
Average Delivery Time by City: (Top Left Corner)
o
Semi-Urban areas have the highest average delivery time at 49.40 minutes.
o
Metropolitan areas have an average delivery time of 27.18 minutes.
o
Urban areas have the lowest average delivery time at 22.94 minutes.
2.
Total Amount of Orders Over Time: (Great Indian Holi Festival)
o
There was a significant spike in orders in March, with nearly 20,000 orders.
o
Orders dropped sharply after March and remained relatively stable for the rest of the year, with minor fluctuations. With average amount of orders per month of (1660)
3.
Total Amount of Orders:
o
The total number of orders from January to September 2022 is 45,584.
4.
Average Rating of Delivery Persons:
o
The average rating for delivery persons is 4.63 out of 5, indicating high customer satisfaction.
5.
Average Delivery Time by Vehicle Type:
o
Motorcycles have the highest average delivery time at approximately 27 minutes.
o
Bicycles and scooters have progressively lower average delivery times.
o
Electric scooters have the lowest average delivery time at around 24 minutes.
6.
Average Delivery Time by Driver Age in Traffic Density:
o
Delivery times vary by driver age and traffic density.
o
High and Jam traffic conditions generally lead to longer delivery times.
o
Delivery times tend to decrease as delivery persons age from 20 to 30 years, then stabilize or increase slightly.
7.
Breakdown of Multiple Deliveries:
o
Most orders involve single deliveries (29,000 orders).
o
A smaller number of orders involve multiple deliveries, with 14,000 orders involving zero additional deliveries, and only 2,000 orders involving two additional deliveries.
Presentation Tips:
•
Highlight Key Trends: Emphasize the significant spike in orders in March and discuss potential reasons for this trend. - (Great Indian Holi Festival)
•
City-wise Analysis: Point out the variations in delivery times across different city types and explore possible causes. – Semi Urban Analysis - Maybe discontinue longer orders unless its multiple or look for a closer restaurant (We need to see the revenue of those 166 purchase)
•
Vehicle Efficiency: Discuss the efficiency of different vehicle types in terms of delivery times, highlighting the advantages of using electric scooters.
•
Customer Satisfaction: Showcase the high average rating of delivery persons as a key indicator of customer satisfaction.
•
Traffic Impact: Explain how traffic density and driver age impact delivery times, with a focus on optimizing routes and schedules. – By setting Expectations to the customers in Hours of High Demand
•
Order Patterns: Analyze the breakdown of multiple deliveries to understand delivery patterns and potential areas for optimization.
These insights can help stakeholders understand various aspects of the delivery operations and identify areas for improvement.
