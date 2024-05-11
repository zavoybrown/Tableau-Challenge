# Tableau-Challenge

This challenge contains an analysis of CitiBike data from May 2020 and May 2021. 
The data was sourced from http://citibikenyc.com

Data was initially cleaned and normalized using python and pandas. Notebooks are included in repository.

The completed project on Tableau Public: https://public.tableau.com/app/profile/matt.zavala/viz/CitiBikeAnalysis_17154030316590/CitiBikeRiderAnalysisMay2021?publish=yes

# Analysis

![Most Popular Start Stations](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/1aa4a5de-2f22-4e4c-b415-3025a4c398ac)
![Most Popular End Stations](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/f3d18020-33eb-4795-bab4-4bb24a9204be)

We start our Year Over Year (YOY) analysis by comparing the most popular start and end stations. Velocity is up across the board, serving thousands of more riders at
the most popular stations since last year. E 17th & Broadway claims the top spot for both starting and ending rides.

Stations placed in and around Tribeca continue to see the most traffic this year. Scheduling maintenance visits, repairs, and inspections at these stations should to be a
 top priority to ensure quality/safety.

![Top and Bottom Start Stations](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/3148cf44-d3f1-4783-8214-c98c9e48c56e)

We move on to a comparison of top and bottom performers in the next visualization. From an equipment ROI perspective, it seems like there could be more analysis done to determine what equipment can be
better allocated to higher demand areas. There seems to be newer stations that are seeing steady growth like South Slope (zip 11232), Sunset Park (11220), and Kensington (11218). These new markets
should be taken into account when assessing performance of bottom performers in 2021.

![2020 Gender Mix Start Time](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/86e5e273-543c-4040-84af-4a5aebef5431)
![2020 Gender Mix Riders Per Day](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/2f7c9e30-4891-4f12-8da1-332ee2284c32)

Gender mix results seems to have been made unavailable for 2021, but there was a ridership that is predominately male throughout the month of May last year. There is a correlation of
about 11,000 to 15,000 less female riders than male riders at a given time (this metric might be self-reported through profile setup, as many rides are not gender specified). Marketing campaigns
targeting female riders could close this gap.

![Start Station Concentration YOY](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/c4d2793b-f3a0-4b5f-bc6d-d071fdd2d57e)

This map visualizes ride-start concentration across the city. Newer stations can be more easily visualized here, like the emergence of rides starting in the neighborhoods listed above (South Slope,
Sunset Park, and Kensington). There has also been an explosion of activity north of Harlem in the Manhattanville and Charlotte Gardens neighborhoods (zip codes 10030-10040, and zip codes 10450-10460).

![Count of Rider Per Hour YOY](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/9073fdbc-df7a-42a0-842e-b7df8c8f197c)

Here we see when most of the CitiBikes are in use throughout the day. This visualization could be used to ensure that scheduling maintenance and repairs on damaged bikes can happen
during the lowest volume times. It seems pretty self explanatory that repairing damaged units overnight would have less of an impact on available inventory, but here we can see
that over two thirds of all rides have been taken by as early as 8:30 pm in 2021. This is a considerable amount of time before companies pay an overnight payroll differential
for overnight workers if any plan is in place.

We also see in this visualization that three times as many rides are being taken by 8am since 2020. This signals that there are potentially many more people commuting to work by bicycle
than on other modes of public transport.

![Ride Duration YOY by Member Type](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/6da1b9f1-75c5-4f72-ba41-f67d43987105)
![Count of Rides Per Day by Member Type](https://github.com/zavoybrown/Tableau-Challenge/assets/152356657/bcea4680-507d-4e8f-b06d-da7fc7ca4a70)

Lastly we take a look at ride duration and volume by membershipo status. The average ride time for members is down by around 5 minutes YOY, and by around ten minutes for casual riders.
This could be due to the expansion of stations into newer markets that were visualized earlier, or by some other phenomenon. These rides were most likely taken when COVID-19
regulations were still in place to varying degrees, so this vary well might have impacted ride time from a health and safety perspective, or by a social desire to stay closer to home.

Overall, rides increased by around 20,000 per day.

