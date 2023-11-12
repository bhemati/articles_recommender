# Recommender Systems in Python

This notebook introduces Recommender Systems from the practical point of view by implementing examples of them in Python.
The main filtering techniques which are Popularity Filtering, Content-Based Filtering, Collaborative Filtering and Hybrid Filtering are illustrated with examples. Their performance is also tested and compared.


A dataset about user posts and comments in CI&T Deskdrop platform is utilized for the examples.
This dataset is shared in Kaggle and can be downloaded from https://www.kaggle.com/gspmoreira/articles-sharing-reading-from-cit-deskdrop.
The data consist of logs in a time period of 12 months CI&T's Internal Communication platform. There are about 73000 logged user interactions on 3000 public articles shared in the platform. 
The two main data structures are the shared articles and the user interactions with those articles. The latter can be View, Like, Comment, Follow, Bookmark.
