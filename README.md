# CPU Anomaly Detection System — ML-2

## Overview
Real-time CPU monitoring system that detects anomalies using Statistical and ML methods.

## Dataset
- cpu_utilization_asg_misconfiguration.csv
- 18,050 readings | May 2014 → July 2014

## Methods Used
- Statistical Detection (Mean + 2σ threshold)
- Isolation Forest (Scikit-learn)
- PyOD Anomaly Detection

## Results
- Total Anomalies: 1,450 (8.03%)
- Critical: 826 | Warning: 624

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, PyOD, Matplotlib

## How to Run
1. Open notebook in Google Colab
2. Upload dataset from Data/ folder
3. Run all cells step by step
4. Check Output/ for results
