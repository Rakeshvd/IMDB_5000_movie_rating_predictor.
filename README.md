# IMDB_5000_movie_rating_predictor.

Goal: Predicting the imdb rating of a movie.

Feature used are:
color
director_name	
director_facebook_likes
actor_1_name
actor_1_facebook_likes
actor_2_name
actor_2_facebook_likes
actor_3_name
actor_3_facebook_likes
cast_total_facebook_likes
movie_facebook_likes
duration
facenumber_in_poster
num_user_for_reviews
num_critic_for_reviews
language
country	content_rating
budget
gross	title_year
num_voted_users
GENRES

I have used Catboost(Categoricl boosting) to biuld model.

This is a very useful package ,it is mainly used to handle categorical variables automatically.

more info: *https://catboost.ai/

How does Catboost handle categorical variables: 
*https://catboost.ai/docs/features/categorical-features.html

*https://catboost.ai/docs/concepts/algorithm-main-stages_cat-to-numberic.html

IMDB_500.ipynb - Contains EDA and how training and testing data is split.

main_code.ipynb - contains the main model.




