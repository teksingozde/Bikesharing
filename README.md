# Bikesharing
## Overview of Project
The customer will give a sales pitch in support of the idea of a bike sharing program in Iowa. To this end, he requested a presentation of the Citi Bike analysis conducted in New York. After the obtained data were made suitable for visualization, visualization was provided with various graphics.

### Resources
#### Datasets:
- 201908-citibike-tripdata-csv.zip

#### Other Sources:
- Python 3. 9. 12
- Jupyter Notebook 6. 4. 8
- Tableau public 2022.3

## Overview of the Analysis  
First of all, we created the “2019-08-citibike-trip-data” dataset, which we obtained from https://s3.amazonaws.com/tripdata/index.html, in the form of a data frame with the pandas library on Jupyter Notebook. After creating the DataFrame, we determined the data types and the names of the columns. The important point is, we changed the "tripduration" column, which is integer data type, to datetime. Later, we exported our data and renamed it as adjusted. Adjected data means; improve coverage, classification, timing and valuation of the data; conform to an accounting and recording basis; or. address data quality differences in compiling specific data sets.
To visualize the adjusted citibike trip data dataset, we uploaded it to the Tableau public environment and then used visualization techniques in accordance with the dataset we have. These visualization techniques include line, circle, heatmap, and bar graphics. 

## Results
#### Graph 1. Checkout Times for Users
<img width="898" alt="Screen Shot 2022-12-22 at 3 13 25 PM" src="https://user-images.githubusercontent.com/26927158/209246334-c971ee82-39df-42cf-991e-26c68b3c2d4a.png">
The chart above shows how long the bike has been used. The region, which is generally called the peak point, is seen as 5 minutes. In general, the number of trips used for 5 minutes is 146,752.

#### Graph 2. Checkout Times by Gender
<img width="899" alt="Screen Shot 2022-12-22 at 3 13 44 PM" src="https://user-images.githubusercontent.com/26927158/209246391-67bb4771-baf2-4457-9176-4e97726a5e95.png">
In the graph shown above, the distribution of trip numbers by gender is shown with a line graph. In the graph, blue shows men, oranges women, and red shows people who do not specify their gender. It is seen that the number of trip minutes is 5, the gender distribution of the people is male, and the number of trips is 108,087.

#### Graph 3. Trips by Weekday per Hour
<img width="898" alt="Screen Shot 2022-12-22 at 3 14 02 PM" src="https://user-images.githubusercontent.com/26927158/209246524-9d2aba97-3844-4733-b05f-d0b12f9628ec.png">
Graph 3 is organized specifically for the structure of the heatmap graph. In the graph, the least number value with the least color and the region with the highest number value are shown in bold. In this graph, if we look at the darkest region, it can be seen in a single graph that the most trips are made at 6 pm and the day of the most trips is Thursday, and at the same time, the number of trips made at this hour and per day is 44,905.

#### Graph 4. Trips by Gender (Weekday per Hour)
<img width="899" alt="Screen Shot 2022-12-22 at 3 14 15 PM" src="https://user-images.githubusercontent.com/26927158/209246595-3685ba76-c3d4-4d8c-a38a-56075bbeb20a.png">
As is known, graph 4 is called heatmap graph. The main thing in the heatmap chart is to rank the numerical value from the least to the highest, and to darken the color with the lowest numerical degree correct, while the color with the least is lighter. So in our heatmap chart, we will focus on the lightest colors to determine the least and the darkest color to determine the most arrow values. Graph 4 presents the graphic image on the condition that it is based on every hour of the day according to the genders. Here, when we focus on the region with the darkest color, we can see the time period and day when male users generally make the most active trips at 6 pm on Thursdays. It is also observed that the number of trips during this period is 30,749. In the heatmap scale, which is located in the upper right corner, it is confirmed that this value is the highest number.

#### Graph 5. User Trips by Gender by Weekday
<img width="884" alt="Users Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/26927158/209246633-c398b5ea-b19f-4f9f-8354-7b8564eaf448.png">
User Trips by Gender by Weekday heatmap graphic includes classification as user type and gender. User type; They are in the form of customer and subscriber. According to this heatmap graphic, if we interpret the darkest color, subscriber men use citi bikes more intensely on Thursdays. The number of these people is 259,316.

#### Graph 6. Number of Trips w/Bike ID
<img width="883" alt="Screen Shot 2022-12-22 at 5 44 19 PM" src="https://user-images.githubusercontent.com/26927158/209246728-898176ab-5ee5-4935-807f-7b2c735c7e10.png">
The bar graph above shows the numbers for each bike ID. While the bike information belonging to the highest number is Bike ID: 38124, the number of bikes with this bike ID is 479. Also, if we look at the coloration scale, if the darkest red is the lowest number, the coloration becomes lighter as we approach the average of the highest and lowest number. In other words, the approximating value is shown with the open value, while the value deviating from the mean is shown with a darker color. Bike values with less than average numbers are in red, while bike values with more than average are in blue. In other words, there are three bikes above the average. It is clearly seen that there is 1 bike in the average value.

#### Graph 7. Bike Utilization
<img width="900" alt="Screen Shot 2022-12-22 at 3 11 35 PM" src="https://user-images.githubusercontent.com/26927158/209246798-dd93ffe6-bd51-441a-a96f-5065ce6a669c.png">
The circle graph above shows the trip time of each bike id. The longest tripping Bike ID: 39570, while the tripping time is 3,838,486.

#### Graph 8. Top Stops
<img width="897" alt="Screen Shot 2022-12-22 at 3 08 22 PM" src="https://user-images.githubusercontent.com/26927158/209246849-8ad16f51-2944-4b83-9c17-036d4fdee8c6.png">
On the top stops graphic, there are the names of the stops, the total number of bikes stopped at these stops and station ID information. According to this, 16,455 bikes were stopped at the station named Pershing Square North, whose station ID is 519.

## Summary
In general, it can be easily seen that the most valuable part of a work is visualization. With the help of visualization techniques, more than one data can be compared in a table and thought analytically, and a useful study can be created.




















