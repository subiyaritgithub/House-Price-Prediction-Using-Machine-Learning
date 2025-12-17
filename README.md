# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview

This project aims to analyze and predict house prices based on various property features such as area, number of bedrooms, bathrooms, stories, parking availability, and additional amenities. The goal is to preprocess real-world housing data and prepare it for machine learning-based price prediction.

## 📊 Dataset Description

The dataset contains **545 housing records** with both numerical and categorical features.

### Key Features:

* **Numerical:** Area, Bedrooms, Bathrooms, Stories, Parking
* **Categorical:** Main Road Access, Guest Room, Basement, Hot Water Heating, Air Conditioning, Preferred Area, Furnishing Status
* **Target Variable:** Price

## ⚙️ Project Workflow

1. **Data Loading**

   * Loaded housing dataset using Pandas.

2. **Exploratory Data Analysis (EDA)**

   * Analyzed data shape, statistics, data types, and missing values.
   * Used correlation matrix and visualizations for insights.

3. **Data Preprocessing**

   * Converted categorical variables (`yes/no`) into numerical format.
   * Encoded furnishing status.
   * Applied feature scaling using `StandardScaler` for numerical features.

4. **Data Visualization**

   * Correlation heatmap to identify relationships.
   * Histograms to understand data distribution.

5. **Feature Selection**

   * Separated independent variables (X) and target variable (y) for machine learning.

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries Used:**
  * Pandas
  * NumPy
  * Scikit-learn
  * Matplotlib
  * Seaborn
* **Platform:** Google Colab

## 📈 Results & Insights

* Strong correlation observed between house price and features like area, bathrooms, and stories.
* Dataset successfully transformed into a machine-learning-ready format.
* Suitable for applying regression models such as Linear Regression, Ridge, or Lasso.

## 📂 Project Structure

📁 House-Price-Prediction
│── house_price.ipynb
│── Housing.csv
│── README.md
