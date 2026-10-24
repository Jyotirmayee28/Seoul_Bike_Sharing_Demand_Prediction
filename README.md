# 🚲 Seoul Bike Sharing Demand Prediction
🚀 Machine Learning System for Predicting Bike Rental Demand


---

## 📜 Project Overview  
The **Seoul Bike Sharing Demand Prediction System** is a Machine Learning-based project designed to predict the number of bikes rented based on various environmental, seasonal, and operational factors. The system analyzes factors such as **temperature, humidity, wind speed, visibility, rainfall, snowfall, season, holiday status, and functioning day** to understand their impact on bike rental demand.

The project uses **Exploratory Data Analysis (EDA)** and data preprocessing techniques to clean and prepare the dataset for Machine Learning. Missing values and duplicate records are handled, while the **Interquartile Range (IQR)** method is used to identify and remove outliers from the target variable.

Categorical features such as **Seasons, Holiday, and Functioning Day** are converted into numerical values using Label Encoding. A **Linear Regression** model is then trained to predict bike rental demand and evaluated using **Mean Squared Error (MSE)**.

---

## 🎯 Key Features  
✅ Bike rental demand prediction using Machine Learning 🚲  
✅ Exploratory Data Analysis using visualizations 📊  
✅ Missing-value and duplicate-record handling 🧹  
✅ Outlier detection using the IQR method 🔍  
✅ Categorical data encoding using Label Encoder 🔢  
✅ Linear Regression-based prediction 🤖  
✅ Model evaluation using Mean Squared Error 📈  
✅ Feature coefficient analysis to understand feature impact 🔬

---

## 🛠️ Tech Stack  
- **Programming Language**: Python 🐍  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn  
- **Algorithm**: Linear Regression  
- **Preprocessing**: Label Encoding, Missing Value Handling, Outlier Removal  
- **Model Evaluation**: Mean Squared Error (MSE)  
- **Dataset**: Seoul Bike Sharing Dataset (`SeoulBikeData.csv`)

---

## 🖥️ How It Works

1️⃣ **Load Dataset:** Import the Seoul Bike Sharing dataset using Pandas and inspect the available records and features.

2️⃣ **Data Cleaning:** Remove missing values and check for duplicate records to improve the quality of the dataset.

3️⃣ **Outlier Detection:** Apply the **Interquartile Range (IQR)** method to identify and remove extreme values from the bike rental count.

4️⃣ **Date Processing:** Convert the `Date` column into a proper datetime format for structured data handling.

5️⃣ **Feature Encoding:** Convert categorical features such as `Seasons`, `Holiday`, and `Functioning Day` into numerical values using Label Encoding.

6️⃣ **Feature Selection:** Separate the input features from the target variable, **Rented Bike Count**, while excluding the `Date` column.

7️⃣ **Train Model:** Split the dataset into training and testing sets using an **80/20 train-test split** and train a Linear Regression model.

8️⃣ **Generate Predictions:** Use the trained model to predict bike rental demand for the test dataset.

9️⃣ **Evaluate Model:** Evaluate prediction performance using **Mean Squared Error (MSE)** and analyze the model coefficients to understand the contribution of different features.

---

## 📊 Model

**Algorithm Used:** Linear Regression

The model learns the relationship between environmental and operational factors and the number of rented bikes.

**Target Variable:** `Rented Bike Count`

**Train-Test Split:** 80% Training | 20% Testing

**Evaluation Metric:** Mean Squared Error (MSE)

