# Soccer_Players-rating_Prediction
An interactive project to predict the overall rating of soccer player based on their attributes such as 'crossing', 'finishing etc.

## About the Dataset
###
The dataset used is from European Soccer Database(https://www.kaggle.com/hugomathien/soccer) has more than 25,000 matches and more than
10,000 players for European professional soccer seasons from 2008 to 2016.

###
It contains match statistics (i.e: scores, corners, fouls etc...) as well as the team formations,with player names and a pair of coordinates to indicate their position on the pitch.

### 
It is sourced from EA Sports' FIFA video game series, including the weekly updates Team line up with squad formation (X, Y coordinates) Betting odds from up to 10 providers Detailed match events (goal types, possession, corner, cross, fouls, cards etc...) 

###
The dataset also has a set of about 35 statistics for each player, derived from EA Sports' FIFA video games. It also covers the weekly updates. So for instance if a player has performed poorly over a period of time and his stats get impacted in FIFA, you would normally see the same in the dataset.

## Explanation of the OLS Regression Results :
- Adjusted R-squared indicates that 99.9% of player ratings can be explained by our predictor variable.
- The regression coefficient (coef) represents the change in the dependent variable resulting from a one unit change in the predictor variable, all other variables being held constant.
- In our model, a one unit increase in potential increases the rating by 0.4525.
- The standard error measures the accuracy of potential's coefficient by estimating the variation of the coefficient if the same test were run on a different sample of our population.
- Our standard error,0.001, is low and therefore appears accurate.
- The p-value means the probability of an 0.4525 increasing in player rating due to a one unit increase in potential is 0% , assuming there is no relationship between the two variables.
- A low p-value indicates that the results are statistically significant, that is in general the p-value is less than 0.05.
- The confidence interval is a range within which our coefficient is likely to fall. We can be 95% confident that potentials's coefficient will be within our confidence interval, [0.450,0.455].
