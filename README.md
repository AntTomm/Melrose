# Melrose, Bronx NY


### The Effects of Carbon Dixoide Emissions on Melrose, The Bronx, NYC

This site will allocate collected data in depictions such as bar graphs, interpreted conclusive data, photographs, and more. 

![MelroseFINALFINAL](https://github.com/AntTomm/Melrose/assets/148288592/68de2d54-d31e-4840-9480-6411b7b589d9)

The above is my highlighted neighborhood from HC6. Using **matplotlib** & **numpy**, I was able to create a highlighted map of my neigborhood! To improve upon this, in the future I could try & create a more highly specific shape that literally "shapes" Melrose as a whole neighborhood. 

<img src="https://github.com/AntTomm/Melrose/assets/148288592/49cc837a-0cf9-42f5-9d2f-d71396d8e35b" alt="CS Recitation Project" width="300"/>

The following is HC2, which is our neighborhood analysis. I provided a general photograph of the neighborhood, as well as a Melrose highlighted on a map of Manhattan. Some more fun facts about Melrose are: 

- Tobacco retailers are more prevalent in the **NEIGHBORHOOD** Melrose than in the city at all.
- It was originally settled by both Irish & German immigrants in the late 19th century.
- The overall population was mostly German up until World War 2.
- The number of public schools in Melrose is above average.

### HC3: The Clean Heat Program Overview:

The New York City "Clean Heat Program" was started by the NYS Energy Research & Development Authority, and it's purpose is to change the city's energy landscape to improve air quality reduce carbon emissions, and overall increase the quality of life throughout New York In part with this, some harmful fuels, such as oil number 4 and number 6, are derived from a dangerous chemical called petroleum, and both of these types of oils contribute heavily to the pollution of the area; fortunately, they are set to slowly be phased out by January 2030. The DEP Boiler Registration is a initiative implemented by the Dept. of Environmental Protection in order to monitor & improve the environmental performance of boilers used in NYC. By monitoring the fuel usage and boiler registration dates, the DEP can take proper action to improve upon it, as well as reduce the air pollution and improve overall environmental quality. Additionally, the Greener, Greater Buildings Plan deals with the energy consuming skyscrapers, and it is in part with plaNYC, which is a set of goals related to improving the quality of air, water, standard of living, etc. Along with transparency, this plan also helps the city save a quarter billion dollars. Through the means of clean heating fuels, such as electricity or solar power, it would expand upon the eco-friendly options in the city. Programs like the "Utility Rebate Program" attempts to increase the number of contractors that will do clean-emission projects, and by 2030, the city is projected to cut C02 emissions by 40% and have 70% of it's electricity from clean, renewable energy!

### HC4: New York City Emissions Report:

Throughout this emissions report, we were able to determine that multiple parts of the city have been also trying to stop c02 emissions, such as the Department of Education. The DOE contributed a ttoal decline of 14% across all boroughs including the Bronx. However, we also learned that the Bronx is also one of the few boroughs that is lagging behind with their emissions goal as compared to other states; . The borough has only seen a 7% decrease in their emissions, while the highest borough has been Staten Island with 16%. Traffic and car congestion has gotten increasingly worse from 2017 - 2022, and it contributes highly to the emissions even today. This is mostly depicted in certain Bronx neighborhoods such as Mott Haven and Port Morris, both located in the South Bronx. Emission sources within the Bronx mirrored those of the city at large. Residential, commercial, and industrial buildings in the Bronx contributed to emissions primarily  through energy use.

### HC 7 & 8: Data Analysis - Borough + Neighborhoods:

![LOW MMBTU](https://github.com/AntTomm/Melrose/assets/148288592/e8e8f2b1-9658-494b-b7e8-92479b3de4ba)

With Bronxdale having an alarmingly high MMBTU, it goes to show that there is most likely a high demand for things like heat and a high volume of citizens living there. However, high MMBTU contributes to varioius types of pollution such as Greenhouse Gas Emissions, land pollution (waste disposal), indoor air pollution, and chemical pollution since there are constant chemicals being released into the air. This may also contribute to the idea we discussed in HC4, where the Bronx is lagging behind the other boroughs in terms of its emissions goal. Last time we researched, it was only determined that the Bronx reached a mere 7% decline. 

![RESUNITS](https://github.com/AntTomm/Melrose/assets/148288592/a4c7cacc-99fe-4ebf-ac33-aa1010f6bd24) 

From the following bar graph, we are able to determine that Bronxdale has the **most** amount of housing for residents, with the number being well over 80. South Fordham, on the other hand, exhibts the lowest amount of available housing. Since South Fordham is located in the South Bronx, when compared to our findings in HC4, the South Bronx often has increasingly concerning traffic congestion. This may elucidate the idea that there are too much highways and roads, but not enough space for residents. They also contribute heavily to the c02 emissions - affecting around 17% of young children in the South Bronx neighborhoods.

**Building Type Distribution in the Bronx:**
- Elevator Apartments               0.530040
- Walk-Up Apartments                0.425234
- Educational Structures            0.012016
- Churches, Synagogues, etc.        0.007343
- Factory & Industrial Buildings    0.005340
- Store Buildings                   0.004005
- Condominiums                      0.004005
- Office Buildings                  0.003338
- Hospitals & Health                0.003338
- Warehouses                        0.002670
- Vacant Land                       0.001335
- Hotels                            0.000668
- Asylums & Homes                   0.000668


*Concerningly, the reader could notice that *"Hospitals and Health"* are towards the ***bottom*** of the list. This may explain why so many people have health issue within the Bronx that go untreated, since there are no nearby hospitals. There are also an **alarming number of Factory & Industrial buildings**, which we can note that there is an increased risk of c02 emissions since there is a large amount of them.*

Average building age in the Bronx: ***1929.0***

We notice that the **"average building age"** of most buildings in the Bronx is **1929**. This is a huge contribution to the health of the children and elderly living in certain parts like Melrose or Mott Haven, since they are at increased chances of getting asthma. The materials used in the buildings are also extremely old, and most likely spread cancer causing or gaseous air throughout the borough.


<iframe src="MelroseData.html" width="600" height="400" frameborder="0" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<img width="809" alt="CodeOFFICIAL" src="https://github.com/AntTomm/Melrose/assets/148288592/c2bde4fe-be4e-49c2-8054-7dc96ef3ca89">


Using ***folium*** along with ***pandas***, I was able to create a interactive html map in Python! I took specific columns and rows from my CSV file and created a variable to match the names within the conditions of the columns and rows. In a for loop, I initiated lat, lon, and name as 3 variables that pulls the exact coordinates and names for each marker, and then I initiate a variable newMarker = folium.Marker([lat, lon], popup=name), which adds each marker to the map. After the for loop is done going through it, the html map is successfully saved onto my desktop!


