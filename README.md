# Recommendation_Engine_Movielenz_dataset

## Personalized movie recommendation based on user's historical behavior

A recommendation systems is a machine learning algorithm that helps recommend new products or services to the users. In order to do this, the historical behavior of the user is collected and analyzed. Recommender systems are widely used today. Generating a playlist, a platform suggesting the next move to watch or next item to purchase are all part of this information filtering system.
In this particular project, we aim to understand the content consumed by the users and the ratings provided by them to develop a sophisticate model that will recommend the next set of content that the user could potentially consume.

## Dataset Description:
For this project, we will be using the MovieLense dataset from Kaggle
(https://www.kaggle.com/grouplens/movielens-20m-dataset)
This dataset contains 20 million movie rating and tagging activies from 1995. These activities span across more than 7800 users. The data spans from January 09 1995 to March 31 2015 and was generated as of October 17 2016. Users in this dataset were selected at random, with each selected user having at least 20 ratings.
Keeping in mind this specific project, this dataset will further be contain only a subset of these users. The dataset contains five different tables which were merged to form a master dataset.
Dataset 1: Tag - This contains the tags applied to the movies by the users. Dataset 2: Ratings - This contains the ratings of the movies by the users. Dataset 3: Movies - This contains information about the movie itself, such as the movie title and genres Dataset 4: Link - This contains the mapping information of the various identifies. Dataset 5: Genome Scores - This contains the relevance of the tags applied by the users. Dataset 6: Genome Tags - This contains the tag names and tag IDs.
The primary focus of this project will be using Dataset 1, Dataset 2 and Dataset 3
## Recommendation Systems Overview:
Information filteing, for recommendation specifically have multiple approaches to choose from. The most relevant approaches for this project are 
(A) Collaborative filtering and (B) Content-based filtering.

### (A) Collaborative filtering:
Collaborative filtering is an algorithms which aims to find similar users or items and multiple ways to calculate rating based on ratings of similar users. Depending on the choices you make, you end up with a type of collaborative filtering approach.For this project, we have used item based filtering techniques.
### (B) Content filtering:
Content-based filtering uses features or parts of the content consumed to recommend other items similar to what the user likes, based on their previous ratings. For this project, we have used genere as the base for the content filtering
