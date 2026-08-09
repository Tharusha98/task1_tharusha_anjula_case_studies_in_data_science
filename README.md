# Individual Task 1 - Fraud Detection Code

Coursework code for Case Studies in Data Science (RMIT). Logistic Regression and Random Forest on two credit card fraud datasets.

## Datasets

Download the raw files from Kaggle and place them in the paths below. Processed files are created by the preprocess notebooks.

| Dataset | File | Path | Size | Link |
|---|---|---|---|---|
| ULB Credit Card Fraud | creditcard.csv | Dataset/creditcardfraud/ | ~144 MB | https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud |
| Simulated Fraud Detection | fraudTrain.csv, fraudTest.csv | Dataset/fraud-detection/ | ~335 MB / ~143 MB | https://www.kaggle.com/datasets/kartik2112/fraud-detection |

Processed outputs (run preprocess notebooks to create):

- `Dataset/processed/creditcard_clean.csv` (~141 MB)
- `Dataset/processed/frauddetection_train_clean.csv` (~591 MB)
- `Dataset/processed/frauddetection_test_clean.csv` (~251 MB)

See `Dataset/README.md` for folder layout.

## Setup

```
pip install -r requirements.txt
```

## Run order

Run from the `Code/` directory:

1. EDA: `eda_creditcard.ipynb`, `eda_frauddetection.ipynb`
2. Preprocess: `preprocess_creditcard.ipynb`, `preprocess_frauddetection.ipynb`
3. Train: `train_creditcard.ipynb`, `train_frauddetection.ipynb`

Plots and metric CSVs are saved under `Code/outputs/creditcard/` and `Code/outputs/frauddetection/`.

## Author

Tharusha Anjula - RMIT University
