# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Ashqar Ahamed S.T
#RegisterNumber: 212224240018
import numpy as np
A = np.array([[1,-3],[3,1]])
B = np.array([0,10])
C = np.linalg.solve(A,B)
print(C)
```

## Output:
<img width="966" height="828" alt="Exp1" src="https://github.com/user-attachments/assets/f62b8841-a0af-49a8-b206-eeec01d048de" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

