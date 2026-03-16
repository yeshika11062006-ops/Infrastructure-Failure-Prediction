# Infrastructure Failure Prediction using Machine Learning

## Project Overview

This project builds a predictive maintenance system to detect potential infrastructure failures using machine learning models. The goal is to identify high-risk conditions early and support preventive maintenance decisions.

## Dataset

The dataset used in this project is the AI4I 2020 Predictive Maintenance Dataset from the UCI Machine Learning Repository.

Features include:

* Air temperature
* Process temperature
* Rotational speed
* Torque
* Tool wear

Target:

* Machine Failure (0 = No failure, 1 = Failure)

## Machine Learning Models

Three classification models were trained and compared:

* Logistic Regression
* Decision Tree
* Random Forest

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 96.75%   |
| Decision Tree       | 98.8%    |
| Random Forest       | 99.1%    |

The Random Forest model achieved the best performance.

## Visualizations

The project includes several analysis plots:

* Confusion Matrix
* ROC Curve
* Feature Importance
* Model Accuracy Comparison

## Key Insights

Feature importance analysis shows that factors such as tool wear, torque, and operational stress significantly influence failure risk.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Outcome

The final model can serve as an early warning system for infrastructure failure prediction and predictive maintenance planning.
