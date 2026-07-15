# 🛒 Big Mart Sales Prediction Using Machine Learning

## 📌 Project Overview

This project demonstrates how to build a **Machine Learning Regression Model** to predict **product sales in Big Mart outlets** using the **XGBoost Regressor**.

The notebook covers the complete machine learning workflow, including data exploration, preprocessing, feature engineering, model training, evaluation, and sales prediction. It uses the **Big Mart Sales Dataset**, which contains product and outlet information collected from different Big Mart stores.

XGBoost is chosen because of its excellent performance on structured tabular datasets and its ability to capture complex non-linear relationships.

---

## 🎯 Objectives

- Understand the Big Mart Sales dataset
- Perform Exploratory Data Analysis (EDA)
- Handle missing values and inconsistent data
- Apply feature engineering and categorical encoding
- Train an XGBoost Regression model
- Evaluate model performance using regression metrics
- Predict product sales for unseen data

---

## 📂 Dataset

**Dataset Used:** Big-Mart-Dataset.csv

The dataset contains information about products sold across multiple Big Mart outlets.

### Features Include

- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type

### Target Variable

- **Item_Outlet_Sales**

---

## 📖 Concepts Covered

- Regression Analysis
- Exploratory Data Analysis (EDA)
- Missing Value Treatment
- Feature Engineering
- Label Encoding
- Data Preprocessing
- Train-Test Split
- XGBoost Regression
- Model Evaluation
- Feature Importance
- Sales Prediction

---

## 🛠️ Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## ⚙️ Implementation Steps

### Data Loading

- Load the Big Mart Sales dataset
- Explore dataset structure
- Analyze numerical and categorical features

### Data Preprocessing

- Handle missing values
- Clean inconsistent categorical values
- Encode categorical variables
- Prepare data for model training

### Exploratory Data Analysis (EDA)

- Study feature distributions
- Analyze relationships between variables
- Visualize sales patterns
- Identify important predictors

### Model Training

- Split dataset into training and testing sets
- Train the XGBoost Regressor
- Learn relationships between product features and sales

### Model Evaluation

- Calculate R² Score
- Compute Mean Absolute Error (MAE)
- Compute Mean Squared Error (MSE)
- Compare predicted and actual sales

### Prediction

- Predict sales for unseen products
- Analyze model performance on new data

---

## 🔍 Key Observations

- XGBoost performs exceptionally well on structured tabular datasets.
- Proper preprocessing and feature engineering significantly improve prediction accuracy.
- Product price (MRP), outlet characteristics, and product type have a strong influence on sales.
- Gradient boosting models effectively capture complex relationships among features.

---

## ✅ Advantages

- Complete end-to-end Machine Learning project
- Real-world retail sales prediction problem
- Covers data preprocessing and feature engineering
- High-performance XGBoost implementation
- Easy to understand and beginner-friendly workflow

---

## 💻 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## 🏁 Conclusion

This project demonstrates how **XGBoost Regression** can accurately predict **Big Mart product sales** using product and outlet information. It walks through every stage of the machine learning pipeline—from data preprocessing and feature engineering to model training, evaluation, and prediction—making it an excellent project for learning regression on real-world business data.
