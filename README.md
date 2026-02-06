# handwriting-recognition_project
KNN vs Neural Network for handwriting analysis
# handwriting-recognition/
├── code/
│   └── letter_recognition_analysis.py
├── reports/
│   └── Handwriting_Recognition_Report.pdf
├── visualizations/
│   ├── 01_data_quality_report.png
│   ├── 09_knn_confusion_matrix.png
│   ├── 12_nn_confusion_matrix.png
│   └── ... (18 total)
└── README.md
# Handwritten Letter Recognition for Motor Skill Assessment

![Python](https://github.com/mackaembaxs/handwriting-recognition_project/blob/528f1fb64d945876590c7383ee673157ccdbfe92/Final%20work_%20Letters.html)
![Accuracy](https://img.shields.io/badge/Accuracy-96%25-success)
![Status](https://img.shields.io/badge/Status-Complete-success)

## 🎯 Project Overview

Machine learning models for educational screening to identify students who may need motor skill development support through handwriting analysis.

## 🤖 Models Compared

| Model | Test Accuracy | Precision | Recall | F1-Score |
|-------|---------------|-----------|--------|----------|
| KNN (K=5) | 0.93 | 0.93 | 0.93 | 0.93 |
| **Neural Network** | **0.96** | **0.96** | **0.96** | **0.96** |

## 🏗️ Architecture

**Neural Network Configuration:**
- **Layers:** (100, 50) hidden layers
- **Activation:** ReLU
- **Output:** Softmax (26 classes)
- **Optimization:** Adam with early stopping

**KNN Configuration:**
- **K Value:** 5 (optimized via cross-validation)
- **Distance:** Euclidean
- **Weights:** Uniform

## 🛠️ Technologies

- **Python 3.12**
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- **Techniques:** PCA, Cross-validation, Confusion matrices

## 📈 Key Results

- **Dataset:** 20,000+ handwritten letters (A-Z)
- **Best Model:** Neural Network (96% accuracy)
- **PCA:** 95% variance in 150 components
- **Visualizations:** 18 analytical charts

## 📁 Repository Structure
 handwriting-recognition/
├── code/
│   └── letter_recognition_analysis.py
├── reports/
│   └── Handwriting_Recognition_Report.pdf
├── visualizations/
│   ├── 01_data_quality_report.png
│   ├── 09_knn_confusion_matrix.png
│   ├── 12_nn_confusion_matrix.png
│   └── ... (18 total)
└── README.md

## 📊 Sample Results

### Model Comparison
![Accuracy Comparison](visualizations/14_metric_comparison.png)

### Confusion Matrix - Neural Network
![Confusion Matrix](visualizations/12_nn_confusion_matrix.png)

## 💡 Key Findings

- Neural Network superior across all metrics
- (100, 50) architecture optimal
- Minimal overfitting (train-test gap < 3%)
- Challenging letters: B/D, M/N, I/J pairs

## 📧 Contact

**Daniel Mackaemba**
- mackaembaxs@gmail.com
- [LinkedIn Profile](https://www.linkedin.com/in/daniel-mackaemba-b957732a5)
- [Portfolio](https://daniel-mackaemba.github.io)
