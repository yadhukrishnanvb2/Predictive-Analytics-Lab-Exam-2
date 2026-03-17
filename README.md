# Lab Exam – Binary Classification

## What this is

This is my submission for the lab exam on binary classification. The dataset has two features (`Feature1`, `Feature2`) and a binary target (`Yes` / `No`). I used **Logistic Regression** to classify the data and evaluated the results.

---

## Files

| File | Description |
|---|---|
| `Lab_Exam_binary_classification_dataset.csv` | The raw dataset |
| `lab_exam_classification.ipynb` | Main notebook with all tasks |
| `class_distribution.png` | Bar chart of class counts |
| `feature_distributions.png` | Histogram + KDE for each feature |
| `boxplots_by_class.png` | Box plots comparing features across classes |
| `scatter_by_class.png` | Scatter plot of Feature1 vs Feature2 |
| `correlation_heatmap.png` | Correlation matrix |
| `decision_boundary.png` | Decision boundary plot |
| `confusion_matrix.png` | Confusion matrix on test set |
| `roc_curve.png` | ROC curve |

---

## Tasks Covered

1. **EDA** – Checked for missing values, removed an extreme outlier, explored class balance, distributions, and correlations.
2. **Model** – Trained a Logistic Regression model with standard scaling and `class_weight='balanced'` to handle class imbalance.
3. **Decision Boundary** – Plotted the decision boundary overlaid on the dataset.
4. **Evaluation** – Reported accuracy, precision, recall, F1, ROC-AUC and  confusion matrix

---

## How to Run

Make sure you have the required packages installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Then open the notebook:

```bash
jupyter lab lab_exam_classification.ipynb
```

> **Note:** The dataset has a mild class imbalance (~78% No, ~22% Yes) and low feature-target correlation, which limits the performance of a linear classifier like Logistic Regression. This is discussed in the notebook observations.

