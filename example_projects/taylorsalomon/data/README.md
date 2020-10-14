## Data files for COMM318 _Stories from data_ Final Project

* This folder should contain the data files you have used in your analysis


* You should update this README file to list and describe the files.


* You can also create additional sub-folders to better organize your data.
    * For example, you could have a folder called `raw` or `orig` to contain the original data files you downloaded and then a folder called `final` or `clean` that contains versions of these data sheets that you have worked with to clean up missing data, to subset or merge etc.
    
## My data

### COMM318_Final_Project/data/Raw folder
* this folder contains:
    * 2016President_1.csv - the original voting data for NYS in the 2016 presidential election
    * Hate_Crimes_by_County_and_Bias_Type__Beginning_2010 (1).csv - the original hate crime data for NYS counties since 2010
    * NYS_Pop.csv - the original NYS population by county data

### COMM318_Final_Project/data/Clean folder
* this folder contains:
    * 2016President_clean.csv - the voting data for New York State in 2016 after being cleaned in the cleaning_voting_df notebook
    * Hate_Crimes_clean.csv - the hate crimes by county for New York State after being cleaned in the cleaning_hate_crimes_df notebook
    * Hate_Crimes_Normalized.csv - the hate crimes by county when normalized using the NYS population data
    * NYSpop - the NYS popualtion data only with the columns necessary for my analysis
    
### COMM318_Final_Project/data/geodata folder
* this folder contains
    * gz_2010_us_050_00_5m.zip
    * ny_state_counties.json
    * both used to make geo plots of NYS