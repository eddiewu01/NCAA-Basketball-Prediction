# NCAA-Basketball-Prediction

## Overview

Our team is building a classification model that can accurately predict the outcome of matchups in the march madness tournament, and at the same time we are investigating the impact of game statistics on the matchup outcomes. In total of nine classifiers are trained and tested using the regular season per-game data as the training set and the tournament per-game data as the testing set, and we have chosen Adaboost and Logistic Regression due to their high classification accuracies (94.2% and 97.2%), high F1 score (0.942 and 0.9721) and excellent performance on their learning curves without signs of overfitting. In addition, we
have found that teams in the regular season with higher number of assists or defensive rebounds are more likely to win the game, and those with lower number of turnovers hardly
lose the matchup. It is also shown that teams with higher number of steals & blocks in the tournament have greater probabilities to win any tournament matchup, according to our final models.

## Structure

#### NCAA_Predictions_And_Insights.ipynb
This jupyter notebook file contains all the steps for building this model, from preparation of data to testing the model on 2017 march madness matchups. 

#### Reports
This folder contains the proposal and final report of this project.

#### Data
This folder contains the initial unprocessed csv files downloaded from https://www.kaggle.com/c/march-machine-learning-mania-2017/data# as well as https://www.sports-reference.com/cbb/seasons/2018-school-stats.html

#### Plots
This folder contains some of the useful plots our team generated in NCAA_Predictions_And_Insights.ipynb (see above), for example, one can see the data visualization of turnover comparision between winning and losing teams.

#### Intermediate_notebooks
This folder contains some of the other notebooks our team used during the process of developing the classifier. 