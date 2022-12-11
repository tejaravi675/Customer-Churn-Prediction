# Customer-Churn-Prediction

The main aim of the project is to predict whether the person is satisfied with current facilities provided by the bank or exited. ANN are used to train and 
predict the model. Preprocessing steps such as checking for missing values, converting categorical variables are used. 

Once the data is split between training and testing, feature scaling technique is used so as to prevent data leakage. Validation set is used to estimate the 
model's accuracy on predicting new data. Overall, the model performs at 82% training accuracy and 84% testing accuracy.

Important things learnt:
1. Data is highly imbalanced, using sampling technqiues did not work because the skewness of the data is too much. Only way is to gather more 
data to balance the classes.
