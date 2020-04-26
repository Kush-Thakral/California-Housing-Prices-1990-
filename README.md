# California-Housing-Prices-1990 

This model is based on the dataset california housing prices (1990) from the book "Hands-on Machine Learning with Scikit-Learn and Tensorflow" 

## Business Problem:
To predict the prices of houses in Californa (1990) based on their different specifications and locations

## Description :
This dataset is a modified version of the California Housing dataset available from Luís Torgo's page (University of Porto). Luís Torgo obtained it from the StatLib repository (which is closed now). The dataset may also be downloaded from StatLib mirrors.

This dataset appeared in a 1997 paper titled Sparse Spatial Autoregressions by Pace, R. Kelley and Ronald Barry, published in the Statistics and Probability Letters journal. They built it using the 1990 California census data. It contains one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

The information was collected on the variables using all the block groups in California from the 1990 Census. In this sample a block group on average includes 1425.5 individuals living in a geographically compact area. Naturally, the geographical area included varies inversely with the population density. Distances were computed among the centroids of each block group as measured in latitude and longitude and all the districts reporting zero entries for the independent and dependent variables were excluded. The final data contained 20,640 observations on 9 variables. The dependent variable is ln(median house value). The other variables are as follows:

     -longitude: A measure of how far west a house is; a higher value is farther west
     -latitude: A measure of how far north a house is; a higher value is farther north  
     -housingMedianAge: Median age of a house within a block; a lower number is a newer building
     -totalRooms: Total number of rooms within a block
     -totalBedrooms: Total number of bedrooms within a block
     -population: Total number of people residing within a block
     -households: Total number of households, a group of people residing within a home unit, for a block
     -medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
     -medianHouseValue: Median house value for households within a block (measured in US Dollars)  
     -oceanProximity: Location of the house w.r.t ocean/sea
