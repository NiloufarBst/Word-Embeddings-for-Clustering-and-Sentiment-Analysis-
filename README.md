# Word-Embeddings-for-Clustering-and-Sentiment-Analysis-
Word Embeddings & Sentiment Analysis — AI534 Assignment 4
This project explores the use of pre-trained GloVe word embeddings for unsupervised learning and sentiment classification tasks using Twitter data.

Part 1: Explore Word Embeddings
Seed Words: flight, good, terrible, help, and late

Tasks:
Found 29 most similar words per seed using Euclidean distance
Applied PCA and t-SNE for dimensionality reduction and visualization
Used K-Means Clustering with k ranging from 2 to 20
Evaluated clustering with Purity, Adjusted Rand Index, and Normalized Mutual Information

Part 2: Improve Sentiment Classification
Dataset: Tweets labeled with sentiment (from IA3)
Objective: Enhance the bag-of-words representation using GloVe embeddings

 Methods:
Weighted average of word embeddings
Bag-of-word-clusters from clustered vocabulary
Extended vocab matching (e.g., stemming, token splitting)

Evaluation: Compared classification performance on validation set (focus on exploration, not just accuracy)

Tools & Libraries
Python, scikit-learn, matplotlib, gensim, GloVe embeddings

 
