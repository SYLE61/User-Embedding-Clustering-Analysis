# User-Embedding-Clustering-Analysis

## Project Overview
This project analyzes user interactions with locations (places) by leveraging embedding vectors. It includes the following functionalities:

* Data Integration and Preprocessing: Merges user and place data from multiple CSV files and processes embedding vectors for analysis.
* Personalized User Embeddings: Generates weighted user embeddings based on their interactions ("fav", "visited", "dislike", "want to try") with various locations.
* Dimensionality Reduction: Applies PCA (Principal Component Analysis) and t-SNE for dimensionality reduction to visualize data clearly.
* User Similarity Analysis: Computes cosine similarity between users based on embeddings, identifying similar user profiles based on interaction patterns.
* Clustering Analysis: Uses Gaussian Mixture Models (GMM) on t-SNE reduced data to segment users into meaningful clusters, facilitating targeted analysis or recommendations.

## Technologies used:
* Python (pandas, NumPy, scikit-learn, matplotlib, seaborn)
* PCA, t-SNE for dimensionality reduction
* Gaussian Mixture Model (GMM) for clustering
* Cosine similarity for user profiling and comparison
