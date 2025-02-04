# Retail_Price_Analysis

## Overview
Retail Price Analysis is a machine learning-based approach designed to analyse retail pricing data, perform feature engineering, train predictive models, and evaluate their performance. It provides insights into pricing trends and allows businesses to optimise their pricing strategies.

### Dataset
The dataset used for this project contains historical retail price data, including attributes such as `qty`, `unit_price`, `comp_1`, and `total_price`. The dataset is preprocessed to handle missing values, detect outliers, and create derived features for better model performance.

### Key Features
📌 **Data Preprocessing**
- Handles missing values using median imputation
- Outlier detection and treatment using the IQR method
- Feature scaling using StandardScaler

📊 **Exploratory Data Analysis (EDA)**
- Correlation heatmap to understand feature relationships
- Feature distribution plots using histograms and KDE

🤖 **Machine Learning Model Implementation**
- Uses Random Forest, Gradient Boosting, and XGBoost Regressors
- 5-fold cross-validation for better generalization
- Model evaluation using MSE, RMSE, MAE, and R² score

🔍 **Prediction & Visualization**
- Generates future price predictions
- Compares actual vs. predicted prices using interactive Plotly charts

### Conclusion
This project demonstrates how machine learning models can be used to analyse and predict retail pricing trends. By leveraging historical price data and predictive modeling, businesses can make informed pricing decisions. Future improvements may include hyperparameter tuning, feature selection, and adding more external factors like seasonal trends.

🔹 **Next Steps**: Optimize model performance, integrate real-time price data, and experiment with deep learning approaches! 🚀

