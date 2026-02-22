# Study-of-Numpy
## Name- Srushti J. Nalawade
## PRN- 25070123157
## Batch- A1
## Aim:
To study the NumPy library and perform basic operations on NumPy arrays.
## Objectives 

>Generate various NumPy array configurations. 

>Execute arithmetic and mathematical computations on datasets. 

>Examine array properties and master element selection via indexing. 

>Utilize integrated NumPy methods for data processing. 


## System & Software Needs 


Language: Python 


Package: NumPy 


Environment: Google Colab, Jupyter Notebook, or any standard Python IDE 


## Theory

NumPy (Numerical Python) serves as the fundamental framework for scientific computing within the Python ecosystem. At its core is the ndarray, a multidimensional container for homogeneous data, which allows for high-speed mathematical operations that would be significantly slower using native Python structures. 


### Key Benefits: 


Speed: Significantly outperforms standard Python lists. 


Efficiency: Optimized to utilize less memory. 


Vectorization: Supports streamlined operations without explicit loops. 


Functionality: Offers a robust set of statistical and algebraic functions. 


## Procedure


Library Initialization import numpy as np 
+1


Basic Array Generation data = np.array([10, 20, 30, 40]) print(data) 
+1


Generating Specialized Arrays (Zeros, Ones, and Ranges) print(np.zeros(4)) print(np.ones(4)) print(np.arange(1, 10, 2)) 
+1


Inspecting Metadata (Attributes) matrix = np.array([[1, 2, 3], [4, 5, 6]]) 
+1

Dimensions: matrix.ndim 

Shape: matrix.shape 

Element Count: matrix.size 

Data Category: matrix.dtype 


Modifying Array Structure flat_array = np.array([1, 2, 3, 4, 5, 6]) print(flat_array.reshape(2, 3)) 
+1


Arithmetic Calculations x = np.array([10, 20, 30]) y = np.array([1, 2, 3]) print(x + y), print(x - y), print(x * y), print(x / y) 
+1


Data Analysis & Statistics vals = np.array([10, 20, 30, 40]) print(np.mean(vals)), print(np.sum(vals)), print(np.max(vals)), print(np.std(vals)) 
+1


Accessing & Slicing Segments sample = np.array([10, 20, 30, 40, 50]) print(sample[1]) (Single item) print(sample[1:4]) (Range of items) 
+1


## Observations

Successfully initialized and populated NumPy arrays. 

Completed element-wise arithmetic operations. 

Extracted key statistical metrics from the data. 

Verified structural properties of created objects. 


## Conclusion 

The experiment effectively demonstrated how to implement and manage essential NumPy array operations and functions.
