# Tableau Homework Assignment
## CitiBike Data Analysis

## Overview of Project

We were given the task of analyzing a year of data related to New York City's CitiBike program and making a series of conclusions from the data and explaining them.  In this analysis I explore the overall ridership with the CitiBike program and some rider analytics such as gender and age.  I also explore some bike statistics and station statistics.  Finally, I was tasked with finding some strange phenomena that appear in the data that would otherwise be unexplained.  

All of the screenshots used here are available in the screenshots folder.  I also was unable to link to the data here on GitHub, so the raw data and the tableau workbook are available from the mega.co.nz download links that are in the markdown file "linkstocsvsandtbwx.md".  The process I used was to go ahead and download the data from the CitiBike website (https://www.citibikenyc.com/system-data).  I went with about a year of raw ride data covering the timespan of May 2018 to May 2019, to make the most current and up to date analysis.  I then combined the data and imported it into tableau to analyze the data.

### Total Ridership Over Time and Split between Customers and Subscribers

Here, I have a graph that shows overall ridership over the time period sampled.  Overall ridership is the green line on top.  Then the ridership is split between single ride customers and subscribers.  You can clearly see in this image that the subscribers to CitiBike are their major source of ridership and that there are significantly fewer customers than subscribers.  This trend continues throughout the year sampled.

<br/>

![](screenshots/isSubscriber.png)

### Age and Gender Analysis

Here we explored some analytics of the riders.  We broke down ridership by gender and age.  First, let's explore the CitiBike riders and their gender.

Here in this first image you can see the overall ridership by gender separated three different ways.  We display the overall total ridership between gender as a total number, throughout the year as the graph, and we've got the average trip duration and trip length by gender.  It is clear by a very large margin that a majority of CitiBike riders are male with about 14 million male rides over the year as opposed to 4 million female and around 100 thousand rides taken by someone of unknown gender.  However, on average males take shorter rides in duration and length than female riders and riders of unknown gender.

![](screenshots/GenderInfo.png)
<br/><br/>

In this second image here we analyze overall ridership by gender and year of birth. Here we can see, once again that the most common users of CitiBike are males.  However we add their birth year to this image.  So we can see that the most common user of the CitiBike program are Males born in the year 1988.  We have also displayed a chart (fully viewable in the workbook that is available in the above linked file) showing a range of birth years that are common.  In the range we can that the most common birth year of riders (not separated by gender) is also the year 1988.  So the most common users of the CitiBike over the sampled time are 31 year old males.
<br/><br/>

![](screenshots/BirthYearandGender.png)

Here we explore the average trip duration by age of the rider.  We can see that the users with the highest trip duration are the youngest users at around the age of 17.  However there is a peak right around the user's age hitting 31 as we explored above.  This can likely be explained by the 31 year old users being commuters from elsewhere in the city and using CitiBike as a more healthy, earth-conscious, and cost effective option to either owning a car or frequently using mass transit.
<br/><br/>
![](screenshots/TripDurationbyAge.png)

### Analysing bikes by ID likely due for inspection and service.

We were also tasked with identifying which bikes, by bike ID would likely be due for inspection or service.  This is examined by exploring which bikes are used the most and which are used the least during a period of time (again, the one year sampled period).  Here we see the most frequently used bikes along with their average rider age, which is surprisingly 39 years old as opposed to the 31 year olds who we saw are the most frequent riders on the system.  We also explored on the right-hand side how many bikes are in service throughout the year.  A general observation that we can make here is that we can take bikes out of the system for service in the months of July, September, and October.  This is likely due to July being too hot to use the CitiBike service and September and October being less active with tourists to the New York City area.  A conclusion I can draw here is that we ought to take top listed bikes on the left hand side out for service the next time they become available.
<br/><br/>
![](screenshots/BikeIds.png)



### Start Stations and Stop Stations

In the below images you can see a map of the popularity of start and stop stations with CitiBike throughout NYC.  In these images you can discern that the most popular stations to start and stop a CitiBike rider are in the boro of Manhattan.  We can also see a list of the most and least popular stations to start and stop a CitiBike ride.  The least popular stations to start and stop a ride seem to be system stations or on the outskirts of the city.  There is a very large discrepancy between the most and least popular stations in number.


![](screenshots/StartStations.png)

<br/>

![](screenshots/EndStations.png)

### Peak Riding Hours in Summer and Winter Months
<br/>

In this analysis I was looking to examine the peak riding hours throughout the year.  We were looking to compare the peak riding hours between the summer months and the winter months.  The analysis of the summer months can be seen in the first image below.  This image analyses the months between June and September.  The darker the line gets the higher the ridership gets.  Here you can see that the peak ridership aligns with the AM and PM rush hours at 8 AM and 5 PM.  Prior to finding more conclusions we need to examine the winter ridership.
<br/><br/>
![](screenshots/SummerPeakHours.png)


This second image here displays the peak ridership hours in the winter months.  The months surveyed in this image are December to March and uses the same color logic as the above image.  Here you can see that the peak ridership per day in the winter months also coincides with the AM and PM rush hours.  It is worth noting the severe difference in ridership counts in the summer and winter.  The peak ridership in the winter is about half of that in the summer months.  Otherwise, the ridership in the winter and summer months are very similarly shaped.

![](screenshots/WinterPeakHours.png)

### Unexplained Phenomena

##### Phenomena Number 1 - Unexplained

The first unexplained phenomena I encountered can be seen below.  There is an excess of user registrations of unknown gender totaling about 1,547,272 (as seen in the below image) that have a birth year of 1969.  A possible explanation for this is that this is the default gender and birth year of registrations or what a new registration form auto populates to.
<br/><br/>
![](screenshots/Unexplained1.png)

##### Phenomena Number 2 - Unexplained cluster of stations.

In the Bronx there is very little CitiBike ridership.  However, in the images shown below there is a cluster of ridership.  This cluster is in the Bronx around Fordham University.  This cluster is in the middle of a CitiBike drought.  There is no usage around it until Manhattan.  This cluster is not shown in the above images of ridership because there is no other ridership in the Bronx.  Therefore these were assumed to be an unexplained phenomena and not displayed in those above maps.
<br/><br/>
![](screenshots/Unexplained2.png)
