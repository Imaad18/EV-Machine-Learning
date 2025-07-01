![image](https://github.com/user-attachments/assets/05872c1f-3d9d-4015-a8b8-c506fc10d0e8)


# ⚡ Electric Vehicle Specifications 2025 — Data Science & ML Project 🚗

This project explores a dataset of **478 modern electric vehicles**, analyzing their performance, range, efficiency, charging, and dimensions. It also uses machine learning to predict **range** and **market segment** using real-world specs.

---

## 📊 Features

✅ Advanced Feature Engineering  
✅ Stunning Visualizations (Radar, Violin, Pairplot, Parallel Coordinates)  
✅ XGBoost Regression for Range Prediction  
✅ XGBoost Classification for Segment Detection  
✅ SHAP Explainability (Model Transparency)  
✅ GridSearchCV for Hyperparameter Tuning  

---

## 📁 Project Structure

ev-ml-project/
├── data/ # Dataset (Kaggle download)
├── notebook/ # Jupyter notebook
├── plots/ # Saved charts (optional)
├── requirements.txt # Python packages
└── README.md # You're here


---

# > 📌 Dataset Source:  
> [Kaggle - Electric Vehicle Specifications 2025 by urvishahir](https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025)

- 🔢 Records: 478 EV models  
- 📌 Features: Battery, Charging, Speed, Acceleration, Dimensions, Segment, Drivetrain, etc.

---

## 📈 Visualizations

- ⚡ **Violin plots**: Acceleration by drivetrain  
- 🚘 **Radar chart**: Spec comparison for top 3 EVs  
- 🧬 **Pairplot**: Feature relationships  
- 📊 **Parallel coordinates**: Segment differentiation  
- 🔍 **SHAP Beeswarm**: Feature importance from ML models  

---

## 🧠 Machine Learning

| Task                      | Model           | Target             |
|---------------------------|------------------|---------------------|
| 🔋 Range Prediction        | XGBoostRegressor | `range_km`          |
| 🎯 Segment Classification | XGBoostClassifier| `segment`           |

✔️ ML Metrics: R² Score, Classification Report  
✔️ Feature importance with SHAP  
✔️ GridSearchCV for tuning  

---

## 🚀 How to Run



1. Clone the repo:
```bash
git clone https://github.com/yourusername/ev-ml-project.git
cd ev-ml-project


pip install -r requirements.txt




