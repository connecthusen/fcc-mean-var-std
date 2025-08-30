# FreeCodeCamp: Mean-Variance-Standard Deviation Calculator

This project is part of the **Data Analysis with Python** certification on [freeCodeCamp](https://www.freecodecamp.org/).

## 📖 Project Goal
Create a function `calculate()` that:
- Takes a list of 9 numbers
- Converts it into a 3x3 NumPy matrix
- Returns a dictionary with mean, variance, standard deviation, max, min, and sum (row-wise, column-wise, and flattened)

## 🛠️ Files
- `mean_var_std.py` → main solution
- `main.py` → test script

## ▶️ Example Run
```python
from mean_var_std import calculate

print(calculate([0,1,2,3,4,5,6,7,8]))
