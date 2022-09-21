# NYC Bike Sharing Analysis
To uncover NYC Bike sharing trends with Tableau's visualization tools
## Overview of Project
This weeks challenge helps us build upon our skills learned in the Tableau module. We were tasked to convince investors that a bike-sharing program in Des Moines is a great investment opportunity. One of the key stakeholders wanted to see a bike trip analysis to solidify the solid buisness proposal.
client wanted additional information analyzed from the election results. For the analysis, Pandas was used to change the "tripduration" column (extracted from NYC's Bike sharing database) from an integer to a datetime datatype. Using the converted datatype, a set of visualizations were made describing: the length of time that bikes are checked out for all riders and genders, the number of bike trips for all riders and genders for each hour of each day of the week, and the number of bike trips for each type of user and gender for each day of the week. To concluded, the visualizations created in this analysis were used to pitch to investors.

## Results
The analysis had few tasks. For deliverable 1, a CVS file was extracted from a NYC bike sharing database to convert the trip duration datatype to one that can be easily analyzed through Tableau. Doing so helped us determine the number of bikes being used within the first few hours of the trip duration, as shown below.

![1](https://user-images.githubusercontent.com/107658895/191388669-ec24281b-0d92-4f12-ad58-f22a974fde42.png)

One of the biggest questions we wanted to answer for our stakeholders is "Who is our main support and who can we improve on marketing for". The visual below shows the number of bikes being used within the first few hours of the trip duration by gender. It was interesting to see there was a significant gap between males and females. 

![2](https://user-images.githubusercontent.com/107658895/191388820-404d4071-692d-4d13-9cd5-33fd6636263e.png)

Next, we wanted to figure the bike traffic. A heatmap was chosen to help show the patterns by weekday. It was noted that during the weekdays there was heavy usuages right before regular work hours (around 8AM) and right after work hours (around 5PM, ** Wednesdays seemed to be an exception**). An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.

![3](https://user-images.githubusercontent.com/107658895/191388910-8cbc291d-8a0e-4bd6-918d-dc69a6cd0ac3.png)

![4](https://user-images.githubusercontent.com/107658895/191389027-f84dea53-1e6a-44b6-8dff-6be52d1b60ca.png)

![5](https://user-images.githubusercontent.com/107658895/191389120-25b8762e-b495-4f32-8787-992dcb80b959.png)







In this congressional election, there were 369,711 votes that were cast. Provided below are the counties with the largest number of votes in decending order:
* Denver
  * 306,055 votes (82.8%)
* Jefferson 
  * 38,855 votes (10.5%)
* Arapahoe
  * 24,801 votes (6.7%)

Below is a breakdown of the number of votes and their respective percentage of the total votes each candidate recieved. The canidate that won was Diana DeGette and the runners up in decending order by total votes are shown below:
* Diana DeGette
  * 272,892 votes (73.8%)    
* Charles Casper Stockham
  * 85,213 votes (23.0%)
* Raymon Anthony Doane
  * 11,606 votes (3.1%)

### Election Results Summary
![election_results](https://user-images.githubusercontent.com/107658895/176082445-ede641f1-8329-431c-8e59-a02f2ff13f01.png)
##### Figure 1 above displays the election results that were printed on the terminal and text file


This Tableau story can be seen here, [at this link](https://public.tableau.com/app/profile/fermin.banuelos/viz/BikesShares/Story1?publish=yes).



## Summary
Based on the functionality of this script, it's propose can be used for other elections big or small. It would be an interesting parameter to see the geographical location of each person who voted and create a heat map. This will give valuable information of where to do more outreaching to get a more wholistic representation of the local population. The limitations of this dataset are that they only limit a few parameters. It would also be interesting to see the age groups and genders that participated in the election so that the parties can go about better strategizing for target audiences they struggled. 
