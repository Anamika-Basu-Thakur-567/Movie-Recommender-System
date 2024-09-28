# Movie-Recommender-System

## Description
This project focuses on building a movie recommender system. The process begins by creating subsets of the dataset to isolate the most relevant columns, which are crucial for accurately recommending movies. Feature engineering techniques were applied to transform the data into a format suitable for machine learning algorithms. The new relevant column, containing information about the movies, was transformed into an array of vectors using CountVectorizer. The system then employs Cosine Similarity to compare movies and generate recommendations based on the highest similarity scores, allowing users to discover movies similar to the ones they enjoy.

## Features
- **Dataset Subsetting:** Focused on the most relevant columns necessary for improving the accuracy of the recommender system.
- **Feature Engineering:** Extracted and engineered new data, transforming it into vectors using CountVectorizer to capture key movie attributes.
- **Cosine Similarity:** Utilized this metric to compute the similarity between movies, recommending the ones with the highest similarity scores.
- **Movie Recommendations:** Based on user inputs or selected movies, the system provides a list of recommended movies by analyzing similarities.
