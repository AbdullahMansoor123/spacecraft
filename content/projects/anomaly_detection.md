# Project 4: Anomaly Detection with Autoencoders for Rare Defect Identification

## Problem Statement
Supervised models fail to detect rare or unseen defects.

## Objective
Develop an unsupervised anomaly detection system using autoencoders trained only on defect-free images.

## Solution Overview
A CNN-based autoencoder reconstructs normal images. Defects are detected via high reconstruction error and visualized with heatmaps.

### Workflow
1. Train autoencoder on clean data
2. Compute reconstruction error
3. Threshold to identify anomalies

## Technologies Used
- Keras / TensorFlow
- OpenCV, NumPy
- MVTec AD dataset
- Streamlit (optional UI)

## Results
- AUC-ROC: 0.91
- Detection Accuracy: ~90%
- False Positive Rate: ~8%

## Visuals
*(Insert input vs. reconstructed images, heatmaps, and pixel-score thresholds here)*

## Deployment
Useful for early-stage QA systems or evolving production lines.

## Business Impact
First-line defense against unseen defects, minimizing warranty claims and product recalls.

## Links
- GitHub: [github.com/your-username/anomaly-detector-autoencoder](#)
- Demo: [yourname.streamlit.app/anomaly-detection](#)
