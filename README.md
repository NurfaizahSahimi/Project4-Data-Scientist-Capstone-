# Project4-Data-Scientist-Capstone-

## Directory 
[💪Motivation](#project-motivation)

[💾Library](#library-and-installation)

[📂Files & Description](#files-and-description)

[📚Data Preparation](#data-preparation)

[📊Summary](#summary)

[🎈Acknowledgment](#acknowledgement)

## Project Motivation ##

This is the final project for Udacity Nanodegree Data Scientis program. Students are free to choose whatever topics they would like to explore using data science. I chose this topic since I am a loyal user of Netflix and wants to understand deeper on how recommendation engine works, and perhaps build my own recommendation engine. 


## Library and Installation ##

I used python 3 to complete this project. The library and installation command used in this project are listed as below: 

Library           | Command Installation             | Description
-------------     | -------------                    | -------------
Numpy             | `pip3 install numpy`             | Python library used for working with arrays
Pandas            | `pip3 install pandas`            | Open source Python package that is most widely used for data science/data analysis and machine learning tasks
Matplotlib        | `pip3 install matplotlib`        | Matplotlib is a cross-platform, data visualization and graphical plotting library for Python 
Sklearn           | `pip3 install sklearn`           | Sklearn library contains a lot of efficient tools for machine learning and statistical modeling 
Seaborn           | `pip3 install seaborn`           | Open-source Python library built on top of matplotlib. It is used for data visualization and exploratory data analysis.
Matplotlib-inline | `pip3 install matplotlib-inline` | %matplotlib inline is a magic command for IPython that allows you to add plots to the browser interface
Pandas_profiling  | `pip3 install pandas-profiling`  | Quick explarotary data analysis with few codes
re                | `pip3 install re                 | Regular expression operations

## Files and Description ##

<details>
           <summary>netflix_movie_data.csv</summary>
           <p>This is dataset used to gather information in order to seek answers for questions asked in project motivation. This dataset is downloaded from <a href="https://www.kaggle.com/shivamb/netflix-showst">here</a>.</p>
         </details>
         
<details>
           <summary>Netflix Movie Recommendation.ipynb</summary>
           <p>This is jupyter notebook that consists all of the working code.</p>
         </details>
         
 <details>
           <summary>README.MD</summary>
           <p>This is a readme file that is used to represent this project.</p>
         </details>

## Data Preparation ##

1. Data Understanding

   The project begin by trying to understand the dataset and gain much knowledge about data, the curiosity the data will satisfy, its content and its type. It's crucial to understand the data in order to extract useful information from it.
   
2. Data Preparation

   During data preparation, I rename few columns to make them more meaningful. I also separate the column Duration into Duration and Seasons for better analysis since this column originally consists of duration of a movie and count of seasons for tv show. 
   
3. Data Exploration & Data visualization

   I have a lot of question running through my mind when I first start this project, and I try to answer all of that by data exploration. Data visualization gives better presentation to answer all my curiosity. All deployment, visualization, and working codes is nicely prepared in jupyter notebook. I also use jupyter notebook to output chart and graph for better visualization. A blog post regarding    this analysis was published using [Medium](https://nurfaizahbtsahimi.medium.com/ready-for-some-netflix-recommendation-52393b6e42f8 "Medium").
   
   

## Summary ##

This project can be enhanced if any future work needed. There's a lot of improvement can be done to gives out better recommendation to user. There's also few challenges I faced such as multiple genre for one movie/tv show, and also facing some attribute error, and this already handle carefully in Jupyter notebook.


## Acknowledgement ##
Special thanks to this website for their existence, really help me to conduct data analysis for this project with providing lesson, dataset and example :  

✅ [Udacity](https://www.udacity.com/ "Udacity")

✅ [Kaggle](https://www.kaggle.com/ "Kaggle")

✅ [StackOverflow](https://www.stackoverflow.com/ "StackOverflow")

✅ [GeeksforGeeks](https://www.geeksforgeeks.org// "GeeksforGeeks")
