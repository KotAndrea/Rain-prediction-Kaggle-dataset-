# Rain Prediction – Binary Classification problem

This project explores a weather dataset from Kaggle to predict whether it will rain tomorrow. It’s a binary classification task using real-world meteorological data.

## Objective

Predict the binary target `RainTomorrow` (Yes/No) based on various weather features recorded today.

- **Target**: `RainTomorrow`
- **Type**: Binary classification
- **Metric**: ROC AUC

## Dataset

- Source: Kaggle (https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

## Techniques Used

- Data cleaning and imputation of missing values
- Label encoding and target encoding
- Handling outliers using IQR method
- Feature engineering
- Applying under and oversampling techniques for imbalanced sets
- Model training using XGBClassifier
- Hyperparameter tuning using GridSearch
- Evaluation using ROC curve

