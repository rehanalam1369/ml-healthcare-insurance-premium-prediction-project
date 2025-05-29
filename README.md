# ml-healthcare-premium-insurance-prediction-project
Healthcare premium insurance  prediction project

🏥 ML Healthcare Premium Insurance Prediction Project
This project predicts health insurance premium costs based on various user attributes using machine learning. It includes a deployed Streamlit web application where users can input demographic and medical details to receive a cost prediction.

🚀 Demo


Check out the app here: Streamlit App Link


https://ml-healthcare-insurance-premium-prediction-project.streamlit.app/

📌 Features
Streamlit-powered UI for user interaction

Dynamic input form (age, region, smoking status, etc.)

Intelligent preprocessing of inputs

Separate models for different age groups (≤25 and >25)

Model & scaler loading with joblib

Risk normalization from medical history

📂 Project Structure

ml-healthcare-premium-insurance-prediction-project/
│
├── artifacts/
│   ├── model_young.joblib
│   ├── model_rest.joblib
│   ├── scaler_young.joblib
│   └── scaler_rest.joblib
│
├── main.py                   # Streamlit frontend code
├── prediction_helper.py      # Model logic and preprocessing
├── requirements.txt
└── README.md
🛠 Technologies Used
Python 🐍

Streamlit 🎈

Scikit-learn 🤖

Pandas 🐼

Joblib 💾

📊 Input Features
Age

Number of Dependents

Income (in Lakhs)

Genetical Risk Score (0–5)

Insurance Plan (Bronze/Silver/Gold)

Employment Status

Gender

Marital Status

BMI Category

Smoking Status

Region

Medical History (e.g., Diabetes, Heart disease, etc.)

📈 Model Details
Two separate models:

model_young: for users ≤ 25 years

model_rest: for users > 25 years

Custom scaling logic for numerical features

One-hot encoding for categorical features

Normalized risk score derived from medical history

📌 Future Improvements
Add visualizations for predicted vs actual values

Deploy with Docker

Add CI/CD pipeline

Integrate with cloud-based APIs (e.g., Google Cloud AI)

🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

📜 License
This project is part of the Codebasics ML course. All rights reserved to codebasics.io.

