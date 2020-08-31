## COMM318: _Stories from data_: Introduction to programming for data journalism

**Fall 2020: M/W 5:00-6:30pm**  

**Professor**: Dr. Matt O'Donnell (he/him/his)
**Email**: mbod@asc.upenn.edu

**TA**: Darin Johnson (he/him/his)
**Email**: darin.johnson@asc.upenn.edu


**Office hours**: Virtual online meetings through Zoom

* Initially we have scheduled:

	1. Thursdays 4-5.30pm EST when Darin will be available
		 * To schedule a 15 minute slot go to
		 		https://www.wejoinin.com/sheets/axytb

	2. Fridays 1-2pm EST Friday will be an open coding help session

**Information technology and programming  assistant**: Ettiene Jacquot
**Email**: etienne.jacquot@asc.upenn.edu (he/him/their)


## Course Description, Goals and Objectives

Today masses of data are available everywhere, capturing information on just about everything and anything. Related but distinct data streams about newsworthy events and issues -- including activity from social media and open data sources (eg: The Open Government Initiative) -- have given rise to a new source for and style of reporting sometimes called Data Journalism. Increasingly, news sites and information portals present visually engaging, dynamic, and interactive stories linked to the underlying data (e.g. The Guardian DataBlog, LA Times Data Desk). This course offers an introduction to Python programming for data analysis and visualization. Students will learn how to collect, analyze, and present various forms of data. Second, because numbers and their visualizations do not speak for themselves but require context, interpretation, and narrative, students will practice making effective stories from data and presenting them in blogs, articles and other formats.

No prior programming experience is required. Through this course students will gain skills writing Python programs to handle large amounts of data and become familiar with some of the key techniques used by data scientists, which is currently one of the most in-demand jobs.

* This course will provide an introduction to Python programming for collecting, cleaning, describing and analyzing a range
of publicly available datasets, including demographic (e.g., age, race, education levels by geographic area),
medical (e.g. vacination, ER intakes for certain conditions like flu, measles, etc),
financial (e.g., spending on infrastructure, education, other initatives, income distribution, etc.), event (e.g., crime data, road accidents) and
transportation (e.g., usage statistics for public transportation and private schemes, e.g. bike shares).

* Each week one session will be in lecture form and provide background for the theory and techniques and the second will be a lab session
in which students will work through programming exercises using Jupyter notebooks (a web-based programming environment well suited for data science and class-based assignments).

* By completing this course students will:
	* gain an understanding of how data can be used to support the reporting and making of news and other types of storytelling
    * practice skills of making stories by collecting, transforming, visualizing and analyzing publicly available data
	* explore the range of various kinds of data now available through initiatives such as Open Government Data initiative (data.gov) and a range of other available and curated data archives
	* be exposed to a range of techniques from data journalism, data science and information visualization and understand how they can be used to tell news/media stories
	* gain a basic level of programming proficiency in the Python programming language and have completed a number of programming exercises to collect, clean, analyze, visualize and interpret such data

## Resources

* Readings on data journalism and resources for learning Python programming and data analysis will be made available on the class Canvas site and the course github repository.


## Assessment


1. **Attend weekly lab sessions and complete the assigned readings and exercises (40%)**
  * Wednesday class sessions will usually be programming labs. We will be using Jupyter notebooks to learn Python, which are part of a web-based interactive programming environment. You must have a github account to access the server. If you do not have an account go to https://github.com/join and set one up. Assignments will be completed in this environment and submitted to the instructor. Details of using this system for assignments will be covered in the first lab session.
	* Assignments will usually be due at 11.59 p.m. (EST) on the Friday following lab session (but this may vary). These assignments are intended to help students practice the programming concepts and structures introduced in lab and build confidence. They should not be difficult or take excessive time but they do build from week to week so it is _very_ important to keep up.

2. **Complete a project that uses the techniques and theory covered in class to carry out a data analysis of a specific research question agreed upon with the instructor (60%)**
    * The goal of this project is to create:
        1. an engaging data-driven online article
        2. a data and analysis repository on `github.com`  

      similar those produced by data journalists (e.g. the `LA Times Data Desk`), for example:
      * github repo: https://github.com/datadesk/notebooks
      * article: https://www.latimes.com/local/lanow/la-me-ln-homeless-housing-hhh-20190320-story.html


    * The steps in the project are:

			1. Decide upon a tractable research question that involves analysis of available data sources (e.g. data.gov or other easily available datasource)

			2. Identify, retrieve and prepare relevant data

			3. Explore, describe and analyze the dataset

			4. Visualize data to help discover patterns

			5. Interpret findings

			6. Setup a github repository to make your data and analysis publicly available

			7. Tell your data story

			 _You can be creative to how you decide to present your data story. You could write a web-based article, a blog post, a white paper or research report or you create a video, etc. to communicate the stories discovered in your data._


       These steps will be scheduled throughout the course allowing for the instructor to help you find a manageable problem, acquire the necessary data and be able to carry out the appropriate computational analysis.

     * More details of the kinds of projects that would be appropriate and manageable will be discussed during the first few weeks of class.




