# Data_Science_Movie_Recommendation

**CS5304/INFO5304 Data Science in the Wild** - Final Project

We used the dataset “[The Movie Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)” from Kaggle.

In this project, we aim to create a personalized movie recommendation engine that generates accurate movie recommendations to users. We have implemented and analyzed different recommendation algorithms (content-based recommendation and collaborative filtering) and examined their independent performance based on their root-mean-square error (RMSE). From our results, SVD latent factor model for matrix factorization collaborative filtering had the best performance. We combined content-based recommendation and SVD as our final recommendation model to improve the performance. Our recommendation system achieved an RMSE of 0.9029 and it satisfied most of the 10 users we have surveyed.

Our final recommendation system can be found in `hybrid_model.ipynb`.
