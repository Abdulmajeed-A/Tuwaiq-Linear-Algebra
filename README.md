# Tuwaiq-Linear-Algebra
Unit 2 Project: Linear algebra / Group 5 / Eigenvalues &amp; Eigenvectors in AI

Spotify Data Analysis
Project Overview:
This project demonstrates how eigenvalues and eigenvectors are applied in AI and data analysis, using Spotify song features as a practical example.

The main goals are:
Eigenvalues & Eigenvectors Fundamentals:
Explored AX = λX for 2×2 matrices.
Calculated characteristic equations, eigenvalues (λ), and corresponding eigenvectors.
Showed how diagonalization reconstructs matrices using P D P⁻¹.
Applying PCA on Spotify Data:
PCA uses eigenvalues and eigenvectors of the covariance matrix to reduce dimensions.
Reduced 10 audio features into 5 principal components capturing ~81% variance.
Loadings show the contribution (positive/negative) of each feature to each principal component.
Clustering Songs Using PCA Components:
KMeans applied on PCA-reduced data to group songs into 5 clusters.
Visualized clusters along PC1 and PC2.
Eigenvectors (PC loadings) help interpret cluster characteristics.
Dataset
Source: Spotify Tracks Dataset
Shape: 114,000 songs × 10 selected features
Features Used: danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms
Key Concepts

1️⃣ Eigenvalues (λ)

Measure variance explained along a direction (eigenvector).
Higher λ → more important direction in the data.

2️⃣ Eigenvectors (X)

Define directions in the feature space.
PCA uses them as principal components to project data.

3️⃣ PCA Connection

Covariance matrix → eigenvectors give PC directions
Eigenvalues → variance explained per PC
Loadings tell which features increase or decrease each PC
Results & Insights
Eigenvalues of covariance matrix show which directions (PCs) carry most variance.
Eigenvectors (loadings) reveal relationships between song features.
PCA + KMeans clusters show meaningful groupings of similar songs.
.

References

Spotify Tracks Dataset

[https://www.kaggle.com/datasets/yashdev01/spotify-tracks-dataset]

https://malabdali.com/wp-content/uploads/2023/10/Abdi-EVD2007-pretty.pdf

https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors

https://www.geeksforgeeks.org/engineering-mathematics/eigen-values/

https://towardsdatascience.com/eigenvalues-and-eigenvectors-378e851bf372/

https://byjus.com/jee/eigenvalues-and-eigenvectors-problems-and-solutions/

