# PyBer_Analysis

## Project Overview

The purpose of this project was to analyze the differences between three different types of cities: Urban. Suburban, and Rural. The analysis will be used to make decisions based on total weekly fares in the first quarter of 2019.

## Resources

- Data Resources: city_data.csv and ride_data.csv
- Software: Python 3.9.1, Visual Studio Code 1.51.1, jupyter-notebook 6.1.4

# Results

Initially, I created a DataFrame to produce the numerical information regarding the three city types as seen in image below:

![](/analysis/pyber_summary.png)

Rural
- 125 total rides
- 78 total drivers
- $4,327.93 in total fares
- $34.62 average fare per ride
- $55.49 average fare per driver

Suburban
- 625 total rides
- 490 total drivers
- $19,356.33 in total fares
- $30.97 average fare per ride
- $39.50 average fare per driver

Urban
- 1,625 total rides
- 2,405 total drivers
- $39,854.38 in total fares
- $24.53 average fare per ride
- $16.57 average fare per driver

This information was then broken down into a weekly basis analysis and transcribed onto the graph below:

![](/analysis/PyBer_fare_summary.png)

This graph indicates that urban cities make the most money in total fares while rural cities make the least total.

## Summary

The data makes it clear that urban cities are where the most money in fares are made, however there is a disparaity in the averages of the fares both per ride and per driver. Rural areas have the highest averages for rides likely because the rides are significantly longer, and thus the fares earned for those rides are higher. Also, due to the lower number of drivers in those areas, the average fare per driver is also higher. This disparity leads me to provide three recommendations:

1. Begin investing in marketing around rural cities to drive up demand. With the high margins in those areas, increase in demand will likely lead to significant gains in the average fares per ride and total fares for the city type. It is unlikely that the distance for those rides will change, so increasing demand will ultimately lead to an increase in total fare revenue.
2. Increase the prices in urban cities. Because of the high demand for PyBer in urban areas, increasing prices in small incrememnts could lead to significant financial gains without significant loss in total rides. This would in turn lead to significant increase in fare recenues in an area that tends to have shorter and therefore less expensive fares.
3. Decrease the number of dirvers in urban areas. There are nearly four times as many drivers in urban areas as there are in suburban areas, which is has lead to a signifcant decrease in average fare per driver. The low earnings per driver could lead to higher quality drivers leaving PyBer to find better work elsewherem which in turn could lead to poorer services for our customers. By moving the fares per driver average up, you ensure quality service and continued high demand in those areas, which will be important if you also raise prices in the area.

By following these recommendations, PyBer will be able to increase their revenues in these areas and ultimately become an even more successful company.