# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module.
### Step 2: 
Define a 3x3 numpy array A with the values [[5,-3,-10],[2,2,-3],[-3,-1,5]].
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
Use the print() function to output the value of the rank variable to the console.
### Step 5 :
End the program.
## Program:
```Program to find the rank of a matrix.
#Developed by: HARISH RAGAV S
#RegisterNumber: 212222110013

import numpy as np
A =np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![image](https://user-images.githubusercontent.com/119345345/226119375-5860067f-c044-4a57-bd1d-7ff7adb1e1fd.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

