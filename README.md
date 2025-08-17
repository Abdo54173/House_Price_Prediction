# 🏡 House Price Prediction Project

This machine learning project predicts **house prices in Melbourne** using regression models on the **Melbourne Housing Dataset**.

---

## 📁 Project Structure

- `data_preprocessing.py` – Handling missing values, feature engineering (encoding, imputation, date splitting).
- `eda.ipynb` – Exploratory Data Analysis (EDA), correlations, skewness, distributions.
- `model_training.ipynb` – Trained models:
  - **Decision Tree Regressor**
  - **Random Forest Regressor**
- `hyperparameter_tuning.ipynb` – GridSearchCV & RandomizedSearchCV for best model performance.
- `feature_importance.ipynb` – Extracted & visualized top 15 important features.
- `requirements.txt` – Project dependencies.

---

## ⚙️ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** (Decision Tree, Random Forest, GridSearchCV, RandomizedSearchCV)
- **Jupyter Notebooks**
- **Git & GitHub**

---

## 📊 Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/YourUsername/house-price-prediction.git  

# Navigate into the project
cd house-price-prediction  

# Install dependencies
pip install -r requirements.txt  
