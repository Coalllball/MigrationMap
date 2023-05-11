# Young People's Migration Trends
#### A StoryMap of Migration Patterns from 2000 to 2018

## Introduction

Young people migration is a global phenomenon that has gained significant attention over many years. Many young people are leaving their hometowns and migrating to other places in search of better opportunities, including education, employment, and quality of life. The migration of young people has become an important issue for policymakers, researchers, and society as a whole. Understanding the trends, driving factors, and impacts of young people migration is crucial for addressing the challenges and opportunities associated with this phenomenon.

## About this Project

The purpose of this project is to analyze the trends of young people migration in the United States and identify the potential factors that drive their movements. Through the use of GIS analysis, this project aims to visualize the spatial patterns and relationships of young people migration across different regions in the US. By examining the distribution and characteristics of young people migration, this project seeks to provide insights into the driving forces and potential impacts of this phenomenon.

## Data Sources

For this study, we utilized a comprehensive dataset sourced from migrationpatterns.org, which incorporates data collected by the US Census Bureau. This dataset provides detailed information on the migration patterns of young people, specifically those born between 1984 and 1992, at the ages of 16 and 26. The dataset covers a significant time span from 2000 to 2018, allowing us to capture long-term trends and changes in migration patterns.



## Popualtion

The US population has grown from an estimated 281,421,906 in 2000 to 327,514,334 in 2018. This represents a population growth rate of approximately 16.3% over the 18-year period. While this growth rate may not be considered significant in comparison to some other countries, it is quite significant when we look at the change in a geological aspect. To gain a better understanding of the population distribution, we examined the spatial patterns of population density across different regions. Our analysis revealed distinct variations, with denser populations observed along the east and west coasts, while the mid-western region exhibited comparatively lower population density.

These maps are on the commuting level, the green one indicates counts of people who moved in to the commuting zone from other places, and the red map indicates how many young people moved out of their hometowns.  

This graph displays the net population changes throughout these two decades.

## Moran's I

In order to visualize and analyze the migration patterns of young people, we employed GIS software to map the migration flows across the United States. This allowed us to identify both hotspots and cold spots, representing regions with notable influxes or outflows of young individuals. By examining the spatial relationships between migration flows and population characteristics, we gained insights into the dynamics of young people's movement.

The green indicates hotspots that are popular destinations of young adults. The orange indicates cold spots clusters near hotspots. 

The dark blue shade indicates cold spots where people are leaving. But the light blue shade indicates where the population increased and it is surrounded by coldspots.

When compared with the move out map, it is noticeable that there are massive overlaps between cold spots and commuting zones where people are leaving. 


## Correlation and Linear Regression Analysis

Several potential factors were considered to understand the reasons behind people leaving certain regions. These factors included state GDP, GDP per capita, average personal income, per capita expenditure on recreation, and elementary school enrollment numbers. Since many young people in the dataset may have had children at the time of data collection, the number of elementary school enrollments was included as a proxy for family-related factors.

Regression analysis included examining correlation coefficients and p-values to assess the statistical significance of the various relationships. A positive coefficient indicates a positive correlation, meaning that an increase in the factor is associated with a higher likelihood of migration. Conversely, a negative coefficient indicates a negative association, suggesting that an increase in the factor is associated with a lower likelihood of migration.

## Conclusion

Linear regression analysis revealed mixed results regarding the factors influencing youth migration. While GDP per capita and recreational expenditures per capita showed statistically significant relationships, with higher GDP per capita associated with lower migration rates and higher recreational expenditures associated with higher migration rates, other factors, such as GDP, average personal income, and student population showed relationships that were not statistically significant or marginally significant. These findings suggest that economic factors and recreational opportunities may play a role in the migration of young people, but other unmeasured factors and personal circumstances may also have an impact. Further research and analysis is necessary to gain a comprehensive understanding of the complex dynamics driving the migration of young people.


# ArcGIS Story Map

https://storymaps.arcgis.com/stories/fa7812bc413c4206ae093604137cd4ca
