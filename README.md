# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SARVESH.M
#RegisterNumber:212225240140

import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0,  0,  3]
              ])

e, v = np.linalg.eig(A)

print("Eigen values are", e, "and Eigen Vectors are", v)

```

## Output:

<img width="1889" height="904" alt="Screenshot 2026-02-06 085958" src="https://github.com/user-attachments/assets/33725cca-4341-49d4-a0ba-699a90004a3a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
