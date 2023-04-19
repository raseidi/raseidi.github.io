---
layout: post
---

# Survey on graph databases for similarity-based retrieval

Graph methods have outperformed other ones (e.g. tree and hash methods) in the problem of similarity search in the past few years. However, there are many variations of graph methods in the literature, such as kNN-based or SW-based, and no work before had evaluated important issues regarding scalability and parametrization. Thus, we performed a survey to better understand the differences of behaviors among several algorithms accross several datasets.

![Survey](/assets/img/posts/graph_database/survey.jpg)

In this work, we evaluated the scalability regarding cardinality and dimensionality, query strategies (e.g. exact and approximate), trade-offs between construction and query parameters, and which properties in the datasets affect the most each algorithm and parameters.
You can find the published research [here](https://www.researchgate.net/publication/339488943_A_survey_on_graph-based_methods_for_similarity_searches_in_metric_spaces)

# Automatic Selection of Graph Algorithms and Parameters 

In our previous survey, we concluded that selecting the best graph algorithm is not a trivial task, since each graph configuration might behave differently according to the datasets' characteristics. Thus, we developed a recommender system based on meta-learning to automatically select the best algorithm and its set of parameters (including both index and query parameters).

![AutoSelection](/assets/img/posts/graph_database/rec_sys.jpg)

We used meta-learning techniques to map several datasets' characteristics into the performances achieved by different algorithm configurations. This way, when a new dataset is available, the recommender system is capable of analysing its underlying properties and automatically recommend a suitable algorithm configuration according to the user preferences. For instance, a user has may require a configuration that speeds up the queries without caring about the memory usage; or require the best precision possible with the lower query time possible.
You can find the published research [here](https://www.researchgate.net/publication/363636261_A_Meta-learning_Configuration_Framework_for_Graph-based_Similarity_Search_Indexes)

[back](/)