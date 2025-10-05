# Titanic Survival Prediction

This project applies **supervised machine learning** to predict passenger survival from the Titanic disaster.  
The model uses a **Random Forest Classifier**, tuned with GridSearchCV, and achieves an accuracy of **0.79186** on Kaggle.

---

## Project Overview

The goal is to predict whether a passenger survived (`Survived` = 0 or 1) based on features like:
- Passenger class (`Pclass`)
- Gender (`Sex`)
- Age
- Fare
- Number of siblings/spouses (`SibSp`)
- Number of parents/children (`Parch`)
- Embarkation port (`Embarked`)

---

## Learning Approach

This project was completed by following **Titanic Survival Prediction in Python - Machine Learning Project** to understand data preprocessing, feature engineering, and model development.  
All model training, tuning, and evaluation were performed independently to apply and deepen learning.

https://youtu.be/fATVVQfFyU0?si=K3I6cHX9emOtjXj9

---

## Steps in the Notebook

1. **Data Loading** — Import and inspect datasets.  
2. **EDA** — Explore relationships and correlations.  
3. **Data Cleaning & Preprocessing** — Handle missing values and encode categorical variables.  
4. **Feature Engineering** — Create useful derived features (e.g., family size, title extraction).  
5. **Model Training** — Fit a Random Forest model.  
6. **Hyperparameter Tuning** — Optimize using GridSearchCV.  
7. **Prediction & Submission** — Generate predictions for Kaggle.

---

## Model Details

- **Algorithm:** Random Forest Classifier  
- **Tuning Method:** GridSearchCV  
- **Example Best Parameters:** `max_depth=17, n_estimators=250`  
- **Accuracy:** **0.79186**

---

## Libraries Used

- pandas  
- numpy  
- matplotlib / seaborn  
- scikit-learn  

---

## Result

- **Kaggle Public Leaderboard Accuracy:** `0.79186`

---

## 📁 File Structure

Titanic.ipynb # Jupyter Notebook
prediction.csv #prediction output
kaggle_score.png #screenshot of the kaggle accuracy score
README.md # Project documentation
