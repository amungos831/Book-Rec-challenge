Book_Recommendation_Engine-KNN_fcc

This project demonstrates how to build a book recommendation algorithm using K-Nearest Neighbors.
The Book-Crossings dataset is used, featuring 1.1 million user ratings (on a scale of 1-10) for 270,000 books from 90,000 users. The dataset is preloaded in the notebook, so no extra download is necessary.

The goal is to use the NearestNeighbors class from sklearn.neighbors to construct a model that suggests books similar to a provided title. Nearest Neighbors works by measuring distance to determine how “close” two instances are.

You are required to implement a function called get_recommends, which takes a book title (present in the dataset) as input and returns a list of five similar books with their distances to the given title.
To ensure reliability, filter the dataset to include only users with at least 200 ratings and books with at least 100 ratings.
