# Ghana

Wicked Problems S1 2019 final

## Administrative Subdivisions of Mongolia

![](mongolia.png)

This plot demonstrates the national (adm0), provincial (adm1), and district (adm2) boundaries of Mongolia. Names of each province, or aimags, are in blue, with districts subdivided within each state as demonstrated by the thin, white lines. Mongolia has 21 aimags and 331 districts. 

![](closeupmon.png)

As you can see from the plot describing just the districts, Mongolia's administrative boundaries are very conplex and contain a lot of data. These large numbers ultimately made it difficult to continue on with Mongolia as my LMIC for the rest of the semester as it took a long time and a lot of computational power to process all data. Therefore, for the rest of the semester, I focused on Ghana. With fewer provinces/districts, this switch simplified and quickened the processing of data. 

## Population of Ghana's regions

![](ghana2019.png)

The above plot and chart demonstrate the population density in Ghana within its regional boundaries. Much smaller than Mongolia, Ghana has only 10 regions, their eqivalent to Mongolias aimags. The highest densities are within the Ashanti region and Greater Accra -- the historical/cultural center and modern trading hub. In general, there is a higher density towards the southern part of the country as this is where Ghana borders the ocean. In the north lies the Saharah desert, a less habitable and more formidable climate to live in. 

![](rplot1.png)

The histogram above describes the most common population numbers in Ghana. This histogram helps confirm what is shown in the plot and chart above, as very few areas are very densily populated, instead, most are faily lowly populated. The two bars to the very right are clearly the Greater Accra and Shanti regions, while the majority of population numbers are much lower.

## Ghana population means

Below are four plots describing:
1. My predicted mean population of Ghana 
2. The 2015 predicted mean population of Ghana
3. The difference between my predicted results of the mean population and 2015 estimates
4. A 3D model of plot 2

Note: Though for most the most accurate plots are the one that have the log of population as the response variable and mean of covariates as predictors, for Ghana, the plots with the least error are the plots whose response variable is simply the population and the mean of covariates are the predictors. I know this because the error found by the cellStats() command has significantly less error for the population found by mean (13708950) than the plots demonstrating population by sum (16805209) and log of population by mean (16351012).

![](populationmeans.png)

This plot begins to show urban areas. Most highly populated areas are in the regions which past plots have shown to be highly populated/dense.

![](POP15.png)

Similar to plot #1, urban areas are shown as highly populated, this plot does though, demonstrate the location of important roads, as you can see population spikes in vein-like patterns

![](diffmeans.png)

The highest amount of controversy between plots 1 and 2 occurs in highly populated areas -- with the majority of the country's population development staying in sync with past predictions. In general compared to my predition plot, the 2015 plot overpredicted populations in city centers and underpredicted populations in the outskirts of cities.

![](3Dmeans.png)

## Ghana human settlements, roadways, and healthcare facilities

![](combined2.png)

This plot demonstrates the population and density of settlements within the two districts Kwabre and Atwima. Both are in the Ashanti region.


Next, I added roadways and healthcare facilities:

![](proj3final.png)

The main take-away from this plot is the urban center which Kwabre and Atwima surround. Since roads lead to the same place, all clinics (green) and hospitals (blue) are where the roads intersect, and the urban areas the Kwabre and Atwima all are centered around the same location, we can assume there is a big city at its center. Further research showed that this city is Kumasi, the second largest city in the nation.  
 
![](proj4week1final.png)

Above is a 3D plot which also considers the topography of the region. This new information shows that the countries cultural hub is in a plateau surrounded by mountains. Therefore, the area in which most people reside is flat, making transportation easier. 
