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
#Developed by: LATHIKESHWARAN J
#RegisterNumber: 212222230072
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
soln=np.linalg.solve(A,B)
print(soln)
```
## Output:
![Screenshot (284)](https://github.com/LATHIKESHWARAN/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119393556/534b20b2-2e52-40b9-a033-a6d18e8cd21f)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

