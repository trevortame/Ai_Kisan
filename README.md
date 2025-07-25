# 🌾 AI Kisan – Smart Crop & Fertilizer Recommendation System

AI Kisan is a Flask-based machine learning API that helps farmers make informed decisions by recommending the most suitable **crop** and **fertilizer** based on soil and weather conditions.

## 🚀 Features
- 🌱 Predicts the best crop to cultivate based on soil nutrients, pH, and rainfall.
- 🧪 Recommends the right fertilizer using environmental data.
- 📡 Lightweight and easy to integrate with any frontend.

## 🧠 Models Used
- **Crop Prediction**: k-NN Classifier
- **Fertilizer Recommendation**: Decision Tree Model

## 🔧 Tech Stack
- Python (Flask)
- scikit-learn
- joblib
- Flask-CORS

## 📨 API Endpoints

### `/crop/` (GET)
**Params**: `nitrogen`, `phosphorous`, `potassium`, `temperature`, `humidity`, `ph_level`, `rainfall`  
**Returns**: Recommended crop 🌾

### `/fertilizer/` (GET)
**Params**: `nitrogen`, `phosphorous`, `potassium`, `temperature`, `humidity`, `moisture`  
**Returns**: Suggested fertilizer 🧪

## 🛠️ Setup Instructions
```bash
pip install flask flask-cors joblib scikit-learn
python app.py
## 💡 Future Scope
Add soil testing dataset integration.

Build a web dashboard or mobile app.

Multilingual support for Indian farmers.

