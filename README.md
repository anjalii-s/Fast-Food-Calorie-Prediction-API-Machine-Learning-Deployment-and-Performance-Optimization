# Fast Food Calorie Prediction API

## 📌 Overview

This project demonstrates the end-to-end deployment of a machine learning model as a REST API.  
A **Random Forest Regressor** was trained on 1,147 fast food items to predict calorie content with **98.1% R² accuracy** and deployed using **Flask + Gunicorn + Docker**.  
The API achieves **24.5ms single prediction latency** and supports **40+ requests/sec** through systematic performance optimization.

## 🚀 Features

- Random Forest model with feature engineering (nutritional ratios, categorical encodings).
- REST API with endpoints for health check, single prediction, batch prediction, and metadata.
- Dockerized deployment with production-ready Gunicorn server.
- Performance optimization: model preloading, efficient feature preparation, parallel processing.
- Comprehensive testing suite for reliability and scalability.

## 📊 Performance

- **MAE:** 16.16 calories  
- **R² Score:** 0.9814  
- **Latency:** 24.5ms per request  
- **Throughput:** 40+ requests/sec  

## 🛠️ Tech Stack

- Python (Scikit-learn, Flask, Gunicorn)
- Docker for containerization
- Pandas, NumPy for preprocessing
- Custom testing & monitoring scripts

## 📈 Business Value

- Real-time calorie predictions for nutrition apps.
- Batch menu analysis for restaurants.
- Scalable architecture for high-traffic environments.

## 📂 Future Improvements

- Request caching & response compression
- Model quantization for faster inference
- Asynchronous batch processing
- Microservices & load balancing for scaling

Dataset used : https://www.kaggle.com/datasets/joebeachcapital/fast-food/data
