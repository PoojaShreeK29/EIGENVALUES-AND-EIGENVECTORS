# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Read the inputs.
### Step 2: 
Import the NumPy library as np .
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the eigenvalues and eigenvectors as output.

## Program:
###
#Program to find the eigen values and eigen vectors.
###
#Developed by: POOJA SHREE K
###
#RegisterNumber: 26018233
###
import os
###
os.environ["OPENBLAS_NUM_THREADS"]="1"
###
import numpy as np
###
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
###
values,Vector=np.linalg.eig(A)
###
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vector))

## Output:
<img width="806" height="626" alt="image" src="https://github.com/user-attachments/assets/a1f17e23-1d77-45c0-91ac-ca6b16711515" />
<img width="1318" height="212" alt="Screenshot 2026-10-13 174251" src="https://github.com/user-attachments/assets/3d50f2b2-cf1a-462c-a201-afb09de8f1f4" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
