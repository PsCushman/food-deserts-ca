# Food Deserts in Northern California

![Screen Shot 2023-06-21 at 3 05 21 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/b8e719bb-f40a-4ab8-994d-7af9d73ae489)

## Analysts

*Payson Cushman*

*Vandrea Foronda*

*Mina Kemmer-Lee* 


## Summary

Food deserts are regions where people have limited access to healthful and affordable food. This may be due to having a low income or having to travel farther to find healthful food options. The USDA formed the Food Access Research Atlas, which we used for our analysis, ‘maps food access indicators for census tracts using ½-mile and 1-mile demarcations to the nearest supermarket for urban areas, 10-mile and 20-mile demarcations to the nearest supermarket for rural areas, and vehicle availability for all tracts.’  The USDA uses accessibility to sources of healthy food, as measured by distance to a store or by the number of stores in an area, individual-level resources that may affect accessibility, such as family income or vehicle availability, and neighborhood-level indicators of resources, such as the average income of the neighborhood and the availability of public transportation to define access levels. In this report, we examine the socioeconomic and demographic characteristics of these tracts to see how they differ from county to county in Northern California.


In our analysis, high food desert scores in Northern California tend to come from counties with smaller populations, are more rural or agricultural, from counties with population loss, and lower incomes.


Census tracts with a greater population of families with lower incomes are more likely to be food deserts but, in our analysis, otherwise similar low-income census counties in rural areas had higher low access scores than counties with very dense and highly populated urban areas. Further, counties with smaller populations and/or with population loss, saw on average, higher decreases of access to healthy food options. 


Overall, of the 25 counties on which we focused, there were only 5 counties that saw a significant increase (over 5%) in low access, most of them rural or agricultural.

**County       FIPS**

Madera       6039     5.25%

Merced       6047     9.52%

San Joaquin  6077    11.17%

Amador       6005    12.13%

Calaveras    6009    17.17%

At the start of our analysis, we expected that as access decreased, fast food options would flourish and grocery stores to suffer, health problems would be persistent, and that demographics would be one of the largest determining factors. We found the results of our analysis to be more nuanced. Negative health indicators were more determined by income than by limited ability to source healthy food.  While demographics were indeed important variables, the population’s income and geography were the more conspicuous determinates of a county’s low access score. 

## Limitations

First, the data sets we used provided data at the county level, so this does not preclude areas with otherwise “good” food desert scores from containing multiple areas or tracts where food deserts are present. Also, we focused our analysis Northern California. Consequently, while there may be moderate or even high correlations between, for example low access scores and low-income population,  p-values tended to be high as well. For that reason, the scope may be a little too focused to draw any concrete conclusions without further analysis.


## Evidence

**Regional Differences**

We found that over the 5 years from 2010 to 2015, two of the three of Northern California’s regions did better and had a smaller population that lived in areas with low access.

Pie Chart 1 - All Counties 2010 Population by Access and Low Income Low Access 

https://github.com/PsCushman/food-deserts-ca/blob/main/Outputs/AllCounties_2010Pop_byAccessandIncome.png

Pie Chart 2 -  All Counties 2015 Population by Access and Low Income Low Access 

https://github.com/PsCushman/food-deserts-ca/blob/main/Outputs/AllCounties_2015Pop_byAccessandIncome.png

In both the Bay Area and the Central Valley, we saw a decrease from in the population of people with low-income and low access residents. The Sacramento region showed the least progress, while the Bay Area showed the most. 


Additionally, while the Sacramento region saw an increase in the population with low access to healthful foods, it was not dramatic. It also contained two of the five counties with the largest decrease in access. The region also had almost no overall population change, meaning that it was the only region to not see a large increase in population in the three on which we centered our attention. As we will see, this might be the biggest indicator of the rise in low access percentages. 


**Access, Groceries, and Ronald**

The presence of grocery store and superstore access are two of the most important indicators of low access to healthy food options. As access decreased so did grocery stores, but not as drastically as we expected. 


However, fast food options stayed more or less constant in Northern CA even as other options, grocery stores for example, decreased, leaving counties with low access scores, higher access to fast food in comparison to other healthy options. When comparing increases in low access to increases in fast food, we had a p-value of significantly less than .05 and a correlation coefficient of essentially zero (-.01)  


**Demographics**

Expectedly, low-income populations were mostly likely to with low access. 


In addition, while rural communities saw the greatest increases in low access, there was also evidence that as the percent of minority community increased, low access increased as well. 


Overall, we found a moderate negative correlation between the percentage of White residents and low access scores. While communities with a larger percentage of Black, Asian, and Hispanic communities saw lower access to healthy food options in 2015 and their respective populations increased. Counties with larger White populations saw higher access to healthy food options. In contrast, we saw that for every other demographic, that county wide access decreased or stayed constant as their population increased.

https://github.com/PsCushman/food-deserts-ca/blob/Dre/Outputs/scatterplot_race_and_food_access_data_2010.png


That said, the median percentage of access by race was highest in White communities and Latino populations, implying that while low access my increase as communities include more minorities, Whites and Latinos see the least amount of access that other groups on average in Northern California. 

![Screen Shot 2023-08-01 at 10 56 48 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/5a823214-7cf7-47a7-a109-5eaee111f2fa)

Communities with a larger share of seniors had a negative correlation with low access, which is a positive sign. However, communities with a higher concentration of children (under 18) had a moderate positive correlation to low access with an even more pronounced relationship in low-income areas, which is scary. 

