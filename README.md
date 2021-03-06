# NBA2k-Overall-Algorithm
# What It Is
NBA 2K is a basketball video game. Each player in video game has a rating that corresponds to how good (or bad) the player is. In order to try and figure out exactly how the developers of the video game conceived the algorithm for the rating system, I built a Machine Learning model to predict a player's rating in the NBA 2K21 video game based on their performance in real life.

# What I Used
This Algorithm uses the Machine Learning model Random Forest Regression to estimate a NBA player's overall in the NBA 2K video game

I used Random Forest Regression as the necessity for extrapolation was extremely minimal (if not non-existent) in this problem

Through tweaking the amount of features in my model, I uncovered a set of 24 NBA statistics that can be used to closely estimate a player's Rating in the 2K video game

# Accuracy and Errors
Using simple random sampling of the 2020-2021 Rookie Class (ie: randomly sampling players that have never been analzyed in the 4 years of data in my training set), I determined that my algorithim predicts an accurate player overall with an average percent error of 2.57% and a Mean Squared Error of around 4 overall points.

The explanation of my error can be attributed to two main explanations. Firstly, the error can be attributted to the efficiency of the model I used. I can solve this through trial and error by experimenting with various models. The error can also be attributed due to possible non-statistical reasonings behind a player's 2K overall. For example, a player's work-ethic and leadership qualities may effect a player's overall, and the scope of this model does not account for these kind of the attributes

# Future Of The Project
In the future, I plan to continue to test new models in order to further improve the efficiency of my data set. I also plan to test the current accuracy of my model through a larger test set
