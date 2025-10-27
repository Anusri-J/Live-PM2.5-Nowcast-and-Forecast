**🌫️ Live_PM2.5_Nowcast_Forecast**

A real-time air quality monitoring project that fetches, analyzes, and forecasts PM2.5 (fine particulate matter) concentration using live environmental data from OpenAQ and Open-Meteo APIs.
It combines machine learning, anomaly detection, and Streamlit visualization to help users track pollution trends and anticipate air quality changes up to 48 hours ahead.

**📌 Project Overview**

This project focuses on:

🌍 Tracking live PM2.5 levels across global locations

💨 Forecasting air quality for the next 24–48 hours using ML

⚠️ Detecting pollution anomalies and unusual readings

📊 Displaying real-time data and predictions through a Streamlit dashboard

**🧠 Skills Gained**

🔗 API integration (OpenAQ, Open-Meteo)

📦 Data preprocessing and feature engineering

🤖 Time series forecasting (recursive prediction)

🚨 Anomaly detection using Isolation Forest

🧮 Model training with Scikit-learn

🖥️ Streamlit dashboard development

✅ Data validation and quality monitoring

**🧩 Steps Involved**

**✅ Step 1: Data Ingestion**

Fetched live PM2.5 and weather data (temperature, humidity, wind, pressure) from OpenAQ API.
Fallback to Open-Meteo Air Quality API for missing data.

**✅ Step 2: Feature Engineering**

Created lag features, rolling means, and interaction terms.
Filled missing values and standardized numeric features for modeling.

**✅ Step 3: Anomaly Detection**

Applied IsolationForest to identify abnormal PM2.5 readings — helpful for spotting sudden pollution spikes.

**✅ Step 4: Model Building**

Trained a Gradient Boosting Regressor to forecast PM2.5 recursively for 24–48 hours.

**✅ Step 5: Streamlit Dashboard**

Built an interactive interface to display live PM2.5 data, forecasts, and anomalies with user input filters for location and time horizon.

**📊 Sample Dashboard Features**

🌫️ Current Air Quality: Displays the most recent PM2.5 reading

🕐 Next Hour & 48h Forecast: Shows predicted pollution trend lines

⚠️ Anomaly Indicator: Highlights abnormal readings detected by the model

📈 Feature Importance: Displays which weather factors influence PM2.5 most

**🛠 Tech Stack Used**

✅ Python – Data processing and model training

✅ Pandas & NumPy – Data cleaning and manipulation

✅ Scikit-learn – Machine learning and anomaly detection

✅ Streamlit – Interactive web visualization

✅ OpenAQ & Open-Meteo APIs – Real-time air quality and weather data sources

✅ Google Colab + ngrok – Cloud-based app execution and tunneling

**🎯 Business Use Cases**

🏥 Public Health Monitoring – Early alerts for pollution spikes and poor air quality days

🏙️ Smart Cities – Integrate forecasts with urban air management systems

📊 Environmental Policy – Support evidence-based air quality decisions

🌬️ IoT Integration – Predictive data for smart purifiers and sensors

☁️ Climate Research – Analyze pollution-weather correlations

**🧩 Key Learnings**

✔️ Handling real-time API data and fallback strategies

✔️ Engineering lag and rolling window features for time series

✔️ Applying anomaly detection on environmental data

✔️ Recursive multi-hour forecasting with Gradient Boosting

✔️ Building a live interactive dashboard using Streamlit and ngrok

**🧾 Evaluation Metrics**

📉 MAE (Mean Absolute Error) – Measures prediction accuracy

✅ Coverage % – Valid data availability vs expected readings

⚠️ Anomaly Detection Accuracy – Correctly identifying outliers

📊 Forecast Reliability – Number of valid predicted steps


**📎 References**

🔗 OpenAQ API

🔗 Open-Meteo API

📘 Streamlit Documentation

🧠 Scikit-learn Documentation
