# movie-recommendation
movie ratings using pyspark and MLlib

# Predicting Movie Ratings

One of the most common uses of big data is to predict what users want. This allows Google to show you relevant ads, Amazon to recommend relevant products, and Netflix to recommend movies that you might like. This lab will demonstrate how we can use Apache Spark to recommend movies to a user. We will start with some basic techniques, and then use the [Spark ML][sparkml] library's Alternating Least Squares method to make more sophisticated predictions.

In this project, we will use MLlib to make personalized movie recommendations tailored for you. We will work with 10 million ratings from 72,000 users on 10,000 movies, collected by MovieLens. This dataset is can be found at https://grouplens.org/datasets/movielens/latest/. You may want to start with a smaller version of the dataset.
