This project focuses on predicting credit card defaulters using American Express(AMEX) dataset.

# Dataset Preparation:
- **Original Dataset**: The original dataset was a 16.4 GB CSV file.
- **Conversion**: The CSV file was converted into a 4.7 GB Parquet file for optimized performance.

# Exploratory Data Analysis (EDA):
EDA was conducted to gain insights. This includes:
- Distribution analysis of variables
- Analysis of missing values and implementation of imputation strategies
- Correlation checks(high correlation and low correlation) were performed to reduce redundancy

# Model Development:
- The LightGBM(Light Gradient Boosting Model) was chosen for model development due to its speed and efficincy.
- The dataset was split into a ratio of 70:20:10 in which 70% of the dataset was used as training set, 20% of the dataset was used as validation set and the rest 10% of the dataset was used as test set.
- The LightGBM model was trained, validated and tested, achieving an accuracy of 95% which includes various evaluation metrics such as ROC-AUC score and F1-score.

# Current Status:
- Dataset loading and conversion
- Completed initital EDA
- Flattened the dataset
- Model development
- **Next Step**: Model Deployment

# Next Step:
- Deploying the trained model for real-time fraud detection
