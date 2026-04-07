An end-to-end AI-powered medical diagnosis system that predicts diseases based on user-input symptoms using Machine Learning (Random Forest, XGBoost) and NLP (BERT). The system also integrates SQLite for persistent storage and provides analytics and visualization.


Features:
1)Predict diseases from symptoms
2) Random Forest model (fast & reliable)
3)XGBoost model (high accuracy)
4) BERT model (NLP-based approach)
5) SQLite database integration
6) Confusion Matrix & model evaluation
7) Analytics on stored predictions
8) Multiple test cases for validation

AI-Medical-Symptom-Checker/
│
├── dataset/
│   └── Diseases_and_Symptoms_dataset.csv
│
├── notebook/
│   └── AI_medical_symptom_checker.ipynb
│
├── database/
│   └── medical_ai.db
├── README.md


How to Run : 
1)Load the dataset
2)Train models (RF, XGBoost, BERT)
3)Run prediction system:
4)run()-Enter symptoms: ever chills headache

Input: fever chills sweating headache

Output: Predictions
1. Flu (72.5%)
2. Malaria (18.2%)
3. Dengue (9.3%)

5)SQLite Integration:The system stores predictions in a local database:

