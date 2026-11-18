# Bank Loan Approval Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning to predict payment-difficulty risk using the Home Credit Default Risk dataset.

The project implements a Gradient Boosting Classifier with a complete preprocessing pipeline, model evaluation, and model export.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Joblib

## Dataset

Dataset: Home Credit Default Risk

Download: https://www.kaggle.com/competitions/home-credit-default-risk/data

Required file: `application_train.csv`

Target variable:
- 0 – No recorded payment difficulties
- 1 – Payment difficulties

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Perform exploratory data analysis.
4. Handle missing values.
5. Separate features and target.
6. Split training and testing data.
7. Apply numerical feature scaling.
8. Apply categorical one-hot encoding.
9. Build a preprocessing pipeline.
10. Train Gradient Boosting Classifier.
11. Evaluate model performance.
12. Generate confusion matrix and ROC curve.
13. Save evaluation metrics.
14. Export the trained model using Joblib.
15. Verify the saved model.

## Machine Learning Algorithm

GradientBoostingClassifier

## Model Evaluation

The project evaluates the model using:

- Accuracy
- ROC-AUC Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

Actual evaluation results are generated when the notebook is executed.

## Installation

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib joblib notebook
```

## How to Run

1. Clone or download this repository.
2. Download `application_train.csv` from Kaggle.
3. Place the dataset in the notebook's working directory.
4. Open Jupyter Notebook.
5. Open `Bank_Loan_Approval_Prediction.ipynb`.
6. Execute all cells sequentially.

## Output Files

The notebook generates:

- `bank_loan_pipeline.joblib`
- `metrics.json`
- `roc_curve.png`
- `metadata.json`

## Model Export

The trained preprocessing and classification pipeline is exported using Joblib for future predictions.

## Limitations

This is an educational credit-risk prediction project. It does not represent a complete bank loan approval system and should not be used for real lending decisions.

## Author
##Purva Ghate##

Machine Learning Project – Bank Loan Approval Prediction
