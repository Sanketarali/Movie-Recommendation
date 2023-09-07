
# Movie-Recommendation
A simple movie recommendation system based on content-based filtering using movie genres.

# Prerequisites
Python<br>
Jupyter Notebook<br>
pandas library<br>
scikit-learn library<br>

# Preprocessing
The data is preprocessed to prepare it for the recommendation system. In this example, we use the movie genres for content-based filtering. A TF-IDF vectorizer is used to convert genres into numerical features. This vectorizer helps us represent movies as numerical vectors, making it possible to compute similarity between movies based on their genres.

# Computing Cosine Similarity
The cosine similarity between movies is computed using the TF-IDF vectors. Cosine similarity is a measure of how similar two vectors are and is used to identify movies with similar genre profiles. The resulting similarity matrix helps identify movies with the most similar genres to a given input movie

# Getting Recommendations
A Python function called get_recommendations is defined to get movie recommendations based on similarity. It takes an input movie title and returns a list of recommended movies. Here's how it works:

1.It finds the index of the input movie title in the dataset.
2.If the input movie title is not found, it displays a message indicating that the title was not found in the dataset.
3.If the title is found, it computes the similarity scores between the input movie and all other movies.
4.The movies are sorted by similarity scores in descending order.
5.The top 10 most similar movies (excluding the input movie itself) are returned as recommendations..

# Example
To demonstrate the movie recommendation system, an example is provided where recommendations are generated for the movie "Iron Man." The recommended movies are based on the similarity of their genres to "Iron Man."

![image](https://github.com/Sanketarali/Movie-Recommendation/assets/110754364/5c547642-a60a-4462-850c-bce8163ccfd3)


