# 🔐 AI-Based Intrusion Detection System using Machine Learning

An **AI-Based Intrusion Detection System (IDS)** built using **Machine Learning** to detect malicious network traffic from real-world datasets.  
This project uses the **CICIDS dataset** and is implemented entirely in **Python using Google Colab**.

---

## 📌 Project Overview

Intrusion Detection Systems (IDS) are essential for identifying unauthorized access and malicious activities in computer networks.  
This project applies **machine learning techniques** to classify network traffic as **Normal (BENIGN)** or **Attack**.

The system follows a complete ML pipeline:
- Data collection
- Data preprocessing
- Feature scaling
- Model training
- Intrusion detection
- Performance evaluation

---

## 🎯 Objectives

- Detect network intrusions automatically using AI
- Classify traffic as **Normal or Attack**
- Achieve high detection accuracy
- Build a reusable and scalable IDS model

---

## 🗂 Dataset

- **Dataset Name:** CICIDS Collection  
- **Source:** Kaggle  
- **Type:** Network traffic flow-based dataset  
- **Classes:**  
  - `BENIGN`  
  - Multiple attack types (merged into `Attack`)

The dataset contains real network traffic with labeled attack scenarios.

---

## 🛠 Technologies Used

- **Programming Language:** Python  
- **Platform:** Google Colab  
- **Libraries:**
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Joblib
- **Algorithm:** Random Forest Classifier

---

## 🧠 Machine Learning Model

### Random Forest Classifier
Chosen because:
- Handles large and high-dimensional datasets
- Resistant to overfitting
- Works well for intrusion detection problems
- Supports feature importance analysis

---

## ⚙️ System Workflow

1. Download dataset using KaggleHub  
2. Load and merge multiple CSV files  
3. Clean data (handle NaN and infinite values)  
4. Encode labels (BENIGN → 0, Attack → 1)  
5. Feature scaling using StandardScaler  
6. Train-test split  
7. Model training (Random Forest)  
8. Prediction and evaluation  
9. Model saving for future use  

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## ✅ Results

The model successfully detects intrusions with **high accuracy** and balanced precision-recall performance, proving the effectiveness of machine learning for network security applications.

---
