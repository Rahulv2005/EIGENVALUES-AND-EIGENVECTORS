# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step1 :
Import the numpy module to use the built-in functions for calculation.

Step 2:
Prepare the lists from each equations and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program
```
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:RAGHUL V 
#RegisterNumber: 212223240132
import numpy as np
A = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Rahulv2005/EIGENVALUES-AND-EIGENVECTORS/assets/152600335/6fa00ec5-8762-43b1-8d03-cb9ed68fb044)
![image](https://github.com/Rahulv2005/EIGENVALUES-AND-EIGENVECTORS/assets/152600335/f81d9154-e58f-4c2b-83e2-271934b70454)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
