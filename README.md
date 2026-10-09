# Fraud Detection Using Anomaly Detection

## Overview
This project explores machine learning techniques for identifying unusual patterns in credit card transactions through a hands-on fraud detection workshop.

## Techniques Implemented
- Z-score statistical anomaly detection
- Local Outlier Factor (LOF)
- Isolation Forest
- Custom anomaly threshold selection
- Anomaly visualization using scatter plots

## Results

| Method | Anomalies Flagged |
|---|---:|
| Z-score | 4,076 |
| Local Outlier Factor | 5,697 |
| Isolation Forest | 5,697 |
| Custom threshold | 2,849 |

## Tech Stack
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab

## Dataset
The notebook uses a credit card transaction dataset containing 284,807 rows and 31 columns. Please refer to the original dataset source for attribution and licensing information.

## Limitations
The anomalies flagged by these techniques are not necessarily fraudulent transactions. The counts represent detected anomalies, not confirmed fraud cases or model accuracy. Evaluation against verified fraud labels is needed to assess performance.

## Learning Outcomes
- Data preprocessing and feature scaling
- Unsupervised anomaly detection
- Comparing anomaly detection techniques
- Visualizing detected anomalies
- Selecting a custom anomaly threshold

## Acknowledgements
Completed as part of a hands-on fraud detection workshop. Credit the workshop organizers and original notebook author where applicable.
