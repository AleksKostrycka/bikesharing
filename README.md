# bikesharing

## Overview of the Analysis

Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, I used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I created a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.
* Finally, I added these new visualizations to the two created earlier in the module for the final presentation and analysis to pitch to investors.

## Results

Below are the results of the analysis. Not picutred is the .ipynb file that was used to convert the tripduration column from an integer to a datetime datatype. This can be found here: [link to file](https://github.com/AleksKostrycka/bikesharing/blob/main/NYC_Citibike_Challenge.ipynb) 

A new CSV file was created with the change to the trip duration column which was then used to create all below visualizations. This file could not be uploaded to Git Hub becuase of the size of the file. 

Visualization # 1 Checkout Times for All Users:

![This is an image](https://github.com/AleksKostrycka/bikesharing/blob/main/Resources/Checkout%20Times%20for%20Alll%20Users.png?raw=true)

This graphing of number of trips with in the dataset by trip duration show that the vast majority of trips taken on CitiBike bikes are over an hour in length. More specifically, most trips are increasing with duration of 2 hours. 

Visualization # 2 Checkout Times by Gender 

![This is an image](https://github.com/AleksKostrycka/bikesharing/blob/main/Resources/Checkout%20Times%20by%20Gender.png?raw=true)

In this visualization, I graphed the length of time that bikes are checked out for each gender.This breakdown of number of rides by duration, by gender, makes it more apparent how many more rides are taken by male-identifying individuals.

Visualization # 3 Trips by Weekday for Each Hour

![This is an image](https://github.com/AleksKostrycka/bikesharing/blob/main/Resources/Trips%20by%20Weekday%20per%20hour.png?raw=true)

A heatmap helps show weekly usage patterns. We can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. We can still see low-usage time in the early morning hours, every day of the week.

Visualization # 4 Trips by Gender (Weekday per Hour)

![This is an image](https://github.com/AleksKostrycka/bikesharing/blob/main/Resources/Trips%20by%20Gender%20(Weekday%20per%20Hour).png?raw=true)

This visualization reinforces two points made above that: 1) male identifying individuals take significantly more rides than female identyfing individuals, and 2) that the heaviest bike usage is during the weekday commute times. Therefore in the graphis above you can see the differences in male anf female bike usage as well as the heavy usage during weekday commuting times. 

Visualization # 5 User Trips by Gender by Weekday

![This is an image](https://github.com/AleksKostrycka/bikesharing/blob/main/Resources/User%20Trips%20by%20Gender%20and%20Weekday.png?raw=true)

This heatmap reinforces again how much of the userbase is dominated by male-identifying users. Why this is the case is unclear and could be an additional question answered by further study & analysis. 

Visualization # 6 Users of CitiBike

![This is an image](https://github.com/AleksKostrycka/bikesharing/blob/main/Resources/Trips%20by%20UserType.png?raw=true)

This visualization represents the population of users of CitiBike in NYC. As you can see from the graphic the majoirty of users are Subscribers with 1.9M users. These individuals are frequent riders who use the bikes regulary and are a predictable source of income for CitiBike. Customers who are more like one time users make up less than 500K of the population of users. 

Visualization # 7 Users of CitiBike be Gender

![This is an image](https://github.com/AleksKostrycka/bikesharing/blob/main/Resources/Trips%20by%20Gender.png?raw=true)

Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.









