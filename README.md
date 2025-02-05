# AI-model-Endoscopic-vs.-Histology-Score-Discrepancy-Prediction-
AI model to predict the discrepancy in endoscopic and histology scores of inflammation bowel disease
Endoscopic vs. Histology Score Discrepancy Prediction

Overview

This project focuses on predicting discrepancies between endoscopic and histology scores in assessing inflammation from medical images. The goal is to improve diagnostic accuracy by identifying cases where endoscopic and histological evaluations diverge.

Data Description

Input Data: Endoscopic and histology images.

EHR: Diagnosis Data.

Frameworks Used: TensorFlow and PyTorch.

Methodology

1. Data Pipeline

Connected image files with corresponding clinical scores.

Preprocessing included resizing, normalization, and data augmentation.

Data split into training and validation sets.

2. Model Architecture

Custom CNN with Attention Mechanism:

Enhanced feature extraction with attention layers.

Class weights added to address data imbalance.

Comparison Model: ResNet-151.

3. Training Details

Optimized with cross-entropy loss.

Batch size, learning rate, and epochs tuned for best performance.

Evaluation Metrics

Confusion Matrix: To analyze true positives (TP), true negatives (TN), false positives (FP), and false negatives (FN).

Classification Report: Precision, recall, F1-score, and accuracy metrics.

Model Comparison: Performance of the custom CNN with attention mechanism was compared against ResNet-151.

Results

Model Performance: Custom CNN showed improved sensitivity in detecting discrepancies.

Visualization: Included confusion matrices and performance charts.

Future Work

Integration of multi-modal data for enhanced accuracy.

Exploring advanced attention mechanisms.

Acknowledgements

Special thanks to the data providers and clinical experts who supported this project.
