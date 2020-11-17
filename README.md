# Bike Sharing

## Overview
Analyze the New York City 'Citi Bike' trip data that has been released to the public for August 2019. Prepare a bike trip analysis for NYC, and use that analysis to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. However caution is needed when looking at the data, as it applies specifically to New York City—Des Moines is quite different!


## Resources
- Data Source: ["Aug 2019 NYC Trip data"](https://s3.amazonaws.com/tripdata/index.html)
- Software: Python 3.7, Jupyter Notebook, Tableau 
- Library: Pandas


## Results

- Dashboard
  - We get a quick overview about the number of trips for the month of August in 2019, gender breakdown, top starting locations and average trip duration.
  - Pie Chart colors:
    - Orange = Male
    - Blue   = Female
    - Red    = Unknown
  
  !["Dashboard"](./Images/dashboard.png "NYC story dashboard")
  
  
- Utilization
  - Bike utilization shows how much a particular bike is utilized
  
  !["Utilization"](./Images/bike_utilization.png "Bike Utilization")
  
  
- Times for Users
  - This shows us that a large number of bikes are utilized around 5 am.
  
  !["Times for Users"](./Images/checkout_times_for_users.png "Times for Users")
  
  
- Times for Users by Gender
  - Furthermore we see that more men use the bikes in morning than women.
  
  !["Times for Users by Gender"](./Images/checkout_times_for_users_by_gender.png "Times for Users by Gender")
  
  
- Trips by weekdays by Hour
  - More trips were recorded during mornings between 4 am and 10 am and afternoons between 4 pm and 8 pm. Friday shows more trips after lunch. Saturday and Sunday show more trips between 10 am and 8 pm.
  
  !["Trips by weekdays by Hour"](./Images/trips_by_weekdays_by_hour.png "Trips by weekdays by Hour")
  
  
- Trips by weekdays by Hour by Gender
  - Even with splitting the data by gender shows the same results.
  
  !["Trips by weekdays by Hour by Gender"](./Images/trips_by_weekdays_by_hour_by_gender.png "Trips by weekdays by Hour by Gender")
  
  
- Trips by weekdays by Gender
  - More trips were recorded by subscribers as opposed to customers.
  
  !["Trips by weekdays by Gender"](./Images/trips_by_weekdays_by_gender.png "Trips by weekdays by Gender")
  
  
- Tablaeu
  - A Full story of the above information is stored in the link below.
  
  ["Tablaeu story link"](https://public.tableau.com/profile/subbarao.bellamkonda#!/vizhome/Module14ChallengeSBB/NYCStory?publish=yes)


## Summary
Based on the data collected on the New York City bike trip data we can conclude that having a bike sharing program in New York city is a solid business proposal. However we do not have enough information to make a decison for Des-Moines. 

### Business Recommendations 
Based on the analysis done following additional visualizations are suggested.
 1. Analyze the return on investment for the whole year.
 2. Analyze the profitable business model customers vs subscribers.
 
