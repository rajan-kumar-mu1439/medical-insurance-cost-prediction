<h1>Medical Insurance Cost Prediction Using Machine Learning</h1>

👉Summary

A machine learning model that predicts medical insurance charges based on demographic and health-related features.

👉 Overview

Medical insurance costs vary significantly depending on factors such as age, BMI, smoking habits, and number of dependents.

This project applies supervised machine learning regression techniques to analyze these factors and predict insurance charges accurately.

The goal is cost estimation, not medical diagnosis—confusing these would be a conceptual error.

👉Objective:

Build a machine learning model that predicts insurance charges using historical customer data with high accuracy.

📊 Dataset:

📂 Source:<a href="https://github.com/rajan-kumar-mu1439/medical-insurance-cost-prediction/blob/main/insurance.csv">Medical Insurance Dataset</a>

👉 Features:

age – Age of the policyholder

sex – Gender

bmi – Body Mass Index

children – Number of dependents

smoker – Smoking status

region – Residential area

charges – Insurance cost (Target Variable)

👉Technologies

Python, NumPy, Pandas, Matplotlib & Seaborn, Scikit-Learn, Jupyter Notebook

👉 Methods & Approach

 -> Step-by-Step Pipeline:

 1.Data Loading

 2.Data Cleaning & Encoding

 3.Exploratory Data Analysis 

 4.Train-Test Split (80% Train / 20% Test)

 5.Regression Model Training

 6.Model Evaluation

 👉Algorithms Used:

-> Linear Regression


👉 Key Insights

 Findings from analysis:

🚬 Smokers pay significantly higher insurance charges

 <img width="545" height="541" alt="Screenshot 2026-01-18 085631" src="https://github.com/user-attachments/assets/42178c4d-6033-4807-9e86-3ef060c67c4e" />


📈 Insurance cost increases with age and BMI

<img width="477" height="497" alt="Screenshot 2026-01-18 085437" src="https://github.com/user-attachments/assets/b0451f96-1d31-4101-9ec5-661ce21ca114" />

<img width="476" height="498" alt="Screenshot 2026-01-18 085537" src="https://github.com/user-attachments/assets/3e413d0e-7803-48a6-96ba-e9da10624c90" />

👶 Number of children has less impact than expected

<img width="533" height="544" alt="Screenshot 2026-01-18 085557" src="https://github.com/user-attachments/assets/0dbe3c28-84e7-4727-b7c5-c8a2eb50dcb0" />


🌍 Region has minor influence

<img width="537" height="543" alt="Screenshot 2026-01-18 085650" src="https://github.com/user-attachments/assets/7bba6358-f5ac-427a-b166-c8fc5e0424c2" />


📊 Dashboard / Model Output

<img width="1536" height="1006" alt="dashboard1" src="https://github.com/user-attachments/assets/2a438e3b-c986-4c1f-a935-ba5ac2081154" />

 
📉 Visual Outputs:

-> Feature vs Charges plots

-> Correlation heatmap

-> Actual vs Predicted graph

📈 Model Performance:

-> hige R² score

-> Low Mean Absolute Error (MAE)


✅ Results & Conclusion

-> The model successfully predicts insurance charges with high accuracy using basic demographic and health data.
-> This proves that machine learning can replace manual premium estimation with better consistency and fairness.

🔮 Future Work

Use advanced models (Random Forest, XGBoost)

Deploy as a web app (Flask / Streamlit)

Add real-time prediction API

Include more health metrics


👤 Author & Contact

👨‍💻 Rajan Kumar

🎓 BCA Final Year Student

Skills: Python, Machine Learning, data Analytic

🔗 LinkedIn: https://www.linkedin.com/in/rajan-kumar-mu1439/

📧 Email: rajankumarmu1439@gmail.com
