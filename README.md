# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to use the bulit-in functions for calculation
### Step 2: prepare the lists from each equations and assign in np.array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:singamala venkata sai kumar reddy 
#RegisterNumber:23004205
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors = np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)

```
## Output:

![Screenshot 2023-12-19 112438](https://github.com/23004205/EIGENVALUES-AND-EIGENVECTORS/assets/138971114/93acb1fa-0a65-4029-99bc-259fbfa48cf9)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
