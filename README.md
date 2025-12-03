# Suicide-Prediction-using-Machine-Learning

This project develops a machine-learning pipeline to predict suicide attempts using demographic and behavioral data from the ForeverAlone Dataset. The goal is to identify individuals at higher risk by training and evaluating multiple classification models.

Dataset:
The dataset includes features such as:
- Demographics (age, income, education level, etc.)
- Lifestyle and behavioral traits
- Social and relationship-related variables
- Binary labels indicating whether the person has attempted suicide

Data Preprocessing:
The following preprocessing steps were applied:
- Cleaning
Removed irrelevant or high-missing-value columns, Handled missing values in binary and numeric columns, Processed categorical variables
- Encoding
One-hot encoding for all categorical features and Mapping education levels into numerical categories
-Feature Scaling
Standardization using StandardScaler
Train/Test split for model evaluation

Models Trained:
Three machine learning algorithms were implemented:
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest

Evaluation Metrics:
Each model was evaluated using:
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix
Performance comparisons allow identification of the model best suited for suicide attempt prediction.
