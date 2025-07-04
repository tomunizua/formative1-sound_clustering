# Sound Dataset Clustering – ML Techniques II Assignment

This repository contains the implementation of clustering techniques on an unlabeled sound dataset. The goal was to explore feature extraction, dimensionality reduction, and clustering performance using both K-Means and DBSCAN.

## Contents
- `Sound_Clustering_Assignment.ipynb` – Main Jupyter notebook with code, visualizations, and analysis
- `hmm_capstone_writeup.pdf` – A one-page document explaining how a Hidden Markov Model could be used in my capstone idea
- `unlabelled_sounds/` – Dataset ZIP folder containing all the audio files

## Key Concepts Covered
- Mel Spectrogram feature extraction using `librosa`
- Dimensionality reduction via **PCA** and **t-SNE**
- Clustering with **K-Means** (optimized via Elbow Method & Silhouette Score) and **DBSCAN**
- Evaluation using **Silhouette Score** and **Davies-Bouldin Index**
- Interpretability of clustering and the role of dimensionality reduction
