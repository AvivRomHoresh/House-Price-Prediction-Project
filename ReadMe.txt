# 🏠 House Price Prediction Project

This project demonstrates a complete supervised machine learning pipeline for predicting median house values in California, based on housing and demographic features.

## 📋 Project Structure

- `Assignment2_supervised_learning_flow.ipynb`: Main notebook containing the full ML flow.
- `housing_train.csv`: Training dataset used to fit and evaluate models.
- `housing_test.csv`: Test dataset used for final predictions.

## 📌 Workflow Overview

1. **Exploratory Data Analysis (EDA)**: Identified outliers, feature distributions, and correlations.
2. **Feature Engineering**: Created new features (e.g., `RoomRatio`), and normalized data.
3. **Model Selection & Tuning**:
   - Compared models: Linear Regression, Random Forest, XGBoost
   - Used 5-Fold Cross Validation with Grid Search
4. **Final Model Training**: Trained the best model (Random Forest) on the full training set.
5. **Test Prediction**: Applied the trained model to the test set and evaluated predictions.

## 🧠 Goal

To accurately estimate the median house value based on features such as income, number of rooms, population, and more.

## 🎓 Author

Aviv Horesh
