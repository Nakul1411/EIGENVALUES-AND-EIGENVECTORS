# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in function in the calculations .
### Step 2: 
Prepare the lists from each equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program .
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: NAKUL R 
#RegisterNumber:212223240102
import numpy as np
matrix=np.array(([2,2],[1,3]))
eigenvalues,eigenvectors= np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
## Output:
![Screenshot 2024-04-15 192451](https://github.com/Nakul1411/EIGENVALUES-AND-EIGENVECTORS/assets/138849780/f5dec494-f940-4484-85ce-0b401bb884a0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
