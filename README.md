# Overview of Analysis:
This Analysis helps to create an algorithm using Machine learning and neural networks to predict whether applicants will be successful if funded by fictionla non-profit foundation, Alphabet Soup.

# Results
## Data Processing:
- What variable(s) are the target(s) for your model?
    IS_SUCCESSFUL
- What variable(s) are the features for your model?
    APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE,ORGANIZATION,STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
- What variable(s) should be removed from the input data because they are neither targets nor features?
    EIN, NAME

## Compiling, Training, and Evaluating the Model
The model was required to achieve a target predictive accuracy higher than 75%. I made three official attempts using machine learning and neural networks. I manage to achive 73% accuracy after these attemps, which is slightly less than required target accuracy.

- ATTEMPT 1

The first attempt resulted in an accuracy score of 73.7%. This was the highest accuracy score of the three models. This means that 73.7% of the model’s predicted values align with the dataset’s true values.

The hyperparameters used were:
layers = 2
layer1 = 9 neurons : activation function = ‘relu’
layer2 = 18 neurons : activation function = ‘relu'
epochs = 100

- ATTEMPT 2

The second attempt resulted in an accuracy score of 68%.This was the lowest accuracy score of the three models.

The hyperparameters used were:
layers = 3
layer1 = 8 neurons : activation function = ‘relu’
layer2 = 16 neurons : activation function = ‘relu'
layer3 = 24 neurons : activation function = ‘relu'
epochs = 100

- ATTEMPT 3

The second attempt resulted in an accuracy score of 73.2%.

The hyperparameters used were:
layers = 3
layer1 = 12 neurons : activation function = ‘relu’
layer2 = 24 neurons : activation function = ‘relu'
layer3 = 36 neurons : activation function = ‘relu'
epochs = 100

# Summary
In the three attempts I have made, the model was unable to achieve a target predictive accuracy higher than 73.7%. Hypertuning resulted in virtually no improvement. I would consider using another classification model to see if it is better at predicting whether applicants will be successful if funded by Alphabet Soup.