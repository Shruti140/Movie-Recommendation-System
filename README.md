# Movie Recommendation System

**Introduction**

This Movie Recommendation System is a content-based recommendation system designed to suggest movies to users based on the similarity of movie content. It utilizes cosine similarity to analyze movie features such as genres, keywords, and actors, providing personalized recommendations to users.

**Features**

* Content-Based Recommendations: Utilizes movie features such as genres, keywords, and actors to suggest similar movies to users.
* Cosine Similarity: Calculates the similarity between movies based on their feature vectors using cosine similarity.
* TMDB 5000 Movies Dataset: Utilizes the TMDB 5000 Movies dataset from Kaggle for movie information.
* Python Implementation: Developed using Python programming language in PyCharm IDE.
* User Interface: Provides a simple command-line interface for users to interact with the recommendation system.

**How It Works**

* Data Preprocessing: Extracts relevant features such as genres, keywords, and actors from the TMDB 5000 Movies dataset.
* Feature Vectorization: Converts the extracted features into numerical vectors using techniques like one-hot encoding or TF-IDF.
* Cosine Similarity Calculation: Calculates the cosine similarity between movies based on their feature vectors.
* Recommendation Generation: Recommends movies to users based on the similarity scores obtained from cosine similarity.
* User Interaction: Users interact with the system by providing movie title as input and receiving personalized recommendations with movie poster.
