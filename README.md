# Content based and collaborative filtering recommender systems for Google Play applications

A recommender system is simply a tool that implements machine learning algorithms in order to give users accurate recommendations and help them find items that they will be interested in. In this case, the recommender system recommends applications that the user might find fun, useful or helpful.

A common architecture for building recommender systems follows these three stages:

1. Candidate generation
2. Scoring
3. Re-ranking

This project mainly focuses on the first stage of recommender system, i.e., candidate generation.

Candidates can be generated using two main approaches: **content-based filtering** and **collaborative filtering**.

Content-based filtering uses similarity between items to recommend other similar items to the ones the user liked.

On the other hand, collaborative filtering uses both similarities between items and similarities between users to recommend items.

In this project, you will find implementations of both strategies.

The dataset used by the recommender system can be found [here](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps). It contains metadata about approximately 2.3 million applications on Google Store.

> Disclaimer: In this project, I'm only using a subset of the whole dataset.
