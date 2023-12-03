# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import numpy as np
### Step 2: Initialze a variable 'A' and make it a array using the np module
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:print the eigenvalue then eigen vector as desired
## Program:
```py
#Program to find the eigen values and eigen vectors.
#Developed by: MANOJ KUMAR S
#RegisterNumber: 23002959
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
# Output:
#![eigenvalues](https://github.com/Mkumar262006/EIGENVALUES-AND-EIGENVECTORS/assets/147139472/c69534de-a7c2-4a57-a723-4b32e2cf65c2)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
