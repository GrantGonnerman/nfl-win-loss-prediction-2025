# NFL Win-Loss Prediction 2025

**Sports Analytics & Predictive Modeling Project** | Predicting NFL game outcomes using historical team statistics and advanced features.

## 📋 Project Overview
This project builds machine learning models to predict NFL game winners (Win/Loss) for the 2025 season. By aggregating and engineering team performance metrics, the models provide data-driven insights for sports betting, fantasy football, or team performance analysis.

## 🎯 Business / Real-World Value
Accurate NFL outcome prediction has significant applications in sports betting, fantasy sports, coaching decisions, and sports media analytics. This project demonstrates practical application of predictive analytics in sports.

## 🗂️ Dataset
- **Source**: Historical NFL game and team statistics ([Yahoo Sports](https://sports.yahoo.com/nfl/stats/weekly))
- **Target**: Binary classification (`Win` / `Loss`) for each team in a matchup
- **Features**: Offensive/defensive ratings, yards per game, turnover differentials, home/away advantage, recent form, strength of schedule, and many engineered features.

## 🔧 Key Techniques & Models
- **Data Processing**: Data aggregation (`Data_agg.ipynb`), feature engineering, and advanced statistics creation
- **Exploratory Data Analysis**: Season trends, team performance distributions, and key predictor analysis
- **Modeling**:
  - Logistic Regression (baseline)
  - Random Forest
  - Gradient Boosting
  - XGBoost, LightGBM, CatBoost
- **Advanced Techniques**: Hyperparameter tuning, feature importance analysis, model comparison, and probability calibration

## 📊 Results
- Strong predictive performance using ensemble tree-based models (XGBoost / LightGBM)
- Identified the most important factors for predicting game outcomes (e.g., turnover margin, offensive efficiency, home advantage)
- Achieved competitive accuracy and log-loss on validation/test sets

## 📄 Reports
- [Full Project Report (PDF)](NFL%20Win-Loss%20Prediction%202025/Reports/NFL%20Win-Loss%20Prediction%202025%20Report.pdf)
- [Presentation Slides (PDF)](NFL%20Win-Loss%20Prediction%202025/Reports/NFL%20Win-Loss%20Prediction%202025%20Slides.pdf)

## 🛠️ Technologies Used
**Python** • **pandas** • **scikit-learn** • **XGBoost** • **LightGBM** • **CatBoost** • **Matplotlib** • **Seaborn**
