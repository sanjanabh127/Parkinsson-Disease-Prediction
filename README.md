# 🧠 Parkinson’s Disease Detection Using Machine Learning (SVM)  

![Python](https://img.shields.io/badge/Python-🐍-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Data%20Modeling-F7931E?logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Viz-11557C?logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-2E5EAA?logo=seaborn&logoColor=white)
  

---

##  Project Overview  

Parkinson’s Disease (PD) is a **progressive neurodegenerative disorder** affecting movement and speech. Early detection is critical for **timely intervention and improved quality of life**.  

This project leverages **machine learning**, specifically a **Support Vector Machine (SVM) classifier**, to predict whether an individual has Parkinson’s Disease based on **24 biomedical voice features**.  

---

## 🗂 Dataset  Source: 
-**Parkinson Disease Detection** - Kaggle
- **Features:** 24 numeric voice measurements (e.g., **Jitter, Shimmer, NHR, HNR**)  
- **Target Column:** `status` (0 = Healthy, 1 = Parkinson)  
- **Samples:** Multiple records from patients and healthy individuals  

---

##  Tools & Libraries  

- Python 3.12  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  

---

## Project Workflow  

1. **Data Loading:** Import the CSV dataset using Pandas  
2. **Exploration & Preprocessing:** Analyze distributions, handle missing values, and clean the data  
3. **Feature Selection:** Use all 24 voice features for model training  
4. **Train-Test Split:** Divide the dataset into training (80%) and testing (20%) sets  
5. **Model Training:** Train a **Support Vector Machine (SVM)** classifier  
6. **Evaluation:** Assess performance using **accuracy, classification report, and confusion matrix**  
7. **Prediction:** Predict Parkinson’s Disease status for new individuals  

---

##  Results  

- **Accuracy:** ~[87]%  
- **Insights:** The model effectively distinguishes between healthy individuals and Parkinson’s patients using voice features  
- **Confusion Matrix:** Visual representation of **actual vs predicted** classifications  

---


