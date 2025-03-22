Here's a more polished and professional version of your text with enhanced readability, clarity, and the addition of emojis for better presentation:  

---

# 🚀 Bitcoin Price Prediction Using Machine Learning  

## 📌 Overview  

This project focuses on predicting Bitcoin prices using historical data and advanced machine-learning techniques. We employed **data processing, feature engineering, and model building** to identify the most effective model for price prediction. The models explored include:  
✅ **XGBoost**  
✅ **K-Nearest Neighbors (KNN)**  
✅ **Linear Regression**  
✅ **Random Forest**  

## 📊 Dataset  

The dataset comprises historical Bitcoin price data with key financial indicators, including:  
📅 **Timestamp**  
📈 **Open Price**  
📊 **High & Low Price**  
💰 **Close Price**  
📦 **Trading Volume**  
💱 **Currency**  
⚖️ **Weighted Price**  

## 🔄 Data Processing  

To ensure high-quality inputs for modelling, the following preprocessing steps were applied:  
1️⃣ **Loading Data** – Data is imported from CSV files into structured DataFrames.  
2️⃣ **Handling Missing Values** – Missing entries are imputed using appropriate statistical techniques.  
3️⃣ **Data Normalization** – Features are scaled to maintain uniformity and improve model performance.  

## 🏗️ Feature Engineering  

📌 **Feature Extraction** – Advanced features such as rolling averages and volatility indicators are derived.  
📌 **Feature Selection** – Irrelevant features are eliminated to enhance efficiency and accuracy.  

## 📉 Stationarity Check  

To confirm that the time series data is suitable for modelling, we conducted a **stationarity check** using the **Augmented Dickey-Fuller (ADF) test**. This helps determine whether transformations like differencing are required.  

## ⚙️ Model Building  

We implemented and assessed multiple machine learning models to identify the best-performing one:  

🔹 **Linear Regression** – Establishes baseline predictions by modelling linear relationships.  
🔹 **K-Nearest Neighbors (KNN)** – Captures local patterns using a non-parametric approach.  
🔹 **Random Forest** – Enhances accuracy through an ensemble of decision trees.  
🔹 **XGBoost** – Leverages gradient boosting for superior predictive performance.  

## 📊 Model Evaluation  

Each model was rigorously evaluated based on performance metrics such as **Mean Squared Error (MSE), Mean Absolute Error (MAE)**. The model delivering the highest accuracy and reliability on the validation set was selected as the final predictive model.  
