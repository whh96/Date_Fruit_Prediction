# Date_Fruit_Prediction

## This project utilizes data visualization techniques, label encoding, logistic regression, and hyperparameter tuning to accurately predict the species of a date fruit.

Using label encoding and z-scores, I was able to isolate and remove the values that had potential to interrupt the efficiency of my machine learning model which is required step when dealing with an abundance of outlying information. Appropriate scaling methods were then implemented to accurately normalize the data before processing. 

After the data has been efficiently preprocessed, I then trained a rudimentary Logistic Regression model which was able to identify the correct species with an accuracy of 87%. Improvement is possible so I utilized a 3-fold cross validation grid search technique to tune the appropriate hyper parameters. With these new parameters, I was able to increase the accuracy to 92%. 

Out of curiosity, I tested my model against other classification techniques but the initial choice of Logistic Regression proved to be the best choice.
