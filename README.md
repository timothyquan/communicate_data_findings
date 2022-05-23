# Ford GoBike Data Exploration

## by Timothy Lee Quan

![Ford GoBike](https://icdn.digitaltrends.com/image/digitaltrends/ford-gobike.jpg)

## Dataset

For this project I selected the 'Ford GoBike' dataset.
The dataset contains 183,413 records of bike rides in February 2019 only.
Each row represents a 'ride', and contain a combination of time, location, and user data for each ride.

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District.[3] Bay Wheels is 'the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company.
[Bay Wheels (Ford GoBike)](https://en.wikipedia.org/wiki/Bay_Wheels)

## Summary of Findings

* Peak usage time is between 07:00-10:00 and then again between 16:00-20:00 on weekdays. This may indicate a primary use case being commuting. Non-subscribers usage trend is less pronounced during this commute hours, and additionally see some peak usage between 10:00-18:00 on weekends.
* People tend to have longer rides on weekends, and non-subscribers tend to go on much longer rides.
* There is a surprising trend for longer rides between 00:00-05:00, which may indicate something about nightlife.
* Because members aren't identified in the dataset with a member_id, there was no way to reconcile individual rider patterns over multiple rides.
* Considering the dataset only covers 28 days, the bikes see a lot of use. The time limitation probably prevents any further analysis regarding wear and tear, break downs.

## Key Insights for Presentation

For the presentation, I would focus on time/day and membership, in this order:

* Distribution of ride start times - what are the peak times that people start rides?
* User type by rides - in what proportion are the user types represented (customer vs subscriber)?
* Average ride duration by user type - does one user type ride longer than the other?
* Duration by day of week and hour of day: customer vs subscriber - Given any differences in duration for customers and subscribers, do they share any trends or distinctions by week and time of day?
* Top riding times by day of week and hour of day: customer vs subscriber - Given any trends in peak times to start rides, are they shared or distinct with the user types?
