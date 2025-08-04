# Predicting-House-Prices
Predicting house prices using Linear regression
# 🏡 California Housing Price Prediction

This project uses machine learning to predict house prices in California based on features like median income, house age, and more. The dataset is sourced from the `scikit-learn` library and provides insights into housing conditions across California districts.

## 📂 File Included

- `Predicting_House_Prices.ipynb`: A complete Jupyter Notebook for data exploration, visualization, model training, and evaluation.

## 📊 Dataset

The **California Housing dataset** is a built-in dataset from `sklearn.datasets`. It contains 20,640 samples with the following features:

- `MedInc` – Median income in block group
- `HouseAge` – Median house age in block group
- `AveRooms` – Average number of rooms
- `AveBedrms` – Average number of bedrooms
- `Population` – Block group population
- `AveOccup` – Average house occupancy
- `Latitude` – Block group latitude
- `Longitude` – Block group longitude

The target is the **median house value** in each district.

## 🧪 ML Workflow

1. **Importing Libraries**
2. **Loading the Dataset**
3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Distribution plots  
   - Correlation heatmaps  
4. **Data Preparation**
   - Feature scaling
   - Train-test split
5. **Model Training**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
6. **Model Evaluation**
   - Mean Squared Error (MSE)
   - R² Score
