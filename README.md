# Human-Activity-Recognition-from-Smartphone-Accelerometer-Data
Using various ML models to classify 6 human activities based on accelerometer data captured over time interval

# Results

## Decision Tree:
Test Accuracy before tuning : 85.54 %

Best hyperparameters: {'criterion': 'gini', 'max_depth': 5, 'min_samples_split': 9}

Test accuracy after tuning : 85.54 %

## Random Forests:
Test Accuracy before tuning : 92.36 %

Best hyperparameters: {'criterion': 'gini', 'max_depth': 16, 'max_features': 'log2',
'n_estimators': 500}

Test accuracy after tuning : 94.06 %

## Naive Bayes:
Test Accuracy before tuning : 77.02 %

Best hyperparameters: {'var_smoothing': 0.1}

Test accuracy after tuning : 82.52 %

## KNN Classifier:
Test Accuracy before tuning : 90.15 %

Best hyperparameters: {'n_neighbors': 16, 'weights': 'distance'}

Test accuracy after tuning : 90.73 %

## SVM Classifier:
Test Accuracy before tuning : 95.04 %

Best hyperparameters: {'C': 10, 'degree': 2, 'gamma': 0.01}

Test accuracy after tuning : 96.19 %


## ANN Classifier:
Test Accuracy before tuning : 94.91 %

Best hyperparameters: {‘activation’ : ‘logistic’, ‘max_iter’ : 100, ‘batch_size’ : 64}

Test accuracy after tuning : 96.06 %

# Conclusion

SVM provides us with the most accurate results in this case, and correctly classifies the movement upto 96% accuracy.