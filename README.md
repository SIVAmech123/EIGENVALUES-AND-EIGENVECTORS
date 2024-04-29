# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
#Program to find the eigen values and eigen vectors.

#Developed by: sivakumar.R

#RegisterNumber:23013501

import numpy as np

A=[[2,-3,0],[2,-5,0],[0,0,3]]

values,vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
<img width="638" alt="Screenshot 2024-04-06 132351" src="https://github.com/SIVAmech123/EIGENVALUES-AND-EIGENVECTORS/assets/151629067/2ca15ac8-3b5f-4558-a0f4-dc86f0f10496">









<img width="668" alt="Screenshot 2024-04-06 132405" src="https://github.com/SIVAmech123/EIGENVALUES-AND-EIGENVECTORS/assets/151629067/fc13dac8-e013-4a09-9e5e-02e9bd93bfaf">

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
