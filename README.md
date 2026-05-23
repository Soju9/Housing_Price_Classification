# Housing_Price_Classification
Supervised machine learning project predicting whether houses are expensive using preprocessing pipelines, encoding, GridSearchCV, and classification models.

# Housing Price Classification

This project predicts whether a house is expensive or not using supervised machine learning.

## Goal

Build a classification model that predicts the `Expensive` target variable from housing features.

## Methods Used

- Data preprocessing
- Missing value imputation
- Ordinal encoding
- One-hot encoding
- Decision Tree
- K-Nearest Neighbors
- Random Forest
- GridSearchCV
- Train/test evaluation
- Overfitting check

## Best Model

The best performing model was Random Forest.

## Metrics

Final model score on competition test dataset (submission.csv): 0.977

| Model | Accuracy | Recall | Precision | F1 Score | Balanced Accuracy |
|---|---:|---:|---:|---:|---:|
| Decision Tree | 0.938 | 0.729 | 0.875 | 0.795 | 0.854 |
| KNN | 0.942 | 0.688 | 0.943 | 0.795 | 0.840 |
| Random Forest | 0.955 | 0.750 | 0.973 | 0.847 | 0.873 |

## Files

- `notebooks/housing_final.ipynb`: final notebook
- `data/`: datasets
- `submissions/submission.csv`: final prediction file

## How To Run

1. Install requirements:

```bash
pip install -r requirements.txt
