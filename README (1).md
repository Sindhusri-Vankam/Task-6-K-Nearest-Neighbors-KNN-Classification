# 🌸 K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 📌 Objective
Implement and understand the **K-Nearest Neighbors (KNN)** classification algorithm using the **Iris dataset**. The task involves preprocessing data, training the model with various `k` values, evaluating the model performance, and visualizing decision boundaries.

---

## 📚 Concepts Covered

- Instance-based learning
- Euclidean distance metric
- Feature normalization
- Choosing optimal value of `k`
- Confusion matrix & accuracy
- Decision boundary visualization

---

## 📦 Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

---

## 📁 Dataset

**Iris Dataset**  
Provided by Scikit-learn / Seaborn  
Contains 150 samples from 3 species of Iris (Setosa, Versicolor, Virginica) with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

---

## 🚀 Steps Performed

1. **Loaded** the Iris dataset using Seaborn
2. **Explored** the dataset with basic visualizations and `info()`
3. **Split** features and target variable
4. **Normalized** the features using `StandardScaler` (important for distance-based models)
5. **Split** into training and testing sets (80-20)
6. **Trained** the KNN model with various `k` values (`1, 3, 5, 7, 9`)
7. **Evaluated** using accuracy score and confusion matrix
8. **Visualized** decision boundaries (using only 2 features for 2D plot)

---

## 📊 Model Evaluation

| K | Accuracy |
|---|----------|
| 1 | 1.00     |
| 3 | 1.00     |
| 5 | 1.00     |
| 7 | 1.00     |
| 9 | 1.00     |

*(Accuracy may slightly vary depending on train/test split seed)*

---

## 🧩 Confusion Matrix

Displayed using `ConfusionMatrixDisplay` from `sklearn.metrics` for best-performing `k`.

---

## 🖼️ Decision Boundary

The decision boundary is plotted using only the **first two features** of the dataset.  
To visualize multi-class separation, the classes were encoded using `LabelEncoder`.


