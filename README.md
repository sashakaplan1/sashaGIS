# sashaGIS
# Sasha Kaplan's Portfolio
Passionate about GIS, cartography, and data analytics.  These examples were complied during my studies at California State University, Long Beach.

# Project 1: The Opioid Epidemic in the American Southwest

![](https://user-images.githubusercontent.com/96799772/147707246-0d4d37e7-14c0-4ec9-9c79-8d20c045b259.png) ![](https://user-images.githubusercontent.com/96799772/147708056-3f76574a-a816-4e90-9ddf-356d110d89f6.PNG)

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147713074-d82cc0b0-5e59-40d4-b390-b9d07963ae47.png"/>
</p>

* A multiple regression and clustering analysis of drug overdose mortalities as compared to demographic variables
* Demographic varaibles include: percentage of people below poverty level, median household income, percentage with a bachelor’s degree or higher, percentage with a disability under 65 years, and unemployment rate
* States included in the analysis: Arizona, Colorado, Nevada, Utah, and New Mexico by census tracts
* Simple linear regressions and multiple regressions measured at the alpha of 0.01
* Three cluster groups identified: Cluster 1 and Cluster 2 define low risk areas for drug overdose mortalities while Cluster 3 indicates high risk areas for drug overdose moralities

# Project 2: Colorado Food Deserts and Obesity

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147707251-d3bb9e75-d379-49f8-91e5-9cc1ff9fe87a.png"/>
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147707258-e7b21bc6-fa9d-4623-8049-55cb46ef29a5.png"/>
</p>

* Research questions: Which Colorado census tracts are most susceptible to being in a food desert?  How do these food desert locations compare to obesity rates?
* Data: US Census Bureau - census tract shapefile, American Community Survey - poverty 2016, ESRI - grocery store locations 2014, Colorado Department of Public Health and Environment - obesity rates 2019
* Methodology: find most at-risk areas (greater than 25% poverty), create one mile buffer around grocery stores, erase one mile buffer from at risk areas, food deserts are identfied, spatial join obesity data, compare greater than 30% obesity to potential food desert tracts
* Results: Food deserts found most commonly in suburban and rural areas, strong realtionship does exist between high obesity rates and food deserts

# Project 3: Hot and Cold Spot Analysis of 911 calls in Portland, OR

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147711658-d55774f1-f6fd-4e1e-a2a0-adccc2020744.png"/>
</p>

* Point data of 911 calls,  hot and cold pots identfied in relation to the three emergency response stations

# Project 4: Network Analysis in San Francisco

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147711093-6eaae2f3-f674-4469-bcb1-58d970fb9ad3.png"/>
</p>

* Using the network analysis tool, a transporation route was identfied 
* The transporation route included four stops in the greater San Francisco area
* The quickest route was found as a result

# Project 5: Bubbles the Hippo Escape Route

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147782996-c766b136-39ad-4999-8032-1c34c7723790.png"/>
</p>

* Bubbles the Hippo escaped from his zoo enclosure in Orange County, CA
* This project investiagted the potential rotues bubbles took from his enclouse to where he was ultimately found
* Three potenital escape routes were identifed based on vegetation, roads, and slope of the region
* The weighted sum and weighted overalay tools were utlized with the variables weighted at different scales
* Vegetation was predicted as the most influential variable, followed by slope, and then roads



