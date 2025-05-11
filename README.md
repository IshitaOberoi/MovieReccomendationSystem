# MovieReccomendationSystem

The ever-growing collection of movies in the entertainment industry has created a challenge for viewers: choosing what to watch from a vast array of options. To address this, recommendation systems have emerged as essential tools for delivering personalized content suggestions based on user preferences and behaviors. This project aims to develop a Movie Recommendation System using the K-Nearest Neighbors (KNN) algorithm, a straightforward yet powerful approach that identifies similarities between movies to generate relevant recommendations.

Datasets used: 
1. https://www.kaggle.com/code/heeraldedhia/movie-ratings-and-recommendation-using-knn/input?select=tmdb_5000_movies.csv
2. https://www.kaggle.com/code/heeraldedhia/movie-ratings-and-recommendation-using-knn/input?select=tmdb_5000_credits.csv

Methodology:
1. Data Acquisition and Integration:
To obtain movie data from multiple sources, specifically the TMDB dataset, ensuring a comprehensive and up-to-date collection of movie information, encompassing a wide range of titles, genres, and production details.
To integrate this data into a unified dataset, combining core movie details (title, overview, etc.) with supplementary information such as cast and crew, creating a rich and interconnected foundation for subsequent analysis and feature extraction.

2. Feature Engineering:
To extract relevant features from the movie data, such as genre, cast, and crew information, that contribute to a deeper understanding of movie content and influence user preferences, moving beyond simple title-based recommendations.
To transform these features into a structured format suitable for analysis, such as lists, or numerical representations, enabling the system to effectively discern relationships between movies and identify patterns in user taste.

3. Content Representation:
To transform the extracted features into a format suitable for calculating movie similarity, such as vectorized representations (e.g., using techniques like Count Vectorization), capturing the essential characteristics of each movie's content in a quantitative and comparable manner.

4. Similarity Assessment:
To quantify the similarity between movies based on their content, employing appropriate metrics such as cosine similarity, to identify movies with shared attributes and determine the degree of resemblance between them.

5. Recommendation Generation:
To recommend movies to users based on their similarity to other movies, leveraging the calculated similarity scores to suggest titles that align with their preferences and viewing history.

6. Evaluation:
To assess the quality and performance of the movie recommendations, employing appropriate metrics such as precision, recall, and F1-score, to objectively measure the system's accuracy and effectiveness in delivering relevant suggestions.
