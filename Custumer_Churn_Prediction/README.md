Customer Churn Prediction
Project Type: Machine Learning | Classification

Project Overview
Interconnect, a telecom provider, wants to predict customer churn to improve retention strategies. By analyzing contract details, service usage, and customer data, we built a machine learning model to identify users at risk of churning. This allows the company to proactively offer incentives and improve customer satisfaction.

Dataset
The dataset contains information about customer contracts, personal details, and service usage patterns. The target variable is whether a customer churned (EndDate column = 'No').

Files in the dataset:
🔹contract.csv – Contract details (contract type, monthly charges, tenure)
🔹personal.csv – Customer demographic data
🔹internet.csv – Information about internet services used
🔹phone.csv – Details about telephone service

Goals & Objectives
🔹 Develop a predictive model to identify customers at risk of churning.
🔹 Minimize false negatives to avoid missing churned customers.
🔹 Evaluate model performance using AUC-ROC and accuracy.

Technologies Used
🔹Python (Pandas, NumPy, Matplotlib, Seaborn)
🔹Machine Learning: XGBoost, Scikit-learn
🔹Evaluation Metrics: AUC-ROC, Accuracy
🔹Feature Engineering: Handling categorical data, scaling numerical features

Model Performance & Results
🔹XGBoost achieved an AUC-ROC score of 0.8222, indicating strong predictive performance.
🔹Missed churners (False Negatives) were minimal, ensuring that at-risk customers are accurately identified.

How to Use
1️⃣Clone the repository:
git clone https://github.com/JuanDivine/Data_Projects_TripleTen.git

2️⃣Navigate to the project directory:
cd Customer_Churn_Prediction

3️⃣Open customer_churn.ipynb in Jupyter Notebook and run the analysis.

Final Insights
This project provides a robust foundation for predicting churn, allowing Interconnect to improve customer satisfaction and retention by proactively addressing churn risks.