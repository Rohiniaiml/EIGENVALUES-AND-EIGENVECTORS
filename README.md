# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy module to use the built-in function for calculation
### Step 2: prepare the list from  each linear equations and assign as np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the peogram

## Program:
```python
import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
![Screenshot 2024-12-16 120551](https://github.com/user-attachments/assets/5c2585f5-c5cb-4b47-a3bf-09d308b118bc)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
