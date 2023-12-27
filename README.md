# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: T Thrishendra
#RegisterNumber:23003501


import numpy as np

a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![Screenshot 2023-11-20 190635](https://github.com/Thrishendra/EIGENVALUES-AND-EIGENVECTORS/assets/145742464/c9a907d2-1df6-4137-87aa-d2b7deb81576)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
