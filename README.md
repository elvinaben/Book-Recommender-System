# Collaborative Filtering-Based Book Recommender System
In this project, a Collaborative Filtering-Based approach is implemented to recommend books based on user preferences and behavior, by identifying the interests of similar users.

## Models Developed:
- Model 1: Uses Cosine Similarity.
- Model 2: Uses KNN with the brute algorithm.
- Model 3: Uses KNN with the brute algorithm and cosine similarity metric.

## Model Comparison:
Upon comparing Models 1 & 2, it was evident that Cosine Similarity performed better in this context. Therefore, Model 3, which combines the brute algorithm with the cosine similarity metric, was developed and deployed.

## System Concept:
The system allows the user to select one book, and it provides 8 recommendations based on the chosen book.

## Dataset:
The dataset used in this project is sourced from Kaggle: [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

## Deployed Model:
The deployed model can be accessed via Streamlit at: [Book Recommender System](https://book-recommender-system-by-elvina.streamlit.app/)
