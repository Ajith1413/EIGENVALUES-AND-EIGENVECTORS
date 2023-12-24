# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculations.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: AJITH KUMAR A
#RegisterNumber: 23002150
import numpy as np
a = [[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(a) 
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![image](https://github.com/Ajith1413/EIGENVALUES-AND-EIGENVECTORS/assets/139842524/d4ae8a6f-4e56-4870-b4fa-bda0b7bcdfdc)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
