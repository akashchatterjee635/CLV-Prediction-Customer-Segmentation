1. Data Cleaning & Preprocessing
Loaded real-world transactional data (Online Retail).

Handled missing values, removed invalid rows, created TotalPrice.

2. RFM Analysis
Computed Recency, Frequency, and Monetary values per customer.

Scored each RFM feature (1–5 scale) and created a RFM_Score.

This identifies high-value customers (e.g., those who buy often and spend more).

3. Customer Segmentation (K-Means)
Clustered customers using RFM features.

Identified distinct customer segments (e.g., loyal, dormant, big spenders).

Visualized clusters to understand behavior.

4. Customer Lifetime Value (CLV) Prediction
Engineered features like:

AvgOrderValue

NumOrders

DaysActive

Trained a linear regression model to predict CLV.

Evaluated model performance (R², RMSE).# CLV-Prediction-Customer-Segmentation
