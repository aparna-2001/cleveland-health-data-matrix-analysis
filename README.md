

## Cleveland Heart Disease Matrix Analysis

This repository contains a Python-based analysis of the **Cleveland Heart Disease dataset** using matrix and linear algebra concepts.

### Project Overview

* Focuses on representing health data in **matrix form**
* Applies basic **linear algebra operations** for data analysis
* Designed for **learning and exploration**, not predictive modeling

### Code Structure

  * Data loading and preprocessing - zipfile and csv
  * Matrix construction using Numpy
  * Linear algebra–based analysis and interpretation

* **`analyze_matrix.py - a single function for matrix analysis`**

  * Contains a **single wrapped function**
  * contains - Determinant, Rank, Inverse, Eigen Values and Eigen vectors
  * The function is written once and reused across the analysis
  * Imported and applied to the dataset wherever required

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

### 🛠 Tools & Libraries

* Python
* NumPy
* Pandas
* Zipfile

### 📊 Dataset

* Cleveland Heart Disease Dataset - from Kaggle 
* Commonly used for educational and research purposes in health data analysis

