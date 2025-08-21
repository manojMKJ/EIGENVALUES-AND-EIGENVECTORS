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

<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/cd6bef10-2f87-4d87-bc02-e946b6b9cef1" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
