## Data files for COMM318 _Stories from data_ Final Project

* This folder should contain the data files you have used in your analysis
* You should update this README file to list and describe the files.

To start, my research project will be to analyze the school systems in Philadalphia, specifically in West Philadelphia, within a certain radius outside of Penn's campus. I decided to look at the schools that are within a three mile radius of Penn's campus and analyze whether or not an Ivy League University has any impact on the surrounding communities, and if so what kind of an impact.  I want to specifically look at the attendance and graduation rate of the students that attend the schools within this radius of Penn's campus as opposed to students attending a school in the remainder of the Philadelphia district.

In order to gather research to answer my research question regarding the Philadelphia school district, I have had to analyze multiple data files.

Initially, I found a spreadsheet with a list of all of the schools within the Philadelphia district.  I then was able to search each individual school by name, and determine their address, and distance away from Penn's campus.  Through this tedious process I was able to determine the 65 schools (out of 322 schools) that I was going to seperate out and hone in on.

The file `COMM318_Final_Project/data/enrollment_demographics.csv`- which I further broke down into two subsets `COMM318_Final_Project_data/penn_phl_school_ed.csv` and `COMM318_Final_Project_data/nonpenn_phl_school_ed.csv` gives a running list of all of the schools in the Philadelphia school district with the total number of students enrolled at each school along with the breakdown of enrollment by grade. The file also breaks down the demographic of each grade in each school. In addition there is a CEP, IEP, and ELL count for each of the schools.  
    *CEP - "Community Eligibility Provision" non-pricing meal option for schools and school districts in low-income areas
    *IEP - "Individualized Education Program"
    *ELL - "English Language Learner"

The file `COMM318_Final_Project/data/phl_school_metric_scores_revised.csv` - which I also broke down into two sets `COMM318_Final_Project/data/sms_penn_schools.csv` and `COMM318_Final_Project/data/sms_nonpenn_schools.csv`.  (But later in my analysis I realized there was a problem with one of the sets and I cleaned and re-uploaded the file as `COMM318_Final_Project/data/updated_sms_nonpenn_schools,csv`) presentes "score cards" from the Philadelphia School District Open Data site.  The report looks at 69 different metrics in total.  I selected from these metrics, specific areas that I wanted to focus on for my research question. 

`COMM318_Final_Project/data/95_attendance_yearly.csv` is a file that contains the breakdown of each school in the Philadelphia district, seperated by grade, by the percentage of students that attend more than 95% of instructional days in a given year.  They also partner the percentage of students with the exact number of students that this equates too. 