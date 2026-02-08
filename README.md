<img width="860" height="779" alt="image" src="https://github.com/user-attachments/assets/c54628a7-305e-41f4-9d99-a978c95497e0" />
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
```p
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
sol=np.linalg.solve(A,B)
print(sol)
```
## Output:

<img width="1293" height="835" alt="image" src="https://github.com/user-attachments/assets/9d611f47-5f04-4401-92ea-d5c1762f6599" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

