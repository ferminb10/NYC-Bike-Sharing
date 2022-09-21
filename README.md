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

Next, we wanted to figure the bike traffic. A heatmap was chosen to help show the patterns by weekday. It was noted that during the weekdays there was heavy usuages right before regular work hours (around 8AM) and right after work hours (around 5PM, **Wednesdays seemed to be an exception**).

![3](https://user-images.githubusercontent.com/107658895/191388910-8cbc291d-8a0e-4bd6-918d-dc69a6cd0ac3.png)

Similarly like before, we wanted to figure out "Which gender provides the most traffic throughout the week". In the figure below we can see similar trends between the groups, but slighly more active amongst males.

![4](https://user-images.githubusercontent.com/107658895/191389027-f84dea53-1e6a-44b6-8dff-6be52d1b60ca.png)

Finally, we wanted to see the significant differences between the userbase (**Subscriber vs Customers**). The data shows that a subscriber tends to be consitently more active throughout the week than a customer. There was even more activity with the Female Subscriber group than the Male Customer (**the dominant group**). This tells use that a subscriber is going to use the subscription. It'd be interesting to see how long it takes a customer to go from Customer to Subsriber to measure a sort of customer progression/satisfaction rating.  

![5](https://user-images.githubusercontent.com/107658895/191389120-25b8762e-b495-4f32-8787-992dcb80b959.png)


This Tableau story can be seen here, [at this link](https://public.tableau.com/app/profile/fermin.banuelos/viz/BikesShares/Story1?publish=yes).



## Summary
Based on the functionality of this script, it's propose can be used for other elections big or small. It would be an interesting parameter to see the geographical location of each person who voted and create a heat map. This will give valuable information of where to do more outreaching to get a more wholistic representation of the local population. The limitations of this dataset are that they only limit a few parameters. It would also be interesting to see the age groups and genders that participated in the election so that the parties can go about better strategizing for target audiences they struggled. 
