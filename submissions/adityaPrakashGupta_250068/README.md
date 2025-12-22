# Titanic Survival Predictor
#### Made by **Aditya Prakash Gupta**

The project uses logistic regression to predict survival rate of individuals and predict their accuracy.

## Pipeline
- **Cleaning the data and preprocessing it** -> Deleting columns which do not provide any important information to the model and handling null values.
- **Analyzing Data** -> Visualizing and analyzing graphs to get familiar with data.
- **Encoding and Scaling** -> OneHotEncoding the categorical values and scaling the numerical columns makes our data readable for regression model.
- **Training and Testing** -> Training on train data and testing to create accurate predctions.
- **Analyze Efficiency** -> Analyze how good the predictions are.

## Key Prediction Analysis Results
- Overall Accuracy of the model is `94.26%`
- Class 0 (Did not Survive) has better precision,recall and accuracy as compared to class 1 (Survived).

### An Abnormal Observation:
On using linear regression on the model by rounding off the results, we get slightly better accuracy. This happens because most of the people in the model fall under class 0 category. Even though Linear regression is not the correct model to use in classification, an false improvement is seen because of the bias in training data itself.
