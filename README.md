# mean-variance-std-calculator
This Python calculator computes statistical metrics such as mean, variance, standard deviation, maximum, minimum, and sum for a given 3x3 matrix. It reshapes 1D lists into matrices and calculates results for rows, columns, and the entire matrix using NumPy. Results are organized into a structured dictionary for easy reference.

# Calculator for Statistical Operations
This Python project calculates statistical metrics such as mean, variance, standard deviation, maximum, minimum, and sum for a given 3x3 matrix.

## Features
- Computes metrics along rows, columns, and for the entire matrix.
- Supports reshaping 1D lists into a 3x3 matrix.

## Example Usage
```python
from calculator import calculate

result = calculate([1, 2, 3, 4, 5, 6, 7, 8, 9])
print(result)

