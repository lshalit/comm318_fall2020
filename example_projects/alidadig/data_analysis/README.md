## Data analysis notebooks for COMM318 _Stories from data_ Final Project

My notebooks are split between Initial_Exploration_and_Analysis and Deeper_Analysis folders. 

My Initial_Exploration_and_Analysis folder contains notebooks for each of my datasets:
    Explored and Cleaned Income.ipynb: Takes a look at the income levels for all 48 zipcodes, cuts the dataset down to only the columns I need and renames them
    Explored and Cleaned Diabetes.ipynb: Takes a look at the diabetes counts for all 48 zipcodes, cuts the dataset down to only the columns I need and renames them
    Explored and Cleaned Farmers Markets.ipynb: Condenses the dataset into just the columns I need and renames them, also splits geometry into latitude and longitude. 
    Explored and Cleaned Healthy Corner Stores.ipynb: Condenses the dataset into just the columns I need and renames them, also splits geometry into latitude and longitude. 
    Explored and Cleaned Convenience Stores.ipynb: Condenses the dataset into just the columns I need and renames them, also splits geometry into latitude and longitude. 
    Explored and Cleaned Education.ipynb: Takes a look at the education levels for all 48 zipcodes, cuts the dataset down to only the columns I need and renames them
    
My Deeper_Analysis folder contains notebooks where I analyze and create my own datasets and graphs or maps for my final presentation:
    1. Income and Diabetes (Correlational Graph).ipynb: I create a new dataset using the cleaned income and diabetes sets and plot them on a graph 
    2. All Healthy Food Locations (Interactive Map).ipynb: I create a new dataset combining the cornery store locations and farmers markets and plot them as an interactive plotly map. 
    3. Convenience Store Locations (Interactive Map).ipynb: I plot the cleaned convenience stores as an interactive plotly map. 
    4. All Food Locations (Dot Map).ipynb: I plot the combined dataset for all healthy locations with the convenience store dataset using their geometry coordinates to show the dominance of convenience store locations over healthy store locations. 
    5. Healthy Store Counts Analysis.ipynb: I take the combined dataset for all healthy store locations and count the number of locations in each zipcode as a list. 
    6. Unhealthy Food Counts Analysis.ipynb: I count the number of locations for convenience stores in each zipcode into a list. 
    7. Healthy to Unhealthy Ratio Analysis.ipynb: I divide the healthy list by the unhealthy list to find a ratio of healthy to unhealthy store locations per zipcode as a new list. 
    8. Income, Diabetes, Healthy Stores, Unhealthy Stores, Ratio (Graphs).ipynb: I plot the healthy store counts as a third dimension with diabetes and income as a plotly bubble map. Then I do the same with the unhealthy store counts. Then I create a third one with the ratio list. 
    9. Education, Income, Diabetes (Graph).ipynb: Because the access to healthy stores and the ratio of healthy to unhealthy stores proved not to be a significant link between income and diabetes, I turned to another factor that could be a link: education. I plot education level as a third dimension with diabetes and income level using a plotly bubble map. 