# Breast Cancer Diagnosis using Logistic Regression

# Objective
To build a binary classification model using Logistic Regression to accurately detect breast cancer as malignant (M) or benign (B) using the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

---

# Dataset
**Source:**-"C:\Users\alfai\Downloads\data.csv"

- Total Records: 569
- Features: 30 numeric features related to cell nuclei characteristics
- Target:
  - `M`: Malignant (1)
  - `B`: Benign (0)

# Tools & Libraries
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

# Project Workflow
# 1. **Data Preprocessing**
- Loaded and explored the dataset
- Removed irrelevant columns (`id`, `Unnamed: 32`)
- Converted categorical target to binary: `M` → 1, `B` → 0

# 2. **Train-Test Split**
- Used an 80-20 split on the data
- Standardized features using `StandardScaler`

# 3. **Model Building**
- Trained a `LogisticRegression` model from scikit-learn

# 4. **Model Evaluation**
- Evaluated using:
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC-AUC Score
  - ROC Curve Visualization

# 5. **Threshold Tuning**
- Tested different probability thresholds (e.g., 0.3) for model performance improvement

# 6. **Sigmoid Function Visualization**
- Plotted sigmoid function to understand logistic regression output

# Results

| Metric         | Value (default threshold 0.5) |
|----------------|-------------------------------|
| Accuracy       | ~96%                          |
| Precision      | High (~95%+)                  |
| Recall         | High (~95%+)                  |
| ROC-AUC Score  | ~0.99                         |

# Visualizations Included
- Confusion Matrix Heatmap
- ROC Curve
- Sigmoid Function Plot

# Key Concepts Covered
- Logistic Regression for classification
- Feature scaling with `StandardScaler`
- Binary target encoding
- Threshold tuning
- Evaluation metrics: Precision, Recall, AUC
- Understanding sigmoid activation
