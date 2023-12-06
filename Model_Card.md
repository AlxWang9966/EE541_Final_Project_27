# Model Card for Recommendation Systems

## 1. Model Details
- **Model Date**: Dec.5.2023
- **Model Type**: Collaborative Filtering & Content-Based Filtering
- **Model Parameters**: 
  - Collaborative Filtering Model Parameters: UserId, MovieId, Ratings
  - Content Filtering Model Parameters: id, title, genre, overview

## 2. Model Use
- **Goal of the Model**: These models are designed to recommend movies to users based on their preferences and movie characteristics.
- **General Process**:
  - Content Filtering: Utilizes item features to suggest similar items.
  - Collaborative Filtering: Recommends items based on user-item interactions and similarities.

## 3. Data, Performance, and Limitation
- **Data Used**:
  - Content Filtering: Only used "movies_metadata.csv".
  - Collaborative Filtering: Used "movies_metadata.csv" and "ratings_small.csv".
- **Model Performance**:
  - Content Filtering: It depends on the different values of the parameters "max_features". 
  - Collaborative Filtering: It depends on the predicting accuracy.
- **Limitation of the Model**:
  - The model's limitations include a focus on user-based predictions, making it less effective for movie ID inputs, and challenges in evaluation metrics due to its unsupervised learning approach, partially addressed by adjusting the TF-IDF algorithm's "max_features" parameter.

