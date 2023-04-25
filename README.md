# IE 555 Project Proposal

## Team Members:  
- **Vamsi Krishna Kunapareddy**, **vkunapar@buffalo.edu**
- **Vikas Dadadalli Kumar**, **vikasdad@buffalo.edu**
- **Karthikeyan Saravanan**, **ksaravan@buffalo.edu**
- **Hemanth Ramineni Damodhar**, **hraminen@buffalo.edu**


---

## Project Title

**Analysis of effects Soccer matches on the inflow of flights to the match location**

--- 

## Project Type

### Option 2 - Online Data Analysis

#### Data Sources
- *970+ football leagues & cups. Live score (updated every 15s), live & pre-match odds, events, line-ups, coaches, players, top scorers, standings, statistics, transfers, predictions*
    https://www.api-football.com/documentation-v3
- *The aviationstack API was built to provide a simple way of accessing global aviation data for real-time and historical flights as well as allow customers to tap into an extensive data set of airline routes and other up-to-date aviation-related information. Requests to the REST API are made using a straightforward HTTP GET URL structure and responses are provided in lightweight JSON format*
    https://aviationstack.com/documentation
#### Analysis Plan
- *Dynamically import data from the website 'api-football' using API key with endpoints being the dates of the match when league, competing teams are provided as parameters*
- *Using the date and location of the matches as parameters import data from aviationstack with endpoints as the number of flights during those days*
- **Determine change in the traffic of flights due to soccer match**
     - *The data is visualized with time on X- axis and the number of flights on Y- axis. This provides the effect of soccer match on flight traffic quantitatively*
     - *This graph over a duration can be compared for two different countries. For example, matches between England and Spain over a period which happened in either England or Spain are compared to determine which location gives more air traffic*
     - *Compare the airlines visually to determine which airlines have maximum change in the traffic due to a soccer match*
     - *Visualize the change of average delay of the flights due to soccer match and determine which airline has the least or highest delay*
    - *Compare match attendance (api-football) with incoming flight data(aviationstack) to identify the proportion of foreign attendees*
#### Justification
   *The chosen data contains all the parameters that are considered for this analysis*

#### Motivation
*Considering that flight delay is most studied field in Airline operations and that Soccer is a sport watched by millions of people not only on Television but also visiting the stadium, the effects of the sport on average delay and surge of the demand to book tickets seemed really interesting*
