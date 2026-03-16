# Credit Score Prediction using Machine Learning

An end-to-end machine learning project that predicts customer credit scores using financial behaviour and credit history data. The project demonstrates the full data science workflow from data cleaning and exploratory analysis to model training, evaluation, and prediction.

---

## Project Overview

Financial institutions rely on credit scores to assess the risk of lending to customers. Accurately predicting credit scores can help support better credit risk management and automated lending decisions.

This project builds a machine learning pipeline to explore financial indicators and predict credit score categories.

---

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab

---
## How to Run

1. Open the notebook in Google Colab
2. Install the required libraries
3. Run the notebook from top to bottom

## Dataset

The dataset contains financial and behavioural attributes used to classify customer credit score categories.


Dataset source: https://www.kaggle.com/datasets/parisrohan/credit-score-classification

---

## Project Workflow

1. Data cleaning and preprocessing
2. Exploratory data analysis (EDA)
3. Feature engineering
4. Model training
5. Model evaluation
6. Final predictions on test data

---

## Models Tested

* Logistic Regression
* Random Forest
* Hist Gradient Boosting

Among the tested models, **Hist Gradient Boosting achieved the best overall performance**.

---

## Model Performance

Example comparison of model accuracy.

![Model Comparison](https://github.com/puongmint/TracyNguyen_Portfolio/blob/main/credit-score-ml-prediction/images/model_comparison.png)

---

## Confusion Matrix

Evaluation of the best-performing model.

![Confusion Matrix](https://raw.githubusercontent.com/puongmint/TracyNguyen_Portfolio/main/credit-score-ml-prediction/images/confusion_matrix.png)

---

## Key Insights

* Payment behaviour is a strong predictor of credit score.
* High credit utilisation is associated with lower credit scores.
* Historical financial behaviour significantly influences credit risk.

---


## Future Improvements

* Hyperparameter tuning using GridSearchCV
* Model explainability using SHAP
* Advanced models such as XGBoost or LightGBM
* Deploy the model as a simple web application (Streamlit)

---

## Author

Tracy Nguyen
MSc Artificial Intelligence & Data Analytics
Loughborough University London
