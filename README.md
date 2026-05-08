# 🚗 Auto-Predict — Used Car Price Prediction App

Auto-Predict is a cross-platform mobile application that predicts the market price of used cars using Machine Learning. The project combines a trained ML regression model with a modern mobile frontend to provide fast and accurate vehicle price estimations.

The application was built as part of an MSc Artificial Intelligence & Robotics project and demonstrates the integration of cloud-based ML deployment with a mobile application ecosystem.

---

## ✨ Features

- 📱 Cross-platform mobile app built with React Native
- 🤖 Machine Learning price prediction model
- ☁️ AWS SageMaker model training & deployment
- 🔐 User authentication with AWS Cognito
- 📦 Cloud storage using AWS S3
- ⚡ REST API integration for predictions
- 🎨 Modern mobile UI/UX
- 📊 Real-time used car price estimation

---

## 🛠 Tech Stack

### Frontend
- React Native
- Expo
- TypeScript / JavaScript

### Backend & ML
- Python
- Scikit-learn
- Pandas
- NumPy
- Flask / FastAPI (depending on your implementation)

### Cloud & Deployment
- AWS SageMaker
- AWS Amplify
- AWS Cognito
- AWS S3
- API Gateway / Lambda

---

## 📷 Screenshots

> Add your screenshots here

| Home Screen | Prediction Screen |
|-------------|------------------|
| ![](./screenshots/home.png) | ![](./screenshots/prediction.png) |

---

## 🧠 Machine Learning Model

The prediction engine was trained using historical used car datasets containing:

- Vehicle brand
- Model
- Year
- Mileage
- Fuel type
- Transmission
- Engine size
- Additional specifications

### Model Workflow

1. Data preprocessing
2. Feature engineering
3. Model training using Scikit-learn
4. Evaluation & optimisation
5. Deployment to AWS SageMaker endpoint
6. REST API integration with mobile app

---

## ☁️ AWS Architecture

```text
React Native App
        │
        ▼
AWS Amplify Hosting
        │
        ▼
REST API Gateway
        │
        ▼
AWS SageMaker Endpoint
        │
        ▼
ML Prediction Response
