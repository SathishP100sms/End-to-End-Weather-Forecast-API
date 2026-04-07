# 🌦️ AI Probabilistic Weather Forecast

AI-powered probabilistic weather forecasting using deep learning. The app predicts current and next 7-day temperatures with uncertainty bands (10% - 90 %) using an Attention-based LSTM model, OpenWeather An AI-powered probabilistic weather forecasting system that predicts current temperature and the next 7-day forecast.

## 🚀 Live Demo
Web APP : https://ai-powered-weather-forecast.netlify.app/  

## ✨ Features
- Real-time weather data
- 7-day probabilistic forecast
- Confidence intervals (10%–90%)
- Interactive charts (Chart.js)
- Dark/Light mode UI

## 🧠 Model
- Attention-based LSTM
- Time series forecasting
- Built using TensorFlow/Keras
- Open Weather API

## 🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript  
Backend: FastAPI  
ML: TensorFlow, Keras  
Deployment: Netlify, Render  

## 📂 Project Structure
ai-weather-forecast/
│
├── backend/
├── frontend/
├── requirements.txt
└── README.md

## ⚙️ Setup

### Clone Repo
git clone https://github.com/SathishP100sms/End-to-End-Weather-Forestcast-API

### Backend
pip install -r requirements.txt
uvicorn main:app --reload

### Frontend
Open index.html

## 🌍 Deployment
- Backend → Render
- Frontend → Netlify

## 🔐 Env
OPENWEATHER_API_KEY=your_key

## 📜 License
MIT [LICENSE](LICENSE)
