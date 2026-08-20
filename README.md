# Anomaly Detection using DBSCAN and Isolation Forest

## Overview

This project explores anomaly detection using unsupervised machine learning techniques.

Two different anomaly detection approaches are implemented using a healthcare dataset:

1. DBSCAN
2. Isolation Forest

The purpose of this project is to understand how different unsupervised learning algorithms can be used to identify unusual observations or potential anomalies in a dataset.

## Objectives

- Explore and understand the healthcare dataset
- Perform data preprocessing
- Select relevant features for anomaly detection
- Apply DBSCAN for density-based anomaly detection
- Apply Isolation Forest for anomaly detection
- Visualize the detected anomalies
- Understand the differences between the two approaches

## Algorithms Used

### 1. DBSCAN

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is a density-based clustering algorithm.

It groups data points based on their density and identifies points that do not belong to sufficiently dense regions as noise.

Noise points are represented by:

```text
-1
