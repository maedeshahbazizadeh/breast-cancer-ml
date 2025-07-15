#  Breast Cancer Prediction Using Machine Learning

This project leverages the **Breast Cancer Wisconsin (Diagnostic) Dataset** to build supervised machine learning models for predicting whether a tumor is **benign (B)** or **malignant (M)** based on diagnostic features extracted from medical imaging.

---

## 📁 Dataset

- **Source**: [Breast Cancer Wisconsin Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Samples**: 569
- **Features**: 30 numeric features (e.g., radius, texture, perimeter)
- **Target Variable**: `diagnosis`  
  - `M` = Malignant  
  - `B` = Benign  

---

## Project Objectives

- Load and explore the dataset
- Build a clean ML pipeline using Scikit-learn
- Apply and compare classification models:
  - Logistic Regression
  - Random Forest
- Tune hyperparameters with GridSearchCV
- Evaluate using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC
  - Confusion Matrix
  - Learning Curves & Feature Importance
- Address ethical considerations in medical AI systems

---

## 💻 Notebook

📔 You can run the project directly in **Google Colab**:  
**👉 _[Open in Colab]([https://colab.research.google.com](https://colab.research.google.com/drive/1FM6EvOwl7rhLUEl2UOP6WRkrhK5qv1rm#scrollTo=q4uz2UjKwUG-)_**

---

## Requirements

This project runs in **Google Colab** using the following Python libraries:

- `numpy`, `pandas`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## Sample Results

| Metric             | Score               |
|--------------------|---------------------|
| **Train Accuracy** | 1.00                |
| **Test Accuracy**  | 0.95                |
| **F1 Score**       | 0.938               |
| **Precision**      | 0.957               |
| **Recall**         | 0.920               |
| **MSE**            | 0.046               |
| **AUC (avg)**      | ~0.98 - 1.00        |

Visualizations included:
- ✅ ROC Curves across outer CV folds
- ✅ Confusion Matrix
- ✅ Learning Curves
- ✅ Feature Importances (Random Forest)

---

---

## 👤 Author

**Maede Shahbazi Zade**  
📎 [GitHub Profile](https://github.com/maedeshahbazizadeh)

---

## ⚠️ Disclaimer

This project is for **educational purposes only** and should **not be used for real-world diagnosis**. The models are trained on public academic data and are **not suitable for clinical use**.
