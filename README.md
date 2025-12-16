![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-green?logo=scikitlearn&logoColor=white)

# 🎮 PUBG Win Prediction

A machine learning project that predicts **winPlacePerc** (final placement percentage) in PUBG matches using player-level gameplay statistics.

---

## 🚀 Overview

This project builds a regression model to estimate how well a player/team will perform in a PUBG match based on combat, movement, and survival metrics. The prediction output ranges from `0–1` and is converted into a human-readable percentage (e.g., **86.38%**).

---

## 🎯 Objective

- Analyze PUBG match data  
- Predict `winPlacePerc` using machine learning  
- Optimize performance with hyperparameter tuning  
- Test the model with unseen sample data  

---

## 📂 Dataset

Player-level PUBG match statistics including:

- **Combat**: kills, assists, DBNOs, damageDealt  
- **Movement**: walkDistance, rideDistance, swimDistance  
- **Resources**: heals, boosts, weaponsAcquired  
- **Context**: matchType, matchDuration  

**Target:** `winPlacePerc`

---

## 🧹 Preprocessing

- Removed duplicates and missing values  
- Dropped leakage-prone features (`killPoints`, `rankPoints`, `winPoints`)  
- Label encoded `matchType`  
- Applied `log1p` transformation to skewed numerical features  

---

## 🤖 Model

- **XGBoost Regressor**  
- Hyperparameter tuning using **GridSearchCV**  
- Strong performance on non-linear tabular data  

---

## 📈 Evaluation

- RMSE  
- MAE  
- R² Score  

The tuned model generalizes well and shows low prediction error.

---

## 🧪 Sample Prediction

Predicted winPlacePerc: 0.8638
Predicted winPlacePerc (Percentage): 86.38%


---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Jupyter Notebook  

---
### 📬 Contact Me

If you have any questions, suggestions, or feedback regarding this project, feel free to reach out through the channels below:

## 👤 Author

**Athul**  
Machine Learning | Data Science | Data Analytics

**📧 Email:** athuldevkoroth@gmail.com  
**🔗 GitHub:** https://github.com/athuldevkoroth  
**💼 LinkedIn:** https://www.linkedin.com/in/athuldev-k  
