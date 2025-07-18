# 🏡 House Price Prediction – Linear Regression

A beginner-friendly machine learning project that predicts California housing prices using a linear regression model trained on the **California Housing dataset**.

## 📂 Project Structure

House-Price-Prediction/

├── House Price Prediction - Linear Regression.ipynb

├── requirements.txt

└── README.md

## 📊 Dataset

- **Source**: `sklearn.datasets.fetch_california_housing()`
- **Features**: Median income, house age, average rooms, location, etc.
- **Target**: Median house value (`MedHouseVal`)

## 🧠 ML Workflow

1. **Data Exploration**
   - Used `pandas`, `seaborn`, and `matplotlib` for analysis and visualization.
2. **Preprocessing**
   - Checked for nulls, outliers, and feature distributions.
3. **Modeling**
   - Applied **Linear Regression** from `scikit-learn`.
   - Split dataset into training and testing sets.
4. **Evaluation**
   - Used **Mean Squared Error (MSE)** and **R² score**.
   - Visualized predictions vs actual values using scatter plots.

## 📈 Results

- **MSE**: `0.5559`
- **R² Score**: `0.5758`

> Interpretation: The model explains ~57.6% of the variance in housing prices.

## 📦 Requirements

Install dependencies with:

pip install -r requirements.txt


## 🚀 Future Work
Apply feature scaling and transformation

Try other regression models (e.g. Ridge, Lasso, Decision Tree)

Improve performance using grid search and cross-validation

## 👩‍💻 Author
Arfa Tariq — Aspiring AI/ML Engineer with a practical-first learning mindset
