# Lab-8-ML-KNN

## Overview
This project applies the K-Nearest Neighbors (KNN) algorithm to a classified dataset. The goal is to build a model that predicts the target class based on feature values and improve performance by tuning the value of K.

## Steps Performed

### 1. Import Libraries
Used essential libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

### 2. Load Dataset
- Loaded `KNN_Project_Data` into a DataFrame
- Displayed first few rows to understand structure

### 3. Exploratory Data Analysis (EDA)
- Created a pairplot using seaborn
- Used `TARGET CLASS` as hue to visualize class separation

### 4. Data Preprocessing
- Standardized features using `StandardScaler`
- Converted scaled data into a new DataFrame

### 5. Train-Test Split
- Split data into training (70%) and testing (30%)

### 6. Model Training (K=1)
- Created KNN model with `n_neighbors=1`
- Trained model using training data

### 7. Evaluation
- Generated predictions on test data
- Evaluated using:
  - Confusion Matrix
  - Classification Report

### 8. Choosing Optimal K
- Tested K values from 1 to 39
- Calculated error rate for each K
- Plotted Error Rate vs K Value

### 9. Retraining Model
- Selected best K (e.g., K=30)
- Retrained model
- Evaluated performance again

## Results
- Initial model (K=1): ~75% accuracy
- Improved model (K=30): ~84% accuracy


