# Anime-Recomender-System
I like anime, this is a Machine Learning model: collaborative filtering type RecomenderNet neural network based anime recommendation system.

what it basically does?
there is a bunch of data on kaggle "https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020"

Clean data, join with multiple csv files and preprocess it, analyse it, do feature extraction, scale the features, feature embedding. Built the RecommenderNet neural network which uses cosine similarity between the X features to calculate the closeness between feature vectors in vector space train the model set the callbacks, optimizer, learning rate, run the model save the weights, use the weights to recommend the anime

simple!!

RecommenderNet architecture:

![image](https://github.com/MrVersatile007/Anime-Recomender-System/assets/96414851/82d047a0-b01a-4892-ba14-78b0128c1bf7)
