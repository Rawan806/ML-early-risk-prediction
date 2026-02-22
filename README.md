# Cardio Risk Prediction

Predict cardiovascular disease risk using supervised machine learning on tabular clinical features.

## Dataset
Source: Hugging Face – e1e1e1/Cardio  
Target: `cardio` (0/1)

## Project Structure
- `notebooks/` : EDA, baseline, modeling & tuning
- `data/processed/` : cleaned/preprocessed data (if generated)
- `results/` : figures and tables (ROC, confusion matrix, etc.)

## How to Run
1. Open the notebooks in Google Colab (recommended) or Jupyter.
2. Run `notebooks/00_data_check.ipynb` then `01_baseline.ipynb`.

## Requirements
- pandas
- numpy
- scikit-learn
- matplotlib
- datasets (Hugging Face)
