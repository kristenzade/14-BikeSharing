# 14-BikeSharing
# NYC Citi Bike Analysis

## Overview of Project

### Purpose
The purpose of this project was to assist Kate with a business proposal to display how a bike-sharing business may work in Des Moines, Iowa. To do so, NYC Citi Bike data from the month of August was analyzed to understand how the bike share business operates. This included analyzing data of bike usage based on the time of day, the weekday, gender, and trip duration. The objectives were to:

- Checkout times for users - this graph can be filtered by each hour of the day. This shows investors the times of the day that ride-sharing is utilized the most
 ![Checkout Times for Users](https://user-images.githubusercontent.com/80215894/121521967-a7252580-c9c2-11eb-8c4e-2e166641f27d.png)

 - Checkout times for users by gender - this graph can be filtered by each hour of the day as well as by gender. This expands on the graph above by breaking it down by gender
![Checkout Times by Gender](https://user-images.githubusercontent.com/80402142/130329593-d9bc2030-ddb7-4538-bcd6-a764f7a36a00.png)


 - This heatmap shows the trips by weekday per hour. The legend shows that areas of dark red are peak trip times
 ![Trips by Weekday per Hour](https://user-images.githubusercontent.com/80402142/130329607-8de4dd77-b053-4232-80b8-20dc57f8da65.png)

 - This heatmap shows the trips by weekday per hour by gender. Dark red shows peak times and the map is filterable by gender
![Trips by Gender - Weekday per Hour](https://user-images.githubusercontent.com/80402142/130329612-2308fb1c-e06d-41ff-97e1-303326619936.png)

 - This heatmap shows the trips by user type and gender by weekday. Areas of dark blue are peak days of the week. The map is filterable by user type as well as gender
 ![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/80402142/130329584-a7f2b812-66d3-40af-9818-43613e95d8c6.png)

 - This heat map shows the number of bikes in service and how many times each has been ridden. This helps pinpoint bikes that may need service soon. The darker the color, the more the bike has been ridden
![bike repairs](https://user-images.githubusercontent.com/80402142/130329538-0f5b9016-2cde-4ae2-a8c7-aaab069d3f34.png)


## Summary ##

- Peak hours for rides occur between 7 AM-9 AM and 4 PM-7 PM, with 6 PM being the most popular time for users. This corresponds with normal work hours- users rent a bike on their way to work between 7 AM-9 AM, and rent a bike in the afternoon when heading home, between 4 PM-7 PM. The high bike usage could be due to lower costs when compared to other forms of transportation.
- The highest usage of Citi Bikes during peak hours occurs on Thursdays. This anomaly would need further investigation to understand why Thursday is a popular day for bike usage.
- There appears to be low usage on Wednesdays between peak afternoon hours of 4 PM-7 PM. It can be inferred that many people do not rent bikes on Wednesday evenings due to after-work events, such as happy hours. These types of events are common on Wednesday, i.e., Wine Down Wednesdays, and would require safer travel options, including taxis, rideshare options, or the subway.
- Males are more likely than females to subscribe to or use the bike share business. This is most likely due to concerns for safety. Women may not feel safe riding their bikes in the busy streets of New York. With a lack of bike parking spaces or designated bike lanes, women are less likely to bike around the city.
- Users are more likely to use bikes for less than one hour, with the most common time being 5 minutes. It can be understood that the bikes are used for short distances, rather than longer commutes, and possibly more for convenience than the actual exercise.

## Recommend Visual ##

1. The First visual will be good to see what is price consumer is paying by the customer type (Subscriber VS Customer)
2. The Bike repair and loss of asset value.
3. How much companies payout is out of business.

These visuals help to see the bigger picture.

### Resources
Data Source: [Citi Bike August Data](https://s3.amazonaws.com/tripdata/index.html); Select 201908-citibike-tripdata.csv.zip
<br>
Software: Jupyter Notebook, Tableau Desktop Public Edition version 2020.4.2







