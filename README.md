# Movie-Recommendation-System
## In this machine learning project, I build a content based recommendation system from the ground up to suggest movies to the user based on his/her preferences.

# Dataset - > TMDB 5000 Movie Dataset
## About dataset -> TMDB 5000 Movie Dataset is a collection pf 5000 movies, and The dataset contains two CSV files, credits, and movies. The credits file contains all the metadata information about the movie and the movie file contains the information like name and id of the movie, budget, languages in the movie that has been released, etc.
## Dataset Link ->https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

# About Movie Recommendation Project -> 
## In this machine learning project, I build a content based recommendation system from the ground up to suggest movies to the user based on his/her preferences.

# The approach to build the movie recommendation engine consists of the following steps-

## 1. Data Analysis -> Analyse the data
## 2. Feature engineering -> Select important features for the project.
## 3. Data Cleaning -> clean the data.
## 4. Data Preprocessing -> For this step NLTK library is used, and following steps are done-
###   Lowercasing
###   remove stop words
###   remove speacial symbols
## 5. Vectorization -> converting text into vector by the help of 'TF-IDF'
## 6. Similarity -> By the help of cosine distace, findout the similarity between the movies.
## 7. Making a function for showing recommeneded movies
## 8. Pickle the files and make a website by the help of streamlit library and finally deploy the model on 'Heroku'.

# DEMO PICTURES OF APP -
## 1.Recommendation for Spider-man
![Screenshot 2022-09-19 190749](https://user-images.githubusercontent.com/103623927/191043701-7978010e-29e5-4bc0-9c4d-ea8bb39907c5.png)

## 2. Recommendation for Harry potter
![Screenshot 2022-09-19 190527](https://user-images.githubusercontent.com/103623927/191044444-cbff79f4-a3f1-4f8b-bfe9-c8ae47df90d7.png)
