# Spark-Python-MovieReviews

This is a script with dataset to run and find similarities between from a big data set using Python and Spark. One needs to essesntially pass an id for the movie and then find similar movies based on item based collaborative filtering. One can change the values of threshold and modify accordingly.

# Files

1. Big movie dataset with over 1,00,000 movie reviews from https://grouplens.org/datasets/movielens/.
2. Movie similarities script in python.

# To Run

1. Dependencies installed (Spark, Python etc.)
2. > spark-submit movie-similarities.py #id (The id of the movie to find similarities for, 50 is for star wars!).
