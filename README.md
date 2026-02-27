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

## Technologies Used

**Languages & Libraries**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

**Visualization**
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

**Environment**
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=flat&logo=anaconda&logoColor=white)

### Models Implemented:

* Logistic Regression

* K-Nearest Neighbors (KNN)

* Random Forest

* Gradient Boosting

* Voting Classifier (Ensemble)

### Model Evaluation Metrics: 

Accuracy, Recall, Precision, F1-Score, Confusion Matrix

### Development Environment:

Jupyter Notebook / Anaconda

## Conclusion

The Random Forest classifier provides the best balance between recall and accuracy, making it the recommended model for deployment in NovaGen Research Labs' workflow.

## Future Improvements

Hyperparameter tuning for further performance gains

Testing additional ensemble models

Deployment pipeline integration