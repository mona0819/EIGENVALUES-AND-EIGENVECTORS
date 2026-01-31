# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy library, which contains the linalg (linear algebra) module required for spectral decomposition.
### Step 2: Initialize a square matrix A (in this case, a 2x2 matrix) using the np.array() function.
### Step 3: Call the np.linalg.eig(a) function. This function returns a tuple.
### Step 4: Use formatted strings to print both the eigenvalues and their corresponding eigenvectors to the console.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Mohana Priya D
#RegisterNumber: 212225230182
import numpy as np
a=np.array([[4,2],[2,4]])
val,vec=np.linalg.eig(a)
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
```


## Output:
<img width="1242" height="782" alt="image" src="https://github.com/user-attachments/assets/372e3e48-dd30-4ce8-94e5-41e3d9866949" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
