# 📊 Predictive Maintenance of Industrial Equipment using Machine Learning Models
## CS527 Data Science – Group Project (Co-developer: Nay Lin Aung)

This project develops machine learning models to predict machine failures using the AI4I 2020 Predictive Maintenance Dataset. In addition to achieving strong predictive performance, the project emphasizes interpretability and actionable insights using SHAP analysis and counterfactual recourse.

## 📌 Project Overview

Manufacturing equipment failures can lead to costly downtime and operational disruptions. This project applies data science and explainable AI (XAI) techniques to:

- Predict whether a machine will fail
- Identify the most likely failure type
- Explain the key drivers behind predictions
- Recommend actionable changes to reduce failure risk

## 📂 Dataset

**Source:** AI4I 2020 Predictive Maintenance Dataset 
- UCI Machine Learning Repository
- 10,000 simulated manufacturing records<br>
:https://www.google.com/urlq=https%3A%2F%2Farchive.ics.uci.edu%2Fdataset%2F601%2Fai4i%2B2020%2Bpredictive%2Bmaintenance%2Bdataset 


## 🧠 Methodology
**1. Data Audit and Provenance**
- Verified dataset integrity
- Removed data leakage variables
- Documented modeling assumptions

**2. Exploratory Data Analysis (EDA)**
- Failure rate distribution
- Correlation analysis
- Feature visualizations

**3. Feature Engineering**
Created physics-informed variables:<br>

- Temperature Difference
- Power = Torque × Rotational Speed
- Wear × Torque Interaction

**4. Binary Classification Models**

Compared:<br>
- Logistic Regression
- Random Forest
- XGBoost

Evaluation Metrics:<br>
- ROC-AUC
- PR-AUC
- F1 Score
- Precision
- Recall
- Balanced Accuracy
  
**5. Explainable AI**
- SHAP global and local explanations
- Dependence plots
- Feature importance analysis

**6. Multiclass Classification**
Predicted specific failure causes using:<br>
- Multinomial Logistic Regression
- Multiclass XGBoost
  
## 📸 Screenshots
**1.Operation Conditions by Failure Outcomes**
<img width="1429" height="745" alt="Screenshot 2026-05-11 at 12 03 22" src="https://github.com/user-attachments/assets/3d7fef08-5b15-4e31-99ed-597d9db4c4b3" />

**2.Permutation Important of Selected Binary Models**
<img width="1429" height="745" alt="Screenshot 2026-05-11 at 12 05 05" src="https://github.com/user-attachments/assets/e7876bb0-72fb-4c61-ad71-8524a8e0986e" />

**3.Mean | SHAP**
<img width="1429" height="745" alt="Screenshot 2026-05-11 at 12 06 03" src="https://github.com/user-attachments/assets/52915a48-cd5f-4034-af14-0fa779e5a272" />

**4.Top Multiclass XGBootst Features Importance**
<img width="1429" height="745" alt="Screenshot 2026-05-11 at 12 08 41" src="https://github.com/user-attachments/assets/46d274d0-22b6-4d20-99cd-6c5bc1db116b" />

## 📈 Key Findings
- XGBoost delivered the strongest predictive performance.
- Torque, tool wear, and power were the most influential features.
- SHAP explanations provided transparent and interpretable insights.
- Counterfactual analysis suggested operational adjustments to avoid failures.

## 🛠 Tools Used
- Python, Pandas, NumPy
- Matplotlib Seaborn
- Scikit-learn,  XGBoost, SHAP

## 🚀 Learning Outcomes

This project demonstrates: <br>
- End-to-end machine learning pipeline development
- Feature engineering using domain knowledge
- Handling imbalanced classification problems
- Explainable AI techniques
- Translating model outputs into operational decisions
