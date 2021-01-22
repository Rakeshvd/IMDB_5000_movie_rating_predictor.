# IMDB_5000_movie_rating_predictor.

Goal: Predicting the imdb rating of a movie.

Feature used are:
1. color
2. director_name	
3. director_facebook_likes
4. actor_1_name
5. actor_1_facebook_likes
6. actor_2_name
7. actor_2_facebook_likes
8. actor_3_name
9. actor_3_facebook_likes
10. cast_total_facebook_likes
11. movie_facebook_likes
12. duration
13. facenumber_in_poster
14. num_user_for_reviews
15. num_critic_for_reviews
16. language
17. country	content_rating
18. budget
19. gross	title_year
20. num_voted_users
21. GENRES

I have used Catboost(Categorical boosting) to biuld model.

This is a very useful package ,it is mainly used to handle categorical variables automatically.

more info: *https://catboost.ai/

How does Catboost handle categorical variables: 

*https://catboost.ai/docs/features/categorical-features.html

*https://catboost.ai/docs/concepts/algorithm-main-stages_cat-to-numberic.html

IMDB_500.ipynb - Contains EDA and how training and testing data is split.

main_code.ipynb - contains the main model.




