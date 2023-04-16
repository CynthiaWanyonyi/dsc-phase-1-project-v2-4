# PHASE 1 PROJECT - MICROSOFT MOVIE STUDIO
Author: Cynthia Wanyonyi

The Outline is as follows:

**Project Overview**: The project goal
**Business Problem**: The client, the questions asked before the analysis
**The Data**: The data sets used
**The Process**: Data sorting, cleaning and analysis utilized
**Results**: The output of the analysis
**Reccomendations**: The insights given to solve the business problem

# Project Overview
In this project,we'll use exploratory data analysis to analyze performance of movies and identify trends in popular movie genres, which will help inform decision-making for Microsoft's new movie studio.


## Business Problem
Microsoft is embarking on an exciting new venture - creating a new movie studio. The movie industry has been rapidly evolving, and Microsoft has decided to jump in on the action. However, as a technology company, they don't have expertise in the film industry. 

The purpose of this presentation is to explore what types of films are currently performing well at the box office and provide actionable insights to help Microsoft's new movie studio make informed decisions about what type of films to create. This presentation, hopes to provide valuable insights that will help guide Microsoft's foray into the movie industry.

Questions that will guide the analysis
1. Optimal runtime for a film
2. Best movie directors to hire
3. Genre profit margins for local vs worlwide sales

# Data
In the folder zippedData are movie datasets from:

IMDB - an invaluable SQL database with information within tables on basic movie information e.g titles, genre, runtime, ratings, movie directors, movie writers among others

Rotten Tomatoes - gives collected reviews from professional film critics and calculates a rating based on the percentage of positive reviews. (we will only be focusing on the ratings)

TheMovieDB - gives us start year, release date, among other things

The Numbers - a database that provides information on the financial performance of movies. It provides data on domestic and worldwide box office gross, as well as other financial metrics such as production budget, marketing costs, and home video sales.

# The Process
After reviewing all the datasets, I chose some specific datasets needed for the analysis(and columns within those datasets) to combine, then followed the following process as needed:

1. Data Cleaning
This involved cleaning the data by removing any duplicate or incomplete records and filling in Nan values with the mean or median, correcting any errors or inconsistencies within the columns by removing outliers 

2. Data Analysis
Exploratory data analysis by calculating descriptive statistics such as mean, median, and creating visualizations such as line graphs, scatter plots, and bar charts to identify patterns and trends.

# Results
After the analysis, we interpreted the results by identifying the types of films that are currently performing well, as well as the factors that contribute to their success.

1. To start off the optimal runtime for a film was 70 to 90 minutes for top 4 most popular genres. The scatter plots below show the relationship between runtime and average rating for top 4 genres

![image.png](attachment:image.png)

2. The best directors to use when producing a film are shown in the bargraph below

![image-2.png](attachment:image-2.png)

3. Finally we sort to find the genres with the highest profit margins both locally and internationally. 

![image-4.png](attachment:image-4.png)

![image-3.png](attachment:image-3.png)

# Conclusion
1. Make an Animation, Family, Documentary or Sport film, rated G between 70 to 90 minutes

2. Hire Directors like Christopher Nolan, Joss Whedon, Tim Miller, Gary Ross, J.J. Abrams, Peter Jackson, Alan Taylor that produce movies that get very high ratings

3. International markets yield higher profits especially for the Comedy, Musical, Classics, Drama and Romance films however marketing costs are higher. Local markets yield lesser profits however marketing costs are lower

# Next Steps
Exploring the data further can definitely help in refining the recommendations for Microsoft by:

1. Using consistent data and increasing the size of the dataset, you can improve the accuracy of the analysis and better understand the trends and patterns in the data.

2. Additionally, examining the background and experience of the directors, writers, editors, and actors can provide insights into the potential success of their future projects. This information can help Microsoft make more informed decisions about which films to invest in

3. Understanding how marketing budgets affect ROI and gross revenue can also be highly valuable. This can help Microsoft optimize their marketing strategies and allocate resources more effectively to maximize profitability.

4. Finally, comparing the performance of films across different venues, such as theaters and streaming platforms, can provide insights into market trends and consumer preferences. This information can be used to inform decisions about distribution channels and release dates, which can have a significant impact on the success of a film.

### Non-Technical Presentation
* [You can find the presentation slides here!](https://github.com/CynthiaWanyonyi/dsc-phase-1-project-v2-4/blob/master/Project%20Presentation.pdf)
