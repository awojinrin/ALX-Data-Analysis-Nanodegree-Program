# Analysis for San Francisco Bay Ford GoBike
## by Gbenga Thompson Awojinrin


## Dataset

>This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. https://www.lyft.com/bikes/bay-wheels/system-data

The data for each trip is anonymized and includes information like:

<li>Trip Duration (seconds)</li>
<li>Start Time</li>
<li>End Time</li>
<li>Start Station ID</li>
<li>Start Station Name</li>
<li>Start Station Latitude</li>
<li>Start Station Longitude</li>
<li>End Station ID</li>
<li>End Station Name</li>
<li>End Station Latitude</li>
<li>End Station Longitude</li>
<li>Bike ID</li>
<li>User Type (Subscriber or Customer)</li>
<li>user's birth year</li>
<li>user's gender</li>
<li>If the user shared the ride during the trip</li>

> **Data Wrangling steps carried out include:**
<li>Identifying and cleaning data tidiness and quality issues.</li>
<li>Extracting the hour and day the ride started from the start time feature</li>
<li>Transforming features using a user-defined log transformation function when appropriate</li>
<li>Filtering out outliers where necessary</li>


## Summary of Findings

> Trips with the longest durations are usually taken by relatively younger users between the ages of 20 and 45.  

> Customers were also observed to, on average, take rides that lasted longer than rides taken by subscribers.  

> Rides taken during weekdays were on average observed to take longer than rides on weekends.  

> Rides during the weekends were less frequent than during weekdays. We observed a bimodal distribution of rides during weekdays with peak periods at 8AM and 5PM. However, on weekends, peak period is around 1-2PM, and it is not bimodal. This kind of suggests that the usage during weekdays is highly influenced by opening and closing hours of business, while the weekend is more flexible and dependent on the whims of the users.


## Key Insights for Presentation

> The distribution of subscriber trips across the days of the week indicates that the bike sharing service is used during weekdays majorly for commuting to work. This is due to the evident bimodal nature of the distribution of subscriber's usage, with peak periods that coincide with the start and close of working hours. 

> Peak periods of bike usage occur at 8AM and 5PM on weekdays, and 1PM on weekends, so subscribers can plan their rides to avoid the traffic bound to occur at these times, while customers can take advantage of the increased demand during these periods.

> Bike users between the ages of 20 and 50 tend to take longer rides, so if this is a monetized service, encouraging marketing that targets this user demographic is a plausible strategy for increasing revenue.