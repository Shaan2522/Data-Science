# Car Sales Forecasting using Machine Learning

📌 Project Overview

This project aims to forecast product sales using machine learning based on historical sales data. By analyzing various factors such as advertising spend, promotions, and customer segmentation, the model helps businesses optimize marketing strategies for sales growth.

🚀 Features

📊 Data preprocessing: Handling missing values, outliers, and feature scaling.

🔍 Exploratory Data Analysis (EDA) to understand key sales trends.

🤖 Model training using regression algorithms to predict future sales.

📈 Model evaluation using appropriate metrics such as RMSE, MAE, and R-squared.

📉 Visualization of predictions and insights for business optimization.

📂 Dataset

The dataset consists of historical sales records, including:

Date: Timestamp of sales record

Sales Volume: Number of units sold

Advertising Spend: Amount spent on marketing

Customer Segments: Demographic information of buyers

Promotional Discounts: Impact of sales promotions on sales volume

🛠 Installation & Setup

Clone this repository:

git clone [https://github.com/yourusername/sales-forecasting.git](https://github.com/Shaan2522/Data-Science.git)

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook or Python script:

jupyter notebook Car_Sales_Price_Prediction.ipynb

🏗 Data Preprocessing

Handling Missing Values: Imputed using mean/median/mode.

Outlier Detection: Used IQR method to remove extreme values.

Feature Scaling: Standardized numerical variables using MinMaxScaler/StandardScaler.

Encoding Categorical Data: Used One-Hot Encoding for categorical features.

🤖 Model Training

Trained Linear Regression, Decision Tree, and Random Forest models.

Compared model performance using:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R-squared score

📊 Model Evaluation & Results

The Random Forest model performed best, achieving the lowest RMSE.

Feature importance analysis revealed that advertising spend and promotional discounts had the highest impact on sales.

Predictions showed a strong correlation with actual sales trends.

🎯 Conclusion

This project demonstrates how machine learning can be leveraged for predicting sales trends and optimizing marketing strategies. Businesses can use the model insights to make data-driven decisions for improved sales performance.
