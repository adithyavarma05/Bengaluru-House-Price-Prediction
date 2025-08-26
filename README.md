# 🏡 Bengaluru House Price Prediction  

This project implements a **Machine Learning framework** to predict housing prices in Bengaluru’s real-estate market. The model leverages structured data, advanced preprocessing techniques, and regression algorithms to deliver **highly accurate price forecasts**—helping buyers, sellers, and real-estate professionals make data-driven decisions.  

---

## 📂 Project Structure  

- `Bengaluru_House_Data.csv` → Raw dataset containing property details (location, size, total_sqft, bath, price, etc.)  
- `project1.ipynb` → Jupyter Notebook with complete workflow: data cleaning, feature engineering, model training, and evaluation.  

---

## 📊 Dataset Overview  

The dataset consists of Bengaluru housing records with the following key features:  

- **Location** – Area/region of the property  
- **Size** – Number of bedrooms (BHK)  
- **Total Sqft** – Property area in square feet  
- **Bath** – Number of bathrooms  
- **Price** – Target variable (price in lakhs)  

---

## 🔑 Key Steps  

1. **Data Cleaning & Preprocessing**  
   - Handled missing values, inconsistent formats, and outliers.  
   - Converted categorical variables (like location) into numerical encodings.  
   - Standardized numerical features for model efficiency.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of property size, location clusters, and price ranges.  
   - Identified correlations and influential features affecting housing prices.  

3. **Feature Engineering**  
   - Created new features (e.g., price per sqft).  
   - Reduced dimensionality by grouping rare locations.  

4. **Model Development**  
   - Applied multiple regression algorithms: **Linear Regression, Lasso, Decision Trees, Random Forest, and XGBoost**.  
   - Hyperparameter tuning using **GridSearchCV**.  

5. **Performance Evaluation**  
   - Achieved **85%+ predictive accuracy** on test data.  
   - Compared models based on **R² score, RMSE, and MAE**.  

---

## 🚀 Results  

- **Best Model:** Random Forest Regressor (after hyperparameter tuning)  
- **Accuracy:** ~85% on test dataset  
- **Key Insight:** Location, sqft, and number of bathrooms are the most influential predictors.  

---

## ⚙️ How to Run  

1. Clone this repository or download the project files.  
2. Install required dependencies:  

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
