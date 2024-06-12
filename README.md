---
Title: 'Math Methods'
Description: 'Performs mathematical operations on arrays.'
Subjects:
  - 'Computer Science'
  - 'Data Science'
Tags:
  - 'NumPy'
  - 'Math'
  - 'Methods'
  - 'Arrays'
CatalogContent:
  - 'learn-python-3'
  - 'paths/computer-science'
---

In NumPy, **Math Methods** are used to perform mathematical operations on arrays. These methods encompass arithmetic operations, trigonometric functions, exponential and logarithmic functions, and more. They play a crucial role in scientific computing, data analysis, and machine learning, making NumPy indispensable across scientific research, engineering, finance, and data analysis domains.

## Syntax

The generic syntax for the NumPy math methods is as follows:

```pseudo
numpy.math_method()
```

## Example

```py
import numpy as np

# Perform element-wise addition of two arrays using numpy.add() method
result = np.add([1, 2, 3], [10, 20, 30])
print("Result of addition:", result)
```

```shell
Result of addition: [11 22 33]
```

## Basic Categories of Math Methods

### 1. Basic Arithmetic Operations

- Addition `numpy.add()`: Performs element-wise addition of arrays.
- Subtraction `numpy.subtract()`: Performs element-wise subtraction of arrays.
- Multiplication `numpy.multiply()`: Performs element-wise multiplication of arrays.
- Division `numpy.divide()`: Performs element-wise division of arrays.
- Power `numpy.power()`: Performs element-wise exponentiation of arrays.

### 2. Trigonometric Functions

- Sine `numpy.sin()`: Computes the sine of each element in the array.
- Cosine `numpy.cos()`: Computes the cosine of each element in the array.
- Tangent `numpy.tan()`: Computes the tangent of each element in the array.
- Inverse Sine `numpy.arcsin()`: Computes the inverse sine of each element in the array.
- Inverse Cosine `numpy.arccos()`: Computes the inverse cosine of each element in the array.
- Inverse Tangent `numpy.arctan()`: Computes the inverse tangent of each element in the array.

### 3. Exponential and Logarithmic Functions

- Exponential `numpy.exp()`: Computes the exponential of each element in the array.
- Natural Logarithm `numpy.log()`: Computes the natural logarithm of each element in the array.
- Base-10 Logarithm `numpy.log10()`: Computes the base-10 logarithm of each element in the array.

### 4. Miscellaneous Functions

- Absolute Value `numpy.absolute()`: Computes the absolute value of each element in the array.
- Square Root `numpy.sqrt()`: Computes the non-negative square root of each element in the array.
- Ceiling `numpy.ceil()`: Rounds each element of the array to the nearest integer greater than or equal to that element.
- Floor `numpy.floor()`: Rounds each element of the array to the nearest integer less than or equal to that element.
- Rounding `numpy.round()`: Rounds each element of the array to the nearest integer.





---
Title: 'NumPy cos'
Description: 'Returns the cos of the argument.'
Subjects:
  - 'Computer Science'
  - 'Data Science'
Tags:
  - 'NumPy'
  - 'Math'
  - 'Methods'
  - 'Arrays'
CatalogContent:
  - 'learn-python-3'
  - 'paths/computer-science'
---

In NumPy, the **cos** function computes the cosine of each element in an array. This trigonometric function is essential for various mathematical computations, especially in physics, engineering, computer graphics, and signal processing. By applying the **cos** function element-wise, NumPy enables efficient and fast calculations on large datasets, making it an indispensable tool for scientific computing, data analysis, and machine learning. 

## Syntax
The generic syntax for the NumPy math methods is as follows:
```pseudo
numpy.cos(argument)
```

## Example
```py
import numpy as np

# Example array of angles in radians
angles = np.array([0, np.pi / 4, np.pi / 2, np.pi])

# Calculate the cosine of each angle
cos_values = np.cos(angles)

print("Angles (radians):", angles)
print("Cosine values:", cos_values)
```

```shell
Result of cos: [0, 0.78539816, 1.57079633, 3.14159265]
```

## Basic Categories of Math Methods

### 1. Basic Arithmetic Operations

- Addition `numpy.add()`: Performs element-wise addition of arrays.
- Subtraction `numpy.subtract()`: Performs element-wise subtraction of arrays.
- Multiplication `numpy.multiply()`: Performs element-wise multiplication of arrays.
- Division `numpy.divide()`: Performs element-wise division of arrays.
- Power `numpy.power()`: Performs element-wise exponentiation of arrays.

### 2. Trigonometric Functions

- Sine `numpy.sin()`: Computes the sine of each element in the array.
- Cosine `numpy.cos()`: Computes the cosine of each element in the array.
- Tangent `numpy.tan()`: Computes the tangent of each element in the array.
- Inverse Sine `numpy.arcsin()`: Computes the inverse sine of each element in the array.
- Inverse Cosine `numpy.arccos()`: Computes the inverse cosine of each element in the array.
- Inverse Tangent `numpy.arctan()`: Computes the inverse tangent of each element in the array.

### 3. Exponential and Logarithmic Functions

- Exponential `numpy.exp()`: Computes the exponential of each element in the array.
- Natural Logarithm `numpy.log()`: Computes the natural logarithm of each element in the array.
- Base-10 Logarithm `numpy.log10()`: Computes the base-10 logarithm of each element in the array.

### 4. Miscellaneous Functions

- Absolute Value `numpy.absolute()`: Computes the absolute value of each element in the array.
- Square Root `numpy.sqrt()`: Computes the non-negative square root of each element in the array.
- Ceiling `numpy.ceil()`: Rounds each element of the array to the nearest integer greater than or equal to that element.
- Floor `numpy.floor()`: Rounds each element of the array to the nearest integer less than or equal to that element.
- Rounding `numpy.round()`: Rounds each element of the array to the nearest integer.



