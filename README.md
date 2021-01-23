# Bikesharing Analysis

## Overview
To understand whether or not a bike sharing program should be adopted in Des Moines, we decided to take a look at the NYC CitiBike ridership program to get an idea of when people ride, how long they ride for and if there are differences between ridership of subscribers/non-subscribers and weekly/hour of the day factors. The visuals of this analysis can be found in this Tableau workbook.
https://public.tableau.com/profile/jennifer1946#!/vizhome/TableauChallenge_16113679956150/CitiBikeAnalysis?publish=yes

## Results
### Trip Duration
The most popular number of hours to ride are between 4 and 6 hours. Consider looking at pricing for non subscribers with rates below 4 hours, rates at 4-6 hours and rates greater than 6 hours.
![Screenshot](https://user-images.githubusercontent.com/72076683/105611075-d53dfc00-5d78-11eb-8b7f-11d454c0fb45.png)

### Starting times
During the weekdays the busiest times are in the mornings - around 8AM and in the evenings around 5-6PM. Commuters tend to be active except Wednesdays. This might be a good day to plan maintenance. For the weekends, start times are more steady throught the day, starting around 9AM and getting stronger mid day. There seems to be no remarkable difference between starting/ending times by gender.
![Screenshot](https://user-images.githubusercontent.com/72076683/105611111-1209f300-5d79-11eb-8219-9ac9c1346098.png)
![Screenshot](https://user-images.githubusercontent.com/72076683/105611147-3bc31a00-5d79-11eb-9aa5-8c06ccd28fbd.png)

### Gender Considerations
Overall, there are more men who use the CitiBike service than women. The reason for this is men tend to be suscribers to the service and it looks like it is popular for commuting. 
![Screenshot](https://user-images.githubusercontent.com/72076683/105611099-f6065180-5d78-11eb-8897-90bb98eb0b73.png)
![Screenshot](https://user-images.githubusercontent.com/72076683/105611170-572e2500-5d79-11eb-9120-eceed846c589.png)

### Age Considerations
It looks like subscribers are mostly male and the majority range in age from mid twenties to 40s. For non subscribers the top age hovers around 50. I was curious why this age was so concentrated and found [this article about a boom in cycling during the early 70s](https://archive.curbed.com/2017/6/28/15886810/bike-transportation-cycling-urban-design-bike-boom), prompted by Earth Day. 
![Screenshot](https://user-images.githubusercontent.com/72076683/105613372-b5620480-5d87-11eb-96dc-bbe3fe90f209.png)

### Location Considerations
In looking at the locations for subscribers versus non-subscribers, it looks like most non subscribers start their rides from the upper West/East side of Manhattan where the museums are concentrated. Subscription riders tend to be closer to Mid-town and the financial district. In the Tableau report, you can filter by subscriber/non-subscriber on the map as shown in the image below.
![Screenshot](https://user-images.githubusercontent.com/72076683/105613389-d75b8700-5d87-11eb-90a8-12eaa1a86432.png)

## Summary
To summarize, for NYC, it appears that most non-subscription riders are older, around 50 years of age. I would look at how many people of a similar age visit Des Moines before deciding to offer a bike sharing service for tourists or non-regular commuters. Many non-subscription riders tend to be around tourist locations or museums. To visulaize whether to invest in a non-subscription plan in Des Moines, I would collect from the top tourist destinations visitor data by age visualize this on a map to see if there are clusters of people the right target age (and gender).

I would also take census data and visualize the concentration of men between 25 and 50 to determine if there is a physical cluster of this demotraphic to determine if it would make sense for a commuter bike sharing program. We would need to measure the distance of this cluster to the central business district.
