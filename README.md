# Red Wine Quality Prediction

Binary classification project for predicting high-quality red wine from physicochemical measurements.

## Overview

This project uses the UCI red wine quality dataset to classify wines as:

- `1`: high quality, original score >= 7
- `0`: standard quality, original score < 7

The notebook includes data validation, exploratory analysis, feature correlation checks, model comparison, and holdout evaluation. Because high-quality wines are a minority class, the project compares models using F1 score, recall, precision, ROC-AUC, and accuracy.

## Project Structure

```text
red-wine-quality-prediction/
├── data/
│   └── winequality-red.csv
├── notebooks/
│   └── red_wine_quality_prediction.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Models Compared

- Dummy baseline
- Logistic Regression
- Support Vector Machine
- Decision Tree
- K-Nearest Neighbors

## Key Skills Demonstrated

- Data cleaning and validation with pandas
- Exploratory data analysis with seaborn and matplotlib
- Binary classification with scikit-learn
- Train/test splitting with stratification
- Cross-validation and model comparison
- Evaluation for imbalanced classification problems

## How to Run

1. Create and activate a Python environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/red_wine_quality_prediction.ipynb
```

## Dataset

Dataset: UCI Red Wine Quality dataset, commonly available through Kaggle as `uciml/red-wine-quality-cortez-et-al-2009`.
