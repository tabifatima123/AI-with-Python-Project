🫀 Cardiovascular Disease Prediction using Machine Learning and Reinforcement Learning

📌 Project Overview

This project presents a hybrid AI system for healthcare decision support that combines supervised machine learning and reinforcement learning to:

Predict the presence of cardiovascular disease in patients using clinical data.

Recommend an optimal medical triage decision (Home Care, Outpatient Care, or Emergency) based on predicted risk.

The project demonstrates how prediction (ML) and decision-making (RL) can work together in real-world healthcare systems.



🧠 Key Concept

Machine Learning (ML) → Disease prediction

Reinforcement Learning (RL) → Decision policy

Hybrid AI System → Prediction + Action

This mirrors how modern intelligent healthcare systems operate under uncertainty.



📊 Dataset

The project uses the Cardio Train Dataset, which contains anonymized patient health records.

Features include:

Age

Gender

Height & Weight

Systolic & Diastolic Blood Pressure

Cholesterol Level

Glucose Level

Smoking Status

Alcohol Intake

Physical Activity

Target Variable:

cardio

1 → Cardiovascular disease present

0 → No cardiovascular disease

The dataset is stored in the data/ directory.

⚙️ Methodology


1️⃣ Data Preprocessing

Cleaning and inspection of clinical features

Handling categorical and numerical variables

Feature selection for modeling


2️⃣ Supervised Machine Learning

Models trained to predict cardiovascular disease

Performance evaluated using accuracy and classification metrics


3️⃣ Reinforcement Learning for Triage

Environment designed using predicted disease risk

Actions:

Home Care

Outpatient Care

Emergency Care

Rewards structured to prioritize patient safety and resource efficiency

📁 Project Structure


AI-with-Python-Project/


│
├── notebooks/

│   └── AI_with_python_project.ipynb

│
├── data/

│   ├── cardio_train.csv
│   └── README.md
│
├── outputs/


│
├── requirements.txt
└── README.md


▶️ How to Run the Project
Step 1: Install Dependencies
pip install -r requirements.txt

Step 2: Open the Notebook
jupyter notebook


Open:

notebooks/AI_with_python_project.ipynb

🧪 Technologies Used

Python

Pandas & NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

🎯 Results & Learning Outcomes

Built a complete end-to-end ML pipeline

Understood how ML predictions inform RL decisions

Learned practical GitHub project structuring

Applied AI concepts to a real healthcare use case

🌱 Future Improvements

Use advanced models (XGBoost, Neural Networks)

Incorporate real-time patient monitoring

Add explainability (SHAP / feature importance)

Deploy as a web-based clinical decision support system





Fatima
AI & Machine Learning Enthusiast
Computer Science & Engineering
