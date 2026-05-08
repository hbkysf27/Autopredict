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




|-------------|------------------|
| ![](./screenshots/home.png) | ![](./screenshots/prediction.png) <img width="720" height="1600" alt="Screenshot_20230519_070216_Expo Go" src="https://github.com/user-attachments/assets/6c57988a-aa0b-419c-b608-6a8c5254eeff" />
<img width="720" height="1600" alt="Screenshot_20230519_070209_Expo Go" src="https://github.com/user-attachments/assets/6c1c629a-addf-4aff-9aaf-75bb34c344a5" />
<img width="720" height="1600" alt="Screenshot_20230519_070152_Expo Go" src="https://github.com/user-attachments/assets/84611365-77be-4365-8639-36681c262c86" />
<img width="720" height="1600" alt="Screenshot_20230519_070126_Expo Go" src="https://github.com/user-attachments/assets/7d5e74e7-e85a-49f2-b307-b155962b9efe" />
<img width="720" height="1600" alt="Screenshot_20230519_070121_Expo Go" src="https://github.com/user-attachments/assets/92f85126-50d3-4cf6-8e5d-5601b3718640" />
<img width="720" height="1600" alt="Screenshot_20230519_070107_Expo Go" src="https://github.com/user-attachments/assets/b25842a1-7ab7-4cf4-9320-e7d1cd25128b" />
<img width="720" height="1600" alt="Screenshot_20230519_065752_Expo Go" src="https://github.com/user-attachments/assets/89a1b684-b3ac-41b0-a1ac-de1614b44685" />
<img width="720" height="1600" alt="Screenshot_20230519_065701_Expo Go" src="https://github.com/user-attachments/assets/a5d38b70-a719-429a-851e-54c67379f51c" />
<img width="720" height="1600" alt="Screenshot_20230519_065145_Expo Go" src="https://github.com/user-attachments/assets/ccb7dc1f-bce8-4bc5-9d53-7c62ce49f7b4" />
<img width="720" height="1600" alt="Screenshot_20230519_065139_Expo Go" src="https://github.com/user-attachments/assets/c2208fb5-f87d-4cee-876e-7eae2b6e4203" />
<img width="720" height="1600" alt="Screenshot_20230519_065135_Expo Go" src="https://github.com/user-attachments/assets/50f1a673-c2ae-479c-afc5-16295576fa81" />
<img width="720" height="1600" alt="Screenshot_20230519_064925_Expo Go" src="https://github.com/user-attachments/assets/6805781c-34c8-43e9-9cbd-d0228ced2e76" />
<img width="720" height="1600" alt="Screenshot_20230519_064920_Expo Go" src="https://github.com/user-attachments/assets/d5524164-cb11-4a52-9e3a-d0015c6cf639" />
<img width="720" height="1600" alt="Screenshot_20230519_064910_Expo Go" src="https://github.com/user-attachments/assets/d63fbbc8-af1e-401f-be27-d663abdd5efb" />
<img width="720" height="1600" alt="Screenshot_20230519_064905_Expo Go" src="https://github.com/user-attachments/assets/e536a88f-70b3-4715-9090-9045f5842b78" />
<img width="720" height="1600" alt="Screenshot_20230519_064759_Expo Go" src="https://github.com/user-attachments/assets/2be91698-2469-4a8c-afb6-71e2f44e4f09" />
![Uploading Screenshot_20230519_064759_Expo Go.jpg…]()
|

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
