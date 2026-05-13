# Drug Relapse Risk Predictor

## Overview

This project uses Machine Learning to predict whether an individual falls under a high drug relapse risk category based on substance consumption patterns.

The goal of the project is to explore how behavioral analytics and AI can help identify high-risk individuals early and support preventive healthcare systems.

---

## Why This Project?

Drug addiction and relapse remain major public health challenges worldwide. Early-risk prediction systems can help healthcare professionals, rehabilitation centers, and counselors take preventive action before conditions worsen.

This project was built to:

- Apply Machine Learning to a real-world healthcare problem
- Understand behavioral pattern prediction
- Practice end-to-end ML workflows
- Explore classification models on structured datasets

---

## Problem Statement

The project predicts whether an individual is at:

- `0` → Low Relapse Risk
- `1` → High Relapse Risk

A custom target variable called `RelapseRisk` was created using high-risk consumption levels of substances such as:

- Heroin
- Cocaine
- Methamphetamine

High-risk categories like `CL4`, `CL5`, and `CL6` were labeled as relapse-risk indicators.


## Algorithms Used

### Logistic Regression

Used as a baseline model because:

- It works well for binary classification
- It is simple and interpretable
- It provides fast training and evaluation

### XGBoost Classifier

Used as the primary model because:

- It performs extremely well on structured/tabular datasets
- It captures complex nonlinear relationships
- It improves prediction accuracy using boosting
- It handles feature interactions effectively
- It is widely used in production ML systems


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost


## ML Workflow

- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- Model Training
- Model Evaluation


## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix


## Real-World Relevance

This project demonstrates how Machine Learning can be used in:

- Healthcare analytics
- Addiction recovery systems
- Behavioral risk prediction
- Early intervention systems



## Future Improvements

- Hyperparameter tuning
- Explainable AI integration
- Real-time prediction dashboard
- Deployment using Flask or FastAPI


## How to Run

```bash
git clone https://github.com/adity82much/drug_relapse_detector.git

cd drug_relapse_detector

pip install -r requirements.txt

jupyter notebook
```

---

## Author

Aditya Dushad
