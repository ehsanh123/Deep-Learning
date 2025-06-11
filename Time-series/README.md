# 🧠 Week 10: Transfer Learning & Model Deployment  

This repository contains **Week 10** materials for **Deep Learning CSI_7_DEL**, focusing on **Transfer Learning** and **Model Deployment**. The tutorial and lecture guide you through leveraging pre-trained models for new tasks and deploying models as web applications.  

---

## 📌 Project Overview  

### **1️⃣ Transfer Learning**  
**Transfer Learning** allows us to apply knowledge from one model to another **related task**, reducing training time and improving efficiency.  

**Topics Covered:**  
- Understanding **Transfer Learning** and its advantages  
- Different **types of transfer learning**:
  - **Inductive** (same domain, different task)  
  - **Transductive** (related but different domains)  
  - **Unsupervised** (no labeled data)  
- Hands-on practice with **VGG16 model** for image classification  

**Practical Task:**  
- Classify different dog breeds using a **pre-trained VGG model**  
- Extend the model to classify **vehicle types**  

---

---

## 📂 Files in This Repository  

- `deeplearning_week_10.ipynb` → **Main Jupyter Notebook** for Transfer Learning & Model Deployment  
- `Week_10_Transfer_Learning.pdf` → **Lecture slides** on Transfer Learning  
- `week10-tutorial.pdf` → **Step-by-step tutorial** with practical exercises  

---

## 🛠️ Setup & Installation  

Before running the notebooks, install the required dependencies:  

```bash
pip install tensorflow keras flask flask_ngrok numpy matplotlib
