# Music Recommendation and Analysis System

This project implements a **music recommendation and analysis system** using a Spotify dataset. The system includes steps for data preprocessing, feature scaling, clustering, dimensionality reduction, visualization, and generating song recommendations. Below is a detailed explanation of the project's structure and functionality.

## Overview
The main goal of this project is to cluster songs based on their attributes and recommend similar songs to users. The dataset used contains information about songs, genres, and attributes such as tempo, energy, loudness, and more. 

Key features:
- **Clustering**: Groups songs with similar characteristics using K-Means.
- **Visualization**: Displays song clusters using PCA and t-SNE.
- **Recommendation**: Suggests songs based on similarity to user-provided input.
- **Clustering Evaluation**: Assesses the quality of the clustering.

## Dataset
The project uses a Spotify dataset containing the following files:
- `data.csv`: Main dataset with individual song attributes.
- `data_by_genres.csv`: Dataset aggregated by genres.
- `data_by_year.csv`: Dataset aggregated by year.

## Technologies Used
The following technologies and libraries were utilized in this project:
- **Python**: The programming language used for implementation.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For advanced data visualizations.
- **Plotly**: For interactive visualizations.
- **scikit-learn**: For clustering, scaling, PCA, and evaluation metrics.
- **t-SNE**: For non-linear dimensionality reduction.
- **StandardScaler**: For feature scaling to normalize the data.
- **K-Means**: For clustering songs based on attributes.

## Usage
1. Run the project step-by-step in a Jupyter Notebook or Python script.
2. Provide a song name to the `recommend_songs` function to get recommendations.
3. Visualize clusters using the provided plotting code.

## Results
- **Clustering**: Songs are grouped into clusters based on their audio features.
- **Visualization**: Clear cluster separation is visible in 2D PCA and t-SNE plots.
- **Recommendation**: Songs similar to a given input are successfully recommended.
- **Evaluation**: The silhouette score indicates the quality of clustering.

## Future Work
- Extend the recommendation system to use more advanced techniques like deep learning.
- Implement additional visualizations to explore data trends.
- Integrate this system with a user interface for broader usability.
