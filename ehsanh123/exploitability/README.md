# 🧠 Introduction to SHAP – Model Explainability in Machine Learning

This repository accompanies a video tutorial on using **SHAP (SHapley Additive exPlanations)** to interpret machine learning models. It walks through how SHAP values work, why explainability matters, and how to apply SHAP to tree-based models like XGBoost and Random Forest.

🎥 **Video Tutorial Link:**  
[LSBU Panopto LectureCast – SHAP Intro Tutorial](https://lsbu-lecturecast.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=e597f6e1-66e4-4599-b312-b2b500a60a5f)

---

## 📁 Files

- `Introduction_to_SHAP.ipynb`  
  A Jupyter notebook that demonstrates:
  - Training a classification model (XGBoost)
  - Applying SHAP to explain predictions
  - Visualizing global and local feature importance

---

## 🛠️ Requirements

Install dependencies via pip:

```bash
pip install shap xgboost pandas scikit-learn matplotlib
