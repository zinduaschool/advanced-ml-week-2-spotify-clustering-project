## Spotify Music Clustering Project

### Project Description

Music streaming platforms like Spotify generate vast amounts of data related to song characteristics, user preferences, and listening habits. Understanding patterns in this data can help in tasks such as music recommendation, playlist generation, and genre discovery. In this project you are to focus on using clustering techniques to group songs based on their audio features, uncovering hidden structures in the dataset. By analyzing these clusters, one can gain insights into different music styles and potentially enhance recommendation systems.

If this is something you would like to work on the project instructions, the data and the starter notebook may be found in this GitHub repository:

### Dataset

The dataset to be used in this project is supposed to be obtained from the Spotify Platform, once you obtain the Developer API Key. Alternatively, if you are not able to connect to Spotify, you can use [this data](https://wagon-public-datasets.s3.amazonaws.com/Machine%20Learning%20Datasets/ML_spotify_data.csv). Ideally, the dataset should contain various audio features for songs, including:

- Acousticness: A measure of acoustic sound in a track

- Danceability: How suitable a track is for dancing

- Energy: Intensity and activity level of a song

- Instrumentalness: The presence of vocals in a track

- Liveness: Detects the presence of a live audience

- Loudness: The overall loudness of a track

- Speechiness: The presence of spoken words in a track

- Tempo: The beats per minute (BPM) of a song

- Valence: The musical positiveness of a track

The dataset may require preprocessing steps such as handling missing values, normalizing features, and removing duplicates before applying clustering models.

### Models

To perform clustering, experiment with the following unsupervised learning algorithms:

- K-Means Clustering: A centroid-based clustering algorithm that partitions data into k groups based on similarity.

- Hierarchical Clustering: A tree-based clustering method that groups songs into a hierarchy.

- DBSCAN (Density-Based Spatial Clustering of Applications with Noise): A density-based algorithm useful for identifying clusters of varying shapes and sizes while filtering out noise.

- Gaussian Mixture Model (GMM): A probabilistic clustering method that assumes the data is generated from multiple Gaussian distributions.

Dimensionality reduction techniques such as Principal Component Analysis (PCA) may be used to visualize high-dimensional data and improve clustering performance.

### Model Evaluation

Evaluating clustering models is challenging as there are no ground truth labels. You will use the following metrics and techniques:

- Elbow Method & Silhouette Score (for K-Means): To determine the optimal number of clusters.

- Dendrogram Analysis (for Hierarchical Clustering): To analyze the hierarchy of clusters.

- Cluster Distribution & Interpretability: Analyzing cluster characteristics to ensure meaningful segmentation.

- Visualization: Using t-SNE and PCA to visualize the clusters in 2D space.

***Remember to document your process, explain your decisions, and present your results effectively. Good luck with your project!**
