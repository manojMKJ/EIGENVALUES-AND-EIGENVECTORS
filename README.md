# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation

### Step 2: Prepare the lists from the matrix and assign in np.array()

### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: End the program. 

## Program:
```
import numpy as np
A = np.array([[2, 2],[1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are ,eigenvalues and Eigen Vectors are,eigenvectors")

```

## Output:

<img width="1301" height="954" alt="MA ex4" src="https://github.com/user-attachments/assets/eaf1503a-f9cf-4957-b20d-83d9105202a5" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
