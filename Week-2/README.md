# Thiranex Task 2 — Wine Quality Prediction Using Machine Learning

## Project Overview

This project focuses on predicting wine quality using machine learning techniques. The UCI Wine Quality dataset for red wine was used for the analysis.

The project implements and compares two supervised machine learning classification algorithms:

- Decision Tree Classifier
- Random Forest Classifier

## Dataset

- **Dataset:** UCI Wine Quality — Red Wine
- **Records:** 1,599
- **Input Features:** 11
- **Target Variable:** `quality`
- **Problem Type:** Multi-class Classification

## Features Used

The following physicochemical properties were used as input features:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

## Methodology

The project follows these steps:

1. Load the Wine Quality dataset.
2. Inspect the dataset structure and data types.
3. Check for missing values.
4. Perform exploratory data analysis and statistical analysis.
5. Analyze the distribution of wine quality.
6. Analyze correlations between features and wine quality.
7. Separate input features and target variable.
8. Split the data into 80% training and 20% testing sets.
9. Train a Decision Tree Classifier.
10. Train a Random Forest Classifier.
11. Generate predictions on the test data.
12. Evaluate both models using multiple performance metrics.
13. Generate confusion matrices.
14. Calculate ROC-AUC scores.
15. Analyze feature importance.
16. Compare the performance of both models.

## Models

### Decision Tree Classifier

The Decision Tree Classifier was used as a baseline classification model. It makes predictions using a sequence of decision rules based on the input features.

### Random Forest Classifier

The Random Forest Classifier combines multiple decision trees to produce predictions. It was used to compare its performance against the individual Decision Tree model.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Results

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Decision Tree | 0.6062 | 0.6097 | 0.6062 | 0.6066 | 0.6974 |
| Random Forest | **0.6781** | **0.6531** | **0.6781** | **0.6632** | **0.8376** |

### Best Model

Based on the evaluation results, **Random Forest** performed better than the Decision Tree.

Random Forest achieved:

- **Accuracy:** 67.81%
- **Precision:** 65.31%
- **Recall:** 67.81%
- **F1 Score:** 66.32%
- **ROC-AUC:** 0.8376

## Visualizations

The project includes:

- Wine Quality Distribution
- Decision Tree Confusion Matrix
- Random Forest Confusion Matrix
- Random Forest Feature Importance

## Tools and Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

## Conclusion

The project successfully demonstrates the application of supervised machine learning to wine quality prediction.

Both Decision Tree and Random Forest classifiers were trained and evaluated. The Random Forest model achieved better overall performance across the evaluation metrics, particularly in terms of Accuracy, F1 Score, and ROC-AUC.

The project also demonstrates the importance of exploratory data analysis, model evaluation, confusion matrices, and feature importance when developing a machine learning solution.

## Project Structure

```text
Task-2/
│
├── README.md
├── Thiranex_Task_2_Wine_Quality_ML.ipynb
│
└── wine+quality/
    └── winequality-red.csv
```

## Internship Task

**Thiranex — Task 2: Predictive Modeling Using Machine Learning**
