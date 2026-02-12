## NovaGen-Research-Lab-Data

This project focuses on building and evaluating multiple machine learning classification models to identify the best-performing algorithm for NovaGen Research Labs' predictive tasks


## Models Evaluated

The following classification models were trained and compared:

* Logistic Regression

* K-Nearest Neighbors (KNN)

* Random Forest

* Gradient Boosting

* Voting Classifier (Ensemble)

* Model Selection Criteria

Model performance was evaluated using standard metrics, with Recall chosen as the primary evaluation metric since minimizing false negatives is critical for the NovaGen application.

## Final Model Selection

Based on recall performance and overall evaluation:

Random Forest emerged as the best-performing model.

Accuracy: 93.7%

Strong recall performance

Robust and stable predictions compared to other models

## Conclusion

The Random Forest classifier provides the best balance between recall and accuracy, making it the recommended model for deployment in NovaGen Research Labs' workflow.

## Future Improvements

Hyperparameter tuning for further performance gains

Testing additional ensemble models

Deployment pipeline integration