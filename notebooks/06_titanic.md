## Class 8 Exercise: Predicting Survival on the Titanic

This assignment uses data from Kaggle's [Titanic](https://www.kaggle.com/c/titanic/data) competition. `titanic.csv` is in the repo, so there is no need to download the data from the Kaggle website.

**Tasks:**

1. Read `titanic.csv` into a DataFrame.
2. What is the null accuracy rate for predicting survival? (This means the probability of choosing the largest unique category, either survived or not)
3. Can you think of some variables that are in the dataset that might contribute to predicting survival of the crash?
4. Define Pclass and Parch as the features, and Survived as the response.
5. Split the data into training and testing sets. (Hint: use the train test split modules from sklearn)
6. Fit a logistic regression model and examine the coefficients to confirm that they make intuitive sense.
7. Make predictions on the testing set and calculate the accuracy.
8. Create a confusion matrix and document the model's sensitivity and specificity. (remember you should run metrics on your test classes!)




Always remember to cross validate your models when attempting to gaguge predictive power. You may fit on the entire dataset when attempting to select features by looking at model coefficients.