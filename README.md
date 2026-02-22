# Keras Hyperparameter Tuning

This project explores hyperparameter tuning using **Keras Tuner** to optimize the performance of a neural network model.

## 📌 Objective

To understand how different architectural and optimization choices impact model performance and generalization.

Instead of manually selecting model configurations, this project uses automated hyperparameter search to determine the best combination of:

- Optimizer
- Number of hidden layers
- Number of neurons per layer
- Activation functions

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- Keras Tuner
- NumPy
- Pandas
- Matplotlib

---

## 🔎 Approach

1. Defined a flexible model-building function.
2. Specified hyperparameter search space.
3. Used Keras Tuner (RandomSearch / Hyperband / Bayesian Optimization).
4. Evaluated model performance using validation metrics.
5. Compared tuned model performance with manually configured models.

---

## 📊 Results

The tuned model showed improved validation performance and better generalization compared to manually selected configurations.

Key observations:
- Small architectural changes significantly impacted performance.
- Optimizer choice influenced convergence speed.
- Proper tuning reduced overfitting.

---

## 📂 Dataset

Dataset source: [[Pima Indians Diabetes Database: ](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)]

---

