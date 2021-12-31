# sashaGIS
# Sasha Kaplan's Portfolio
Passionate about GIS, cartography, and data analytics  
Examples were compiled during my studies at California State University, Long Beach

# Project 1: The Opioid Epidemic in the American Southwest

![](https://user-images.githubusercontent.com/96799772/147707246-0d4d37e7-14c0-4ec9-9c79-8d20c045b259.png) ![](https://user-images.githubusercontent.com/96799772/147708056-3f76574a-a816-4e90-9ddf-356d110d89f6.PNG)

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147713074-d82cc0b0-5e59-40d4-b390-b9d07963ae47.png"/>
</p>

* A multiple regression and clustering analysis of drug overdose mortalities as compared to demographic variables
* Demographic variables include: percentage of people below poverty level, median household income, percentage with a bachelor’s degree or higher, percentage with a disability under 65 years, and unemployment rate
* States included in the analysis: Arizona, Colorado, Nevada, Utah, and New Mexico by census tracts
* Simple linear regressions and multiple regressions measured at the alpha of 0.01
* Three cluster groups identified: Cluster 1 and Cluster 2 define low risk areas for drug overdose mortalities while Cluster 3 indicates high risk areas for drug overdose mortalities

# Project 2: Colorado Food Deserts Linked to Obesity

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

# Project 3: An Analysis of a Hippo's Escape Route Using Weighted Overlay / Weighted Sum Tools

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147782996-c766b136-39ad-4999-8032-1c34c7723790.png"/>
</p>

* Background: Bubbles the Hippo escaped from his zoo enclosure in Orange County, CA.  This project investigated the potential routes Bubbles took from his enclosue to where he was captured.  A cost path analysis was conducted using variables slope percent, vegetation, and distance from roads.
* Data: DEM to measure slope, vegetation - US Forest Service, roads -  CalTrans
* Methodology: Create cost layers (rank and classify the three variables), rank the three variables by percent influence using weighted overlay and weighted sum tools, create total cost grid, calculate three pathways, buffer each pathway, combine pathways using union tool
* Rankings: Vegetation was ranked as the most influential variable, followed by slope, and then roads
* Result: Three potential pathways identified

# Project 4: Hot and Cold Spot Analysis of 911 calls in Portland, OR

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147711658-d55774f1-f6fd-4e1e-a2a0-adccc2020744.png"/>
</p>

* Research question: Where are hot and cold spots located for 911 calls in Portalnd, OR?  What is the the spatial relationship between 911 call locations and emergency response stations?
* Results: Hot and cold spot locations were identifed.  One emergency response station located in a cold spot would be better suited to another area.  Additionally, the hot spot area could benefit from another emergency response station.

# Project 5: Sri Lanka Poverty and Agriculture

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147786325-8d1d9dee-20b4-426e-9cfd-5788475ea524.png"/>
</p>

* Background:  To investigate the relationship between percetage of people in poverty vs percentage of agricultutral households in Sri Lanka by district.
* Data: Sri Lanka districts / demographic information
* Results: Red areas have a higher percentage of households in poverty when percentage of agricultural households is high.  Blue areas have lower poverty when percentage of agricultural households is low. 

# Project 6: Point Patterns in Fire Analysis - Density

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147786409-dd872714-8c7f-43b4-b65a-d28208a4d579.png"/>
</p>

* Research questions: With point data of forest fire locations in Idaho, determine where clusters of forest fires may occur?  How can this influence fire management policy?
* Data: Forest fire locations in Idaho - 2004
* Methodology: Using the kernel density tool, I found the most clear results based on updating and refining the search raduis.  In this case, a search radius of 20,000 meters was best visualized.  The larger seach radius is useful in producing a more generalized density output.
* Results: Understanding where clusters of forest fires are concentrated can help with the more efficient distribution of resources to prevent and fight fires.

# Project 8: Catham County, GA

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147786343-f85a6cf0-c8d0-42ab-8ee9-7eecdf204ef6.jpg"/>
</p>

* Reearch question: How is poverty spatially related in Catham County, Georgia by census tracts?
* Data: American Community Survey - 2016, Census boundaries
* Results: Based on the map, there are higher concentrations of poverty in certain areas, in this case the eastern tracts of Catham County.  It is useful to understand where high and low poverty areas may be concentrated to understand a plethora of community characteristics.

# Project 5: Comparing Watersheds - Laguna Beach, CA

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147785424-ff23e2f2-c70d-428b-bfc7-d3e3c2399544.png"/>
</p>

* The purpose of this map is to understand the differences in watersheds based on one hand drawn watershed and two computer derived watersheds.  The 3 meter and 10 meter computer derived watersheds emphasize how scale has an effect on the output.  The 3 meter DEM has a smaller cell size and a smaller resolution and therefore refers to areas that are defined with more detail, while a 10 meter DEM refers to more gernalized areas.  The computer delineated watersheds rely on scale, thereby effecting the watersheds location and position. 


# Project 4: Network Analysis in San Francisco

<p align="center">
  <img src="https://user-images.githubusercontent.com/96799772/147711093-6eaae2f3-f674-4469-bcb1-58d970fb9ad3.png"/>
</p>

* What is the fastest route between four stops in the greater San Francisco area?  The route and stops were created using the network analysis tools.  This example is included in my portfolio to demonstrate the role of GIS in trnasporation and planning routes.



