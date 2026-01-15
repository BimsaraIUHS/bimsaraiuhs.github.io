---
layout: "default"
title: "🫀 Heart-Disease-Prediction - Assess Heart Disease Risk Easily"
description: "❤️ Predict heart disease risk using a machine learning app with a REST API, web interface, and explainable AI for clear insights and accurate assessments."
---
# 🫀 Heart-Disease-Prediction - Assess Heart Disease Risk Easily

[![Download Heart-Disease-Prediction](https://img.shields.io/badge/Download-Heart--Disease--Prediction-blue.svg)](https://github.com/BimsaraIUHS/Heart-Disease-Prediction/releases)

## 🚀 Getting Started

Welcome to the Heart Disease Prediction repository! This application helps assess the risk of heart disease by using machine learning. It is designed for users without technical backgrounds. 

### 📦 Features

- **Accuracy**: This application provides an 88.5% accuracy rate in predicting heart disease.
- **User-Friendly Interfaces**: Use either a web dashboard or a REST API for your interactions.
- **Explainability**: Understand predictions through SHAP (SHapley Additive exPlanations) values.
- **Tracking**: Monitor your machine learning model's performance with MLflow.
- **Easy Deployment**: Use Docker for quick setup and deployment.

## 🛠️ System Requirements

- **Operating System**: Windows 10 or later, macOS, or any recent Linux distribution
- **Python**: Version 3.7 or later
- **Memory**: At least 4GB RAM
- **Storage**: 500MB available space
- **Internet**: Required for initial setup and updates

## 💻 Download & Install

To get started, visit this page to download: [Heart-Disease-Prediction Releases](https://github.com/BimsaraIUHS/Heart-Disease-Prediction/releases). 

### 🕹️ Installation Steps

1. **Go to Releases**: Click the link above to navigate to the Releases page.
2. **Select Version**: Choose the latest version of the software.
3. **Download File**: Look for the executable file (often named `Heart-Disease-Prediction.exe` for Windows or `Heart-Disease-Prediction.dmg` for macOS).
4. **Run Installer**: Open the downloaded file and follow the on-screen instructions. 

## 🌐 Using the Application

Once the application is installed, you can start using it. 

### 1. Launch the Application

- For desktop installations, find the "Heart-Disease-Prediction" icon on your desktop or in your applications folder. Double click to open.

### 2. Using the Web Dashboard

- Open a web browser and navigate to `http://localhost:8501` to access the Streamlit dashboard.

### 3. Accessing the REST API

- You can also interact with the FastAPI REST API. Open your browser or a tool like Postman and navigate to `http://localhost:8000/docs` to see available endpoints.

## 🔍 How to Make Predictions

### Make a Prediction via Dashboard

1. Go to the dashboard.
2. Fill in the required fields. This will usually include your age, cholesterol levels, and other health metrics.
3. Click “Predict”.
4. Wait a moment for the result.

### Make a Prediction via REST API

1. Make a POST request to `/predict`.
2. Send the health data in JSON format.
3. The application will return the risk assessment.

## 📊 Understanding Results

Once you receive a prediction, you will also see an explanation of the result. Look for a breakdown of the factors that contributed to the assessment. This feature uses SHAP to clarify how different inputs affect your risk.

## 🐳 Docker Deployment

If you prefer using Docker for deployment, follow these steps:

1. Ensure Docker is installed on your machine.
2. Open your command line interface.
3. Use the following command to pull the Docker image:

   ```bash
   docker pull YOUR_IMAGE_NAME
   ```

4. Run the Docker container with:

   ```bash
   docker run -p 8501:8501 YOUR_IMAGE_NAME
   ```

5. Access the dashboard through your browser at `http://localhost:8501`.

## 🛠️ Troubleshooting

If you run into any issues:

- **No Response**: Ensure the application is running.
- **Network Issues**: Check your internet connection.
- **Data Input Errors**: Double-check the values you entered.

For more help, visit the [Issues page](https://github.com/BimsaraIUHS/Heart-Disease-Prediction/issues).

## 🔗 Additional Resources

- [Documentation](https://github.com/BimsaraIUHS/Heart-Disease-Prediction/wiki)
- [Contributing](https://github.com/BimsaraIUHS/Heart-Disease-Prediction/blob/main/CONTRIBUTING.md)

Access the releases here: [Heart-Disease-Prediction Releases](https://github.com/BimsaraIUHS/Heart-Disease-Prediction/releases).

Your health matters. Use Heart Disease Prediction to take charge of your well-being.