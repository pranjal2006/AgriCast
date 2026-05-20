# Agricast: AI-Powered Crop & Fertilizer Recommendation System

Agricast is an intelligent full-stack web application designed to help farmers optimize agricultural productivity. By leveraging machine learning models, the system analyzes soil composition and weather parameters to accurately predict the most suitable crops and fertilizer requirements.

## 🚀 Features
- **Crop Recommendation:** Predicts the best crop to cultivate based on soil health and climate conditions.
- **Fertilizer Prediction:** Analyzes nutrient deficiencies and recommends the exact fertilizer needed.
- **Interactive Dashboard:** Features a clean, user-friendly interface with a "Market Insights" card for real-time tracking.

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Flask (Python)
- **Database:** MongoDB
- **Machine Learning:** Scikit-learn (Random Forest / Decision Tree algorithms)

## 📊 Dataset Parameters Used
The machine learning models are trained on critical environmental and soil metrics:
- **N-P-K Values:** Nitrogen (N), Phosphorus (P), and Potassium (K) levels in the soil.
- **Climate Data:** Temperature (°C), Humidity (%), and Rainfall (mm).
- **Soil Property:** pH level of the soil.

## ⚙️ Installation & Setup

### Prerequisites
- Node.js & npm
- Python 3.8+
- MongoDB instance

### 1. Backend Setup (Flask)
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
python app.py
