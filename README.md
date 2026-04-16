# Titanic Survival Prediction

This repository contains notebook-based work on the classic Kaggle Titanic survival prediction problem.

## Project Overview

The repository includes multiple notebooks, the training and test CSV files, and several submission files. The notebooks show both a general exploratory workflow and a more pipeline-oriented machine learning approach.

## Files

| File | Description |
| --- | --- |
| `Titanic survival pred_.ipynb` | Notebook for exploratory analysis and baseline modeling |
| `titanic_with_pipeline.ipynb` | Notebook that uses a more explicit preprocessing/model pipeline workflow |
| `train.csv` | Kaggle Titanic training dataset |
| `test.csv` | Kaggle Titanic test dataset |
| `base_submission.csv` | Prediction submission file |
| `gender_submission.csv` | Reference/baseline submission file |
| `xgb_submission3.csv` | Additional submission output |

## Workflow Summary

The notebooks currently cover work such as:

1. Importing analysis and visualization libraries.
2. Loading the Kaggle Titanic train and test datasets.
3. Combining or comparing train/test data during preprocessing.
4. Exploring passenger features and the survival target.
5. Building a machine learning workflow for predictions.
6. Exporting submission CSV files.

The pipeline notebook specifically uses common scikit-learn tools such as:

- `ColumnTransformer`
- `SimpleImputer`
- `OneHotEncoder`
- `MinMaxScaler`
- `Pipeline`
- `SelectKBest`
- a tree-based classifier

## Dataset

The repository includes the core CSV files directly, so the notebooks can be rerun locally without an extra data download step.

## Outputs

Prediction results are saved as submission CSV files in the repository root.

## Notes

- This is a notebook-first Kaggle project rather than a packaged training pipeline.
- If you revisit the project, a useful improvement would be adding a short results summary comparing the different submission files.
