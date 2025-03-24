# Car Sales Forecasting using Machine Learning

📌 Project Overview

    This project aims to forecast product sales using machine learning based on historical sales data. By analyzing various factors such as advertising spend, promotions, and customer segmentation, the model helps businesses optimize marketing strategies for sales growth.

🚀 Features

1. 📊 Data preprocessing: Handling missing values, outliers, and feature scaling.

2. 🔍 Exploratory Data Analysis (EDA) to understand key sales trends.

3. 🤖 Model training using regression algorithms to predict future sales.

4. 📈 Model evaluation using appropriate metrics such as RMSE, MAE, and R-squared.

5. 📉 Visualization of predictions and insights for business optimization.

📂 Dataset

The dataset consists of historical sales records, including:

1. Date: Timestamp of sales record

2. Sales Volume: Number of units sold

3. Advertising Spend: Amount spent on marketing

4. Customer Segments: Demographic information of buyers

5. Promotional Discounts: Impact of sales promotions on sales volume

🛠 Installation & Setup

1. Clone this repository:

```git clone [https://github.com/yourusername/sales-forecasting.git](https://github.com/Shaan2522/Data-Science.git)```

2. Install dependencies:

```pip install -r requirements.txt```

3. Run the Jupyter Notebook or Python script:

```jupyter notebook Car_Sales_Price_Prediction.ipynb```

🏗 Data Preprocessing

1. Handling Missing Values: Imputed using mean/median/mode.

2. Outlier Detection: Used IQR method to remove extreme values.

3. Feature Scaling: Standardized numerical variables using MinMaxScaler/StandardScaler.

4. Encoding Categorical Data: Used One-Hot Encoding for categorical features.

🤖 Model Training

1. Trained Linear Regression, Decision Tree, and Random Forest models.

2. Compared model performance using:

      Mean Squared Error (MSE)

      Mean Absolute Error (MAE)

3. R-squared score

📊 Model Evaluation & Results

1. The Random Forest model performed best, achieving the lowest RMSE.

2. Feature importance analysis revealed that advertising spend and promotional discounts had the highest impact on sales.

3. Predictions showed a strong correlation with actual sales trends.

🎯 Conclusion

This project demonstrates how machine learning can be leveraged for predicting sales trends and optimizing marketing strategies. Businesses can use the model insights to make data-driven decisions for improved sales performance.
