# 📧 Spam Email Detection Backend

A **Machine Learning–powered backend API** that detects whether an email is **Spam or Not Spam** using NLP techniques and a trained classification model.

Easily integrate with **React, mobile apps, or any frontend** to build a complete spam detection system.

---

## 🚀 Features

✨ **Smart Spam Detection**
Detects spam emails using a trained ML model

⚡ **Fast API Response**
Built with Flask for quick and efficient processing

📡 **REST API Ready**
Easily connect with any frontend (React, Android, etc.)

🧠 **NLP-Based Processing**
Text cleaning, tokenization, and vectorization

🛠 **Lightweight & Deployable**
Simple setup and supports deployment on Render

---

## 🏗️ Tech Stack

| Category       | Technology Used        |
| -------------- | ---------------------- |
| **Backend**    | Flask                  |
| **Language**   | Python                 |
| **ML Library** | Scikit-learn           |
| **NLP**        | NLTK / Text Processing |
| **Deployment** | Render                 |

---

## 📁 Project Structure

```
spam-email-detection-backend/
│
├── model.pkl           # Trained ML model
├── vectorizer.pkl      # TF-IDF vectorizer
├── app.py              # Main Flask application
├── requirements.txt    # Project dependencies
├── Procfile            # Deployment configuration (Render)
└── README.md           # Project documentation
```

---

## 📡 API Endpoint

### 🔹 Predict Spam Email

**Endpoint:**
POST /predict

### 📥 Request Body (JSON)

```json
{
  "email": "Congratulations! You have won a free lottery. Click now!"
}
```

### 📤 Response

```json
{
  "prediction": "Spam"
}
```

---

## 🧠 How It Works

1. 📩 **Input Received**
   Email text is sent via API request

2. 🧹 **Text Preprocessing**
   Cleaning, removing stopwords, tokenization

3. 🔢 **Feature Extraction**
   TF-IDF vectorizer converts text → numerical format

4. 🤖 **Prediction**
   ML model classifies email as:



# 🌐 Render Deployment

🚀 [View Live App](https://spam-email-backend-49b8.onrender.com)
  

