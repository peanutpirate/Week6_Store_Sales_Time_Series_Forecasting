# 🚀 Week6_Store_Sales_Time_Series_Forecasting  

A fun time series forecasting project predicting store sales using historical sales, promotions, holidays, and external factors. Developed as part of my 6th-week data science journey.  

📌 **Project Overview**  
This project focuses on predicting daily sales per store & product category.  
We leverage past sales, promotions, holidays, and oil price to forecast future demand.  

📊 **Dataset**  
- **Source:** [Kaggle Store Sales Time Series Dataset](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)  
- **Train size:** ~2.5M rows (download from Kaggle)  
- **Test size:** ~0.3M rows (download from Kaggle)  
- **Target variable:** `sales`  

🛠️ **Tools & Technologies**  
- Python 🐍  
- Pandas, NumPy 📊  
- Scikit-learn, LightGBM ⚡  
- Matplotlib / Seaborn 📈  
- Google Colab ☁️  

🔍 **Approach**  
1. Exploratory Data Analysis (EDA) 🔎  
2. Missing value handling 💧  
3. Feature engineering ✨ (lag features, rolling stats, date features)  
4. Baseline modeling (Naive & Linear Regression) 📝  
5. Machine learning modeling with LightGBM 🏎️  
6. Evaluation using RMSLE metric 📏  
7. Submission generation 📤  

🤖 **Models Used**  
- Linear Regression 📝  
- LightGBM Regressor ⚡  

📈 **Results**  
- Baseline RMSLE: 2.28  
- Linear Regression RMSLE: 2.28  
- LightGBM RMSLE: improved after tuning  
- Kaggle Score: 55.43 🎯  

📁 **Repository Structure**  
- `notebooks/`  → Jupyter notebooks 🗒️  
- `data/`       → **Download data from Kaggle** [link](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data) 📂  
- `outputs/`    → Submission files 📝  

💡 **Note:**  
Due to dataset size, train CSV file are **not included** in the repo. Please download them directly from Kaggle and place in `data/` folder.  

🔗 **Kaggle Link**  
[Store Sales Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)
