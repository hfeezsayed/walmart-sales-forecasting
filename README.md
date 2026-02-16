🛒 Walmart Sales Forecasting – Retail Analysis Project

📌 Project Overview

This project analyzes historical Walmart sales data (2010–2012) to:
Identify top-performing stores
Analyze seasonal trends
Evaluate holiday impact
Calculate quarterly growth rates
Build a predictive sales forecasting model
The objective is to understand demand patterns and develop a model to forecast weekly sales.

📂 Dataset Description

The dataset includes weekly sales data for 45 Walmart stores with the following features:
Store,
Date,
Weekly_Sales,
Holiday_Flag,
Temperature,
Fuel_Pri,
Unemployment

🔎 Exploratory Data Analysis (EDA)

1️⃣ Store Performance

Store 20 generated the highest total sales.
Store 14 showed the highest sales volatility.

2️⃣ Holiday Analysis

Holiday weeks increased sales by approximately 0.10%.
December consistently recorded peak sales across all years.

3️⃣ Quarterly Growth (Q3 2012)

Most stores experienced negative growth in Q3 2012 compared to Q2 2012.

4️⃣ Monthly & Semester Trends

Strong seasonal pattern observed.
H2 outperformed H1 in 2010 and 2011.
H2 2012 decline due to incomplete year data.

🤖 Machine Learning Model

A Linear Regression model was built for Store 1 using:
Fuel Price
CPI
Unemployment
Holiday Flag
Month, Year, Week

Model Performance:

R² Score ≈ 0.25
MAE ≈ 46,000
RMSE ≈ 67,800

Conclusion:

Economic indicators have limited predictive impact on sales. Time-based features significantly influence forecasting accuracy.

🛠 Technologies Used

Python,
Pandas,
NumPy,
Matplotlib,
Seaborn,
Scikit-learn,
Jupyter Notebook,
VS Code

🎯 Key Takeaways

Sales show strong seasonality.
Holiday spikes are concentrated in December.
Linear regression provides baseline performance.
Advanced models can improve forecasting accuracy.

📌 Author
Your Name: Hafeez Ali
Data Science with Python Project
