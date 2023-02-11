# bikesharing
Module 15: Citibike with Tableau
--------------------------------------

## Overview:
We want to launch a bike-sharing service in Des Moines, Iowa. One of the stakeholders interested in funding the business is interested in some analysis based on the service that exists in New York city. They are initially interested in answering the following questions:

- The length of time that bikes are checked out for all riders and genders
- The number of bike trips for all riders and genders for each hour of each day of the week
- The number of bike trips for each type of user and gender for each day of the week.

The main results can be seen at this [Tableau Public link](https://public.tableau.com/app/profile/alexandra.huang/viz/DataAnalysisBootcamp_Module15Assignment_BUT-VIRT-DATA-PT-10-2022-U-B-TTH/CitiBike_Data?publish=yes)

## Results:

The data used is for all trips taken in August 2029. There were a total of 2,344,224 trips taken with 13,983 bikes. 

**Length of Time**

The chart shows the number of trips at each duration, up to 60 minutes. While there is data for trips over 60 minutes, the bulk of trips fall below 60 minutes - the the most common trips being 10 minutes. 

The bottom chart shows the distribution of trips including those going to 1 or 2 miles, and you can see that the data stays flat after 60 minutes. 

**The number of bike trips accross hours of day** 
This chart shows a heatmap of usage through the day per weekday, with yellow being the least number of rides, to red being the most number of rides. 

The most popular weekdays to ride are Thursday through Saturday, with most rides falling between 8am-10am and 4pm-7pm. 

**Gender Data**
This slide takes the above two charts and duplicates the methods among the gender-identity of the services' users. From the data, it appears that the service's users are predominantly male, but the trends for usage duration and times of day are relatively the same accross genders. 


## Summary:
There may not be a lot of business decision that can come from the analysis so far, but some things we know for sure are that we can assume that users are taking bikes for short distances, and that usage increases as the week progresses. There is much more we can ask from this preliminary look..

Why are the trip durations so short? Is the bike-share considered "last mile transportation"? Or might it be simply due to the nature of NYC? Does distance play a part in the lengeth of trip duration? 

Why is male ridership so high compared to female (and unspecified?). Might there be an untapped consumer base in female riders? 

Other visualizationation worth creating would be instead of gender division, we'd look at user type division. Does the behaviour of subscribers vs non-subscribers differ. We might also be able to dive in to how frequently certain bikes are used, and if bikes seems to stay within a certain geography, or if the bikes get even usage throughout the service area. 

