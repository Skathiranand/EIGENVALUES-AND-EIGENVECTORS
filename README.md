# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the list from each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End of the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: kathir anand.S
#RegisterNumber:23013711
import numpy as np
a = np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![output](https://github.com/Skathiranand/EIGENVALUES-AND-EIGENVECTORS/assets/147141136/c21bcf08-8db2-4de2-b78c-689bac00172d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
