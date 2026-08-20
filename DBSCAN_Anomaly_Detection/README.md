# DBSCAN Anomaly Detection

## Overview

This project demonstrates anomaly detection using the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm.

DBSCAN is an unsupervised machine learning algorithm that groups data points based on their density and identifies points that do not belong to any cluster as noise or potential anomalies.

## Objective

The main objectives of this project are:

- Explore the healthcare dataset
- Perform data preprocessing
- Select relevant features for anomaly detection
- Scale the data
- Apply the DBSCAN clustering algorithm
- Identify noise points as potential anomalies
- Visualize the detected anomalies

## Algorithm Used

### DBSCAN

DBSCAN is a density-based clustering algorithm that uses two main parameters:

- `eps` – Maximum distance between two points to be considered neighbors
- `min_samples` – Minimum number of points required to form a dense region

Data points that do not belong to a sufficiently dense region are classified as noise and assigned the label:

```text
-1