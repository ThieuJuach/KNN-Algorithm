MY comments on the function to train and evaluate the model and the output of the code:

output
Evaluating 80% training and 20% testing split:

X_train shape: (1437, 64)

y_train shape: (1437,)

X_test shape: (360, 64)

Training data percentage: 79.97%

Comment:
This model has very high accuracy.
The larger training set size allows the model to learn more patterns and variations in the data, contributing to its high performance.

output
Evaluating 50% training and 50% testing split:

X_train shape: (898, 64)

y_train shape: (898,)

X_test shape: (899, 64)

Training data percentage: 49.97%

Comment:
The accuracy is slightly lower compared to the 80/20 split, but still very high.
With equal training and testing data, the model has less training data to learn from, but it still maintains good accuracy.

output
Evaluating 30% training and 70% testing split:

X_train shape: (539, 64)

y_train shape: (539,)

X_test shape: (1258, 64)

Training data percentage: 29.99%

Comment:
The accuracy is slightly lower compared to the 80/20 split, but still very high.
With equal training and testing data, the model has less training data to learn from, but it still maintains good accuracy.

