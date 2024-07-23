# Power-BI-Dashboards
Datasets, Jupyter Notebooks in Python and Power BI Dashboards to show BI Skills

First and foremost, lets start describing the type of data we got. We got a Zomato dataset which is a restaurant in Bangalore India. It contains more than 40k records. 
I used power query in power bi to transform the data.
a Few things to mention they were an specific amount of null and incomplete values. We address this issue using python through jupyter notebooks to handlin missing data.
We perform Imputation to fill values with the mean of that particular column and some of the really incomplete data that did not represent more than the 5% was dropped.
After creating a few more columns we get the following dashboard:



Average Delivery Time by City: (Top Left Corner)
Semi-Urban areas have the highest average delivery time at 49.40 minutes.
Metropolitan areas have an average delivery time of 27.18 minutes.
Urban areas have the lowest average delivery time at 22.94 minutes.



Total Amount of Orders Over Time: (Great Indian Holi Festival)
There was a significant spike in orders in March, with nearly 20,000 orders.
Orders dropped sharply after March and remained relatively stable for the rest of the year, with minor fluctuations. With average amount of orders per month of (1660)


Total Amount of Orders:
The total number of orders from January to September 2022 is 45,584.


Average Rating of Delivery Persons:
The average rating for delivery persons is 4.63 out of 5, indicating high customer satisfaction.


Average Delivery Time by Vehicle Type:
Motorcycles have the highest average delivery time at approximately 27 minutes.
Bicycles and scooters have progressively lower average delivery times.
Electric scooters have the lowest average delivery time at around 24 minutes.
Average Delivery Time by Driver Age in Traffic Density:
Delivery times vary by driver age and traffic density.
High and Jam traffic conditions generally lead to longer delivery times.



Delivery times tend to decrease as delivery persons age from 20 to 30 years, then stabilize or increase slightly.
Breakdown of Multiple Deliveries:
Most orders involve single deliveries (29,000 orders).
A smaller number of orders involve multiple deliveries, with 14,000 orders involving zero additional deliveries, and only 2,000 orders involving two additional deliveries.



