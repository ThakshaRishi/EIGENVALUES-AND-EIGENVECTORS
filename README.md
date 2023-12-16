# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Assign the matrix values to a variable.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the output.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Thaksha Rishi
#RegisterNumber: 23013212
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
x,y=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(x,y))
```
## Output:
![Alt text](<Screenshot 2023-12-16 192011.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
