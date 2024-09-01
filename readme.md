# Big Data Computation with Python

## Description
This repository contains practical exercises and assignments for the Big Data Computation course at Gunadarma University, 2023. The focus is on using Python for big data computation, including matrix operations and NumPy arrays.

## Table of Contents
- [Resources](#resources)
- [Python Matrices and NumPy Arrays](#python-matrices-and-numpy-arrays)
  - [Matrix Definition](#matrix-definition)
  - [Python Matrix](#python-matrix)
  - [NumPy Array](#numpy-array)
- [How to Run](#how-to-run)

## Resources
- [GOOGLE COLAB](https://colab.research.google.com/)
- [JUPYTER NOTEBOOK](https://jupyter.org/try)
- [Hypercomputation Gunadarma](https://hypercomputation-hub.gunadarma.ac.id/)
- [Webkumal ARTIFICIAL INTELLIGENCE](https://webkumal.com/tag/artificial-intelligence/)

## Python Matrices and NumPy Arrays

### Matrix Definition
A matrix is a two-dimensional data structure where numbers are arranged into rows and columns. For example, a 3x4 matrix (read as "three by four") has 3 rows and 4 columns.

### Python Matrix
Python does not have a built-in type for matrices. However, we can treat lists within lists as matrices. For example:
```python
A = [[1, 4, 5], 
     [-5, 8, 9]]
```

### NumPy Array
NumPy is a library for scientific computing that supports multi-dimensional arrays. For example:
```python
import numpy as np

a = np.array([1, 2, 3])
print(a)
print(type(a))
```

## How to Run
1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/big-data-computation.git
    cd big-data-computation
    ```

2. Install the required libraries:
    ```sh
    pip install numpy
    ```

3. Open the Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

4. Run the notebooks provided in the repository to explore various matrix operations and NumPy array manipulations.

---

By following the structured approach and utilizing the provided resources, you will gain a comprehensive understanding of using Python for big data computation.