# Vertebral Column Classification (SVM, Logistic Regression, Random Forest)

This project analyzes the Vertebral Column Dataset to classify orthopedic patients as **normal** or **abnormal** using various machine learning models. The dataset contains six biomechanical features relevant for spine condition prediction.

## Dataset

- **Source**: [Kaggle – Vertebral Column Data Set](https://www.kaggle.com/datasets/jessanrod3/vertebralcolumndataset)
- **Features**: 6 biomechanical features (e.g., pelvic incidence, pelvic tilt, lumbar lordosis angle, etc.)
- **Target**: Binary classification  
  - `0` → Abnormal  
  - `1` → Normal

## Models Used

1. Support Vector Machine (SVM)
2. Logistic Regression
3. Random Forest Classifier

Each model was evaluated on the basis of:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC Score

## Visualizations

- Count of the Unique classes
- Confusion Matrix heatmaps for each model
- ROC AUC Curve comparison
- Classification Reports for detailed performance

## Results Summary

| Model                | Accuracy | Precision | Recall | F1 Score | AUC Category |
|--------------------- |----------|-----------|--------|----------|--------------|
| Support Vector       |          |           |        |          |              |
|Machine (SVM)         | 83.87%   | 0.64      | 1.00   | 0.78     | High         |
| Random Forest        | 82.26%   | 0.64      | 0.89   | 0.74     | High         |
| Logistic Regression  | 80.65%   | 0.60      | 1.00   | 0.75     | Good         |


## Insights

- SVM performed best overall in terms of precision, recall, and F1 score.
- Logistic Regression also achieved perfect recall but slightly lower F1.
- Random Forest was less reliable in detecting abnormal cases.

## Tools & Libraries

- Python
- scikit-learn
- seaborn and matplotlib
- pandas, numpy

Made by Surabhi Pandey
