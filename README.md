# Python & Spark Collaborative Filtering Script using Movielens Dataset.

<img src="https://img.shields.io/static/v1?label=Python&message=3.7&color=<COLOR>"> <img src="https://img.shields.io/static/v1?label=Spark&message=2.4&color=<COLOR>"> <img src="https://img.shields.io/static/v1?label=Build&message=Passing&color=<COLOR>">

This is a script with dataset to run and find similarities between from a big data set using Python and Spark. One needs to essesntially pass an id for the movie and then find similar movies based on **item based collaborative filtering**. One can change the values of threshold and modify accordingly.

More here: https://realpython.com/build-recommendation-engine-collaborative-filtering/

## Files

- Big movie dataset with over 1,00,000 movie reviews from https://grouplens.org/datasets/movielens/.
- Movie similarities script in python.

## To Run

- Install Spark & Python on your system.
```console
spark-submit movie-similarities.py <id>
```
(The id of the movie to find similarities for, 50 is for star wars!).

## Maintainers

- Vaibhav Magon
