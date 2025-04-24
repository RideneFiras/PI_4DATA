
# 🔬 Model Comparison – QoS Prediction

This repository is dedicated to testing and evaluating multiple machine learning algorithms for predicting **network throughput (QoS)** in 5G environments. Each branch corresponds to a different approach tested by a group member.

Our aim is to assess the performance of each model using standard regression metrics and identify the most effective solution.

---

##  Performance Comparison Table

| Model                     | RMSE (Mbit/s) | MAE (Mbit/s) | R² Score |
|--------------------------|---------------|--------------|----------|
| **Baseline [(Kaggle Model)](https://www.kaggle.com/datasets/gauravduttakiit/qos-prediction-challenge-aiml-in-5g-challenge?select=Train.csv)** | 10.797        | 6.86         | 0.923    |
| **➡️ Gradient Boosting** | **9.486**     | **5.8**      | **0.949**|
| XGBoost                  | 9.847         | 6.092        | 0.949    |
| Random Forest            | 10.046        | 5.964        | 0.942    |
| HistGradientBoosting     | 10.046        | 6.35         | 0.936    |
| ANN                      | 13.582        | 8.878        | 0.905    |
| Lasso Regression         | 15.530        | 10.86        | 0.863    |
| Ridge Regression         | 16.450        | 11.38        | 0.860    |



---

## 🧑‍💻 Contributor Branches

Each contributor worked independently in their own branch:

- `Firas` ➤ Artificial Neural Network (ANN)
- `Ghassen` ➤ Random Forest
- `Ghada` ➤ Ridge Regression
- `Eya` ➤ HistGradientBoosting
- `Mohamed` ➤ Lasso Regression
- `Louai` ➤ XGBoost

---

##  Goal

The final objective is to choose the **best-performing and most explainable model** to integrate into our throughput prediction system.

