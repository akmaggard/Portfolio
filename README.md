# Poster 

## About this assignment
This assignment was intended to test my ability to create a "poster"-type presentation using R markdown and the posterdown package. 

## Research Topic
My poster subject concerns the relationship between countries' Human Development Index (HDI) scores, climatic conditions and geographic situtaiton, and the prevelance of urban greenspaces in those same countries. Does a country’s level of human development influence the prevalence of urban greenspaces within its borders? Might investment in human development enable countries in more arid climates to overcome their climatic circumstances?

## The Data
I draw on 1,037 observations of urban greenspace data collected by Jennifer Stowell of Boston University’s School of Public Health. Key variables include City, Country, Major_Geo_Region (i.e., the region of the world in which the given Country is situated), HDI_level (i.e., the level of a country’s HDI score), Climate_region (i.e., the type of climate prevailing in a given City in a given Country), and a series of variables (indicator_2010, indicator_2015, indicator_2020, and indicator_2021) - the latter being the Normalized Difference Vegetation Index (NDVI) score for a given City for the years 2010, 2015, 2020, and 2021.

## My Approach
My analysis weighs the influence of a country’s HDI score versus specific natural geographic factors on the prevalance of urban greenspaces in that country’s cities as reflected in the NDVI values for 2021 (i.e. the indicator_2021 variable). I employ a multivariate regression analysis to weigh the relative influence of the HDI_level, Major_Geo_Region, and Climate_Region variables on the indicator_2021 variable - which, as noted above, measures cities’ NDVI values as of 2021.
