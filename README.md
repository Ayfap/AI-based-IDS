# 🔐 Hybrid Classical–Quantum AI-Based Intrusion Detection System

A **hybrid intrusion detection system (IDS)** that combines **classical machine learning** and **quantum-inspired machine learning** techniques to detect malicious network traffic.  
The system is evaluated on the **CICIDS network intrusion dataset** using a **Random Forest classifier** and a **Quantum Support Vector Machine (QSVM)** implemented with Qiskit.

---

## 📌 Project Overview

Intrusion Detection Systems (IDS) play a critical role in securing modern networks by identifying unauthorized access and cyber attacks.  
This project explores a **hybrid classical–quantum approach** where:

- **Classical ML** handles large-scale network traffic efficiently
- **Quantum ML (simulated)** explores complex feature relationships on a small, balanced subset of data

The goal is to **compare performance** and demonstrate the feasibility of **quantum-enhanced intrusion detection** using current quantum simulation tools.

---

## 🎯 Objectives

- Detect network intrusions accurately using machine learning  
- Build a baseline **classical IDS** using Random Forest  
- Implement a **quantum-enhanced IDS** using Quantum SVM  
- Compare classical and quantum model performance  
- Ensure the system is **Google Colab and RAM safe**

---

## 🗂 Dataset

- **Dataset:** CICIDS Collection  
- **Source:** Kaggle  
- **Type:** Real-world network traffic flows  
- **Labels:**  
  - `BENIGN`  
  - Attack traffic (merged as `Attack`)

Due to the large size of the dataset:
- **Classical IDS** is trained on a large sample  
- **Quantum IDS** is trained on a **small, balanced subset** (research-standard approach)

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
  - KaggleHub
  - Qiskit
  - Qiskit Aer
  - Qiskit Machine Learning

---

## 🧠 System Architecture

### Classical IDS
1. Data preprocessing and cleaning  
2. Feature scaling  
3. Train–test split  
4. Random Forest model training  
5. Performance evaluation  

### Quantum IDS (Hybrid Approach)
1. Balanced sampling of small dataset  
2. Feature scaling  
3. PCA-based feature reduction (4 features → 4 qubits)  
4. Quantum feature mapping (ZZFeatureMap)  
5. Quantum kernel computation (fidelity-based)  
6. Quantum SVM (QSVC) classification  

---

## ⚛️ Quantum Computing Details

- Quantum computations are performed using **Qiskit Aer Simulator**
- A **fidelity-based quantum kernel** is used
- Modern **V2 Qiskit primitives** ensure compatibility with current APIs
- This project uses **quantum simulation**, not real quantum hardware

> ⚠️ Quantum models are intentionally trained on small datasets due to current quantum hardware and simulator limitations.

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## ✅ Results Summary

- **Random Forest (Classical IDS):** High accuracy on large-scale data  
- **Quantum SVM (QSVC):** Competitive performance on small, balanced data  
- **Hybrid approach:** Demonstrates practical integration of quantum ML with classical systems  

---
