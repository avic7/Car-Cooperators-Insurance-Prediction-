# Car Insurance Premium Prediction

## Overview
This project focuses on building a **machine learning model** to predict **car insurance premiums** based on customer and vehicle-related features. The aim is to assist insurance companies in pricing policies more accurately, manage risk better, and streamline the underwriting process.

---

## Problem Statement
Predict the **insurance premium** amount for individual policyholders using customer demographics, vehicle characteristics, and claim history.


## Features
- **Predictive Modeling**: Supervised learning models to predict premium amounts.
-  **Data Preprocessing**: Handling missing values, feature engineering, and scaling.
-  **Model Evaluation**: Compare model performances using appropriate regression metrics.
-  **Data Visualization**: Explore data distributions, correlations, and feature importance.
- **Pipeline Ready**: Clean code structure with reproducible pipelines.



## Tech Stack
- **Python 3.x**
- **Pandas**, **NumPy** (Data Manipulation)
- **Scikit-Learn** (Machine Learning Models)
- **Matplotlib**, **Seaborn** (Visualization)
- **XGBoost** / **LightGBM** (Advanced Models)
- **Jupyter Notebook** (Exploratory Data Analysis and Model Training)


## Data Science Workflow
- Load and explore the dataset
- Handle missing values and perform data cleaning
- Feature engineering (encoding categorical features, scaling numerical ones)
- Model building:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting (XGBoost / LightGBM)
- Hyperparameter tuning (Grid Search / Randomized Search)
- Model evaluation using RMSE, MAE, and R² metrics


## Installation

```bash
# Clone the repository
git clone https://github.com/avic7/Car-Cooperators-Insurance-Prediction-.git
cd Car-Cooperators-Insurance-Prediction-

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
