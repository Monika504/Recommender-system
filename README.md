# **Movie Recommendation System – Project Description**


This project builds a content-based movie recommendation system using the TMDB 5000 Movies Dataset. The system suggests similar movies based on their genres, keywords, cast, and crew, helping users discover films related to their interests.

**Technologies Used**: Python, Pandas, NumPy, NLTK, Scikit-learn, CountVectorizer, Cosine Similarity, Jupyter Notebook


The dataset consists of two main files:

_tmdb_5000_movies.csv_ – Contains movie metadata like overview, genres, and keywords.

_tmdb_5000_credits.csv_ – Includes cast and crew information.

**The steps involved include:**

* Merging the two datasets on the movie title.

* Selecting relevant features such as genres, keywords, cast, crew, and overview.

* Parsing strings to extract useful text tokens.

* Text processing and feature engineering, including combining features into a single string and vectorizing them using CountVectorizer.

* Calculating cosine similarity to recommend movies that are most similar to a selected title.

This is a straightforward, explainable system that leverages basic NLP and similarity scoring to help users find movies they might enjoy.
