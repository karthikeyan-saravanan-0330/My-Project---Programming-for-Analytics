

# Analysis of effects Soccer matches on the inflow of flights to the match location

Authors:
- **Vamsi Krishna Kunapareddy**, **vkunapar@buffalo.edu**
- **Vikas Dadadalli Kumar**, **vikasdad@buffalo.edu**
- **Karthikeyan Saravanan**, **ksaravan@buffalo.edu**
- **Hemanth Ramineni Damodhar**, **hraminen@buffalo.edu**

YouTube Video:  [Not ready yet](http://your_link_goes_here)



## Task List

| ID | Task Description | Due Date | Responsible | Status | Comments |
| --- | --- | --- | --- | --- | --- |
| 1 | Find the Soccer and Flight data | 2023-05-02 | Vikas & Hemanth | COMPLETED | Finalised rapid-API |
| 2 | Clearly check for the required end points in the API's| 2023-05-03 | Vamsi & Karthikeyan | COMPLETED | Since all API's might not contain required end points a deep seearch into the API was required|
| 3 | Evaluate the biggest league based on the number of teams playing and extract required data| 2023-05-04 | Vikas & Hemanth | COMPLETED | Based on number of matches UEFA Champions League is finalised |
| 4 | Extract the fixture details of UEFA league in season 2018-19 in a data frame| 2023-05-05 | Vamsi & Karthikeyan | COMPLETED | Assuming Pre- COVID situation gives a better picture |  
| 5 | Merge airport details(ICAO code, size and average flights) of the teams' cities into fixture details dataframe| 2023-05-06 | Vikas & Hemanth | COMPLETED |
| 6 | For a particular home team find the change in number of flights for different away teams | 2023-05-07 | Vamsi & Karthikeyan | COMPLETED |
| 7 | Upload README.md document to Github| 2023-05-08 | Vamsi | COMPLETED |
| 8 | Determine which away teams' number of inbound flights are higher| 2023-05-09 | Vikas & Hemanth | IN PROGRESS |
| 9 | Taking only two teams determine which place has more foreign attendees| 2023-05-09 | Vamsi & Karthikeyan | IN PROGRESS |
| 10 | Merge airline details that operate from an airport to the original data frame | 2023-05-10 | Vikas & Hemanth | Not yet started |
| 11 | Plot the number of inbound flights of different airlines with time on X- axis  | 2023-05-11 | Vamsi & Karthikeyan | Not yet started |
| 12 |  Upload README.md document to Github  | 2023-05-12 | Vamsi | Not yet started |
| 13 |  Plot the delay of airlines on match day and compare with average delay of the airport | 2023-05-13 | Vikas & Hemanth | Not yet started |
| 14 |  Add match attendance and inbound flyers columns to the original data frame and loosely determine percentage of foreign attendees| 2023-05-14 | Vamsi & Karthikeyan | Not yet started | unable to find the required data till now |
| 15 |  Geo spatially plot the  number of inbound flights from away team city  with animation | 2023-05-15 | Vikas & Hemanth | Not yet started | Might cross the deadline since we do not have the required knowledge to animate. In that case, will be delivered without animation |
| 16 | Complete YouTube video and upload to YouTube | 2023-05-16 | Vamsi | Not yet started |
| 17 | Upload README.md document to Github | 2023-05-17 | Vamsi | Not yet started|

--- 

## Introduction
*Considering that flight delay is most studied field in Airline operations and that Soccer is a sport watched by millions of people not only on Television but also visiting the stadium, the effects of the sport on average delay and surge of the demand to book tickets seemed really interesting*

- *We are using soccer data from Rapid API(link in references) which contains interesting end points such as leagues,fixtures, venues and many more!*
- *Flight API with various end points such as airport, airlines, flight information are used to conduct the proposed analysis*
- *It is common observation that influx of people to a city is more due to a soccer match. Here, we try to quantitatively determine the change in the traffic of flights due to soccer match, which can be used by 
local municipalities to administer and manage the event better. This is done by visualising time on X- axis and the number of flights on Y-axis*
- *One might wondrer which is the bettter place (interms of influx of people) when a match happened between two teams, and the result might help taking many inferences such as the interest level of fans,
air transport network or even economy of a country. This is done by taking two teams's matches(one in home and another in away) and comparing the inbound number of flights*
- *Compare the airlines visually to determine which airlines have maximum change in the traffic due to a soccer match*
- *Visualize the change of average delay of the flights due to soccer match and determine which airline has the least or the highest delay*



---

## References

- 970+ football leagues & cups. Live score (updated every 15s), live & pre-match odds, events, line-ups, coaches, players, top scorers, standings, statistics, transfers, predictions
    (https://www.api-football.com/documentation-v3)
-  Flight data API for travel, hospitality, or aviation applications, researchers, small teams, and individual developers.(https://rapidapi.com/aedbx-aedbx/api/aerodatabox)


## Requirements

- *Install pandas and numpy using pip install method. Follow the link for more info https://phoenixnap.com/kb/install-numpy*
- *Sign up in https://rapidapi.com/hub and find API key in your profile and paste this key in the RAPID KEY variable provided in the code*


---
