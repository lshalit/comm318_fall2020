## Data analysis notebooks for COMM318 _Stories from data_ Final Project

### Notebook1_Exploring_2017_df.ipynb (FINAL ANALYSIS NOTEBOOK)
     This notebook is the first analysis that I conducted. Here, I set out to explore the data published about energy in Philadelphia in 2017. This allowed me to understand the data I had for all 5 years and what stories could come out of it. In this nootebook I did the following
     * Primary Inspection 
     * Exploration of different columns (property types, greenhouse gas emissions,  eneryg STAR scores, year built) -- I created different graphs and conducted different analyses to add to different parts of my story 
     * Calculation energy efficiency per square foot 
     * Creation of a CSV for my building searcher tool article
     * Exploration of which zipcode is the least and most efficient
     * Exploration of University City buildings filtering out with 19104 postal code
     

### Notebook2_Analyzing_Efficiency_Over_Time.ipynb: (FINAL ANALYSIS NOTEBOOK)
    This notebook works to analyze energy efficiency (through the metric of Energy STAR scores and GHG emissions) over time. In this notebook, I look to compare GHG emission and scores over time for both Philly as a whole but also by property type. I focus on following 5 property types for my analysis: Office, Industrial, Retail, Housing and Education. This notebook will mostly flow into my article assessing whether or not Energy Benchmarking initatives have led to any tangible energy efficiency changes in the city or not. 

### Notebook3_The_Best_And_Worst_of_2017.ipynb: (FINAL ANALYSIS NOTEBOOK)
    This notetbook looks to prepare my visualizations and data analysis for my article about the "Naughty & Nice List of 2017". That is, I analyze which buildings in Philly were the least and most efficient according to Energy STAR score and prepare analyssi according to these two groups. 

### Notebook4_Timeline .ipynb: (FINAL ANALYSIS NOTEBOOK)
    This brief notebook prepares basic analysis of mean energy STAR scores, total SF reported per year, and total GHG emitted that year for my article detailing the timeline of energy efficiency initatives in Philadelphia. The point of this notebook is to calculate basic metrics for this article. 
   
### Noteboook5_geocode_addresses_from_building_data.ipynb: (TEACHING NOTEBOOK)
    This notebook is where Professor O'Donnell really helped me figure out how to clean my dataframe to be able to look up the necessary information to be able to plot my buildings. Although this notebook was very useful -- I ended up rewriting the code in Notebook 8 for sake of cleanliness and to better explain my thought process. Essentially, however, this notebook cleans up and combines all 5 of my years of data. We use the building id as a unique number associated to a building shared across all 5 data frames. All years but 2013 only provided the street adress and postal code so we had to use a geo-lookup to fit the long and lat to be able to plot the buildings on a map. 
    This code does not necesarilly run all the way through because it is more of a guiding notebook than an actual notebook showing my work.

### Noteook6_Geo-Exploration.ipynb: (PRELIMINARY -- UNFINISHED NOTEBOOK)
    This notebook shows our first attempt at looking up the buildings in every year. We ended up realizing that the code was too long and kept erroring due to a number of issues (inconsistencies in syntax, duplicate buildings, missing information). Further, we realized that it was not necessary to run the code individually per year because the buildings carry over year after year. Thus, we went to notebook 5 to create a code that would clean up the data with building id to prevent having to run a long code that took hours to go through over and over. 
    This notebook ends up not running all the way through because it was my first attempt at mapping. I later learned more stuff needed to be done to set up my data and find the addresess. 

### Notebook7_Merged_Data_Exploration.ipynb (PRELIMINARY -- UNFINISHED NOTEBOOK)
    This notebook was my first attempt at cleaning up the data according to what we realized went wrong in notebook 6 before Professor O'Donnel created notebook 5 to help me sort through. Here, I rename all the column names in each years worth of data to be the same and start cleaning up the building id column by removing duplicates, null values, and non-numeric values. 
     This notebook does not run all the way through because it shows my first attempt at merging my dataframes and cleaning them up. I ended up doing this in a much more efficient way in notebooks 7-9. 
     
### Notebook 8_Rework_of_notebook_5 .ipynb (FINAL ANALYSIS NOTEBOOK)
    This is my final notebook for setting up my data for being able to map it onto a map. This runs a giant lookup over a MASSIVE dataframe to find the longtiude and latitudes of all the buildings reported in my data. This then creates a gpd to plot the points onto the map of Philadelphia. Because this lookup takes so long and crashes, I created notebook 9 to create a smaller subset of buildings to lookup so that I could have a tangible product that displayed all my work on getting this lookup code to work. 
    
### Notebook 9_MapforNaughtyNice. ipynb (FINAL ANALYSIS NOTEBOOK)
    This is my notebook for creating a map for my Naughty and Nice article. I used geolookup to find the latitudes and longitudes of buildings that are most and least efficient in 2017. I then used plotly express to create an interactive map -- plotted color wise red= not efficient, blue = efficient. 