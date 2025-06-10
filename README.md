# RECOMMENDATION-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: CHENNAREDDY HARI KARTHIKEYA

*INTERN ID*: CT06DL832

*DOMAIN*: MACHINE LEARNING

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

DESCRIPTION:

A Recommendation System is a type of software that suggests items to users based on their preferences,behaviour and history. The main goal of the recommendation system is to help users to dicover items they like most.

There are three types of Recommendation system:
1. Content Based filtering:

   It recommends items similar to user which he liked in past based on some features like recentchase history,music genre etc..

2. Collaborative Filtering:

   It recommends items based on the other similar users it does not need any type of features for recommending.\

3. Hybrid Systems:

   This systems combines both content-based and collaborative filtering. It is mostly used recommendation system mostly used in Netflix, Amazon for more accuracy.

Importance of Recommendation System:

1.Improves user experience

2.Increases Engagement

3.Drives revenue to the company.

The recommendation system uses Collaborative Filtering, Matrix Factorization and Cosine similarity. The collaborative filtering is based on user to user similarity. The Matrix factorization reduces the 

dimensionality using SVD and the cosine similarity is to find similar users.

Methods, Functions and libraries used in this recommendation system are:

1.pandas is used for data manipulation and data analysis.

2.numpy is used for numerical computing 

3.sklearn is a powerfull machine learning python library used for data preprocessing, model training and evaluation..

sklearn.decomposition is used for dimensionality reduction and feature extraction it contains PCA,TruncatedSVD,Factor Analysis..

sklearn.metrics.pairwise is used to evaluate pairwise diatance or affinity of sets of samples, this module contains both distance metrics and kernels.

Frist Step is to create a user-item matrix in this ratings.piviot_table is used to tranforms the dataframe into a matrix and .fillna(0) is used to fill all the missing values.

Second Step is to apply TruncatedSVD for Matrix Factorization.

Third Step is to compute cosine similarity it measures the angle between two user matrices.

Fourth Step is to convert the Similarity matrix to a Dataframe.

Next is a function to get top n similar users.

Next is a function to recommend movies to the similar users.

The final step is taking user input and displaying recommendations.

