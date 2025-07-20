# 🏙️ London House Price Prediction — Advanced Techniques  
This project focuses on predicting house prices in London using advanced machine learning and data preprocessing techniques. It showcases a full end-to-end pipeline including feature engineering, scaling, model tuning, and evaluation — designed for those who want to go beyond basic regression.  

## 📌 Problem Statement  
The goal is to build a robust regression model that can predict housing prices in London based on various factors such as number of rooms, location, crime rate, transport accessibility, and more.  

## 🛠️ Techniques Used  
This project applies a wide range of advanced ML techniques:  
- 📊 Feature Engineering: Handling missing values, encoding, log transforms  
- ⚖️ Scaling & Normalization: StandardScaler, MinMaxScaler  
- 🧪 Train/Test Splitting with Stratification  
- 🔁 Cross-Validation (K-Fold)  
- 🔍 Hyperparameter Optimization: GridSearchCV, RandomizedSearchCV  
- 🧠 Algorithms:  
  - Linear Regression (baseline)  
  - Ridge & Lasso Regression  
  - Random Forest Regressor  
  - Gradient Boosting Regressor  
  - XGBoost & LightGBM  
- 🧵 Pipelines for cleaner and reproducible code  
- 📈 Evaluation Metrics: MAE, MSE, RMSE, R²  

## 📁 Project Structure  
- `data/` — raw and cleaned datasets (`London_data.csv`, `processed_data.csv`)  
- `notebooks/` — full analysis, modeling, and experiment tracking  
- `models/` — saved trained models for later use  
- `outputs/` — plots, feature importance visuals, and predictions  
- `requirements.txt` — all dependencies  
- `.gitignore` — files excluded from version control  
- `README.md` — this documentation  

## 💡 Key Insights  
- Feature selection and regularization significantly reduce overfitting  
- Boosting algorithms (especially LightGBM) performed best on validation data  
- Log transformation on target variable improved model stability  
- Pipelines helped streamline the workflow and ensure reproducibility  

![london](https://github.com/user-attachments/assets/8380448d-2024-452d-8679-1cd99a339e1e)


## 🚀 How to Run  
1. Clone the repository:  
```  
git clone https://github.com/SergKhachikyan/London_House_Price_Prediction_Advanced_Techniques.git  
cd London_House_Price_Prediction_Advanced_Techniques
```
2.Install dependencies:
```
pip install -r requirements.txt  
```
3.Launch the notebook:
```
jupyter notebook notebooks/London_House_Price_Regression.ipynb  
```

## 📊  Evaluation
.The models were evaluated using:

.Mean Absolute Error (MAE)

.Root Mean Squared Error (RMSE)

.R² Score

.Best Model: LightGBM with tuned parameters and full pipeline integration.

## 🔮 Future Improvements
.Incorporate more location-based features (e.g. distance to subway, parks)

.Try stacking and ensemble models

.Deploy the best model using Flask/FastAPI for real-time predictions
