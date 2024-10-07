# Breast Cancer Prediction Model

## Project Overview
This project uses a machine learning model to predict breast cancer diagnosis (benign or malignant) based on input features from a dataset. The dataset includes key clinical attributes that can help detect breast cancer early.

## Dataset
The dataset used for this project is publicly available on Kaggle: [Breast Cancer Dataset](https://www.kaggle.com/datasets/nancyalaswad90/breast-cancer-dataset).

## Project Features
The notebook implements several steps in building a breast cancer prediction model:
- Data preprocessing (handling missing values, normalization, etc.)
- Training machine learning models
- Evaluating model performance using metrics like accuracy, precision, recall, and F1 score

## Key Metrics Explained
- **Accuracy**: How often the model makes correct predictions.
- **Precision**: Of all predicted positive cases (cancer), how many were correct.
- **Recall (Sensitivity)**: Out of all actual cancer cases, how many were correctly identified.
- **F1 Score**: Balances precision and recall to give a single performance measure.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/afiadata/breastcancerprediction.git
   cd breastcancerprediction
   ```
2. Dependencies
The project requires the following libraries:

- pandas
- scikit-learn
- matplotlib
- seaborn
- numpy
