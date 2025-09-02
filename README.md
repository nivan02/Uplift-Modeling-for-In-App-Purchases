# 🎮 Gaming Analytics – Uplift Modeling for In-App Purchases

This project focuses on applying **uplift modeling and predictive analytics** to a mobile gaming dataset. The objective was to identify which players should be targeted with in-app promotions to maximize campaign effectiveness and revenue. By leveraging player telemetry data and advanced machine learning, the project demonstrates how data-driven targeting can improve engagement and monetization in the gaming industry.

---

## 📌 Project Overview

Mobile gaming has become a dominant segment of the gaming industry, where revenue is driven largely by **in-app purchases (IAPs)** such as upgrades, new campaigns, and digital goods. The challenge for game developers is deciding **which players to target** with offers, since over-targeting can reduce engagement while under-targeting can leave potential revenue untapped.

This project used **uplift modeling** to estimate the **incremental impact** of marketing interventions, rather than simply predicting purchase likelihood. The analysis aimed to answer: *Which players are most likely to increase their spending if targeted with a campaign?*

---

## 🔍 Methodology

1. **Data Preparation**  
   - Worked with player telemetry data: play frequency, social interactions, in-game achievements, and prior purchases.  
   - Cleaned missing values and standardized variables for modeling.  
   - Created engineered features such as engagement bins and monetization history.  

2. **Modeling Approach**  
   - Baseline models: Logistic Regression and Random Forest to predict purchase probability.  
   - Uplift models: Causal Forests and Two-Model approaches (separate models for treatment vs. control).  
   - Evaluation metrics: Qini coefficient, AUUC (Area Under the Uplift Curve), and expected incremental profit.  

3. **Campaign Simulation**  
   - Simulated different targeting strategies: broad targeting, random targeting, and uplift-based targeting.  
   - Compared campaign ROI across strategies to quantify the value of uplift modeling.  

---

## 📂 Repository Contents

- `cg-uplift.ipynb` – Jupyter Notebook with data preparation, modeling, and uplift evaluation.  
- `creative-gaming.pdf` – Case Study.  

---

## 🛠️ Tools & Libraries

- **Python**: pandas, numpy, matplotlib, seaborn  
- **scikit-learn**: classification models and evaluation  
- **CausalML / EconML**: uplift modeling methods  
- **Visualization**: uplift curves, profit simulations  

---

