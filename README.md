# Breast Cancer Classification using Machine Learning

🎓 **Academic Project — Grade: 30/30**

MSc in Computer Engineering and Applied Artificial Intelligence  
San Raffaele University — 2026

---

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![SHAP](https://img.shields.io/badge/Explainable_AI-SHAP-blue)
![Grade](https://img.shields.io/badge/Grade-30%2F30-brightgreen)

## 🎯 Project Overview

This project explores supervised machine learning techniques
for breast cancer classification using the Breast Cancer
Wisconsin (Diagnostic) dataset.

## 🧠 Machine Learning Models

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

## 📊 Model Performance

| Model | Test Accuracy |
|---|---:|
| Logistic Regression | 97.37% |
| Support Vector Machine | 97.37% |
| Random Forest | 95.61% |

## 🔬 Methodology

- Exploratory Data Analysis
- Data Preprocessing and Standardization
- Principal Component Analysis (PCA)
- Model Training and Evaluation
- Confusion Matrix and ROC Curves
- SHAP Explainability

## 📁 Dataset

- 569 observations
- 30 numerical features
- Binary classification: benign and malignant

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

### Dataset Attribution

Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993).
Breast Cancer Wisconsin (Diagnostic).
UCI Machine Learning Repository.

DOI: https://doi.org/10.24432/C5DW2B

License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

The original dataset is provided without modifications.

## 🚀 Installation & Usage

Developed with Python 3.13.3.

```bash
git clone https://github.com/G1olly/breast-cancer-classification-ml.git
cd breast-cancer-classification-ml

python3 -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt

jupyter notebook breast_cancer_classification.ipynb
```

Run all notebook cells to reproduce the experiment.


## ⚠️ Disclaimer

This project was developed for academic and educational
purposes only. It is not intended for clinical diagnosis.

