# PyBer_Analysis  
## Overview  
After analyzing the rideshare data from Jan to early May 2019 and creating a compelling visualization for the CEO, Omar and I were tasked with creating a summary data frame of the ride sharing data by city type.  We used Pandas and Matplotlib to create a line graph showing the weekly fares for each city type.  
* Deliverable 1: A ride-sharing summary DataFrame by city type.  
* Deliverable 2: A multiple-line chart of total fares for each city type.  
* Deliverable 3: A written report for the PyBer analysis (README.md)  
## Results  
### Deliverable 1  
We used the groupby() function to get the total number of rides, total number of drivers, and total fares for each city type. WE did this using the count() and sum() methods. Our first step was to use our starter code to get the total ride for each city type. We did this by using the groupby() function and applying the count() method to the "ride_id" column. Next we created a data series that has the city type as the index and applied the sum() method to the "driver_count" column.  WE applied the sum() method again to the "fare" column.  
![groupby_using_count_sum](https://user-images.githubusercontent.com/96501958/152714861-144ddbeb-3ec2-4e0c-b2a5-eb665bea6874.png)  
We then calculated the average fare per ride and per driver for each city type. Finally, we created a summary DataFrame using all the data collected thus far and formatted it to our liking.  
![summary_dataframe](https://user-images.githubusercontent.com/96501958/152715317-fca9e3a0-a8be-423e-9cbb-b48de3f36c71.png)  
### Deliverable 2  




## Summary
