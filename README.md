# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Imoprt numpy as np

## Step 2:
Assign a variable and store the array of matrix

## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Step 4:
End the program 

## Program:
```#Program to find the eigen values and eigen vectors.
#Developed by: Kabilan V
#RegisterNumber:212222100018
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues, "and Eigen Vectors are",evector)
```

## Output:
![Screenshot (27)](https://user-images.githubusercontent.com/123469171/230019464-b3566695-4a20-4451-a999-0ed4a1ed152a.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