https://github.com/PsCushman/food-deserts-ca/blob/Dre/Outputs/scatterplot_65_vs_18_and_food_access_data_2010.png

Where were found a very strong correlation is when we looked at change in access and change in low-income population. As the percentage of low access population increased, so did the population of low-income communities with low access. While this may seem obvious, it is important to point out that the changes are strongest in in places where money is in shorter supply. It is noteworthy that access to healthy food is poorest in areas with the highest income security, which underscores the need for policy interventions aimed at improving access to healthy food for all.


**Health**

Interestingly, we did not see much of a correlation between health indicators such as diabetes and low access. The regions in Northern California compare favorably to access able data for the US, where low access is linked to increases in those indicators.  But we did find a weak correlation between increases in diabetes and increases in low access. 


While we expected more positive correlation between low access and a negative health indicator, diabetes, but we also found a low correlation between household income and diabetes. 


**Rural v. Metro**

We found a low correlation (-0.36) with a low p-values (0.000007) between counties with population loss and an increase in low access scores. 

![Screen Shot 2023-08-01 at 10 53 58 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/9e1da75a-2d30-4a44-930c-5b4e32289a86)

In addition, there was a low correlation (-0.34)  with a low p-value (0.000500) between the population totals and change in low access.  This suggests, that while there are still plenty of communities facing low access to healthy foods in metro areas, rural areas have tended to see the greatest negative impacts of changes over the past decades. 

![Screen Shot 2023-08-01 at 10 54 25 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/88473d6f-b3fb-466b-93a9-e1d5c86cd1f6)

In rural counties, grocery stores tended to be clustered around populated areas and resulted in long drives for people living off less populated roads. In Calaveras, where we saw the greatest increase in low access, you can see this illustrated in the two maps below.


Map 1: Calveras County with all its supermarkets and superstores, terrain and roads.

![Screen Shot 2023-08-01 at 10 51 14 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/6a8b2021-5c6e-44e1-92c0-c1cca11637ca)

Map 2: Calveras County and all its supermarkets and superstores, *borders*, and roads.

![Screen Shot 2023-08-01 at 10 52 10 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/793db6db-0302-4048-8c2c-2f1ce4f88044)

In both maps, you can clearly see large chunks of Calaveras County where there are roads, even relatively well traveled roads, and no grocery stores for miles. 


## Conclusion

In conclusion, while the Northern Californian regions explored in our analysis have seen gains in access to healthy option, most of the gains have been see in more metropolitan areas. San Francisco County for example has seen a monster increase in access, so much so that in much of our analysis we had to remove it as an outlier. Alameda County, which has a large minority population, saw gains in access as well. In counties with increasing populations and higher incomes, we see that Northern California is doing quite well on a county level increasing the access to healthy food options.


Where we see the most worrying data is in low-income rural populations. In many counties there has been frightening decreases in access to healthy options. Even more disturbing is that children under 18 are affected disproportionally. 


The exploration of demographics produced more varied results. It was obvious that as the populations of Black, Asians, and Hispanics increased, easy access to healthy food decreases and yet, there large populations of Whites facing food deserts. Again, we see low-income populations suffering lower access to wholesome options at a higher rate than the rest of their cohorts.


In each of the following figures, the steeper correlations between low access to food and the low-income corresponding cohort is obvious. Figure one is shows steeper lines in the lower income of children. Figure two shows the same with demographics, where the lines for the White and Hispanic populations are much more dramatic in low-income group. 

**Figure One:** https://github.com/PsCushman/food-deserts-ca/blob/Dre/Outputs/scatterplot_65_vs_18_and_low_income_food_access_data_2010.png

**Figure Two:** https://github.com/PsCushman/food-deserts-ca/blob/Dre/Outputs/scatterplot_65_vs_18_and_low_income_food_access_data_2010.png

Of all the relationships we explored, the relationship between change in access and change low-income access may have been the strongest. 

![Screen Shot 2023-08-01 at 10 49 00 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/1bf05105-0341-4263-aad4-7830c03a04b3)

Correlation coefficient: 0.93

P-value: 0.145480

The correlation coefficient was a very strong (0.93) and while the p-value was not as low as some others, when we expanded the data set to all of California, the correlation remained strong and the p-value decreased considerably (Correlation coefficient: 0.74, P-value: 0.015667) so we feel confident the significance of this relationship at the county level. (see fig…)

![Screen Shot 2023-08-01 at 10 49 32 PM](https://github.com/PsCushman/food-deserts-ca/assets/122395437/7bbed6b0-b3b9-4b3b-b721-956b2f623001)

While it is not surprising, it is important to stress that in almost all the data, low-income populations of the same cohorts, whether by race, age or geography, tended to see lower access to healthy food options than those with higher incomes. While the limitations of this data have been addressed earlier in this summary, Northern California’s policy makers should do more to increase access to healthy food options for the populations where economic insecurity (and consequently food insecurity) are at their highest. 

## Resources
Each participant has their own folder with their code and outputs if that is something you'd like to check. (PSC=Payson, MKL=Mina, Drea Project=Vandrea) The presentation and analysis was worked on by all participants. We did have to split up maps into two notebook because the map files can be quite big when it includes figures. All outputs should be in the out put folder, but again, if there are any issues, please check our respective folders.

One resource was too big of a file to upload. Find it here... (https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/)
