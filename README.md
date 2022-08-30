# Surfs_Up

## Resources
- Data Source: [hawaii.sqlite](https://github.com/nkinsler/surfs_up/blob/main/hawaii.sqlite)
- Python: [SurfsUp_Challenge](https://github.com/nkinsler/surfs_up/blob/main/SurfsUp_Challenge.ipynb)

## Overview of the Analysis

Provide an analysis of temperature data for the months of June and December in Oahu in order to determine if the surf and ice cream shop business is sustainable year-round.  Includes providing the summary statistics for both June and December in a DataFrame.

## Results

![June_Temp](https://github.com/nkinsler/surfs_up/blob/main/Resources/June_Temp.png)!

![Dec_Temp](https://github.com/nkinsler/surfs_up/blob/main/Resources/Dec_Temp.png)!

1. The minimum temperature difference between June and December is 64 compared to 56, only a 8 degree difference.  This information is useful as the lower the temperature gets the more likely business will be negatively impacted as fewer customers are likely to surf and/or ice cream.
2. 50% of the temperatures for June was between 77 and 73 while temperatures for December was between 74 and 69.  This range is fairly low for both months indicating consistent temperatures for surfing and ice cream for 50% of the time.
3. The standard deviation for December was higher (3.75) than June (3.26) indicating temperature for December are more likely to vary from the mean any given day.  This stat is useful for determining likely hood of consistent sales for a month.  The lower the standard deviation the more consistent temperatures and more likely sales are to be consistent.

## Summary

Overall temperatures are fairly consistent between June and December indicating that opening the surf and ice cream shop has ideal conditions to succeed.  Additional analysis to perform in order to provided additional data for assessment are listed below in "Additional Queries to Run."

### Additional Queries to Run

1. Precipitation

![June_Prcp](https://github.com/nkinsler/surfs_up/blob/main/Resources/June_Prcp.png)!

![Dec_Prcp](https://github.com/nkinsler/surfs_up/blob/main/Resources/Dec_Prcp.png)!

Given the risk inclement weather plays in surfing and eating ice cream, running an analysis on precipitation for June and December is useful information to have.  With the query ran, it was determined that December generally has .08 more rain on average than June.  In addition, the potential for significant rainfall is higher in December with a max rainfall of 6.42 compared to 4.43. 

2.Service Station

![June_Active_Temp](https://github.com/nkinsler/surfs_up/blob/main/Resources/June_Active_Temp.png)!

![Dec_Active_Temp](https://github.com/nkinsler/surfs_up/blob/main/Resources/Dec_Active_Temp.png)!

June average temperatures (73) for most active station stayed relatively consistent with June average temperature (75) for all stations combined only varying by 2 degrees.  December average temperatures (70) for most active station stayed relatively consistent with December average temperature (71) for all stations combined only varying by 1 degree.  For the most part the active station is fairly consistent with the combined station's data for June and December.
