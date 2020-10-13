## Data files for COMM318 _Stories from data_ Final Project

* This folder should contain the data files you have used in your analysis


* You should update this README file to list and describe the files.


* You can also create additional sub-folders to better organize your data.
    * For example, you could have a folder called `raw` or `orig` to contain the original data files you downloaded and then a folder called `final` or `clean` that contains versions of these data sheets that you have worked with to clean up missing data, to subset or merge etc.
    

This folder contains two subfolders, Raw and Cleaned.
* Raw contains the following datasets:
1. human-resources-per-country.csv: numbers of psychatrists, nurses, and social workers working in the mental health sector per country
2. mental-and-substance-disorders.csv: rates of mental illness per country
3. suicide_crude_by_country.csv: suicide numbers per country
4. with-anxiety-disorders.csv: rates of anxiety disorders per country
5. with-depression.csv: rates of depression per country
6. countries_continents.csv: a list of all countries and which continent they are in
7. country_population_data.csv : each country's population
8. world_pop_1000s.csv: contains the population in each country for each year 1990-2018
9. countries.geojson: a geographical dataset of the location of all the countries in the world

* Cleaned contains the following datasets:
1. anxiety_clean: the cleaned anxiety disorders dataset, which includes continents and population
2. anxietydepressiondisorders: a merged dataset of the anxiety, depression, and mental disorders dataset
3. countries.geojson: the cleaned geographical data of the countries of the world
4. depression_clean: the cleaned depression dataset, which includes continents and population
5. megaset: a merged dataset of the five main datasets: anxiety, depression, disorders, suicide, and human resources
6. resources+disorders: a merged dataset of the cleaned resources and disorders datasets
7. resources_clean: a cleaned dataset of the human resources dataset, which includes continents and population
8. suicide-clean: the cleaned suicide dataset, which includes continents and population
9. world_pop_1000s_clean: the cleaned dataset of the population of countries of the world, with each value actually being one thousand times less than the actual value. There is one row for each country, with columns for each year.
10. world_pop_long: a reconfiguration of the population dataset in which each row corresponds to one country and one year.
11. disorders_clean: the cleaned disorders disorders dataset, which includes continents and population
12. suicideanxietydepressiondisorders: merges the cleaned anxiety, depression, disorders, and suicide datasets.