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
# Coefficients
a1, b1, c1 = 1, -3, 0
a2, b2, c2 = 3, 1, 10

# Determinant
D = a1*b2 - a2*b1

# Values of x and y
x = (c1*b2 - c2*b1) / D
y = (a1*c2 - a2*c1) / D

print(f"[{x:.0f}. {y:.0f}.]")
#DEVELOPED BY: ADHI SELVAKUMAR R
#REGISTER NO:212225220003
```
## Output:
<img width="1528" height="966" alt="Screenshot 2026-05-22 132112" src="https://github.com/user-attachments/assets/43f790c6-4e37-4877-bdcf-128182721fa8" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

