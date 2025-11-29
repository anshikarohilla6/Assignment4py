# Assignment4py
#name-Anshika
#course-BCA(AI&DS)
#Roll no-2501060113
#serial no-44

(a) Key Features of NumPy

NumPy (Numerical Python) is a powerful library for scientific and numerical computing in Python.
Important features include:

1. Multidimensional Arrays

Provides ndarray, which can store data in multiple dimensions (1D, 2D, 3D, etc.).

Faster and more efficient than Python lists.

2. High Performance

NumPy arrays are implemented in C, making operations much faster than using lists.

Supports vectorized operations (operate on whole arrays without loops).

3. Mathematical and Statistical Functions

Provides many built-in functions like mean(), sum(), sqrt(), linspace(), log(), etc.

4. Broadcasting

Allows arithmetic operations between arrays of different shapes.

5. Memory Efficient

Uses less memory compared to Python lists because it stores data of the same type.
Examples
Example 1: Creating NumPy Array vs Python List

import numpy as np

# NumPy array
arr = np.array([1, 2, 3, 4])
print(arr)

# Python list
lst = [1, 2, 3, 4]
print(lst)

Example 2: Vectorized Operation
import numpy as np

arr = np.array([1, 2, 3])
print(arr * 2)  
Output:
[2 4 6]

Python list:

lst = [1, 2, 3]
print(lst * 2)


Output:
[1, 2, 3, 1, 2, 3] (list repeats, no math operation)

Example 3: Multi-dimensional Arrays
import numpy as np

matrix = np.array([[1, 2], [3, 4]])
print(matrix)


Python list equivalent:

matrix_list = [[1, 2], [3, 4]]
print(matrix_list)

ques2 
import numpy as np
one_d=np.array([10,20,30,40])
two_d=np.array([[1,2,3],
                [4,5,6]])
print("one-dimensional Array:")
print(one_d)
print("shape:", one_d.shape)
print("dimension:",one_d.ndim)
print("data Type:",one_d.dtype)

print("\nTwo-Dimensional Array:")
print(two_d)
print("shape:",two_d.shape)
print("dimension:",two_d.ndim)
print("data Type:",two_d.dtype)




