# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 :
    Import the numpy module to use the built-in functions for calculations
### Step 2:
    Prepare the lists from each linear equations and assign in np.array()
### Step 3:
    Using the np.linalg.solve(),we can find the solution
### Step 4:
    End the program 
## Program: 
   ```
   #program to find the inverse of a matrix
   #Developed by: PRADEEP.S
   #RegisterNumber:22009034
   
   import numpy as np
   A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
   result=np.linalg.inv(A)
   print(result)  
   ```
## Output: 
   ![inverse of a matrix](https://user-images.githubusercontent.com/120539823/211202297-e50f024b-e7fe-4fe8-a40d-77f6642da92b.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

