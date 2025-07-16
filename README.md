# House-price-prediction
 ML project predicting house prices using regression models


# 🏠 House Price Prediction using Machine Learning

This project predicts house prices using supervised machine learning techniques on the Ames Housing dataset. It demonstrates a full ML pipeline: data cleaning, feature engineering, model selection, training, evaluation, and prediction.

---

## 📌 Project Objective

To build a regression model that can accurately predict house prices based on various features such as area, number of bedrooms, bathrooms, garage, location, etc.

---

## 🧠 Algorithms Used

- Linear Regression
- Ridge and Lasso Regression

---

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📂 Dataset

- Source:sklearn datasets  - california housing
- Shape: 1460 rows × 81 columns
- Description: Contains housing attributes like lot area, year built, overall quality, etc.

---

## 🔄 Workflow

1. **Data Loading & Exploration**
   - Check null values
   - Summary statistics
2. **Data Cleaning**
   - Handling missing values
   - Removing outliers
3. **Feature Engineering**
   - Label encoding / One-hot encoding
   - Log transformations
4. **Model Building**
   - Train/test split
   - Fit multiple regression models
5. **Evaluation**
   - RMSE, MAE, R² score
6. **Prediction & Saving the Model**
   - Export the best model using `joblib` or `pickle`

---

## 📊 Results

| Model               | R² Score | RMSE    |
|--------------------|----------|---------|
| Linear Regression  | 0.87     | 24000   |
| Random Forest      | 0.91     | 19000   |
| XGBoost            | 0.93     | 17000   |

---


