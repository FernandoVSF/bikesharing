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

  - Duration Dashboard
  
![Duration](/Duration.png)

   - Filtering by Shape = light
  
![f1](/f1_shape.png)
  
   - Adding filter by State = ca
  
![f2](/f2_state.png)

   - Adding filter by City = el cajon
  
![f3](/f3_city.png)

   - Adding filter by Date = 1/1/2010
  
![f4](/f4_date.png)
 
## Summary

One drawback of this design is that it requires the user to scroll over the whole list to select the input for the search criteria.  Another one is not being possible to reset filters (although we can select a new criteria for the filter).

As a recomendation for further dvelopments, I suggest the following:

  - Implementing combo boxes in the input fields, to show the possible selections and avoiding typos;
  
  - Implementing an option to reset filters, by "showing all" in the combo box suggested above.
  
