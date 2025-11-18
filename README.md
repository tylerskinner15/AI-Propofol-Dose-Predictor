# Propofol Dose Prediction Using Machine Learning

Predicting anesthesia propofol bolus doses before surgery with ML — a step toward safer, data-driven anesthesia.

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/) 
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## Project Description
Machine learning project focused on predicting **propofol induction doses** using pre-operative patient data. This repository demonstrates a complete workflow, including data cleaning, feature engineering, modeling, evaluation, and inference.

---

## Key Findings
- **Classification model** predicted “high” (>100 mg) vs “low” (<100 mg) bolus dose with ~81% accuracy, outperforming regression models.  
- Regression models had low R², showing weak correlation between most pre-op features and bolus dose.  
- **Fentanyl dose** was the strongest positive predictor of propofol bolus dose.  
- Dataset limitations (HIPAA constraints) restricted model development.  
- Only the **initial bolus dose** was included; ongoing dosing predictions are not possible with this data.

---

## Methods & Tools
- Python, Pandas, NumPy  
- Scikit-learn (classification & regression models)  
- Matplotlib & Seaborn for visualization  
- Data preprocessing & feature engineering  
- Train/Test splitting and model evaluation  

---

## Repository Structure
├── PPFDosePred.ipynb # Main Jupyter notebook

├── data/

├── model/

├── README.md 

└── requirements.txt
