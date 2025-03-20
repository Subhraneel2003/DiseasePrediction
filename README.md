# Medical Predictions App

A Streamlit web application that predicts the likelihood of diabetes and heart disease based on user-provided health metrics.

## Overview

This web application allows users to:
- Check for diabetes risk by inputting glucose levels, insulin levels, BMI, and age
- Check for heart disease risk by inputting chest pain level, blood pressure, cholesterol, and maximum heart rate
- View data visualizations showing the relationship between key health metrics and disease outcomes

## Features

- **Diabetes Prediction**: Uses a Random Forest Classifier trained on clinical data to predict diabetes risk
- **Heart Disease Prediction**: Employs a Random Forest Classifier to assess heart disease risk
- **Data Visualization**: Provides scatter plots showing the relationship between:
  - Glucose levels and diabetes outcome
  - Blood pressure and heart disease status

## Technical Details

- Built with Streamlit for the interactive web interface
- Uses scikit-learn for machine learning models (Random Forest Classifier)
- Implements data visualization using Plotly Express
- Training data stored in CSV files:
  - "Diabetes Predictions.csv"
  - "Heart Disease Predictions.csv"

## Installation and Usage

1. Clone this repository:
   ```
   git clone https://github.com/your-username/medical-predictions-app.git
   ```

2. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

3. Access the web application through your browser at the provided local URL

## Required Data Files

Make sure the following files are in the same directory as the application:
- Diabetes Predictions.csv
- Heart Disease Predictions.csv

## Screenshots
![image](https://github.com/user-attachments/assets/ae85a009-91bc-4c4a-8846-db1c157b6b21)
![image](https://github.com/user-attachments/assets/526d0857-1378-44dc-a720-c4609dfc909b)


## Disclaimer
This application is intended for educational and demonstration purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment.

