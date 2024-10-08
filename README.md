# Hate Speech Detection with BERT and Explainable AI

This project aims to detect hate speech, offensive language, and neutral text using deep learning models like BERT and HateBERT. The project also incorporates Explainable AI (XAI) techniques to interpret model predictions.

## Features

- **Models Used**: BERT, HateBERT
- **Techniques**: Baseline LSTM, data augmentation, hyperparameter tuning
- **Explainability**: Attention visualisation and LIME interpretability

## Dataset

The dataset contains tweets classified as hate speech, offensive language, or neutral text. The classes are imbalanced, which presents a challenge for training robust models.

- **Classes**:
  - Hate Speech: 1
  - Offensive Language: 2
  - Neutral: 0

## Project Steps

1. **Exploratory Data Analysis (EDA)**: Understand the dataset distribution and key characteristics.
2. **Baseline Model**: Train a simple LSTM model as a starting point.
3. **Advanced Models**: Train BERT and HateBERT models, with and without data augmentation.
4. **Hyperparameter Tuning**: Optimize model parameters for better performance.
5. **Explainable AI**: Use LIME to interpret and visualize the model’s decisions.

## Results

- **Best Accuracy**: 92% achieved using the HateBERT model with hyperparameter tuning, including the highest recall score for the Hate Speech detection.
- **Challenges**: Detecting hate speech due to dataset imbalance.
