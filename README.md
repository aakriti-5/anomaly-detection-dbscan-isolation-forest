# 🔍 Anomaly Detection using DBSCAN and Isolation Forest

## 📌 Overview

This project explores **anomaly detection using unsupervised machine learning**.

Two different algorithms are implemented using a healthcare dataset:

- 🔵 **DBSCAN**
- 🟢 **Isolation Forest**

The goal is to identify unusual observations and understand how different algorithms approach anomaly detection.

## 🎯 Objectives

- Explore and preprocess the healthcare dataset
- Apply DBSCAN for anomaly detection
- Apply Isolation Forest for anomaly detection
- Identify potential anomalies
- Visualize and analyze the results

## 📊 Dataset

The project uses **healthcare_dataset.csv**.

The dataset contains healthcare-related information such as **Age, Gender, Medical Condition, Billing Amount, and Medical Test Results**.

## 🧠 Algorithms Used

### 🔵 DBSCAN

DBSCAN groups data points based on their density. Points that do not belong to a dense group are classified as **noise** and can be considered potential anomalies.

[View DBSCAN Implementation](./DBSCAN_Anomaly_Detection/)

### 🟢 Isolation Forest

Isolation Forest identifies unusual observations by isolating them from the rest of the data. Anomalies are generally easier to isolate than normal observations.

[View Isolation Forest Implementation](./Isolation_Forest_Anomaly_Detection/)

## 🔄 Workflow

Dataset → Data Preprocessing → Feature Selection → Apply Algorithms → Detect Anomalies → Visualization & Analysis

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📁 Project Structure

```text
Anomaly_Detection/
│
├── README.md
│
├── DBSCAN_Anomaly_Detection/
│   ├── DBSCAN_Anomaly_Detection.ipynb
│   └── README.md
│
├── Isolation_Forest_Anomaly_Detection/
│   ├── Isolation_Forest_Anomaly_Detection.ipynb
│   └── README.md
│
└── healthcare_dataset.csv

📚 Key Learning

This project provides practical experience with:

Unsupervised Machine Learning
Anomaly Detection
DBSCAN
Isolation Forest
Data Preprocessing
Feature Selection
Data Visualization
👩‍💻 Author

Aakriti Kandpal
