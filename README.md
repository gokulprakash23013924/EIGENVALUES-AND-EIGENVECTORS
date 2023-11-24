# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: assign the matrix in a
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:Gokul Prakash M
#RegisterNumber:23013924
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
Values,Vectors=np.linalg.eig(a)
print("Eigen values are",Values,"and Eigen Vectors are",Vectors)

## Output:
![image](https://github.com/gokulprakash23013924/EIGENVALUES-AND-EIGENVECTORS/assets/150231472/cb63aa71-ea3e-4b1f-b6d5-933d0ca63395)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
