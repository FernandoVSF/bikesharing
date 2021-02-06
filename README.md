# Bike Sharing Analysis
  Analysis of Bike Sharing data in NYC.
  
## Overview of the analysis
Present a business proposal for a bike-sharing company showing bike trip analysis in NYC.
The following outputs will be produced:

- Change Trip Duration to a Datetime Format
- Create Visualizations for the Trip Analysis
- Create a Story and Report for the Final Presentation
  
## Resources
- Data Source: 201908-citibike-tripdata CSV file
- Software: Tableau, Python, Jupyter Notebook

## Results
NYC Story is presented in two dashboards, one showing analysis of trip duration, and the other showing analysis of pick hours/days for bike utilization in NYC.

### Duration Dashboard
![Duration](/Duration.png)

The Duration Dashboard brings the following results:

  - Checkout Times for Users:  This chart shows that the length of time that bikes are checked out for all riders occurs more frequently in 5 hours, with a rapid increase starting in 1 hours, and slow decrease after 5 hours.

  - Checkout Times by Gender:  This chart shows that males are a big majority of the users.  What differs within genders is the fact that after the inflexion point in 5y, average duration decreases more rapdily than other genders.

  - Average Trip Duration: This chart shows that younger users tend to have longer trips, probably explained by having greater resistance and more younger people using bikes as transport.  The data shows users in August 2019 born before 1890, which requires further analysis in data quality.

### Pick Hours Dashboard
![PickHours](/PickHours.png)
   
The Pick Hours Dashboard brings the following results:
 
  - Trips by Weekday per Hour: This chart shows that most of the trips occur around 5-6pm, when people leaves work, and then at 8am, when people head to their workplace.

  - Trips by Gender (Weekday per Hour):  This chart shows that while male and female show similar patterns in time (being male appearing more frequently given most of the users are male), there is no clear patter for unknown gender on businessdays, and more usage during daytime.

  - August Peak Hours: This chart brings another view of the pick hours, showing the same results than the first chart but with a more numeric represenation, and not breaking per weekday. Again, pick hours occor between 5-6pm, sand then at 8am.

  - User Trips by Gender by Weekday:  This chart shows that while subscribers use bike sharing mostly during business weekday, being Thursday the pick day, non-subscribers use mostly during weekends.  Also there are more unknown gender in custumers than subscribers, probably for loser registration requirements.
 
## Summary

Although data was obtained from NYC users, since the analyses were produved using generic information and not city specific, we believe they are very good proxy on how it would behave in any other US location.  Key results were a higher usage of male and younger population, and pick hours at time people go from and to work during business days and more driven to daylight on weekends.  It also shows that most of people who use it for work subscribes to the service, and there's not much registration requirements for regular customers.

We suggest the following additional visualizations for future analysis:

  - User age trend by gender
  
  - Duration time per type of user  
  
## Link to Dashboard
  
[Link to NYC Story](https://public.tableau.com/profile/fernando.santos8046#!/vizhome/challenge_16126440284230/NYCStory?publish=yes "Link to NYC Story")
