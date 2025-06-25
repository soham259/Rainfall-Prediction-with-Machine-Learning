# Rain Prediction Model

## Project Overview
This project builds a machine learning model to predict whether it will rain tomorrow based on historical weather data. It uses features like temperature, humidity, wind speed, and more.

## Dataset
- Contains weather-related features and a target variable `RainTomorrow` (0 = No rain, 1 = Rain).
- Class imbalance was handled by oversampling the minority class.
- Data source: [weatherAUS.csv]([your-dataset-link-here](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package/data))

## Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting
- Linear SVM (with calibration)
- K-Nearest Neighbors (KNN)

Models are evaluated using Accuracy and ROC-AUC score.

## Key Features
- Missing values were handled by using the mode for categorical variables
  and the median for numerical variables
- Oversampling to handle class imbalance
- Feature scaling with Min-Max Scaler
- Visualization of correlations and distributions
- Model training, evaluation, and comparison
