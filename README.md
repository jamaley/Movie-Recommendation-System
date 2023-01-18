# Movie-Recommendation-System
Movie Recommendation System with Cosine Similarity and tfidf


```
print("recommendation for Pirates of the Caribbean [Movie]: At World's End : ")
print(recommend("Pirates of the Caribbean: At World's End"))

# Output

recommendation for Pirates of the Caribbean [Movie]: At World's End : 
12             Pirates of the Caribbean: Dead Man's Chest
199     Pirates of the Caribbean: The Curse of the Bla...
340                                      Cutthroat Island
2556                                   The Princess Bride
1331                                         Nim's Island

```

The following is an example of a movie recommendation system that uses cosine similarity and TF-IDF (term frequency-inverse document frequency) in the implementation.

# Introduction

A movie recommendation system is a tool that suggests movies to users based on their preferences. In this example, we will use a dataset of movie titles and their descriptions to recommend movies to a user based on the titles and descriptions of movies they have previously watched.

# Implementation

Data Preprocessing: The first step is to preprocess the data. In this case, we will be using a dataset of movie titles and descriptions. We will clean and tokenize the data, removing any stop words and punctuation.

* TF-IDF: The next step is to calculate the TF-IDF values for each word in the dataset. This will give us a numerical representation of the importance of each word in the dataset.

* Cosine Similarity: Once we have calculated the TF-IDF values, we can then calculate the cosine similarity between the movies in the dataset. Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space that measures the cosine of the angle between them.

* Recommendation: Finally, we can use the cosine similarity scores to recommend movies to the user. For example, we can recommend movies that have the highest cosine similarity scores to the movies that the user has previously watched.

# Conclusion

In this example, shown simple and basic way, how to use cosine similarity and TF-IDF to create a movie recommendation system. This approach can be used to recommend movies to users based on the titles and descriptions of movies they have previously watched. With this approach, we can recommend movies that are most similar to the user's previous choices, increasing the chances of the user enjoying the recommended movies.
