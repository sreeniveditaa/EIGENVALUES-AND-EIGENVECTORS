# DATE :
# EXP 04 : EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Sree Niveditaa Saravanan
#RegisterNumber: 212223230213
```
```
import numpy as np
a = np.array([[2,2],[1,3]])
val,vect = np.linalg.eig(a)
print("Eigen values are",val,"and Eigen Vectors are",vect)
```
## Output:

![image](https://github.com/user-attachments/assets/e7f4c8c3-6969-4e0a-bf00-9ee36af67ed2)

![image](https://github.com/user-attachments/assets/d601e66a-5199-436b-9f54-c98e01d5a92f)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
