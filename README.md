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
#Developed by: RAMYA R
#RegisterNumber: 212223230169
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
result=np.linalg.solve(A,B)
print(result)
```
## Output:
![Screenshot 2024-02-28 083448](https://github.com/ramya23000505/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/149370791/8cc4b467-dc50-4181-a5cc-ca90718ce7be)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

