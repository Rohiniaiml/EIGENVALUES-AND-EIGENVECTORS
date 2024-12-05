# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module as np from python libaray
### Step 2: Define the matrix as ausing np.array([],[],[])
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Displaying the eingenvalues and eigenvectors using print function

## Program:
import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
## Output:
![Screenshot 2024-12-05 100716](https://github.com/user-attachments/assets/81057592-3d6d-4101-81fa-3fe6566bf5e3)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
