# 🚀 Building SVM and k-NN Classifiers from Scratch

## 📌 Project Overview
This project implements two fundamental machine learning algorithms — **Support Vector Machine (SVM)** and **k-Nearest Neighbors (k-NN)** — completely from scratch using Python, without using Scikit-learn models.

The goal is to deeply understand how these algorithms work internally, including distance metrics, kernel functions, margin optimization, and classification logic.

---

## 🧠 Algorithms Implemented

### 🔷 k-Nearest Neighbors (k-NN)
- Implemented from scratch
- Distance metrics:
  - Euclidean Distance
  - Manhattan Distance
- Majority voting for classification
- Elbow Method used to determine optimal value of K

---

### 🔶 Support Vector Machine (SVM)
- Fully custom implementation
- Linear classifier built from scratch
- Gradient descent optimization
- Margin maximization concept implemented
- Kernel functions included:
  - Linear Kernel
  - Polynomial Kernel
  - RBF Kernel

---

## 📊 Key Features
- No use of Scikit-learn models
- Manual implementation of ML logic
- Custom distance computation
- Kernel trick implementation
- Model evaluation using accuracy
- Visualization of decision boundaries

---

## 🛠️ Technologies Used
- Python 🐍
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📁 Project Structure

Building_SVM_and_k_NN_Classifiers_from_Scratch/
│
├── Building_SVM_and_k_NN_Classifiers_from_Scratch.ipynb
├── README.md
---

## 📈 Output
- Classification on synthetic dataset
- Accuracy comparison between SVM and k-NN
- Elbow graph for selecting best K
- Decision boundary visualization

---

## 🚀 How to Run

### Option 1: Google Colab
1. Open the notebook in Colab
2. Run all cells
3. No installation required

### Option 2: Local System
```bash
pip install numpy matplotlib
jupyter notebook
