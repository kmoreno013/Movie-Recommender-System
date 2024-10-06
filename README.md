# Movie Recommender System
This project is published as a Jupyter Notebook, providing a detailed guide for developing a movie recommendation system that leverages both content-based and collaborative filtering techniques.

## Sections:
### I. Data Preprocessing
* Data Collection: Retrieve and load the MovieLens dataset, which contains user ratings and movie details.
* Data Cleaning: Handle missing values, correct data formats, and ensure all fields are properly prepared for analysis.
* Feature Engineering: Create relevant features from the dataset, such as user preferences and movie genres, to facilitate effective recommendations.
### II. Content-Based Filtering
* User Profile Creation: Develop user profiles based on the movies they have rated, focusing on the attributes and genres of those movies.
* Movie Similarity Calculation: Compute the similarity between movies based on their features (e.g., genres, descriptions) to recommend similar films to the user.
### III. Collaborative-Based Filtering
* User Similarity Calculation: Utilize the Pearson Correlation Coefficient to assess similarities between users based on their ratings.
* Weighted Rating Predictions: Generate movie recommendations by calculating a weighted average of ratings from similar users, prioritizing those with higher similarity indices.
  
## Tools and Libraries:
* Programming Language: Python
* Interactive Programming Tool: Jupyter Notebook
* Data Manipulation: Pandas, NumPy
