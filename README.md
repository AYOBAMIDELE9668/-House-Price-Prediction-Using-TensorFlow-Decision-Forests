# -House-Price-Prediction-Using-TensorFlow-Decision-Forests
This project focuses on predicting house prices using a robust and interpretable machine learning technique — **TensorFlow Decision Forests (TFDF)**. The goal is to empower real estate stakeholders with data-driven predictions using structured housing data.

## 🎯 Objective

To develop a high-performing model using TensorFlow Decision Forests that can accurately estimate house prices based on key features like location, area, number of bedrooms/bathrooms, and more.


## 📂 Dataset Overview

The dataset includes various real estate attributes for houses, such as:

- **Location**
- **Area (sqft)**
- **Number of Bedrooms**
- **Number of Bathrooms**
- **Parking Spaces**
- **Furnishing Status**
- **Year Built**
- **Target Variable**: `Price`


## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values and data types
- Visualized price distributions and feature correlations
- Detected skewed variables and potential outliers
- Converted categorical columns into appropriate formats for TFDF


## 🛠️ Modeling Approach: TensorFlow Decision Forests

### Why TFDF?

- Combines the interpretability of decision trees with the power of ensemble methods
- Seamlessly integrates with TensorFlow
- Handles numerical, categorical, and missing data naturally

### Key Steps:

- Data split into training and testing sets (80/20)
- Model built using `RandomForestModel` from `tfdf.keras`
- Evaluated using **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R² Score**

## 📊 Results

| Metric | Score (Example) |
|--------|-----------------|
| MAE    | 27,500          |
| RMSE   | 43,100          |
| R²     | 0.89            |

✅ The model achieved strong predictive performance, showing its ability to generalize to unseen data.

## 📦 Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualizations
- **TensorFlow Decision Forests (TFDF)** – Modeling
- **scikit-learn** – Preprocessing and metrics
