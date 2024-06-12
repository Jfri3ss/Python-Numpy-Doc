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











## Python Code Example

````
codebyte/python
import numpy as np

# Example array of angles in radians
angles = np.array([0, np.pi / 4, np.pi / 2, np.pi])

# Calculate the cosine of each angle
cos_values = np.cos(angles)

print("Angles (radians):", angles)
print("Cosine values:", cos_values)
````



## Explanation:

1. Import NumPy: First, we import the NumPy library, which provides support for mathematical functions and operations on arrays.

2. Define an Array of Angles: We create an array of angles in radians. The np.pi constant is used to represent π.

3. Compute Cosine Values: We use np.cos() to compute the cosine of each angle in the array. This method operates element-wise on the array, returning an array of the same shape with the cosine values.

4. Print Results: Finally, we print the original angles and their corresponding cosine values.

5. This code snippet demonstrates how to use the np.cos() function to calculate the cosine of given angles in radians, showcasing NumPy's ability to handle array operations efficiently.
