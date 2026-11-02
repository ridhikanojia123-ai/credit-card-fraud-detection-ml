# credit-card-fraud-detection-ml
# Credit Card Fraud Detection Using Machine Learning

## Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning classification algorithms. It explores transaction data, performs data preprocessing and exploratory data analysis, and compares multiple classification models.

## Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses two datasets:

- fraudTrain.csv — 1,296,675 records
- fraudTest.csv — 555,719 records

Each dataset contains 23 columns, including transaction amount, merchant, category, customer information, geographical features, and the fraud target variable.

## Project Workflow

1. Data loading and inspection
2. Missing-value and duplicate checks
3. Data cleaning and feature selection
4. Categorical feature encoding
5. Exploratory Data Analysis
6. Feature scaling
7. Training and evaluating classification models
8. Comparing model performance using accuracy and F1 score

## Machine Learning Algorithms

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

## Model Performance

| Model | Accuracy | F1 Score |
|---|---:|---:|
| Logistic Regression | 96.72% | 0.149 |
| Decision Tree | 99.66% | 0.380 |
| Random Forest | 99.70% | 0.367 |
| Gradient Boosting | 99.75% | 0.620 |

Gradient Boosting achieved the highest reported F1 score among the four evaluated models.

## Key Learning Outcomes

- Handling large transaction datasets
- Understanding imbalanced classification problems
- Performing exploratory data analysis
- Applying machine learning classification algorithms
- Comparing models using accuracy and F1 score

## Project Files

- `Credit_Card_Fraud_Detection_Report.pdf` — Project report
- `README.md` — Project documentation

## Future Improvements

- Apply more robust techniques for handling class imbalance.
- Perform hyperparameter tuning.
- Optimize the classification threshold.
- Evaluate precision, recall and other fraud-specific metrics.

## Author

Ridhi  
Aspiring Data Analyst | Data Science Enthusiast
