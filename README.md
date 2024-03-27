# Project-4-Netflix-TV-Shows-and-Movies
Due Mar 26 by 11:59pm

## Project Concept
Original plan - create a ML movie suggestion tool - allow users to pick 1-3 genres & predict a movie they might like - disproved!

Netflix - who hasn’t heard of the company?  

This project - is looking at the predictability of the IMDb rating.  IMDb (an acronym for Internet Movie Database) is an online database of information related to films, television series, podcasts, home videos, video games, and streaming content online rating.  IMDb offers registered users the opportunity to rate titles on a scale of one to ten.  The average of this becomes the IMDb score. 

To obtain data for this project, we looked at two datasets with multiple spreadsheets on Kaggle. We decided to use the “Official Netflix Viewership Database” and specifically use the titles.csv file because it contained the most complete data.

We applied both the Keras and Linear Regression models to this data. We used Tableau to see if there were other predictions we wanted to make.


## Data Selection and Preprocessing
* Data Source: https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies?select=titles.csv
* License: https://creativecommons.org/publicdomain/zero/1.0/
* Using Jupyter notebook
* Pandas - drop columns related to TV Shows (seasons, tmbd_popularity, & tmbd_score)
* Spark/SparkSQL - remove TV Shows
* Pandas - 
* remove rows where IMDB_score is null  
* remove [], ‘, & extra blanks from fields
* Split genres field into separate fields for each genre

## Data Model useage and optimization
* Keras Model was used against 3 genres keras Tuner was used to optimize the models getting 2 of them above the 75% accuracy
* LinearRegression Model was used to predict imdb rating based off of the features of the dataset - did not achieve meaningful accuracy

## Visualizations using Matplot 
* Plot of genres and the number of people who rated them showed Drama had the most votes
* Plot of min and Max IMDB scores for each Genre shows there was more vartriation in some Genre than others

Tableau public pages: https://public.tableau.com/app/profile/jennifer.white5832/viz/Project4movieratings/Story1?publish=yes
* https://public.tableau.com/views/MovieRatings_17110737906980/GenreScores?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

Powerpoint with Tableau link:
* https://docs.google.com/presentation/d/1fPhWLJrVFiIvvUEJyS8gswrr0U7Y-UuP_RtkRsuqZqQ/edit#slide=id.g2c56b5375f8_0_0

## Acknowledgements/Resources
* Dallin Whitaker - project concept
* https://stackoverflow.com - color options for charts
* https://seaborn.pydata.org/generated/seaborn.barplot.html - making bar plots
* https://en.wikipedia.org/wiki/Motion_Picture_Association_film_rating_system

## Project 4 Rubric:
### Data Model Implementation (25 points)
* A Python script initializes, trains, and evaluates a model (10 points)
* The data is cleaned, normalized, and standardized prior to modeling (5 points)
* The model utilizes data retrieved from SQL or Spark (5 points)
* The model demonstrates meaningful predictive power at least 75% classification accuracy or 0.80 R-squared. (5
points)
### Data Model Optimization (25 points)
* The model optimization and evaluation process showing iterative changes made to the model and the resulting
* changes in model performance is documented in either a CSV/Excel table or in the Python script itself (15 points)
* Overall model performance is printed or displayed at the end of the script (10 points)
### GitHub Documentation (25 points)
* GitHub repository is free of unnecessary files and folders and has an appropriate .gitignore in use (10 points)
* The README is customized as a polished presentation of the content of the project (15 points)
### Group Presentation (25 points)
* All group members speak during the presentation. (5 points)
* Content, transitions, and conclusions flow smoothly within any time restrictions. (5 points)
* The content is relevant to the project. (10 points)
* The presentation maintains audience interest. (5 points)
This project will be evaluated against the requirements and assigned a grade acco
