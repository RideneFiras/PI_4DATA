
# 🔬 Model Comparison – QoS Prediction

This repository is dedicated to testing and evaluating multiple machine learning algorithms for predicting **network throughput (QoS)** in 5G environments. Each branch corresponds to a different approach tested by a group member.

Our aim is to assess the performance of each model using standard regression metrics and identify the most effective solution.

---

##  Performance Comparison Table

| Model                      | RMSE (Mbit/s)   | MAE (Mbit/s) | R² Score |
|---------------------------|----------------:|-------------:|---------:|
| **Old Model (Baseline)**  | 11.232          | 7.432        | 0.913    |
| **ANN**                   | 13.582          | 8.878        | 0.905    |
| **Random Forest**         | 10.046       | 5.964        | 0.942    |
| **Gradient Boosting**     | 9.486        | -            | 0.949    |
| **Ridge Regression**      | 10.046       | -            | 0.860    |
| **HistGradientBoosting**  | 10.046       | -            | 0.942    |
| **LassoRegression**  | 15.53       | 10.86            |  0.8632    |



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

