# **Movie Recommendation System**

This project demonstrates a comprehensive movie recommendation system that employs three fundamental recommendation techniques:
* Demographic Filtering: Recommends movies based on popularity and ratings, implementing the Weighted Rating formula.
* Content-Based Filtering: Suggests movies similar to those a user has liked, using TF-IDF Vectorizer and Cosine Similarity from Scikit-learn.
* Collaborative Filtering: Predicts user preferences using Singular Value Decomposition (SVD), a matrix factorization technique.

The system is designed to highlight the core principles and applications of recommendation systems in a real-world scenario.

## ***Features:***

* Demographic Filtering: Recommends highly rated and popular movies.
* Content-Based Filtering: Provides recommendations based on movie features (e.g., genres, keywords).
* Collaborative Filtering: Leverages user-movie interaction data to predict ratings for unseen movies.
* Detailed visualization of results for better understanding.

## ***Technologies Used:***

* Programming Language: Python
* Libraries:
    * pandas, numpy for data manipulation
    * scikit-learn for TF-IDF Vectorization and Cosine Similarity
    * surprise library for Collaborative Filtering (SVD implementation)
    * matplotlib for data visualization
* Dataset: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata