# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
assign in np.array() in eigen values and vector
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
print the values and vectors and end the program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:
import numpy as np 
A = np.array([[2,-3,0], [2,-5,0], [0,0,3]])

values,vectors=np.linalg.eig(A)
print ("Eigen values are {} and Eigen Vectors are {}".format (values,vectors))
```
## Output:
![OUTPUT](./maths4.png![maths 4](https://user-images.githubusercontent.com/94184990/144454578-08009833-0d9b-41a6-a54c-3f590def2af5.PNG)
)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
