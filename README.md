# Keras Hyperparameter Tuning

This project explores hyperparameter tuning using Keras Tuner to optimize a neural network model.

## 📌 Objective

To understand how different hyperparameters such as optimizer choice, number of layers, and number of neurons affect model performance.

Instead of manually selecting these values, Keras Tuner is used to automatically search for better configurations.

---

## ⚙️ What Was Tuned

- Optimizer (e.g., Adam, RMSprop, etc.)
- Number of hidden layers
- Number of neurons per layer
- Activation functions

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Keras Tuner
- NumPy
- Pandas

---

## 🔎 Approach

1. Defined a model-building function with tunable hyperparameters.
2. Used Keras Tuner to search across different model configurations.
3. Selected the best-performing hyperparameter combination.
4. Trained and evaluated the optimized model.

---

## 📂 Dataset

Dataset source: ([Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database))

---

