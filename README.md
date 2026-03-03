# Tip Prediction Using Linear Regression

## Project Overview

This project predicts restaurant tip amounts using a **Linear Regression** model. It demonstrates the full machine learning pipeline: data loading, visualization, model training, evaluation, and prediction using Python.

The dataset was slightly modified to include missing **weekday** and **daytime** columns in order to improve feature completeness and allow better analysis.

---

## How to Run the Project

1. Install required libraries:

```
pip install pandas scikit-learn plotly
```

2. Open and run the notebook:

```
jupyter notebook TipPrediction.ipynb
```

3. Run all cells to see visualizations, model training, evaluation, and predictions.

---

## Libraries Used

* **Pandas** – data loading and manipulation
* **Plotly Express** – data visualization (`scatter`, `pie`)
* **Scikit-learn** – model training and evaluation

---

## Model Description

* **Model:** Linear Regression
* **Training method:** Supervised learning
* **Data split:** Training and testing sets using `train_test_split` (test_size=0.2)

Linear Regression was chosen because the target variable **tip amount** is continuous and the model is simple, interpretable, and effective for this type of problem.

---

## Results

* **Model evaluation:** Accuracy is calculated using `r2`, `MAE` and `MSE` metrics.
* **Prediction:** Tip amount is predicted for a given feature set using `model.predict()`

---

## Outputs

* Scatter plots showing feature relationships
* Pie charts displaying categorical feature distributions
* Model accuracy scores

