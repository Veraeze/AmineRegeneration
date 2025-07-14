# AmineRegeneration
# Optimal Reboiler Duty Prediction for Amine Regeneration

##  Project Description
This project focuses on predicting the **optimal reboiler duty** for an amine regeneration unit using **machine learning models**. The goal is to minimize energy consumption while ensuring efficient acid gas removal, based on process simulation data generated from Aspen HYSYS.

---

##  Objectives Covered
**Objective 2:** Predict optimal reboiler duty to improve energy efficiency in the amine regeneration process.

---

## Tools and Libraries
- Python (Google Colab)
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for data visualization
- `scikit-learn` for model building
- `xgboost` for advanced regression (optional)
- **Random Forest Regressor** (main model used)

---

## Key Results

| Metric | Value |
|--------|-------|
| **R² Score** | 0.9997 |
| **RMSE** | ~51,191 Btu/hr |

- **Top Features:** `DEA7 - H₂S Composition (ppm)`, `DEA7 - CO₂ Composition (mole %)`
- The model achieves **exceptionally high accuracy** with **strong predictive power** on simulation data.

---

##  Project Workflow
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Training with Random Forest
4. Model Evaluation (R², MSE, RMSE, plots)
5. Feature Importance Analysis
6.  _Next Phase:_ Deployment via a simple dashboard interface (Objective 2 continuation)

---
