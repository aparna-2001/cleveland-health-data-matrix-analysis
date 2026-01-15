
## Cleveland Heart Disease Matrix Analysis

This repository contains a Python-based analysis of the **Cleveland Heart Disease dataset** using **matrix, linear algebra, and PCA concepts**.

### Project Overview

* Focuses on representing health data in **matrix form**
* Applies **linear algebra operations** for data analysis
* Uses **Principal Component Analysis (PCA)** to study redundancy and dimensionality
* Designed for **learning and exploration**, not predictive modeling

---

### Code Structure

* Data loading and preprocessing

  * Uses `zipfile` and `csv`
* Matrix construction using **NumPy**
* Linear algebra–based analysis and interpretation
* PCA-based dimensionality analysis

---

### 🔢 Matrix Analysis Module

**`analyze_matrix.py` – a single function for matrix analysis**

* Contains a **single wrapped function**
* Computes:

  * Determinant
  * Rank
  * Inverse (if applicable)
  * Eigenvalues and Eigenvectors
* Function is written once and reused
* Imported and applied wherever required

---

### 🔁 Wrapped Function Usage

The wrapped function is kept in a separate `.py` file to ensure:

* Reusability
* Cleaner code structure
* Separation of logic and analysis

Example usage:

```python
from matrix_module import analyze_matrix
result = analyze_matrix(file)
```

---

### 📉 PCA Analysis

* PCA is applied to:

  * Identify **redundant features**
  * Reduce dimensionality
  * Understand variance distribution
* Uses:

  * Covariance / correlation matrix
  * Eigenvalues and eigenvectors
* Helps interpret **dominant patterns** in health data

---

### 🛠 Tools & Libraries

* Python
* NumPy
* Pandas
* Zipfile

---

### 📊 Dataset

* Cleveland Heart Disease Dataset (Kaggle)
* Widely used for **educational and research** purposes in health data analysis

