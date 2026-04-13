# Philippine Urban Traffic Vehicle Classification using YOLOv26

## 🚀 Project Overview
This project focuses on the comparative evaluation and optimization of a YOLOv26 model for real-time vehicle detection in complex, high-density Philippine urban environments. By engineering a custom dataset and benchmarking various hyperparameter configurations, this model achieves high-accuracy detection across diverse vehicle classes (e.g., jeepneys, tricycles, cars) in mixed-traffic scenarios.

## 📊 Key Performance Metrics
Peak mAP50: 0.827

Precision: 0.941

Dataset: 2,168 custom-engineered annotations.

Configurations Tested: AdamW vs. SGD vs. Automated optimization strategies.

## 🛠️ Technical Stack
Language: Python

Framework: YOLOv26

Libraries: OpenCV, Matplotlib, NumPy, Scikit-learn

Platform: Google Colab

## 🔬 Methodology & Insights
Data Engineering: Created a custom dataset specifically tailored for "mixed-traffic" (Philippine-specific transit types) to ensure model generalization.

Hyperparameter Tuning: Benchmarked three configurations. The AdamW setup outperformed the baseline, specifically in high-variance lighting and high-density urban settings.

Deployment & Diagnostics: Implemented a diagnostic pipeline to analyze per-class detection behavior, identifying that localized vehicle types (jeepneys/trikes) required specific anchor box adjustments.

## 📁 Repository Structure
Plaintext
├── YOLOv26_Detection_Analysis.ipynb  # Main research & training notebook
├── data/                             # Sample images or dataset links
├── weights/                          # Trained model weights (if applicable)
└── README.md                         # Project documentation

👨‍💻 Authors
Edelle Gibben Lumabi 3rd-year Computer Science Student @ Mapúa University
Craig Zyrus Manuel 3rd-year Computer Science Student @ Mapúa University
