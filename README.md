
# Decision Tree Classfier Algorithm

Problem Statement: Based on the given features we need to find out whether an employee will leave the company or not. (Attrition Problem)



## Overview
Created preprocessing pipeline and transformed thode data according to the requirement.And then we applied Decision tree. We predicted the outpul and also validate the output. Accuracy was coming less so we applied Hyperparameter tuning. Applied different parameters for Decision Tree. We used grid search Cv in order to tune the model according to the best hyperparameters we get. 

## Documentation
1. Loaded the required libraries.
2. loaded the dataset adn performed basic checks
3. Did auto EDA using ydata_profiling.
4. Also manually check correlation of the features and find out 2 columns are highly correlated, so droped one of them.
5. Built Preprocessing pipeline and dump it in a pickle file.

## D.T. Implimentation
1. Splitted the data into train and test.
2. Loaded the Preprocessor and Transform the training data using the preprocessor object or PipeLine.
3. Applying DecisionTree Model from Sklearn.
4. For validating the model, Transform the testing data using the preprocessor object or PipeLine and Predicted outcome from the model.
5. Checked the Accuracy Score and F1 Score.
6. Used Hyperparameter Tunning of DicisionTree
7. Passed model to GridSearchCV and got best parameters from cv using best_params_
8. Again passed best parameter to decision tree and trained model with best parameter.
9. Observed the Accuracy Score and F1 Score Improved.
## Conclusion
After we trained our model for best hyperparameters which we have got after hyperparameter tuning, we saw that the Accuracy has improved.
