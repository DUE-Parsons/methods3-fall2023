---
layout: project-page
title: "Gerry.sg"
linkname: gerry-sg
author: "Gracia"
tagline: "Explores Singapore's strategic manipulation of constituency boundaries and the electoral system to maintain a supermajority"
location:
    - place: Singapore, Singapore
project-link:
    - href: https://arcg.is/WmCDy 
    - href:  https://felt.com/map/Gerry-SG-ert6i618Rq21Dr9C3MgEBOB?loc=1.3359,103.7819,11.12z&share=1
tags:
    - tag: elections
    - tag:  politics
    - tag:  gerrymandering
thumbnail-path: img/gerry-sg/8NAZoai.png
img-folder: ../../img/gerry-sg/
timestamp: undefined
---
In 2011, Singapore's ruling party, the People's Action Party (PAP) only won 60.14% of the votes yet it translated to 93.10% of seats in parliament. How does this happen? In order to answer this question, this project explores Singapore's  electoral system of GRCs and SMCs , as well as the  strategic manipulation of constituency boundaries .

![]({{ page.img-folder }}Q2rYxJo.gif)

Through Singapore’s data.gov.sg platform, I was able to retrieve election data from as far back as 1955, and shapefiles of the electoral boundaries for 2006, 2011, 2016 and 2020. As I wanted to show election boundaries from 2001 as well, I had to create a shapefile using QGIS from a SVG file. 

![]({{ page.img-folder }}mrtyGoL.jpg)

The shapefiles downloaded from data.gov.sg were not consistent in whether they included the sea or not. Using the clip function on QGIS, I tried to match the outer border across the years. Then, I was able to do a join between the shapefiles and the voting data. 

![]({{ page.img-folder }}hO8Dqbt.gif)

With those files, I uploaded them into a Felt map. Initially, I included annotations on the map as layers but the amount of information + added layers under the legend were very overwhelming. 

![]({{ page.img-folder }}1TdyrEo.jpg)

The final map has the same notes but I posted them as comment so that it wouldn’t appear in the List on the left and so that users had the choice to easily hide them. This topic also requires more explanation for one to fully comprehend the map, so made a StoryMaps page to accompany the map and provide more context. 

<iframe width="100%" height="450" frameborder="0" title="Felt Map" src="https://felt.com/embed/map/Gerry-SG-ert6i618Rq21Dr9C3MgEBOB?loc=1.3359,103.7819,11.12z"></iframe>


The StoryMaps page goes into deeper detail about the GRC system, why it is a form of gerrymandering and how the votes from previous years inform the electoral boundaries. I explain one case study from 2016 and 2020, with an embed to the Felt Map at the end. 

With the general elections coming in 2024, I hope to expand more on it and to publish it as an interactive platform for Singaporean voters to discuss and share their views on electoral boundaries. 
