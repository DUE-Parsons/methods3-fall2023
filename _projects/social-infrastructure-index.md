---
layout: project-page
title: "Social Infrastructure Index"
linkname: social-infrastructure-index
author: "Lukas Kernke"
tagline: "An index of several forms of social infrastructure in New York City at the census tract level"
location:
    - place: New York, NY, USA
project-link:
    - href: https://felt.com/map/Social-Infrastructure-wTqS2XATQKGyMapEO9BN2BC?loc=40.714,-73.9493,11z
tags:
    - tag: social infrastructure
    - tag:  social connection
    - tag:  public resources
    - tag:  public realm
    - tag:  public space
    - tag:  inequality
thumbnail-path: img/social-infrastructure-index/flq78Nd.png
img-folder: ../../img/social-infrastructure-index/
timestamp: undefined
---
Social infrastructure, the places in which people can socialize and assemble, is essential for the wellbeing of individuals, communities, and for democratic politics. Nonetheless it is often overlooked in places where liberal individualism is dominant. In New York City, Mayor Adams’ administration has renewed discourse on the public realm, a concept that overlaps social infrastructure, framing it as the means by which to restart the city’s “economic engines” after the COVID-19 pandemic (see the reports, “Rebuild, Renew, Reinvent: A Blueprint for New York City’s Economic Recovery” and “New NY Panel Action Plan: Making New York Work for Everyone”). Yet the Adams administration and its economic advisors have prioritized improving the public realm in commercial areas where it will be most profitable. These areas, like 5th Avenue in Manhattan, often already have considerable social infrastructure. On top of framing social and public life in purely economic terms, which is a problem in itself, this approach neglects areas that are disadvantaged. The index shown here, which considers several major forms of social infrastructure, indicates that social infrastructure is not evenly distributed. Distribution of social infrastructure, while roughly following MTA subway lines, does not match population density and heavily populated areas such as Corona in Queens, and Sunset Park in Brooklyn, are underserved. 

![]({{ page.img-folder }}flq78Nd.png) 

This map began at the census tract level, using data from NHGIS, clipped to the shoreline, and a basemap from NYC.gov. 

![]({{ page.img-folder }}zNNKAbq.png)

I then added eight forms of social infrastructure, using data that was publicly available. All data came from NYC Open Data with the exception of state parks, which came from NY State Parks. The forms of social infrastructure included are: children’s play areas, libraries, public schools, Privately Owned Public Spaces (POPS), NYC Open Streets, DOT public plazas, state parks, and city parks. These forms of social infrastructure were selected because of the free availability of the data. The decision to include Privately Owned Public Spaces is open debate, since some, myself included, question their ability to genuinely enable people to socialize and assemble, particularly when they are heavily policed, uncomfortable and uninviting, and have limited hours. That said, this is not the case for every individual POPS so I have included them to err on the side of caution. 

![]({{ page.img-folder }}fj0tEhf.png) 

Because it would be unreasonable to say that a piece of social infrastructure while positioned within a certain census tract is not available to neighboring tracts, I created a 1000 foot buffer around each form of social infrastructure. This approximates a five minute walk. Each buffer overlapped each tract to different degrees. 

![]({{ page.img-folder }}SikSpc9.png) 

The percentage of overlap of each buffer can be calculated for each census tract. Each buffer was considered separately, so the buffer of a library might cover 20 percent of a given tract while a POPS might cover 30 percent and a school 50 of the same tract. The percentage of overlap of each buffer was then scaled to a number from 0 to 1 for each census tract. These eight scaled numbers each became a factor in the index. The index, which was made by adding all eight scaled numbers together, can therefore range from 0 to 8, however no census tract scored above 6. I turned this into a choropleth coloring census tracts by their score on this index.

![]({{ page.img-folder }}1EG5Af3.png) 

Then, in order to emphasize the places where people live, I marked non-residential census tracts with cross-hatching. 

![]({{ page.img-folder }}flq78Nd.png) 

More than half of the tract scored less than 3. More tracts scored between 1 and 2 than any other range. 

![]({{ page.img-folder }}wUzfxJu.png) 

Generally, tracts that scored higher were close to subway lines. 

![]({{ page.img-folder }}4wPddXM.png) 

To show that again in detail, I started with census tracts

![]({{ page.img-folder }}QjFI45h.png) 

Then added the eight forms of social infrastructure I selected

![]({{ page.img-folder }}lkrUmOM.png) 

Then created 1000 foot buffers around each unit of social infrastructure

![]({{ page.img-folder }}NV88GP4.png) 

And used this to create an index, which was made into a choropleth map

![]({{ page.img-folder }}FTokPWt.png) 

I then marked non-residential tracts

![]({{ page.img-folder }}veFperm.png) 

And with the subway

![]({{ page.img-folder }}uVMvkkf.png) 

And, once again the final map, at the city level looks like this:

![]({{ page.img-folder }}flq78Nd.png) 

I compared this to population density using data from NHGIS. It is worth noting that the population of each tract shown below is adjusted to population per square mile and few tracts are an entire square mile. Notably, this did not match the distribution of social infrastructure. 

![]({{ page.img-folder }}3k4oZny.png) 

Some things are notably missing from this index. First and foremost, this index only accounts for the most public forms of social infrastructure, however the most common forms are actually privately owned places like bookstores, bars, churches, and coffee shops. Unfortunately it is hard to find a comprehensive dataset that includes all of these places which is freely accessible. I also have not included a temporal dimension - places close seasonally and at night - and this can change an area’s social infrastructure. Similarly much socializing happens in places that are informal like people's homes, laundromats, grocery stores, and on the sidewalk. This is much harder to quantify. Lastly, this map suffers from the same issues that many quantitative approaches also contend with. It flattens qualitative factors. It shows any given two libraries, for example, as exactly equal, when this is far from the case. When it comes to social infrastructure, quality is very important. That is, unfortunately, not reflected here. 