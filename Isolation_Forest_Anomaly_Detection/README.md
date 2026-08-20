# Isolation Forest Anomaly Detection

## Overview

This project demonstrates anomaly detection using the Isolation Forest algorithm.

Isolation Forest is an unsupervised machine learning algorithm designed to identify unusual observations or anomalies in a dataset.

## Objective

The main objectives of this project are:

- Explore the healthcare dataset
- Perform data preprocessing
- Select relevant features for anomaly detection
- Apply the Isolation Forest algorithm
- Identify potential anomalies
- Visualize the detected anomalies
- Understand how Isolation Forest can be used for anomaly detection

## Algorithm Used

### Isolation Forest

Isolation Forest works on the idea that anomalies are easier to isolate than normal observations.

The algorithm randomly selects features and split values to isolate individual observations. Anomalous observations generally require fewer splits to be isolated compared to normal observations.

An important parameter used in Isolation Forest is:

- `contamination` – Specifies the expected proportion of anomalies in the dataset.

The model assigns:

```text
-1 → Anomaly
 1 → Normal Observation
 