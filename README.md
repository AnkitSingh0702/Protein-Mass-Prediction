# 🧬 Protein Mass Prediction

This repository contains my practice work for the **MachineHack Challenge**:  
👉 [Biohack: Predicting Protein Mass](https://machinehack.com/hackathons/biohack_predicting_protein_mass)  

The main objective of this challenge is to **predict the protein mass** using given features. Since the dataset was already clean, the focus was on **building regression models** and evaluating their performance.  

---

## 📌 Project Overview  

- Performed **Exploratory Data Analysis (EDA)** (basic checks, as dataset was clean).  
- Built and compared **11 regression models**.  
- Used **Root Mean Squared Error (RMSE)** as the primary evaluation metric.  
- Created a **custom function** to simplify model training and evaluation.  
- Final submission involved scaling the test data before predictions.  
- The **fine-tuned RandomForest Regressor** gave the **lowest RMSE score** among all models.  

---

## ⚙️ Tech Stack & Libraries  

- **Language:** Python 🐍  
- **Environment:** Jupyter Notebook  
- **Core Libraries:**  
  - `pandas`, `numpy` → Data handling  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → Machine Learning models, scaling, evaluation  
  - `joblib` → Model saving/loading  

---
