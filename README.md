# Traffic Volume Prediction Model
A Python-based machine learning model that utilizes basic algorithms like RandomForest regressor, linear regression, and KNN regressor to try to predict the traffic volume on a given day and time. 

I got the data from the UCI Machine Learning Repository, which was quite clean, had no missing values and had all the labels. I decided to work on getting useful information from the DateTime column, by splitting each value into a separate column. For example, the day, such as Monday or Tuesday, had a separate column as we anticipated that weekdays would have more traffic due to people commuting to work. Similarly, the time of the day also played an important role in determining the traffic volume as morning hours, such as 8 am or 9 am, would be the usual times commuters go to their workplace. Also, we suspected holidays would play a role in determining the traffic volume and decided to use OneHotEncoder to create dummy variables. 

We got the accuracy scores for each model and determined that based on the scores, RandomForest regressor had the lowest error and hence the best accuracy. 
