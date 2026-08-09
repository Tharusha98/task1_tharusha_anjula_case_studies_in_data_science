# Individual Task 1 - Hospital Data Analytics Code

Coursework code for Case Studies in Data Science (RMIT). Random Forest and Neural Network models on two healthcare datasets, supporting the Hospital Data Analyst case study in Individual Task 1, Part 1.

## Datasets

Download the raw files from the UCI Machine Learning Repository and place them in the paths below. Processed files are created by the preprocess notebooks.

| Dataset | File | Path | Size | Link |
|---|---|---|---|---|
| Diabetes 130-US Hospitals (1999-2008) | diabetic_data.csv | Dataset/hospital-readmission/ | ~19 MB | https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008 |
| CDC Diabetes Health Indicators | diabetes_binary_health_indicators_BRFSS2015.csv | Dataset/diabetes-indicators/ | ~22 MB | https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators |

Processed outputs (run preprocess notebooks to create):

- `Dataset/processed/hospital_readmission_clean.csv`
- `Dataset/processed/diabetes_indicators_clean.csv`

See `Dataset/README.md` for folder layout.

## Setup

```
pip install -r requirements.txt
```

## Run order

Run from the `Code/` directory:

- EDA: `eda_hospital_readmission.ipynb`, `eda_diabetes_indicators.ipynb`
- Preprocess: `preprocess_hospital_readmission.ipynb`, `preprocess_diabetes_indicators.ipynb`
- Train: `train_hospital_readmission.ipynb` (Random Forest, readmission <30 days), `train_diabetes_indicators.ipynb` (Neural Network, diabetes status)

Plots and metric CSVs are saved under `Code/outputs/hospital_readmission/` and `Code/outputs/diabetes_indicators/`.

## Author

Tharusha Anjula - RMIT University
