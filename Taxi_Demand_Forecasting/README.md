Taxi Demand Forecasting
Project Type: Time Series Forecasting | Machine Learning

Project Overview
Sweet Lift Taxi wants to optimize driver availability by predicting hourly taxi demand. Using historical order data, we developed a machine learning model to forecast demand, ensuring that the Root Mean Squared Error (RMSE) does not exceed 48 on the test set.

Dataset
The dataset contains timestamped taxi orders collected at airports. The data has been resampled to one-hour intervals for better forecasting.
🔹File: taxi.csv
🔹Target Variable: num_orders (Number of taxi orders per hour)

Goals & Objectives
🔹Preprocess & Analyze Data – Clean and resample the dataset for modeling.
🔹 Train & Evaluate Models – Experiment with different algorithms and hyperparameters.
🔹 Optimize for Accuracy – Ensure the final model achieves an RMSE below 48.

Technologies Used
🔹Python (Pandas, NumPy, Matplotlib, Seaborn)
🔹Machine Learning: Scikit-learn, XGBoost, LightGBM
🔹Regression Models: Linear Regression, Gradient Boosting, LightGBM
🔹Time Series Forecasting: Resampling, feature engineering

Model Performance & Results
We trained and tested multiple models, including Linear Regression, Gradient Boosting, XGBoost, and LightGBM.
🔹LightGBM achieved the best performance with an RMSE of 41.17, well below the target threshold of 48.
🔹Gradient Boosting (RMSE: 45.16) and XGBoost (RMSE: 46.33) also performed well, but LightGBM captured the trends in the data more effectively.

How to Use
1️⃣Clone the repository:
git clone https://github.com/JuanDivine/Data_Projects_TripleTen.git

2️⃣Navigate to the project directory:
cd Taxi_Demand_Forecasting

3️⃣Open taxi_demand.ipynb in Jupyter Notebook and run the analysis.

Final Insights
This project successfully developed an accurate time series forecasting model for taxi demand. LightGBM was the most effective model, making it a viable solution for optimizing driver distribution during peak hours.