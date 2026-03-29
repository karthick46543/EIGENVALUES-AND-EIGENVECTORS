# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:import numpy as np A = np.array([[4, 2],[2, 4]]) x,y = np.linalg.eig(A) print("Eigen values are", x, "and Eigen Vectors are" ,y)

## Output:<img width="735" height="201" alt="image" src="https://github.com/user-attachments/assets/1985b9bb-2bf0-4116-99af-2acd19854e75" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
