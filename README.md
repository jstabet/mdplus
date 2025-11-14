# mdplus
2025 Datathon: analysis of "Chronic illness: symptoms, treatments and triggers" Kaggle dataset

This repo contains data, results, and src scripts that preprocess the Flaredown dataset on chronic illness symptoms, treatments, and triggers. It trains a model to predict whether a user will have worse symptoms the next day depending on their entries for the current day day.

## conda env
```mamba create -n mdplus numpy pandas pyarrow matplotlib scikit-learn ipykernel```

## data
```export.csv```: downloaded from [Kaggle](https://www.kaggle.com/datasets/flaredown/flaredown-autoimmune-symptom-tracker)

## results
* preprocessed X and y, EDA, model results and feature importance figures

## src
* ```0_eda.ipynb```: eda
* ```1_preproc.ipynb```: preproc features and outcome (worse symptoms next day)
* ```2_model.ipynb```: model training and feature importance exploration
