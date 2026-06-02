# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
## Output:
#Program to find the rank of a matrix.
#Developed by: 
#RegisterNumber:
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1,  5]])

rank = np.linalg.matrix_rank(A)

print(rank)
## Result:
<img width="1331" height="798" alt="Screenshot 2026-06-02 115221" src="https://github.com/user-attachments/assets/d9ee67b6-b7a9-4a01-9cf2-27d5d7c3e480" />

Thus the rank for the given matrix is successfully solved by  using a python program.

