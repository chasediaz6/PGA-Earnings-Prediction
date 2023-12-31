## **Predicting PGA Season Earnings**

![PGA Earnings](imgs/ESPN_datasource.png)

### Overview

The goal of this project was to build a model that will predict a PGA player's season earnings based on their overall statistics. Using stats such as average score, putts per hole, average driving distance, and age, I trained and tuned an XGBoost model to predict earnings based on data from the 2022 and 2023 PGA seasons. Through data analysis, I was able to determine the relationship between each feature against earnings. My model was able to predict all qualifying players earnings within a root mean squared error (RMSE) of $1.8 million. I find these results successful, as the earnings for each player ranged from $115,000 to $21 million, and the margin in performance between each player is very small. These are the best golfers in the world, and the margin of error between hundreds of thousands of dollars in winnings at each tournament over the course of a year is extremely small, coming down to a few putts, or missing a couple fairways. The ability for the model to project earnings accurately allows players to gauge their performance, and understand which areas they will need to increase their performance in order to increase their yearly winnings. I was also able to inperpret the model, and make sense of which features and values have the highest predictive power in predicting earnings. The data for this project was collected from [ESPN](https://www.espn.com/golf/stats/player)

![PGA Earnings](imgs/shap_values.png)
