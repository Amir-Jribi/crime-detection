# 🚨 New York City Crime Prediction Web Application 

## 🌆 Overview  
This web app predicts the likelihood of crimes in New York City using historical data, helping users identify safe places to visit.  

## 📊 Dataset  
- **NYPD Complaint Data (2006–2021)**  
- **6.9M records** with 35 attributes, including:  
  - **Temporal:** Date, time  
  - **Spatial:** Latitude, longitude  
  - **Crime details:** Type, classification  

## 💻 Features  
- **Interactive Map:** Allows users to input a location and assess its safety.  
- **Detailed Results:** Highlights the crime category with the highest probability of occurrence.  
- **Geolocation Services:** Provides insights based on the user's current location.  

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
