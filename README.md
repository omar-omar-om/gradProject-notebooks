# gradProject-notebooks
# 🛡️ Secure Insights — Machine Learning for Real-Time Malware Detection

This repository contains all preprocessing, encoding strategies, and model training experiments for **Secure Insights**, a real-time malware detection system using the Microsoft Malware Prediction dataset and machine learning techniques.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `data_preprocessing.ipynb` | Handles initial data loading, cleaning, and feature selection |
| `encoding.ipynb` | Applies and compares multiple categorical encoding strategies |
| `frequency_tree.ipynb` | Trains tree model using frequency encoding |
| `label_tree.ipynb` | Trains tree model using label encoding |
| `targetEncodingTree.ipynb` | Uses target encoding with tree-based models |
| `NN_All_ENCODING.ipynb` | Tests all encoding methods using a neural network |

---

## 🧠 Technologies Used

- **Google Colab** for all notebook-based experimentation
- **Python**, with libraries:
  - `pandas`, `numpy` for data processing
  - `scikit-learn` for modeling
  - `xgboost`, `lightgbm` for advanced gradient boosting
  - `PyTorch` for neural network model

---

## 📊 Dataset

- **Microsoft Malware Prediction Dataset** (Kaggle)
- Data consists of anonymized Windows telemetry features

---

## ✅ Goals

- Evaluate various encoding strategies and their impact on ML model performance
- Identify the best-performing setup for real-time malware prediction
- Serve as the backend ML engine for the full system (deployed separately)

---

## 📈 Evaluation Result Snapshot

- Best performing model: **XGBoost with Label Encoding**
- AUC on validation set: **0.7318**
- Evaluation time: **~5.19 seconds**, suitable for real-time use

---

## 🌐 Frontend and Deployment

You can view the full system (web interface, FastAPI backend, and Tableau dashboard) in the linked repo here:

🔗 [[Frontend + API Repository Link Goes Here](https://github.com/omar-omar-om/GradProj)]

---

## 👨‍💻 Author

**Omar Ibrahim**  
Coventry University — The Knowledge Hub  
Supervisor: Dr. Nada Gaballah  
Assistant: Dr. Donia Mohamed

---

