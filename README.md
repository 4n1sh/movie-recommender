Movie Recommender System

A content-based movie recommendation system built in Python that suggests movies similar to a given movie based on metadata like overview, genres, cast, crew, and keywords.

Features

Combines multiple text features (overview, genres, cast, crew, keywords) into a single representation.

Uses CountVectorizer and cosine similarity for content-based recommendations.

Provides a simple recommend() function to get the top 5 similar movies.

Exports models and data as pickle files (movies.pkl, similarity.pkl, cv.pkl) for quick reuse.
