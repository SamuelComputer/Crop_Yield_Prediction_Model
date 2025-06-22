# 🌾 Crop Yield Prediction Model

<p align="center">
  <img src="https://img.shields.io/badge/Python-%2314354C?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-4B0082?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
</p>

---

## 📄 Project Description

This project focuses on predicting crop yield based on multiple environmental and farming factors using Machine Learning regression models. By leveraging historical crop data, the model helps identify key variables that influence agricultural productivity. This project showcases my application of data science and machine learning in the agricultural domain.

---

## 📊 Dataset Overview

**Dataset Source:** [Kaggle - Crop Yield Prediction Dataset](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset/data?select=yield_df.csv)

The dataset includes:

| Feature | Description |
|---------|-------------|
| **ID** | Unique identifier for each farm |
| **Item** | Type of crop cultivated (e.g., Cotton, Carrot, Wheat) |
| **Average_Rainfall (mm/year)** | Average rainfall during crop growth |
| **Average_Temperature** | Average temperature during crop growth |
| **Year** | Year of crop cultivation |
| **Area (Location)** | Geographical area of cultivation |
| **Pesticide_Used (tons)** | Amount of pesticides applied |
| **Yield (hg/ha)** | Crop yield (target variable) |

---

## 🎯 Project Objective

The objective is to:

- Explore relationships between environmental variables and crop yield.
- Build machine learning models that can predict yield based on input features.
- Identify the most significant factors influencing agricultural productivity.

---

## 🧮 Modeling Approach

- **Exploratory Data Analysis (EDA)** was conducted to understand feature distributions and correlations.
- **Feature Encoding** was applied to categorical variables.
- Multiple regression models were trained and evaluated:

### Models Used:

- Linear Regression
- Random Forest Regressor

### Evaluation Metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

### Best Model:

- ✅ **Random Forest Regressor** achieved the best performance across all evaluation metrics.

---

## 🔧 Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit (for deployment interface)
- Git & GitHub

---

## 🚀 Deployment

The project was deployed using **Streamlit** for interactive prediction:

👉 [Demo Application](https://croppy.streamlit.app/)

---

## 📁 Model Storage

The trained Random Forest model is stored as a `.pkl` file (tracked with Git LFS due to file size).

> **Note:** If cloning this repository, ensure Git LFS is installed to retrieve the model file properly.

---

## 📈 Future Improvements

- Incorporate more diverse datasets (soil properties, satellite imagery, NDVI).
- Hyperparameter tuning for improved model accuracy.
- Deploy on cloud infrastructure for real-time prediction service.
- Build REST API using Django or FastAPI for scalable integration.

---

## 🧑‍💻 Author

**Samuel Sunday Iyanu**  
- Agricultural and Bioresources Engineering | Machine Learning Enthusiast  
- [GitHub](https://github.com/SamuelComputer) 

---
