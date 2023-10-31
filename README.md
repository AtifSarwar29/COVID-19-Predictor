# COVID-19-Predictor
## Project Overview:
This project aims to develop an automatic predictor for COVID-19 infection using machine learning techniques. The dataset consists of FCS files representing patient specimens, with labels indicating whether the patients are COVID-19 positive (sick) or negative (healthy). The ground truth labels are provided in "EU_label.xlsx," and marker-channels with "use" = 1 are selected from "EU_marker_channel_mapping.xlsx" as the data features.

## Goals:
* Develop a robust machine learning model to predict COVID-19 infection based on patient specimens.
* Evaluate and fine-tune the model's performance to ensure accurate predictions.
* Provide a model that can assist in diagnosing COVID-19 based on FCS data.

## Key Components:
* Data Preprocessing: Loading and preprocessing FCS files, feature selection.
* Machine Learning Model: Selection of an appropriate ML model (e.g., Random Forest, Support Vector Machine) for classification.
* Model Training: Training the model using the labeled data.
* Model Evaluation: Assessing the model's performance through metrics such as accuracy, precision, recall, and F1-score.

