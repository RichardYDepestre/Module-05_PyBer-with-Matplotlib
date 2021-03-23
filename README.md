# **PyBer Project Analysis**
## Project overview
This is challenge is meant to analyze and summarize ride data for the decision makers at PyBer.
The data compiled and provided to us comes into two datasets:
- The first: citi_data.csv lists the number of drivers that services cities located in three areas: Urban, Suburban and Rural;
- The second: ride_data.csv is more detailed and offers metrics into the dates the rides took place and the rates charges to customers by cities.
## Analysis
Since the two data sets intersect -via city field- we simply merged them and extrapolated information such as:
   1) total rides by areas;
   2) number of drivers the three (3) areas identified earlier;
   3) the total amount of fares PyBer has collected in these areas.
PyBer derives 60% of its revenues from rides in urban areas banking $39,854 (see Attchement 1). In our view there is potential in the other areas if they were to decrease their fares in the in the Suburban and rural areas. The interest to using PyBer's services does exist in the urban and suburban cities. A campaign targeting these areas with fares that appeal to both drivers and customers could generate revenues.
Attachment 1 - [revenue and rides per areas](https://github.com/RichardYDepestre/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png).
Given more time we could have run a model in which we played with fares and showcases the revenues they could have generated. Such a task would have lent more credential to our recommendations. With experience and practice we will get there!
## Recommendations to CEO
We take the liberty and formulate the following recommendation the PyBer's CEO:
   1) start tracking the distances -mileage- covered by drivers and determine a rate that would increase the customer base;
   2) if polling suggest that the rural and suburban areas may expand it would make sense to establish a reward system that would offer incentives to customers, otherwise use option 3;
   3) increase the number of drivers in the city and make Pyber readily available to customers
The attached plot show that the suburban rides show a significant spike in May and may offer as much potential as the urban market Attachment 2 [Total fare by City Type](https://github.com/RichardYDepestre/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png).
## Credits:
To realize this challenge I have utilized resources at specialized sites on the internet. To mention a few, they are:
- https://matplotlib.org/
- https://pandas.pydata.org/docs/reference
- https://stackoverflow.com/
