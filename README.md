📊 Customer Churn Prediction Using Machine Learning

This is a Machine Learning project that predicts whether a customer will Churn (leave the company) or Stay based on various factors like contract type, payment method, monthly charges, tenure, and service usage.

⭐ Project Overview

This project includes:

✔ Data Cleaning

Handling missing values

Converting TotalCharges into numeric

Removing invalid rows

✔ Feature Engineering

Converting categorical columns using One-Hot Encoding

Splitting data into Train/Test

Feature Scaling using StandardScaler

✔ Model Training

Trained using Logistic Regression with:

max_iter=2000

Feature Scaled Inputs

✔ Model Evaluation

Used following metrics:

Accuracy Score

Precision

Recall

F1-Score

Confusion Matrix

📌 Model Performance
Metric	Score
Accuracy	~80%
Precision (Churn)	~65%
Recall (Churn)	~58%
F1-score (Churn)	~61%
ROC-AUC Score	~81%

🔎 This performance is normal because the dataset is imbalanced (26% churn, 74% non-churn). Logistic Regression still performs well and gives interpretable results.

🧠 Why Customer Churn Prediction Matters?

Telecom companies lose revenue when customers leave.
Predicting churn helps companies:

Improve customer retention

Provide personalized offers

Identify at-risk customers

Reduce business loss

🛠 Tech Stack Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib / Seaborn (Optional for EDA)

Jupyter Notebook

📁 Project Structure
Customer-Churn-Prediction-ML-Project/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── /images
     ├── screenshot1.png
     ├── screenshot2.png

📷 Project Screenshots

Add screenshots like this:

![Model Output](images/screenshot1.png)
![Confusion Matrix](images/screenshot2.png)

🚀 How to Run This Project

Clone this repository

git clone https://github.com/<your-username>/Customer-Churn-Prediction-ML-Project.git


Install required libraries

pip install numpy pandas scikit-learn


Open Jupyter Notebook

jupyter notebook


Run all cells inside
Customer_Churn_Prediction.ipynb

🎯 Conclusion

The model predicts churn with 80% accuracy

Helps companies identify customers likely to leave

Logistic Regression is simple, fast, and interpretable

🤝 Connect With Me

If you liked this project or want to collaborate, feel free to contact me on LinkedIn 😊
