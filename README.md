# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import numpy as np

### Step 2:enter the value of an given matrix 

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:use print function to print the values and then run the program


## Program:
#Program to find the rank of a matrix.
#Developed by: LAKSHMI PRIYA P
#RegisterNumber:21001411

import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])

values=np.linalg.matrix_rank(A)
print(values)

## Output:
![output](./rank.PNG)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

