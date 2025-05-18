# 🚨 New York City Crime Prediction Web Application 
An intelligent, map-based web application that leverages machine learning and geospatial data to **predict crime probabilities** in NYC neighborhoods. Whether you're planning a visit or commuting, this tool helps you make **safer decisions, backed by data**.

## 🌆 Overview
Explore New York City with confidence.

This web app analyzes historical crime data to predict the **likelihood of criminal activity** in any given area. Just enter a location  or use your real-time coordinates  and get instant insights into **crime categories** most likely to occur nearby.

## 📊 Dataset  
- **Source:** [NYPD Complaint Data (2006–2021)](https://opendata.cityofnewyork.us/)
- **Size:** 6.9 million+ records
- **Features:**
  - 🕒 **Temporal**: Date, time of incident  
  - 📍 **Spatial**: Latitude, longitude, precincts  
  - 🧾 **Crime Details**: Offense description, classification
    
## ✨ Key Features

| Feature                | Description |
|------------------------|-------------|
| 🗺️ **Interactive Map** | Visualize predicted crime likelihoods directly on an NYC map. |
| 📍 **Smart Geolocation** | Automatically assesses your current location's safety. |
| 🔍 **Detailed Insights** | Reveals the **most probable crime type** in your selected area. |
| 📈 **Predictive Intelligence** | Uses trained ML models to generate risk probabilities. |

## 🛠️ Tech Stack

**Frontend**  
- 🗺️ [OpenStreetMap](https://www.openstreetmap.org/) – Live, interactive mapping  
- 🧪 HTML, CSS, JS – Lightweight and responsive UI

**Backend**  
- ⚙️ **Node.js** – Fast and scalable server environment  
- 🌐 **RESTful API** – For predictions and data retrieval

**Machine Learning**  
- 🧠 **Scikit-learn** – Baseline modeling  
- 🌲 **LightGBM** – Fast and efficient gradient boosting  
- 🔥 **XGBoost** – High-performance crime classification
