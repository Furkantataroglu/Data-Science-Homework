# 📊 Pokémon Dataset Analysis

This repository contains a basic data science project based on the [Pokémon dataset](https://www.kaggle.com/datasets/jaidalmotra/pokemon-dataset) from Kaggle. The project includes data preprocessing, exploration, visualization, and a simple regression model.

## 🧩 Project Overview

- Load and display the dataset  
- Handle and fill missing values  
- Visualize categorical and numerical variables  
- Perform basic statistical analysis  
- Split the dataset into training and testing sets  
- Apply basic feature engineering  
- Train and evaluate a linear regression model  
- Save the cleaned dataset  

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Google Colab  
- Kaggle API  

## 📈 Model Evaluation

A **Linear Regression** model was built to predict a numerical target. The model was evaluated using **Mean Squared Error (MSE)** and **R-squared (R²)** scores:

- **Training MSE**: `1.96`  
  > Indicates the average squared error on the training set. 

- **Training R²**: `1.00`  
  > The model perfectly explains the variance in the training data.

- **Test MSE**: `0.06`  
  > Very low error on the test set, suggesting excellent generalization.

- **Test R²**: `1.00`  
  > The model captures almost all the variance in unseen data — a near-perfect fit.

These results suggest that the model is highly effective in both training and test data, with minimal prediction error.

## 📂 Author

**Furkan Tataroğlu**  
Student ID: G201210089  
Course: Data Science – Assignment 1

[Rapor.pdf](https://github.com/user-attachments/files/18219229/Rapor.pdf)
