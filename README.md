
# House Price Prediction Using Linear Regression

This project was developed as part of an internship at **Prodigy InfoTech**, where the primary task was to implement a linear regression model to predict house prices based on key housing attributes. The model estimates the `SalePrice` using square footage, number of bedrooms, and the total number of bathrooms, ensuring accurate and interpretable predictions.

---

## 📋 Project Overview

The objective of this project is to develop a robust machine learning model that predicts house prices (`SalePrice`) using three key attributes:
1. **Square Footage**: Above-grade living area (`GrLivArea`).
2. **Number of Bedrooms**: Bedrooms above ground (`BedroomAbvGr`).
3. **Total Bathrooms**: Combined full and half bathrooms.

The project follows a structured approach:
1. **Data Preparation**
2. **Exploratory Data Analysis (EDA)**
3. **Model Development**
4. **Evaluation**
5. **Optimization**

---

## 🛠 Internship Task

As an intern at **Prodigy InfoTech**, the key task was defined as follows:  
**Task 1:** *Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.*

This task was completed by leveraging modern data science tools and adhering to best practices in feature engineering, model development, and evaluation.

---

## 🗂 Dataset

The dataset used in this project is sourced from the Kaggle competition: *[House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)*.

### Key Features:
- **GrLivArea**: Above-grade (ground) living area in square feet.
- **BedroomAbvGr**: Number of bedrooms above ground level.
- **TotalBathrooms**: Custom feature combining full and half bathrooms.

### Dataset Files:
- **Training Data**: Includes `SalePrice` for building the model.
- **Test Data**: Excludes `SalePrice`, used for making predictions.

---

## 🛠️ Tools and Libraries

The project was developed using Python with the following libraries:
- **Data Handling**: `Pandas`, `NumPy`
- **Visualization**: `Matplotlib`, `Seaborn`
- **Machine Learning**: `Scikit-learn`
- **Environment**: Google Colab

---

## 🔍 Project Phases

### 1️⃣ **Data Preparation**
- Cleaned missing values and outliers.
- Engineered the `TotalBathrooms` feature by combining `FullBath` and `HalfBath`.
- Applied a log transformation to normalize skewed variables.

### 2️⃣ **Exploratory Data Analysis (EDA)**
- Analyzed the distributions of the target variable (`SalePrice`) and features.
- Visualized relationships between features using scatter plots.
- Identified feature dependencies using a correlation heatmap.

### 3️⃣ **Model Development**
- Built a linear regression model using `GrLivArea`, `BedroomAbvGr`, and `TotalBathrooms`.
- Regularized the model with Ridge and Lasso techniques to improve generalization.

### 4️⃣ **Evaluation**
- Metrics used:
  - **RMSLE** (Root Mean Squared Logarithmic Error): Measures prediction accuracy.
  - **RMSE** (Root Mean Squared Error): Measures the difference between predicted and actual prices.
  - **R² Score**: Assesses the variance explained by the model.

- **Results**:
  - **RMSLE**: 0.0129
  - **RMSE**: 0.16
  - **R² Score**: 0.8405

### 5️⃣ **Optimization**
- Fine-tuned hyperparameters for Ridge and Lasso regression using Grid Search.
- Experimented with feature scaling (StandardScaler and MinMaxScaler) to improve performance.

---

## 🏆 Acknowledgements

This project was inspired by the Kaggle competition *House Prices: Advanced Regression Techniques*.  
Special thanks to **Prodigy InfoTech** for providing the opportunity to work on this project as part of my internship.

---

