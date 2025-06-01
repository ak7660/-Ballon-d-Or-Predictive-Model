# 🏆 Ballon d’Or Predictive Model

This project analyzes historical player data to **predict Ballon d’Or voting outcomes** using statistical modeling. By collecting and cleaning data on top footballers from **2007 to 2024**, the team built regression models that estimate the **percentage of possible Ballon d’Or votes** a player should receive, based on their season performance.

## 📊 Project Overview

* **Objective:** Identify which player statistics (e.g. goals, assists, trophies) best predict Ballon d’Or results.
* **Scope:** Covers all Ballon d’Or nominees from 2007–2024.
* **Data Sources:** Primarily [TransferMarkt](https://www.transfermarkt.com), [FBRef](https://fbref.com), and official Ballon d’Or voting data.
* **Key Metric:** *Percentage of Possible Votes*, which normalizes vote totals across years.

## 🔍 Modeling Approaches

* **Multiple Linear Regression (MLR):** Position-specific models (Forwards, Midfielders, Defenders, Goalkeepers).
* **ANCOVA:** A unified model including position as a categorical predictor.
* **Decision Tree:** Explored for nonlinear relationships (not adopted due to lower accuracy).

## 📌 Key Insights

* **Major Awards** are the strongest predictor of vote share across all models.
* The **MLR model** correctly predicted **13 out of 17** actual Ballon d’Or winners.
* Models highlighted **undervalued players and seasons**, such as Yoann Gourcuff (2009).


## 📈 Future Work

* Expand with recent metrics (e.g. expected goals, progressive passes).
* Build a **real-time prediction system** for current seasons.
* Explore improvements in vote normalization.

---

> *"Statistics never lie — unless the journalists do."*

---

