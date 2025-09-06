# Wine-Quality-Prediction
This repository is about predicting wine quality using various regression models. It includes data exploration, model selection (balancing accuracy and explainability) and performance evaluation.

---

## 📂 Repository Structure

- **data/**  
  White wine dataset (referenced from the UCI Machine Learning Repository).

- **notebooks/**  
  Jupyter notebooks with step-by-step analysis, model building, and results. Includes final lambda/alpha values used in the models.  

---

## 🧠 Approach

- Explored the white wine dataset and checked for missing values or outliers.  
- Tested multiple regression models to evaluate prediction performance.  
- Selected:
  - **Best predictive model** → lowest MSE & highest R².  
  - **Simpler explanatory model** → fewer parameters but good predictive power.  
- Compared the trade-off between **accuracy** and **explainability**.  

---

## 📊 Key Metrics

- **MSE (Mean Squared Error)** → Model error comparison.  
- **R² (Coefficient of Determination)** → Goodness of fit.  
- **Feature Importance** → Key parameters influencing wine quality.  

---

## 👩‍🏫 Non-Technical Explanation

Wine quality is influenced by a few important chemical properties:  
- **Alcohol content** – Higher alcohol often improves perceived quality.  
- **Acidity levels** – Balance between fixed acidity and volatile acidity matters.  
- **Sulphates & residual sugar** – Affect taste, preservation, and freshness.  

In simple terms, wines with balanced acidity, good sugar levels, and slightly higher alcohol are usually rated better.  

---
