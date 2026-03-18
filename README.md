# Disease-Prediction-medibot
MediHealBot — AI-Powered Health Monitoring & Disease Prediction System
MediHealBot is a machine learning-based health monitoring system that predicts multiple diseases based on patient input data. Built using Python and Scikit-learn, the system provides health analysis, test summaries, and reports through a Flask-based web dashboard.

Features

Predicts multiple diseases using trained ML models
Machine learning models: Logistic Regression and K-Nearest Neighbors (KNN)
Model evaluation using Accuracy, Precision, Recall, and F1-Score
Flask-based interactive dashboard for health analysis
Generates test summaries and health reports for users


Tech Stack
ComponentTechnologyLanguagePython 3.xML LibraryScikit-learnWeb FrameworkFlaskData ProcessingPandas, NumPyFrontendHTML, CSSModel PersistenceJoblib

Project Structure
mediahealbot/
├── model.pkl            # Trained ML model
├── model.joblib         # Saved model (joblib format)
├── scaler.joblib        # Feature scaler
├── Heart_Disease_Prediction.csv          # Training dataset
├── templates/
│   └── heart.html       # Frontend dashboard
└── README.md

How to Run

Clone the repository

bashgit clone https://github.com/yourusername/mediahealbot.git
cd mediahealbot

Install dependencies

bashpip install flask scikit-learn pandas numpy joblib

Run the application

bashpython app.py

Open your browser and go to

http://localhost:5000

ML Models Used
Logistic Regression

Used for binary disease classification
Fast, interpretable, and effective for medical prediction tasks

K-Nearest Neighbors (KNN)

Classifies based on similarity to nearest data points
Effective for pattern recognition in patient data


Model Evaluation Metrics
MetricDescriptionAccuracyOverall correct predictionsPrecisionHow many predicted positives are actually positiveRecallHow many actual positives were correctly identifiedF1-ScoreBalance between Precision and Recall

Future Improvements

Add more disease prediction modules
Integrate real-time patient data input
Deploy on cloud platform (AWS/Heroku)
Add user authentication for patient privacy


Author
Sri Dhana Varshini
CSE Graduate — Sathyabama Institute of Science and Technology
Chennai, India
