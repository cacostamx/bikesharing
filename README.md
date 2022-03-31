# Bikesharing Analysis

**TABLEAU DASHBOARD LINK [HERE](https://public.tableau.com/app/profile/carlos.acosta2075/viz/CitibikeChallenge_16485150757890/CitibikeAnalysis)**

## Overview

The purpose of this analysis is to visualize data from NYC Citibike NYC in order to get some insights of its behaviour and to convince investors that a bike-sharing program in Des Moines is a solid business proposal.

The analysis is done to downloaded data from NYC Citibike rides for the month of August 2019, through Tableau visualizations.

### Resources

- Data source: NYC Citibike riding data for August 2019 in file '201908-citibike-tripdata.csv'.

- Software use to perform the analysis: Tableau Desktop Public Edition 2021.4.4 


## Results

### Stations

New York City has around 800 bike stations with around 14,000 bikes. August 2019 data shows that there were 2.3 million rides.

|**NYC Citibike Stations**                             |
|:----------------------------------------------------:|
|![Citibike Stations](/Resources/starting_stations.png)|

- The graph shows the locations of the citibike stations and the circle size corresponds to the number of trips started in each location.  The station with the most usage is the one located neear Grand Central Stations, followed by stations located in important commuting stations (metro, ferry, trains), as well as those around the busiest offices.

### User distributions

|**Users by Gender**                             |**Users by type**                           |
|:----------------------------------------------:|:------------------------------------------:|
|![Users by Gender](/Resources/riders_gender.png)|![Users by type](/Resources/rider_type.png)|

Data shows that male users are 2.6x female users. This contrasts to NYC actual population which show that women comprise 53% of total population.

NYC provides both membership or pay-by-day and pay-by-ride. Data shows that 81% or rides are made by suscriber riders. This would imply that bike transportation is a good alternative to the transportation infrastructure (metro, buses, taxis).  Most non-suscriber rides would be made by tourists.  

### Checkout times
|:------------------|:----------------------------------------------------------------|
|**Overall usage**  |![Checkout times](/Resources/Checkout_times.png)                 |
|**Usage by gender**|![Checkout times by gender](/Resources/Checkout_times_gender.png)|

As it can be seen the average usage time is between 5 and 6 minutes with no really difference between male and female users.

### Trips by weekday

|:------------------------------------|:-------------------------------------------------|
|**Trips per week and hour**          |![trips_week_hour](/Resources/trips_week_hour.png)|
|**Trips per week and hour by gender**|![trips_gender](/Resources/trips_gender.png)      |

The graphs above show that:
- Working days concentrate more trips than weekends.
- During working days, trips are concentrated in the rush hours: 7-10 am and 4-8 pm, whereas during weekends, they are concentrated more towards mid day and afternoon.
- There is a reduction during Wednesdays.
- The above is an indication that most bike commutes are used to get to and from work. Whereas on weekends they are used for sightseeing. 
- The behaviour is the same for both male and female, although, as mentioned earlier, men use the service more than women.


![trips_gender_type](/Resources/trips_gender_weekday.png)

Finally, this last graph reaffirms that most suscribers use bikes for their daily commuting to and from work and during weekends to commute within the city.  Customers (one-ride or day-pass) show more usage during the weekends.

## Summary

Data showed that NYC Citibike service is concentrated for inhabitants commuting to and from work, making the busiest stations those located near or at stations with transfers to other means of transportations. NYC is a place with high costs and traffic for regular transportaion, making bike a very good substitute.

The most important source of income are membership rides and men tend to use bikes more than women. Due to NYC grid, ride last on average 5 to 6 minutes which can be transalated to distances of 1 to 2 km.

### Recommendations

In order to provide a better analysis we recommend the following:

- Make a line graph for the busiest starting stations to all its ending stations to find out the routes usage.
- Determine the bike usage (per bike ID) with the count of rides for each bike.
- Determine the average number of rides each bike has to see if a rollover of locations is needed.
- Import data for other months to see the behaviour throughout the year. 