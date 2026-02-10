# 🧠 Parkinson’s Disease Detection using Machine Learning

## 📖 Project Overview
This project aims to detect **Parkinson’s Disease** using machine learning techniques
based on **biomedical voice measurements**.
The task is formulated as a binary classification problem.

---

## 🎯 Objectives
- Explore and analyze the Parkinson’s voice dataset
- Handle imbalanced data
- Apply feature scaling
- Train and compare multiple machine learning models
- Evaluate models using robust classification metrics
- Analyze feature importance

---

## 📊 Dataset Information
- **Samples:** 195
- **Features:** 22 numerical voice features
- **Target Variable:**
  - `status = 1` → Parkinson’s Disease
  - `status = 0` → Healthy

The dataset includes jitter, shimmer, noise ratios, and nonlinear signal processing features.

---

## ⚙️ Data Preprocessing
- Dropped non-informative column (`name`)
- Stratified train-test split
- Feature scaling using **RobustScaler**

---

## 🤖 Machine Learning Models
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- Cross-validation (F1-score)

### 🔍 Final Results

| Model | Precision | Recall | F1-score |
|------|----------|--------|----------|
| Logistic Regression | 0.933 | 0.965 | 0.949 |
| SVM | 0.931 | 0.931 | 0.931 |
| Random Forest | 0.933 | 0.965 | 0.949 |

**Best Models:** Logistic Regression & Random Forest

---

## 📌 Feature Importance
The most influential features include:
- `spread1`
- `PPE`
- `MDVP:APQ`
- `D2`
- Jitter-related features

These features highlight vocal signal irregularities related to Parkinson’s Disease.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run
Open the notebook and run all cells:

---

## ✅ Conclusion
The results show that machine learning models can effectively detect Parkinson’s Disease
using voice measurements, with Logistic Regression and Random Forest achieving the best performance.

---

## 👤 Author
**Ali Mahmoud**  
Machine Learning & Data Science Enthusiast
