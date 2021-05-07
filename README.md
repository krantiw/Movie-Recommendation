# Movie-Recommendation Using Correlation 

link to my blog on https://krantiwadmare10.medium.com/with-the-rise-in-the-ott-platforms-during-the-covid-19-lockdown-the-recommendation-systems-have-1a8759a56665
1. using Correlation Matrix:
Libraries required
- numpy
- pandas
- matplotlib
- seaborn

 - Steps to be followed:
- 1. Import the necessary libraries and Loading the datasets
- 2. EDA with visual Represenation
- 3. create a movie matrix using pivot table- userid, movieid and ratings as its values
- 4. Create a function to get the top 10 recommended movies:
              - Find user ratings using movie matrix
              - Find the top correlation score of that movie in the movie matrix
              - Join the number of ratings column
              - For number of rating > 100 arrange the correlation score in ascending order
              - return the top movies 10  recommended movies

- The dataset can be downloaded from : https://www.kaggle.com/ayushimishra2809/movielens-dataset
