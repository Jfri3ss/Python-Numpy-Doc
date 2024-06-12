---
Title: 'NumPy cos'
Description: 'Returns the cos of the argument.'
Subjects:
  - 'Python'
Tags:
  - 'numpy'
  - 'numpy cos'
CatalogContent:
  - 'NumPy cos'
  - 'Python NumPy Example'
---

# NumPy cos

In NumPy, the `cos` function is used to compute the cosine of each element in an array. This trigonometric function is essential for various mathematical computations, especially in physics, engineering, computer graphics, and signal processing. By applying the `cos` function element-wise, NumPy enables efficient and fast calculations on large datasets, making it an indispensable tool for scientific computing, data analysis, and machine learning. The ability to handle arrays and easily perform operations like cosine transformations underscores NumPy's pivotal role in scientific research, engineering, finance, and data analysis.

Syntax
The generic syntax for the NumPy math methods is as follows:
````
numpy.cos(argument)
````

## Example

````
codebyte/Python
import numpy as np

# Example array of angles in radians
angles = np.array([0, np.pi / 4, np.pi / 2, np.pi])

# Calculate the cosine of each angle
cos_values = np.cos(angles)

print("Angles (radians):", angles)
print("Cosine values:", cos_values)
````

````
Result of cos: [0, 0.78539816, 1.57079633, 3.14159265]
````

## Explanation:

1. Import NumPy: First, we import the NumPy library, which supports mathematical functions and operations on arrays.

2. Define an Array of Angles: We create an array of angles in radians, in which the np.pi constant represents π.

3. Compute Cosine Values: We use np.cos() to compute the cosine of each angle in the array. This method operates element-wise on the array, returning an array of the same shape with the cosine values.

4. Print Results: Finally, we print the original angles and their corresponding cosine values.

5. This code snippet demonstrates how to use the np.cos() function to calculate the cosine of given angles in radians, showcasing NumPy's ability to handle array operations efficiently.

## Numpy Trigonometric Functions

- Sine numpy.sin(): Computes the sine of each element in the array.
- Cosine numpy.cos(): Computes the cosine of each element in the array.
- Tangent numpy.tan(): Computes the tangent of each element in the array.
- Inverse Sine numpy.arcsin(): Computes the inverse sine of each element in the array.
- Inverse Cosine numpy.arccos(): Computes the inverse cosine of each element in the array.
- Inverse Tangent numpy.arctan(): Computes the inverse tangent of each element in the array.
