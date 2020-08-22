# Movie Recommendation System

Movie Recommendation system to recommend top 5 movies to a user built using SparkML

The dataset can be found from the following webiste - https://grouplens.org/datasets/movielens/latest/

Data Summary:

The dataset contains three csv files namely ratings.csv which contain the movie ratings, movies.csv which contain the movie names and links.csv which links the movieIDs with the ImdbIds and TmdbIds.

Here we use Alternative Least Squares(ALS) Algorithm on SparkML to build a movie recommendation engine to recommend top 5 movies to any user in consideration based on collaborative filtering approach. 