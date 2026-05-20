# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import library Numpy as np.
### Step 2: Define the matrix with the given values.
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix. 
### Step 4: Print the results using formatted string.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Tanushree G
#RegisterNumber:212225040462
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[4, 2],
              [2, 4]])

v1, v2 = np.linalg.eig(A)

print("Eigen values are", v1, "and Eigen Vectors are", v2)
```

## Output:
<img width="661" height="519" alt="image" src="https://github.com/user-attachments/assets/d5e9acf5-3f5b-44c5-a3d3-52836625fab2" />
<img width="1020" height="153" alt="image" src="https://github.com/user-attachments/assets/3d0ca4e2-4ad7-49ca-b18b-2c08759b94d7" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
