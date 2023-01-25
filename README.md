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
Prepare a list for each linear equation and assign in numpy.linalg()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Print the eigenvalue and eigen vector using print() function. End the program

## Program:
'''
#Program to find the eigen values and eigen vectors.
#Developed by:Gokul J 
#RegisterNumber:22009062
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
res,v=np.linalg.eig(a)
print("Eigen values are",res,"and Eigen Vectors are",v)
'''
## Output:
![ev and evec](https://user-images.githubusercontent.com/121165938/214515047-717e2db9-3e99-4b1d-bf25-0a73ed547a87.png)
![eigen value and eigen vector](https://user-images.githubusercontent.com/121165938/214515122-caa66c3d-801b-49c0-8d99-97649301925d.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
