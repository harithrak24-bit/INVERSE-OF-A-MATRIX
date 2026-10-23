# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : read the inputs
### Step 2:import the NumPy library as np 
### Step 3: use the np.linalg.eig(),we get two results (first is eigen value and second is eigen vector) of the given matrix
### Step 4: display the eigenvalue and eigen vector as output

## Program:
#Program to find the inverse of a matrix.
#Developed by: 
#RegisterNumber:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
r=np.linalg.inv(A)
print(r)
## Output:
<img width="852" height="740" alt="Screenshot 2026-10-23 113415" src="https://github.com/user-attachments/assets/d81f1c9e-2ca2-4081-8cea-663e3a7ea646" />
<img width="935" height="312" alt="Screenshot 2026-10-23 113444" src="https://github.com/user-attachments/assets/40a95554-2831-4277-b307-e175b393ad82" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

