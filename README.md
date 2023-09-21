# Movie-Recommender-Collaborative-Filtering
In this Jupyter Notebook project, I create three distinct recommendation engines, each with its unique approach and algorithms:

Content-Based Recommender: We developed two content-based recommendation engines. The first leveraged movie overviews and taglines, while the second utilized metadata, including cast, crew, genre, and keywords. To enhance the recommendations, we introduced a filter that prioritizes movies with higher votes and ratings, ensuring more informed suggestions.

Collaborative Filtering: Leveraging the powerful Surprise library, we implemented a collaborative filtering system based on Singular Value Decomposition (SVD). The achieved Root Mean Square Error (RMSE) of less than 1 demonstrated the system's effectiveness in providing estimated ratings for users and movies.

Hybrid Engine: Combining the strengths of both content and collaborative filtering, we crafted a hybrid recommendation engine. This engine offers movie suggestions to users based on internally calculated estimated ratings. It synthesizes insights from both user behavior and content to provide personalized recommendations.

This project represents a holistic exploration of recommendation systems, spanning various methodologies to cater to diverse user preferences and enhance the movie-watching experience. We've delved into content analysis, collaborative user-based approaches, and the fusion of these techniques, setting the stage for more sophisticated and personalized recommendation systems.
