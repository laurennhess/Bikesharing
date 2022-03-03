# Bike Sharing Analysis

## Overview 
In New York City, there is a bikesharing company that allows people to rent bikes using an app on their phone. The app calculates the ride and charges the customer for the trip. After testing out NYC Citi Bike, a friend and I wanted to see if it would be a good investment to start a bike share company in De Moines, Iowa. De Moines is much smaller compared to NYC, so we wanted to analyze whether or not this idea would survive in a smaller toursim town.

To complete our analysis, we pulled the NYC Citi Bike dataset for the month of August, a month that is popular for tourists to visit NYC. Using pandas, we changed the "trip duration" column to a datetime datatype and then began visualizing our data using Tableau. 

Using Tableau to create visualizations based on the data we gathered from NYC Citi Bike, we came up with a business propsal to present to potential investors. The story that we show in Tableau will outline whether or not the bikesharing company will survive in De Moine, Iowa, using interactive dashboards set with specific and thought out parameters. 

## Results
### 1. Popular Checkout Times for Users
This dashboard shows poular check out times for city bikes as well as trip duration in minutes during each hour the bikes are checked out. Based on the filter we applied on Trip Duration, we can see that "rush hour" for using the city bikes is between 5am - 8am and then again at 5pm - 7pm. These "rush hours" can be correlated to the standard commute and work hours during the work week.
![Checkout Times ](https://user-images.githubusercontent.com/94096530/156621952-38c505a9-d7cf-43d4-86ca-458f59940ae9.png)

### 2. Checkout Times by Gender
This dashboard displays popular checkout times with the added parameter of "gender." Here, we can still see the same peak usage hours as well as the gender of the registered user. From this dashboard, we can see that the male population in NYC makes up most of the Citi Bike users during "rush hour."
<img width="1440" alt="Screen Shot 2022-03-03 at 11 18 37 AM" src="https://user-images.githubusercontent.com/94096530/156627068-45e688c2-3ab2-47a7-a3d6-e8bc79572b7a.png">

### 3. Number of Trips per Weekday
This heat map shows the relationship between the number of citi bikes used on each day of the week, as well as the hour of checkout time. We can see that the demand for citi bikes is higher towards the end of the week and on the weekend. 
![Screen Shot 2022-03-03 at 11 24 37 AM (2)](https://user-images.githubusercontent.com/94096530/156628114-a06857af-c699-45e7-900d-f1e1d0c05e73.png)

### 4. Number of Trips per Gender
This heat map shows us the number of trips taken per weekday by gender of the user. The heat map allows us to see trends in our data more easily since we can see when the "hot times" are - when more citi bikes are being used. 
![Screen Shot 2022-03-03 at 11 28 00 AM (2)](https://user-images.githubusercontent.com/94096530/156628643-8de4b2c7-9ac0-4867-be6b-4529fc639fcb.png)

### 5. Relationship between Gender and User Type
On the citi bike app, you can be registered as a "customer" or "subscriber." Subscribers ride the bikes more often. This heat map shows the relationship between type of user per gender and citi bike usage through the week. We can see that male subscribers make up a majority of citi bike users on a weekly basis. 
![Screen Shot 2022-03-03 at 11 30 32 AM (2)](https://user-images.githubusercontent.com/94096530/156629499-0759f5f8-bcbd-4429-a933-5093c87ea807.png)

### 6. Top Starting Locations in NYC
This map of NYC outlines the popular starting locations of citi bike users across Manhattan based on size. Popular start locations could be based on specific neighborhoods that attract the most tourists or where most office buildings are located for commuters. 
![Screen Shot 2022-03-03 at 11 38 46 AM (2)](https://user-images.githubusercontent.com/94096530/156630524-0328517c-3cde-4ed2-ba75-317e0517b917.png)

### 7. Peak Hours in August
The histogram shows the peak hours for citi bike usage in NYC during August. The peak times are around 7am - 5pm. Thus, when choosing when to upcharge citi bike prices, we can choose based on hours with the most bike usage. We can also determine when the best time to perform bike repairs is, which according to the histogram is between 1am - 5am. 
![Screen Shot 2022-03-03 at 11 39 28 AM (2)](https://user-images.githubusercontent.com/94096530/156630761-03a9fbd6-d1cd-46e0-a955-50101a3a2519.png)

## Summary
The Citi Bike data we have analyzed for NYC provides a lot of useful information we can consider in our business proposal for opening up a citi bike location in De Moines, Iowa. We can use these dashboards to leverage certain business decisions, like peak hours, repair hours, and user trends. 

The visuaizatons provided in this file can be viewed on my Tableau Pubic Account: 
[link to dashboard](https://public.tableau.com/app/profile/lauren.hess/viz/NYCCitiBikeAnalysis_16461975520310/NYCCitiBike)


