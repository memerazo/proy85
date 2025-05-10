# 🚀 Machine Learning Model Comparison Report

## 📊 Performance Overview

| Model                | Accuracy | Precision (0) | Precision (1) | Recall (0) | Recall (1) | F1 (0) | F1 (1) | Support       |
|----------------------|----------|---------------|---------------|------------|------------|--------|--------|---------------|
| 🔥 Random Forest     | 83.58%   | 0.78          | 0.88          | 0.85       | 0.83       | 0.81   | 0.85   | 13,735/19,289 |
| 📏 KNN              | 80.21%   | 0.75          | 0.84          | 0.79       | 0.81       | 0.77   | 0.83   | 13,735/19,289 |
| 📉 Logistic Reg     | 78.35%   | 0.80          | 0.77          | 0.64       | 0.89       | 0.71   | 0.83   | 13,735/19,289 |
| ⚡ SVC              | 74.93%   | 0.91          | 0.71          | 0.44       | 0.97       | 0.59   | 0.82   | 13,735/19,289 |

## 🏆 Model Highlights

### 🥇 Best Overall: Random Forest (83.58% Accuracy)
- ✅ Highest balanced performance
- ✅ Strong F1 scores for both classes
- ✅ Robust to overfitting

### 🥈 Runner Up: KNN (80.21% Accuracy)
- ⚡ Fast training time
- 🔍 Simple to implement
- 🤝 Good balance between metrics

### Special Recognition:
- **SVC**: Best recall for class 1 (97%) - ideal for minimizing false negatives
- **Logistic Regression**: Best precision for class 0 (80%) - best for minimizing false positives

