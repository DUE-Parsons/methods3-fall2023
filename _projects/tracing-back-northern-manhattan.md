---
layout: project-page
title: "Tracing Back: Northern Manhattan"
linkname: tracing-back-northern-manhattan
author: "Daniela Fernández López"
tagline: "Initiating a dialogue about Northern Manhattan, a blueprint for future in-depth cartography, waving into quantitative data and historical maps."
location:
    - place: Northern Manhattan, New York City, USA.
project-link:
    - href: https://felt.com/map/Tracing-back-Northen-Manhattan-sW1I77LlTeO6N3otGJ9CqWC?loc=40.86454,-73.9403,14.23z
tags:
    - tag: history
    - tag:  land
    - tag:  flood
    - tag:  neighborhood
    - tag:  northern manhattan
thumbnail-path: img/tracing-back-northern-manhattan/JO50fNR.png
img-folder: ../../img/tracing-back-northern-manhattan/
timestamp: undefined
---
This project serves as an initial platform to initiate a dialogue about the area I have been living in since my arrival to New York in 2022. It is a blueprint that will be further developed through my thesis next semester, adding more data and complexity to develop a more in-depth cartography.

As a first step, I am gathering information from the American Community Survey: 5-Year Data [2017-2021] to create a preliminary portrait of the current population residing in New York City.

I created a density dot map for each race-ethnicity group and then compiled a GIF that illustrates the distribution in the city and its surroundings.

![]({{ page.img-folder }}bGITqkK.gif)

In the Northern Manhattan area, neighborhood indicators are as follows: Hispanic and Latino individuals comprise the majority at 67.9%, followed by White individuals at 19.2%, and Black individuals at 7.9%. Other ethnicities represent less than 3%.

Next, I delve into additional indicators essential for a deeper understanding. I present them as choropleth diptych maps, using Block Groups as the area divisions.

Renter %: Percentage of Total Housing Units occupied by renters.
Median Household Income in 2021 Inflation-Adjusted Dollars.

NYC MHI citywide average in 2021 was $70,784.
![]({{ page.img-folder }}oIRmiAX.png)

Northen Manhattan MHI average in 2021 was $58,060. 
![]({{ page.img-folder }}LsNwEiT.png)

Vacancy %: Percentage of Vacant Housing Units from the total.
Owner %: Percentage of Total Housing Units occupied by owners.

NYC 
![]({{ page.img-folder }}zzZ7SXX.png)

Northen Manhattan
![]({{ page.img-folder }}f2MCH4s.png)

As a second step, I researched two digital archives: the David Rumsey Map Collection and The New York Public Library: Maps & Atlases. I searched for specific maps encountered during my literature review, with the goal of delving into the details of how the landscape has changed over time. These maps served as my initial guide in tracing the historical transformation of Northern Manhattan.

![]({{ page.img-folder }}v6kG2dX.png)
![]({{ page.img-folder }}Xszv0Wo.png)
![]({{ page.img-folder }}hVmGSHl.png)

Both maps from the David Rumsey Map Collection were in GeoTIFF format, allowing for quicker processing compared to the one from NYPL. I had to georeference the NYPL map in QGIS. Once positioned correctly, I proceeded to trace the land shores of Manhattan, The Bronx, and New Jersey. Subsequently, I mapped the rivers and flood patterns when available in the maps. I created shape layers for each year, including polygons and lines, to later utilize geoprocessing tools such as dissolve and clip as needed. I added the shapefile of Sandy Storm Flood for 2012 and the NYC Future Tide 75” for 2100 from NYC Open Data.

With this data, I exported it from QGIS as an SVG file to create a first draft of a historical map of Northern Manhattan in Illustrator. I used different patterns and line strokes to create a more nuanced cartography.

![]({{ page.img-folder }}JO50fNR.png)

P.S. This blueprint is also available on Felt, offering an interactive option to overlay, at the viewer's leisure, ACS data, rezoning layers, and waterfront property information pulled from NYC Open Data with the first draft of the historic layout.