## Note about learning programming

A central goal of this class is to help students begin to develop programming skills that they can use to approach questions of interest using the various open datasets and data sources available. But like learning any new skill, such as a new language, it takes time and can be frustrating at first. This course does not require students to have any programming background. Realistically it is not possible to become a fully proficient programmer in just one semester. However, the lab sessions and assignments are focused on helping you begin this process and to become comfortable with reading, understanding and modifying Python code examples that you can find on the web etc.



## Course Schedule

* **N.B.** - This is a tentative schedule that is subject to change

### Week 1 - Overview
* Wed 09/02/20 - **Course overview** + JupyterHub setup

### Week 2 - Python basics (1) + stories in simple data
* Mon 09/08/20 - NO CLASS (Labor Day)

* Wed 09/09/20 Introduction to notebooks, Markdown & Python
	* Basics of Python Part 1
		* Objects, pointers & some built in functions
		* Introducing lists & indexing
	* Finding stories in simple data.

### Week 3 - Python basics (2)
* Mon 09/14/20 - Lists, indexing
	* Basics of Python Part 2
	  * Lists, indexing and slicing
		* Loops and conditions
	* _Assignment 1 available in JupyterHub_
* Wed 09/16/20 - Lab session - git & github repos
* Fri 09/18/20 - __Assignment 1 DUE - 11.59pm EST__ (Submit through Jupyterhub)

### Week 4 - Working with _Open Data_ & Python basics (3)
* Mon 09/21/20 - data initiatives & repositories e.g. data.gov
	* Basics of Python Part 2
		* Lists, indexing and slicing
		* Loops and conditions
	* _Assignment 2 available in JupyterHub_
* Wed 09/23/20 - Lab session - git & github repos
* Fri 09/25/20 - __Assignment 2 DUE - 11.59pm EST__ (Submit through Jupyterhub)

### Week 5 - Understanding basic data structures as the components of stories
* Mon  09/28/20 - Tabular data - rows, columns. Looking for stories.
	* _Assignment 3 available in JupyterHub_
* Wed 09/30/20 - Lab session - Working with Pandas #1
* Fri 10/02/20 - __Assignment 3 DUE - 11.59pm EST__ (Submit through Jupyterhub)


### Week 6 - Working with data tables - Finding story dimensions in numbers.
* Mon  10/05/20 - Selecting and transforming columns, subsetting & grouping. Data is messy - cleaning it up!
* Wed 10/07/20 - Lab session - Working with Pandas #2
* Fri 10/09/20 - __Assignment 5 DUE - 11.59pm EST__ (Submit through Jupyterhub)


### Week 7 - Data visualization (Part 1) - Supporting stories with plots
* Mon  10/12/20 - Aggregating & summarizing. Creating simple plots. Thinking about good visualizations.
* Wed 10/14/20 - Lab session
* Fri 10/16/20 - __Assignment 6 DUE - 11.59pm EST__ (Submit through Jupyterhub)



### Week 7 - Data visualization (Part 2)
* Mon  10/12/20 - Using Python visualization libraries. Principles of good infomation visualization.
* Wed 10/14/20 - Lab session

### Week 8 - What is data journalism and what can it do?
* Mon  10/19/20 - Guest lecture: Jennifer Henrichsen
* Wed 10/21/20 - Lab Session

### Week 9 -  Data art (Part 1) - data stories beyond the newspaper
* Mon  10/26/20 - Guest lecture: Roopa Vasudevan
* Wed 10/28/20 - Lab session - data art (processing) - part 1

### Week 10 - Data art (Part 2)
* Mon  11/02/20 - Lab session - data art (processing) - part 2
* Wed 11/04/20 - Project planning and disucssion

### Week 11 - Finding data in the _wild_ using web scraping
* Mon  11/09/20 -  Web scraping concepts, HTML + CSS
* Wed 11/11/20 - Lab session - using `requests` + `BeautifulSoup`


### Week 12 - Putting data on the map
* Mon  11/16/20 - Working with geo data
* Wed 11/18/20 - Lab session


### Week 13 - Interactive visualizations
* Mon  11/23/20 - Adding movement to your data stories
* Wed 11/25/20 - Lab session


### Week 14 - Review & Working on projects (1)
* Mon  11/30/20 - Lab session
* Wed 12/02/20 - Lab session


### Week 15 - Review & Working on projects (2)
* Mon  12/07/20 - Lab session
* Wed 12/09/20 - Lab session
