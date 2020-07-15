# Machine Learning Homework - Exoplanet Exploration

## Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. Three models were created: Logistic Regression, Decision Tree/Random Forest, and K Nearest Neighbor. 

## Models Explained
### Logistic Regression
- Trained the model on the X_train and y_train scaled which had an output of 0.74 for training data and 0.75 for testing data.
- After using grid search, the best score had an output of 0.79 which is higher than test/train data.

### K Nearest Neighbor
- Using k=7, the test accuracy came back as 0.79. Multiple k numbers were used and tested, but settled on 7 for being higher in accuracy, but lower in complexity.
- After using grid search, the best score had an output of 0.80

### Decision Tree
- The Decision Tree train score came in at 0.94 and test score at 0.77.
- The Random Forest train score came in at 0.99 and test score at 0.82.
- After using grid search, the best score had an output of 0.81

## Conclusion
Of the three models used, the Decision Tree yieled the best score of 0.81 and Logistic Regression had the lowest score. With more tuning to the Decision Tree, I'm confident the best score could be improved by tweaking some of the numbers. 
