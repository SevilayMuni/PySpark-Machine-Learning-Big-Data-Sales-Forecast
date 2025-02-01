# PySpark & Machine Learning for Big Data Sales Prediction

<div align="center">
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" >
<img src="https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16" >
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" >
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" >
<img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252" >
</div>

## 📌 Project Overview
The project is a tutorial for a *sales forecasting* model using **PySpark** and **XGBoost**, optimizing predictions with **Optuna**. The dataset consists of **Kaggle-branded sticker sales across various countries and stores**. Feature engineering addresses *seasonality, holiday effects, and store-specific trends*, mimicking real-world e-commerce challenges.

## 🚀 Key Features
- **Big Data Processing with PySpark**: Efficient handling of 230K+ records.
- **Feature Engineering**: Extracted insights from dates, holidays, and store trends.
- **XGBoost Optimization**: Used **Optuna** for hyperparameter tuning.
- **Country-Specific Models**: Tailored models for each market.
- **Visualizations**: Impact of holidays, seasons, and sales trends.

## 🛠️ Tech Stack
- **Data Processing**: PySpark (DataFrame API, SQL functions)
- **Feature Engineering**: Time-based transformations, holiday detection
- **Modeling**: XGBoost with Optuna hyperparameter tuning
- **Evaluation Metrics**: RMSE, MAE, MAPE, R²
- **Visualization**: Matplotlib, Seaborn

## 📊 Data Pipeline
1. **Data Cleaning & Preprocessing**:
   - Handled missing values via mean imputation.
   - Converted date columns into meaningful time features.
2. **Feature Engineering**:
   - **Holidays & Seasonality**: Incorporated retail-specific events.
   - **Cyclical Encoding**: Represented time-based features properly.
3. **Machine Learning Model**:
   - XGBoost with Optuna tuning for hyperparameter optimization.
   - Separate models trained per **country and product**.
4. **Evaluation & Insights**:
   - Identified top-performing stores and seasonal trends.

## 🔍 Key Findings
📈 **Sales Spike on Holidays**: Christmas, Black Friday, and regional holidays heavily impact demand.  
📆 **Seasonality Matters**: Strong sales fluctuations between summer and holiday periods.  
🏬 **Store-Specific Variations**: Premium stores outperform discount stores in key regions.

## 🏆 Results
| Country  | RMSE  | MAE   | MAPE(%) | R² Score | Accuracy(%) |
|----------|-------|-------|---------|----------|-------------|
| Italy    | 43.03 | 27.03 | 5.1%    | 0.985    | 99.95%      |
| Singapore| 68.87 | 43.98 | 5.2%    | 0.985    | 99.94%      |
| Finland  | 64.67 | 39.89 | 5.4%    | 0.983    | 99.94%      |
| Canada   | 107.04| 53.53 | 9.0%    | 0.945    | 99.91%      |
| Kenya    | 2.53  | 1.38  | 9.1%    | 0.951    | 99.91%      |

## 🎯 Next Steps
✅ Integrate into a **real-time forecasting API**.  
✅ Deploy as a **dashboard for sales predictions**.  
✅ Explore **Deep Learning (LSTMs)** for time-series analysis.

📌 **Connect on LinkedIn** if you want to collaborate or discuss insights from this project! 🚀
