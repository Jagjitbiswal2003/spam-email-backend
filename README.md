📧 Spam Email Detection Backend

A machine learning–powered backend system that detects whether an email is Spam or Not Spam using NLP techniques and a trained classification model. This API can be integrated with any frontend (React, mobile apps, etc.) to build a full spam detection system.

🚀 Features
🔍 Detects spam emails using ML model
⚡ Fast API response with Flask
📡 REST API ready for frontend integration
🧠 NLP-based preprocessing
🛠 Lightweight and easy to deploy (Render supported)


🏗️ Tech Stack
Backend: Flask
Language: Python
ML Library: Scikit-learn
NLP: NLTK / Text preprocessing
Deployment: Render


📁 Project Structure
spam-email-detection-backend/
│
├── model.pkl              # Trained ML model
├── vectorizer.pkl         # TF-IDF vectorizer
├── app.py                 # Main Flask app
├── requirements.txt       # Dependencies
├── Procfile               # Deployment config (Render)
└── README.md              # Project documentation

📡 API Endpoint
🔹 Check Spam Email

POST /predict

Request Body (JSON):
{
  "email": "Congratulations! You have won a free lottery. Click now!"
}

Response:
{
  "prediction": "Spam"
}

🌐 Live Deployment - Render 

🧠 How It Works
Input email text is received via API
Text is cleaned and preprocessed
TF-IDF vectorizer transforms text into numerical format
Trained ML model predicts:
Spam
Not Spam
Result is returned as JSON response
