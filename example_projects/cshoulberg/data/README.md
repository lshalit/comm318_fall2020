## Data files for COMM318 _Stories from data_ Final Project

### Data files used: 
The data I found are the Energy Benchmarking data released each year by the Philadelphia Office of Sustainability. This data is acquired from all the largest buildings in Philly (50,000 SF) who report their energy and water use each year to the Office of Sustainability as part of a new mandated Bill. This increased transparency and accountability was created to motivate landlords to go about more efficient practices in hopes of cutting energy usage and Greenhouse gas (GHG) emissions in the city by 2050 by 80%.

2013: energy_usage_large_commercial_buildings_reported_2013.csv 
2014: energy_usage_large_commercial_buildings_reported_2014.csv
2015: properties_reported_2015.csv
2016: properties_reported_2016.csv
2017: properties_reported_2017.csv

means.csv -- took the mean GHG emissions of the buildings and created a new CSV on my computer to visualize the data

### subsequent created csvs:
 
buildings_needing_geoinfo.csv -- a csv created from all the buildings that do not have long and lat that I will use to the geo-lookup pandas tool to find their respective lat and long to be able to plot all my buildings
totaldf_lat_long.csv -- a final CSV of all my buildings with the long and lat that the lookup found. I created a new CSV because the lookup took 3 hours to run all the way through so this allows me to map my data without having to look up all the buildings again.

### exports for wix interactive tables:
2017export.csv -- list of all the buildings in 2017 dataframe 
export.csv -- trial export 
thebestexport.csv -- list of the most efficient buildings
theworstexport.csv -- list of the least efficient buildings