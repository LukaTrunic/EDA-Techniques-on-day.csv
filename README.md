# 🚲 Bike Sharing Demand Prediction – AI Final Project

This project focuses on **exploratory data analysis (EDA)**, **data preprocessing**, and **machine learning** using the **Bike Sharing Dataset**. The goal is to predict daily bike rental counts based on historical weather and seasonal data.


## 📌 Objective

Apply EDA and data preprocessing techniques to prepare a dataset for machine learning. Train and evaluate a predictive model to estimate the number of bike rentals based on contextual features like season, temperature, humidity, and more.


## 🔍 Dataset Description

- **Source**: UCI Machine Learning Repository – Bike Sharing Dataset
- **Records**: Daily observations over two years
- **Features**: 
  - `season`, `yr`, `mnth`, `holiday`, `weekday`, `workingday`
  - `temp`, `atemp`, `hum`, `windspeed`
  - `casual`, `registered`, `cnt` (target)


## 🔬 Exploratory Data Analysis (EDA)

- Dataset overview and structure
- Missing values check
- Summary statistics for numerical features
- Visualizations:
  - Histograms & boxplots to examine distributions and outliers
  - Correlation heatmap to evaluate feature relationships
  - Time series plot for target trend


## 🧹 Preprocessing Steps

- No missing data: dataset is clean
- Feature encoding for categorical variables
- Feature scaling using MinMaxScaler
- Train-test split for model evaluation


## 🤖 Machine Learning Model

- Model: **Linear Regression**
- Target: `cnt` (total bike rentals per day)
- Evaluation:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Square Error)
  - R² Score


## 📈 Results

The model successfully learns the relationship between environmental and seasonal factors and daily bike demand. Evaluation metrics are documented and discussed in the notebook.


## 🧠 Technologies Used

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook


## 📝 Instructions to Run

1. Download the 
   ```bash
   final.ipynb
   ```

2. Drag it to google drive and open it in Google Colab

3. Install the dataset 
   ```bash
   day.csv
   ```
   and put it in the files


## 📬 Author

Luka Trunić
