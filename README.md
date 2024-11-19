
# Credit Card Fraud Detection

The project aims to develop a machine learning model that predicts whether a credit card transaction is fraudulent. The dataset provided contains transaction details of European cardholders, with a focus on imbalanced data, feature engineering, and model evaluation.



## Objectives
- Build a classification model to predict fraudulent transactions.
- Handle imbalanced data effectively using techniques such as SMOTE.
- Perform feature engineering and preprocessing for better model performance.
- Evaluate and compare multiple machine learning models (Logistic Regression, Decision Tree,Random Forest, Navie Bayes and XGBoost).
- Achieve accuracy greater than 75% through hyperparameter tuning and model validation.
## Dataset
The dataset used in this project is highly imbalanced, with only 0.172% of the transactions being fraudulent. The dataset contains features related to transaction time, amount, and various anonymized features.
## Prerequisites
To run the project locally, you'll need to install the following libraries:

- **Python 3.7+**
- **Jupyter Notebook** for running notebooks
- **Required Python packages** listed in `requirements.txt`


Install the required Python packages

- pip install -r requirements.txt
- Dataset: https://drive.google.com/drive/folders/1j2ua12hztuuRuXR5_cDvfnLWlcMfjGEK?usp=sharing

## Results
The **XGBoost model** achieved an accuracy of 99%, with a significant improvement in detecting fraudulent transactions, although precision for the minority class was lower.
## Conclusion
The project successfully demonstrated how to handle imbalanced data and build a robust machine learning model for predicting fraudulent credit card transactions. The XGBoost model, after hyperparameter tuning, provided the best performance.
## Acknowledgements

 - Thanks to the **UpGrad team** for providing the dataset and project structure.
- This project uses several open-source libraries, including `scikit-learn`, `xgboost`, `imbalanced-learn`, and `matplotlib`.

