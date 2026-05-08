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

<img width="720" height="1600" alt="Screenshot_20230519_070216_Expo Go" src="https://github.com/user-attachments/assets/71ae513f-a14c-4554-aecb-707922eeb1d0" />
<img width="720" height="1600" alt="Screenshot_20230519_070209_Expo Go" src="https://github.com/user-attachments/assets/a2c982f3-daee-49d2-8151-814d0b1366fd" />
<img width="720" height="1600" alt="Screenshot_20230519_070152_Expo Go" src="https://github.com/user-attachments/assets/a51dd01a-2d9f-4b99-9d10-ba64501a0f46" />
<img width="720" height="1600" alt="Screenshot_20230519_070126_Expo Go" src="https://github.com/user-attachments/assets/23314939-8574-4568-9617-43365aefc854" />
<img width="720" height="1600" alt="Screenshot_20230519_070121_Expo Go" src="https://github.com/user-attachments/assets/f7c29286-5332-4f70-aa0c-eef90cb70cd3" />
<img width="720" height="1600" alt="Screenshot_20230519_070107_Expo Go" src="https://github.com/user-attachments/assets/8656e448-c9d0-463c-90c5-211e7ef6b9f8" />
<img width="720" height="1600" alt="Screenshot_20230519_065752_Expo Go" src="https://github.com/user-attachments/assets/b2124ba4-f9d0-472a-ba1d-ff2c106439ec" />
<img width="720" height="1600" alt="Screenshot_20230519_065701_Expo Go" src="https://github.com/user-attachments/assets/ed93d317-ef18-42f8-9113-3baac7fef509" />
<img width="720" height="1600" alt="Screenshot_20230519_065145_Expo Go" src="https://github.com/user-attachments/assets/7aa8ee62-db3a-4845-b4b8-9322e7221389" />
<img width="720" height="1600" alt="Screenshot_20230519_065139_Expo Go" src="https://github.com/user-attachments/assets/c218dcfe-ed27-422e-a9a1-866f327631fb" />
<img width="720" height="1600" alt="Screenshot_20230519_065135_Expo Go" src="https://github.com/user-attachments/assets/27d88871-9c95-4850-b32a-e147d26e7f46" />
<img width="720" height="1600" alt="Screenshot_20230519_064925_Expo Go" src="https://github.com/user-attachments/assets/9759b948-08eb-42c4-b07d-4160455e006d" />
<img width="720" height="1600" alt="Screenshot_20230519_064920_Expo Go" src="https://github.com/user-attachments/assets/f122a78a-4552-4c46-b950-70ade488f8ab" />
<img width="720" height="1600" alt="Screenshot_20230519_064910_Expo Go" src="https://github.com/user-attachments/assets/d060f06a-ea1a-4ce9-a105-cdacc8f95e01" />
<img width="720" height="1600" alt="Screenshot_20230519_064905_Expo Go" src="https://github.com/user-attachments/assets/a77b2c05-bad0-4561-a212-3797a51358a1" />
<img width="720" height="1600" alt="Screenshot_20230519_064759_Expo Go" src="https://github.com/user-attachments/assets/6548c664-021e-444e-a05f-bc807efd01d1" />

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
