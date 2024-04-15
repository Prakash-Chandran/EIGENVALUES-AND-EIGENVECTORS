# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the list for each linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
````
#Program to find the eigen values and eigen vectors.
#Developed by: PRAKASH C
#RegisterNumber:212223240122

import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigval,eigvect=np.linalg.eig(matrix)
print("Eigen values are",eigval,"and Eigen Vectors are",eigvect)
````
## Output:

![Screenshot 2024-04-15 222857](https://github.com/Prakash-Chandran/EIGENVALUES-AND-EIGENVECTORS/assets/147120899/c9ae4b22-57d2-4883-a941-d68bba75046f)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
