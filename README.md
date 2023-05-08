# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : we have to initialise program using import numpy to perform mathematical calculation
### Step 2: The input from the user is stored in the variable
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
Developed by: Thivakar.R
RegisterNumber: 212222240109
```
```
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:

![Screenshot 2023-05-08 144541](https://user-images.githubusercontent.com/118707074/236786571-f53ef4a7-c915-4e9d-86c2-6c0a79de90ec.png)


## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
