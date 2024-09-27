# Movie-Similarity-Analysis-Using-Movie-Plot
This mini-project implements a movie recommendation system that suggests similar movies based on their plot descriptions. Using Natural Language Processing (NLP) techniques, the project leverages the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization method to convert movie plot descriptions into numerical representations. Cosine similarity is then calculated to determine the closeness between movies. Given a movie title as input, the system recommends the top 10 most similar movies by analyzing the textual content of their plots.

Key Features:
Uses TF-IDF Vectorizer to analyze movie plot descriptions.
Employs Cosine Similarity to measure the similarity between movies.
Recommends movies based on plot-based similarity scores.
Handles missing data by filling in empty descriptions with placeholders.

Tools and Libraries:
Pandas for data manipulation.
Scikit-learn for TF-IDF vectorization and cosine similarity.
Numpy for numerical operations.
