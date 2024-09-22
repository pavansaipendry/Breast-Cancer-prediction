# Breast-Cancer-prediction using Linear Regression
#### Project Overview
This project involves building a logistic regression model to classify breast cancer tumors as malignant or benign. The data used comes from the Breast Cancer Wisconsin dataset, available from the sklearn.datasets library.

#### Files in the Repository:
- `project.ipynb`: Jupyter notebook containing the full data preprocessing, model training, and evaluation pipeline.
#### Key Steps in the Project:
- Data Loading: The Breast Cancer dataset is loaded using `load_breast_cancer`.
- Preprocessing: Features are standardized using `StandardScaler`.
- Model Training: A logistic regression model is trained using the `LogisticRegression` class from sklearn.
- Model Evaluation: The model is evaluated using `accuracy_scores` and `confusion matrices`.

#### Model Evaluation Result:
Here are the accuracy and other parameters for the model:
- Accuracy: 98.25%
- Precision: 99.06%
- Recall: 98.15%
- F1 Score: 98.60%
