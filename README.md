# K-Nearest Neighbor (KNN) Classification

This repository contains a Python implementation of the **K-Nearest Neighbor (KNN)** algorithm applied to a **CSV-based classification dataset**.  
The project demonstrates end-to-end machine learning workflow including preprocessing, model training, evaluation, and result analysis.

---

## 📌 Project Description

K-Nearest Neighbor (KNN) is a **supervised, non-parametric, distance-based** machine learning algorithm.  
It classifies a data point based on the majority label of its *K* nearest neighbors in the feature space.

This project applies KNN to a real-world dataset to:
- Understand the impact of feature scaling
- Analyze the effect of different values of **K**
- Evaluate classification performance using standard metrics

---

## Dataset Information

- **File format:** CSV
- **Type:** Classification
- **Example dataset:** Lung cancer survey data
- **Target variable:** Binary class label (e.g., 0 / 1 or No / Yes)

### Preprocessing steps:
- Handling missing values
- Encoding categorical features
- Feature scaling (Standardization)
- Train–test data split

---

## Tools & Libraries

- Python 3.x
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## Model Details

- **Algorithm:** K-Nearest Neighbor (KNN)
- **Distance metric:** Euclidean distance
- **Hyperparameter:**  
  - `k` (number of nearest neighbors)

---

## Evaluation Metrics

The model is evaluated using:
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- ROC Curve (if applicable)

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Foysal348/K-Nearest-Neighbor.git
cd K-Nearest-Neighbor


