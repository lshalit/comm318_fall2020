## Data analysis notebooks for COMM318 _Stories from data_ Final Project


The data_analysis folder contains a number of Jupyter notebooks with different purposes. The main and final analyses are in a series numbered 1 through 9.

This readme is a list of the notebooks and a short description of what each one does:


Visualizations:
(https://commjhub.asc.upenn.edu/user/coreymberman/tree/COMM318_Final_Project/data_analysis/visualizations) - 
The visualizations folder has .png files for the non-interactive visualizations used throughout the other data analysis notebooks, which can be downloaded and looked at one by one. It is useful to have these in the same place for reference, although obviously it is more relevant in context. 


Data analysis series:
The main data analysis I did for the project is found in this numbered series of notebooks, from 1 through 9:

(1) 1_Importing_and_exploring.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/1_Importing_and_exploring.ipynb) 
This is where I first imported the data from the COMM course data available from Penn Course Review, cleaned up the columns and removed things that were not needed, renamed columns, etc. I also did some initial playing around and seeing things like how to extract means for each variable and did some basic analyses.

(2) 2_Summer_classes.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/2_Summer_classes.ipynb)
I looked into how COMM summer courses are similar to and vary from regular semester ratings along multiple dimensions, including for courses that are taught in summer and non-summer terms. 


(3) 3_Course_levels.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/3_Course_levels.ipynb)
Here I analyzed differences for COMM class reviews between 100, 200, and 300 and 400 level courses. This included various visualizations, interactive and non-interactive, to show how reviews vary by hundred level.


(4) 4_Professors_teaching_multiple_sections.ipynb
(https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/4_Professors_teaching_multiple_sections.ipynb)
In this notebook, I looked at the ECON department as an example of one where professors teach multiple sections in a given semester, to prove that it is possible for reviews to vary significantly across sections taught. I used loops to show how this could happen, as an advisory for students taking classes with multiple sections.


(5) 5_all_star_classes.ipynb
(https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/5_all_star_classes.ipynb)
I showed how each semester has a class that gets top reviews in each category, and how looping can show the "all-star" classes by seeing which courses regularly receive the highest marks in various variables.


(6) 6_Change_over_time.ipynb ()https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/6_Change_over_time.ipynb
I made graphs to show how course quality and other variables changed over time for COMM courses, to see how stable the ratings have been for Annenberg's undergraduate courses.


(7) 7_Students.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/7_Students.ipynb)
I looked at the number of students taking COMM classes over time, and tried to explain potential spikes in the data. 


(8) 8_Majors_comparison.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/8_Majors_comparison.ipynb)
I introduced other departments' course review data to compare them to COMM in terms of means for each variable, and how those have changed over time. Interactive visualizations helped show these relationships and what correlations may exist.


(9) 9_Proportions_over_3.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/9_Proportions_over_3.ipynb)
This final document in my analysis series documents what proportion of classes in COMM receive top-tier ratings (above 3 on the 4-point scale) along different dimensions. I also compared this data with our other departments first imported in notebook 8.



Initial explorations:
My initial explorations and playing around with the data is preserved in a series of three notebooks. These are not my final analysis that I used for the data story output.

initial_exploration_1.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/initial_exploration_1.ipynb) 
Since my originally available data only came from Wharton, and I expected the project to go in some different directions, I worked on analyzing spring 2019 Wharton data to look for trends and potential stories. This included things like ratings based on Wharton concentration, and how I could manipulate the columns in the dataset to examine these stories. 

initial_exploration_2.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/initial_exploration_2.ipynb) 
In this document I first experimented with the requests function in Jupyter to see how I might pull data from the Penn Course Review API and then do more analses similar to in exploration 1.


initial_exploration_3.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/initial_exploration_3.ipynb)
A continuation of initial exploration 2, using the API call to look at department semester histories and course histories in particular. 


Master_blueprint.ipynb (https://commjhub.asc.upenn.edu/user/coreymberman/notebooks/COMM318_Final_Project/data_analysis/Master_blueprint.ipynb) 
This document is a big rough draft of the data analysis I did in the 9 notebooks. 





