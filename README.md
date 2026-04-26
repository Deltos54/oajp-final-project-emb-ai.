# Final Project: Emotion Detection Application

# Emotion-Detection-App
Emotion Detection app using Python and IBM Watson NLP with Flask deployment, unit testing, and error handling.
# Emotion Detection Application

## 📌 Project Description
This project is an Emotion Detection system built using Python and IBM Watson NLP. It analyzes text input and detects emotions such as joy, anger, sadness, fear, and disgust.

## 🚀 Features
- Detects multiple emotions from text
- Identifies dominant emotion
- Uses Watson NLP API
- Integrated with Flask web application

## 🛠️ Technologies Used
- Python
- Flask
- IBM Watson NLP API

## ▶️ How to Run
1. Install required libraries:
   pip install requests flask

2. Run the server:
   python server.py

3. Open browser:
   http://127.0.0.1:5000/emotionDetector?textToAnalyze=I am happy

## 📊 Example Output
{
  "anger": 0.01,
  "disgust": 0.02,
  "fear": 0.01,
  "joy": 0.95,
  "sadness": 0.01,
  "dominant_emotion": "joy"
}

# Final Project: Emotion Detection Application
