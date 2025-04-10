# Recommender-System
Developed a comprehensive recommender system analyzing over 1.1 million book ratings and 4,803 movie metadata entries, leveraging techniques like TF-IDF, cosine similarity, and collaborative filtering to provide personalized recommendations.


This repository contains a comprehensive Recommender System project that explores multiple approaches to enhance user experience across books and movies datasets. The project is divided into three main components:

Content-Based Movie Recommendation System:

Dataset: Utilized the TMDb 5000 Movies Dataset, containing metadata for 4,803 movies.

Techniques: Employed TF-IDF Vectorization to transform movie overviews into numerical vectors and computed cosine similarities to identify movies with similar storylines or genres.

Outcome: Successfully recommended movies like "Batman Begins" for fans of "The Dark Knight Rises" and "Avengers: Age of Ultron" for fans of "The Avengers."

Popularity-Based Book Recommendation System:

Dataset: Analyzed a dataset of over 271,360 books and 1,149,780 ratings.

Approach: Filtered books with at least 250 ratings and sorted them by average rating to identify widely popular titles.

Outcome: Highlighted books like "Harry Potter and the Prisoner of Azkaban" and "Harry Potter and the Goblet of Fire" as highly recommended.

Collaborative Filtering for Books:

Dataset: Focused on 811 active users who rated more than 200 books and 706 popular books rated by at least 50 users.

Techniques: Constructed an interaction matrix and computed cosine similarities between books based on user behavior.

Outcome: Recommended books like "The Fellowship of the Ring" and "A Wrinkle in Time" for fans of "Harry Potter and the Prisoner of Azkaban."

Key Features:

Data Volume: Managed large datasets with over 1.1 million ratings for books and detailed metadata for movies.

Algorithms Used:

Content-Based Filtering (TF-IDF + Cosine Similarity for movies).

Popularity-Based Filtering (books).

Collaborative Filtering (books).

Impactful Results: Provided personalized recommendations for both books and movies based on user preferences or content features.

Future Enhancements:

Integrate hybrid models combining multiple recommendation techniques.

Explore deep learning models for enhanced performance.

Develop a user interface for interactive recommendations.
