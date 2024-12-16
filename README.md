# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy as np to enable numerical operations.
### Step 2: Define a 2x2 matrix a that will be used to compute eigenvalues and eigenvectors.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the peogram

## Program:
import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))

## Output:
![Screenshot 2024-12-16 095126](https://github.com/user-attachments/assets/280ce86b-4b91-4a5a-924a-810aa49d0a21)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
