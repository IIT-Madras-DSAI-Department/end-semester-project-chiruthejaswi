[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/R05VM8Rg)
# IIT-Madras-DA2401-Machine-Learning-Lab-End-Semester-Project
## **End Semester Project – MNIST Digit Classification**


## 📌 Purpose of this Repository
This repository contains the **complete implementation** of my MNIST multi-class digit classification system for the End Semester Project of **DA2401 – Machine Learning Lab, IIT Madras**.

The project requirements restrict the use of ML libraries such as scikit-learn or XGBoost.  
**All models are implemented from scratch using only Python, NumPy, and SciPy.**

The system includes:
- Linear classification models  
- Generative models  
- Clustering-based classification  
- Bagging ensemble models  
- A stacked meta-learner  
- Extensive hyperparameter tuning  
- Fully reproducible experiments  

All code is modular, clean, and designed strictly according to the assignment guidelines.
---
## 📁 Repository Structure
├── algorithms.py # All ML algorithms implemented
├── main.py # Main experiment script (training, tuning, evaluation)
├── Endsem.pdf # Final report (hyperparameters, bias-variance, analysis)
├── README.md # This file

---
### **Summary of Code Organization**
- **algorithms.py**  
  Contains implementations for:
  - Ridge Regression (One-vs-Rest)
  - Softmax Regression
  - Nearest Centroid Classifier
  - Gaussian Naive Bayes
  - K-Means Classifier
  - Bagging Ensemble
  - Utility functions (F1 score, one-hot)

- **main.py**  
  - Loads MNIST CSV files  
  - Builds feature matrices  
  - Runs multiple hyperparameter combinations  
  - Evaluates train/validation macro-F1  
  - Builds bagged Softmax models  
  - Builds the stacked meta-learner  
  - Prints results + stores them in `experiment_results.csv`  

---

# 📦 Installation & Dependencies

### **Dependencies (No ML libraries used):**
- Python 3.8+
- NumPy  
- SciPy (optional but allowed)
- Matplotlib (only for optional plots)

Install using:

```bash
pip install numpy scipy matplotlib

---

## ▶️ Running the Code

### A. Command-line (recommended for grading)

python3 main.py
  
---

## 🧾 Authors

**<Chiru thejaswi, DA24B036>**, IIT Madras (2025–26)

