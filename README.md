# Podcast-Category-Clustering-Using-Advanced-Embedding-Models
Podcast Category Clustering Using Advanced Embedding Models

## Overview
This project explores the clustering of podcast categories using state-of-the-art embedding models like BERT, RoBERTa, and Sentence Transformers. The embeddings generated from podcast category descriptions are reduced in dimensionality using techniques like UMAP or PCA and then clustered using algorithms like KMeans or DBSCAN. The results are visualized to provide insights into how podcast categories are grouped.

## Dataset
The dataset used in this project contains podcast metadata, including RSS links, categories, and descriptions. The data is preprocessed to extract meaningful information and filter out invalid entries.

## Key Steps
1. **Data Extraction**: Extract podcast metadata from RSS feeds.
2. **Text Embedding**: Generate embeddings using advanced models like BERT, RoBERTa, and Sentence Transformers.
3. **Dimensionality Reduction**: Reduce the dimensionality of embeddings using UMAP or PCA.
4. **Clustering**: Cluster the reduced embeddings using KMeans or DBSCAN.
5. **Visualization**: Visualize the clusters to analyze the grouping of podcast categories.

## Dependencies
To run this project, you need the following libraries:
- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `transformers`: For loading pre-trained embedding models.
- `sentence-transformers`: For generating sentence embeddings.
- `umap-learn`: For dimensionality reduction.
- `sklearn`: For clustering and evaluation metrics.
- `matplotlib` and `seaborn`: For visualization.

Install the required libraries using:
```bash
pip install pandas numpy transformers sentence-transformers umap-learn scikit-learn matplotlib seaborn
