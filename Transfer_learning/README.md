# 🍽️ Transfer Learning with Functional API

This project demonstrates how to implement **Transfer Learning** using **TensorFlow's Functional API**. The model is trained on a subset (10%) of the **10 Food Classes** dataset to classify food images.

---

## 📁 Project Structure

The notebook contains the following main components:

### 📦 Data Loading & Preparation
- Unzips and loads a dataset of 10 food categories.
- Prepares training and validation directories.

### 🏗️ Model Building
- Uses TensorFlow’s Functional API.
- Utilizes a pre-trained model (e.g., `EfficientNetB0`) as the base.

### 🏋️‍♂️ Training
- Compiles and fits the model with transfer learning.
- Implements callbacks for optimization (e.g., early stopping, model checkpointing).

### 📈 Evaluation & Visualization
- Plots accuracy and loss curves.
- Shows sample predictions on validation/test images.

---

## 🧠 Key Concepts

- **Transfer Learning**: Using a model pre-trained on a large dataset (e.g., ImageNet) and fine-tuning it on a smaller, task-specific dataset.
- **Functional API**: Enables more complex and flexible model architectures compared to the Sequential API in TensorFlow/Keras.

---

## 🚀 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/transfer-learning-functional-api.git
cd transfer-learning-functional-api
