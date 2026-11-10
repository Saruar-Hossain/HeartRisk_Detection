# Cardiac Risk Stratification System – TinyML

A Machine Learning-based project for classifying cardiac risk levels using ECG/PPG-related telemetry features, with a focus on wearable health monitoring and TinyML deployment.

### Project Overview
The system classifies cardiac conditions into three categories:
- **Normal (0)**
- **Moderate Risk (1)**
- **High Risk (2)**

### Technologies Used
- Python
- NumPy & Pandas
- Scikit-learn
- Random Forest
- SMOTE
- FastAPI
- TinyML (C/C++ for ESP32)

### Methodology
- Synthetic cardiac telemetry data generation and feature extraction.
- Train-test splitting and class balancing using SMOTE.
- Random Forest model training.
- Model evaluation using Accuracy, Macro F1-Score and Confusion Matrix.
- C/C++ inference rule generation for ESP32.
- FastAPI backend for cardiac telemetry risk prediction.

### Project File
- `cardiac_risk_stratification_tinyml.ipynb` – Complete project implementation.

### Author
**Saruar Hossain**

[GitHub Profile](https://github.com/Saruar-Hossain)
