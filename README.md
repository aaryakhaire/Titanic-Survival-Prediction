# Titanic Survival Prediction using Machine Learning

## Project Overview

This project predicts passenger survival on the Titanic using Machine Learning techniques.  
The project was developed as part of a Kaggle competition and focuses on building a complete end-to-end ML workflow including preprocessing, feature engineering, model training, evaluation, and hyperparameter tuning.

---

## Dataset

Dataset Source:
- Kaggle Titanic Competition

Files Used:
- `train.csv`
- `test.csv`

Target Variable:
- `Survived`
  - 1 = Survived
  - 0 = Did Not Survive

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

### 1. Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Cleaned dataset for ML training

### 2. Feature Engineering
Created additional meaningful features:
- FamilySize
- IsAlone
- Title extraction from passenger names

### 3. Machine Learning Models
Implemented:
- Random Forest Classifier
- XGBoost Classifier

### 4. Model Evaluation
Used:
- Train-validation split
- Cross-validation
- Confusion Matrix
- Classification Report
- Feature Importance Analysis

### 5. Hyperparameter Tuning
Applied GridSearchCV to optimize XGBoost parameters.

---

## Results

### Best Cross Validation Accuracy
- ~84.8%

### Kaggle Public Leaderboard Score
- ~77.2%

---

## Key Learnings

- Importance of feature engineering
- Difference between validation accuracy and leaderboard performance
- Overfitting and model generalization
- Hyperparameter tuning using GridSearchCV
- End-to-end ML workflow development

---

## Project Structure

```plaintext
Titanic-Survival-Prediction/
│
├── data/
├── notebooks/
├── models/
├── images/
├── README.md
├── requirements.txt

Future Improvements
Ensemble Learning
LightGBM/CatBoost implementation
SHAP explainability
Advanced feature engineering
Deployment using Streamlit or Flask

Author
Aarya Khaire


