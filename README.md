# 🏠 House Price Prediction

## 📌 Project Overview
This project focuses on **predicting house prices** using data analysis and machine learning techniques.  
The workflow includes:
- Data loading & cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Statistical analysis & multicollinearity checks  
- Feature scaling  
- Building a **Linear Regression model** to predict house prices  

---

## 📂 Steps in the Notebook

### 1️⃣ Import Libraries
- Imported essential Python libraries: **pandas, numpy, seaborn, matplotlib, warnings**  
- Used for data handling, numerical operations, visualization, and ignoring warnings  

### 2️⃣ Load Dataset & Initial Exploration
- Loaded the dataset: **Housing.csv**  
- Checked:
  - Column names  
  - Dataset shape (rows & columns)  
  - First & last 5 rows (`head()`, `tail()`)  
  - Info of dataset (`info()`)  
  - Statistical summary (`describe()`)  
  - Count of unique values (`nunique()`)  

### 3️⃣ Descriptive Statistics
- Calculated **Mean, Median, Mode, Standard Deviation** for numerical key features 

### 4️⃣ Data Visualization (EDA)
- Used **Seaborn & Matplotlib** for visual insights:
  - Distribution plots of features  
  - Scatter plots   
  - Correlation heatmap  

### 5️⃣ Handling Categorical Variables
- Converted categorical columns into numerical using **encoding**    

### 6️⃣ Multicollinearity Check (VIF)
- Applied **Variance Inflation Factor (VIF)** to detect multicollinearity  
- Dropped features with **VIF > 10** to improve model stability  

### 7️⃣ Feature Scaling
- Applied **StandardScaler** to normalize feature values and created `X_scaled`  

### 8️⃣ Train-Test Split
- Split data into:
  - **Training set → 80%**  
  - **Testing set → 20%**  

### 9️⃣ Model Training – Linear Regression
- Trained a **Linear Regression** model  
- Evaluated performance using metrics:
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - Mean Absolute Error (MAE)  
  - R-squared (R²)  

### 🔟 Results
- The model explained a **good portion of variance** in house prices  
- Predictions captured the relationship between house features and price  

---

## 🚀 Key Learnings
- Cleaning & exploring a housing dataset  
- Understanding descriptive statistics & EDA  
- Handling **multicollinearity** with VIF  
- Applying **feature scaling** before model training  
- Training & evaluating a **Linear Regression** model  

---

## 🛠️ Tools & Libraries
- **Python**  
- **pandas, numpy** → Data handling  
- **seaborn, matplotlib** → Visualization  
- **sklearn** → Scaling, Train-Test Split, Linear Regression, Metrics  
- **statsmodels** → VIF calculation  
