# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
create the function program import numpy as np
### Step 2: 
input as array as list element
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
and print result of the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Manoj Kumar G
#RegisterNumber:22005014
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![eigenvaluesandvectors](https://github.com/manojMKJ/EIGENVALUES-AND-EIGENVECTORS/assets/120717614/426bf426-0cc8-41d7-a440-f2017d40505c)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
