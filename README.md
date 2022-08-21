# surfs_up

## Project Overview
The purpose of this analysis was to review weather data for the Island of Oahu that would determine if it is a good location to open up an ice cream and surf shop.  This would be determined by weather data including temperatures at the location.

## Steps
1. Query the sqlite database using SQLAlchemy
2. Filter the database and add to a dataframe
3. Use the describe method for summary statistics

## Summary
The analysis of the weather data shows that:
- There is a small difference in temperatures between the months of June and December.
  - There is less than 4 degrees of difference between the two months.
  - There is small change in temperatures from day to day in both months (variance is low).
 
## June Temperature Statistics<br>
![June_Temperatures](https://user-images.githubusercontent.com/106936638/185806135-9a687986-3102-46a0-a310-bc7bb54fed44.PNG)
  
## December Temperature Statistics<br>
![December_Temperatures](https://user-images.githubusercontent.com/106936638/185806134-3d689bcc-e656-40d6-b9da-e528a5fd6c5a.PNG)

An additional 2 queries that could be performed to gather more weather data for June and December would include following the same methods to view the percipitation statistics for the two months.
