# Multimodal Vision Transformer for Respiratory Disease Classification

**B.Tech Final Year Project — Alliance University, May 2026**

## Authors
- K. Nithin Kumar
- G. Sai Smaran
- N. Girish
- R. Guna Vardhan

## Overview
A dual-branch Vision Transformer (ViT-B/16) that combines chest X-ray and CT scan images to classify COVID-19, Pneumonia, Tuberculosis, and Normal cases. Achieves ~88% validation accuracy.

## Files
- `final-1.ipynb` — Full training & evaluation notebook
- `capstonereport2_merged.pdf` — Project report

## Tech Stack
- **Language:** Python 3.10
- **Frameworks:** TensorFlow 2.12, Keras
- **Libraries:** OpenCV, scikit-learn

## Results
| Class | Precision | Recall | F1 |
| :--- | :---: | :---: | :---: |
| **COVID-19** | 91% | 89% | 90% |
| **Pneumonia** | 86% | 84% | 85% |
| **Tuberculosis** | 88% | 90% | 89% |
| **Normal** | 92% | 90% | 91% |

## Dataset
Sourced from public Kaggle datasets (COVID-19 Radiography, RSNA Pneumonia, SARS-CoV-2 CT, TB Chest X-ray).
