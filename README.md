# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# Step1 :
Import the numpy module to use the built-in functions for calculation
# Step 2:
Prepare the lists from each equations and assign in np.array()
# Step 3:
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
# Step 4:
End the program

#Program to find the inverse of a matrix.
#Developed by: Sriharan j v
#RegisterNumber:212223100054
import numpy as np  
matrix = np.array([ 
[1, 0, 3],
[-1, 2, -2],
[2, 3, -1]
])
try:
    inverse_matrix = np.linalg.inv(matrix)
    print(inverse_matrix)
except np.linalg.LinAlgError:
    print("Matrix is singular and cannot be inverted.")


## Output:

 ![image](https://github.com/sriharan23000516/INVERSE-OF-A-MATRIX/assets/139841769/0391c8c9-81c1-43f4-92e9-9ea2a9050072)

## Result:
Thus the inverse of given matrix is successfully solved using python program
