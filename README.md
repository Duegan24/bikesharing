# NYC Citi Bike Analysis Report

## Background and Results

### Purpose
Citi Bike is hypothetically evaluating expanding their area of service to provide bike sharing to Des Moines city.  To achieve the evlaution it was necessary to evaluate how they were successful in other metropolitan cities and determine if those factors are also present in Des Moines. In New York, Citi Bike has been very successful and has a deep dataset with a significant amount of activity that will help give a reasonable bases for evaluating the placement of a similar business in Des Moines. The data used for the evaluation was from August 2019 and for each ride shows demographic information of the person riding the bike and the location the ride started and stopped.  This was a useful dataset to evaluate how concentrated the activity was.  In addition, 2018 population density maps and McDonalds store location information was used to help determine similarities between the two cities and where it could be expected that the greatest level of biking activity in Des Moines would likely be concentrated.  Tableau was used to visuallize the data.  

## Resources
- Data Source:  
    - 201908-citibike-tripdata.csv (https://s3.amazonaws.com/tripdata/index.html), 
    - ia_mcdonalds.csv, ny_mcdonalds.csv
- Software:  Tableau version 2020.2.2


### Technical Analysis
The below analysis is based on the information presented in a Tableau Story which can be viewed at:
[link to dashboard](https://public.tableau.com/profile/jason.glascock#!/vizhome/CitiBike_Analysis_15938843506300/Story1?publish=yes)

This evaluation was performed to evaluate some key questions that will be critical to understand before moving forward with the investment into a new ride sharing business in Des Moines.  Some of the basic questions to ask are:
    - How to structure the ride business to insure we are servicing people that want to use our service?
    - What is the population of Des Moines and how does that compare to New York City?
    - Does the population affect the number of people who will use the bike-sharing program?
    - What is the density of McDonald's in New York City versus Des Moines and does this affect where people go n the city?  If so, how?

In evalating the trip data provided for New York in August of 2019, it was important to look at some basic information.  The first two slides show the prime biking time which shows that the window of activity is quite wide with most of the activity between noon and 7pm.  In the next slide I examined how the age of the rider effected their trip duration.  As the age of the rider gets younger the trip duration increases.  The most consistent ride durations were observed to be by riders that were born between 1945 and 1995.  This is a wide range; however, it does show that using a bike sharing service is not issolated to only the young.

The next step was to look at the geolocation information to determine if there is a patern.  On the Critical Starting Location tab, it can be seen that the starting locations are highly concentrated in the city center of New York where there is a higher prevelance of tourist activity.  We will want to simularly concentrate our Des Moines starting locations near the city center.  

To evaluate how Des Moines will compare with New York, I looked at two factors: Population Density and McDonald's locations.  To start with, New York had a population of 8.4 million with a significant amount of that population concentrated downtown.  In addition, we see that the critical starting locations are also concentrated in the greatest concentration of the populaton.  In the Des Moines Population Density slide we see that while Des Moines had a much smaller population in 2018, it also has a large concentration of its population in the downtown area.  This further supports that there would be the necessary density of people to support a bike sharing company.

Finally, I looked at the McDonald's locations in New York.  In that slide we see that there is a significant concentration of McDonald's locations downtown.  Further we see that the bike sharing activity coincides with that concentration of McDonald's locations.  Not suprising, Des Moines also has a concentration of McDonald's locations further supporting the conclusion that downtown would be a prime location to start a bike sharing business.


### Results
As identified by the evalaution, there exellent evidence that there is broad acceptance and use of Citi Bike's ride sharing service in New York across a wide range of ages and broad operating times.  This demonstrates that another city will likely have similar success.  While Des Moines has a signficantly smaller population; that population is most dense downtown which is similar to New York City.  In addition, we see a similar concentration of McDonald's locations further supporting that while the total city population is considerably smaller there would be a large enough community to support setting up a new bike sharing company in Des Moines.