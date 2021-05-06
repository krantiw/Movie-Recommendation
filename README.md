# Movie-Recommendation
Using Correlation and KNN algorithm


1. using Correlation Matrix:
 - Steps to be followed:
- 1. Import the necessary libraries and Loading the datasets
- 2. EDA with visual Represenation
- 3. create a movie matrix using pivot table- userid, movieid and ratings as its values
- 4. Create a function to get the top 10 recommended movies:
-              - Find user ratings using movie matrix
-              - Find the top correlation score of that movie in the movie matrix
-              - Join the number of ratings column
-              - For number of rating > 100 arrange the correlation score in ascending order
-              - return the top movies 10  recommended movies
