# Project-4-Netflix-TV-Shows-and-Movies
Due Mar 26 by 11:59pm
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

## Project Concept

## Data Selection and Preprocessing
* Data Source: https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies?select=titles.csv
* Using Jupyter notebook
* Pandas - drop columns related to TV Shows (seasons, tmbd_popularity, & tmbd_score)
* Spark/SparkSQL - remove TV Shows
* Pandas - 
* remove rows where IMDB_score is null  
* remove [], ‘, & extra blanks from fields
* Split genres field into separate fields for each genre

## Data Model useage and optimization
* Keras Model was used against 3 genres keras Tuner was used to optimize the models getting 2 of them above the 75% accuracy
* 

## Visualizations using Matplot 
* Plot of genres and the number of people who rated them showed Drama had the most votes
* Plot of min and Max IMDB scores for each Genre shows there was more vartriation in some Genre than others

Tableau public pages: https://public.tableau.com/app/profile/jennifer.white5832/viz/Project4movieratings/Story1?publish=yes
https://public.tableau.com/views/MovieRatings_17110737906980/GenreScores?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

