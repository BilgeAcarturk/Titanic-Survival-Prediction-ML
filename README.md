# Titanic Survival Prediction using Machine Learning

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning classification algorithms.

The project covers the complete machine learning workflow, including:

- Data preprocessing
- Feature engineering
- Model training
- Model comparison
- Cross-validation
- Model evaluation
- Feature importance analysis

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

---

## Dataset

The project uses the Titanic dataset, which contains passenger information such as:

- Passenger Class
- Sex
- Age
- Fare
- Family Information
- Embarkation Port

The target variable is:

- Survived (0 = No, 1 = Yes)

---

## Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

Additionally, 5-Fold Cross Validation was performed to evaluate model stability.

---

## Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 0.799 |
| Decision Tree | 0.777 |
| Random Forest | **0.827** |
| Support Vector Machine | 0.665 |

Random Forest achieved the best overall performance.

---

## Feature Engineering

Two additional features were created:

- FamilySize
- IsAlone

Feature importance analysis showed that Fare, Sex and Age were the most influential variables.

---

## Visualizations

The project includes:

- Model Comparison
- Cross Validation Comparison
- Confusion Matrix
- Feature Importance

---

## Future Improvements

Possible improvements include:

- Hyperparameter tuning
- Additional feature engineering
- Grid Search
- Ensemble optimization