# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
      1. Start the program and import the NumPy library (`import numpy as np`). 
      2. Get the input matrix from the user and store it as a NumPy array using `np.array()`.
      3. Compute the 1-norm of the matrix using `np.linalg.norm(matrix, 1)`.
      4. Compute the 2-norm of the matrix using `np.linalg.norm(matrix, 2)`.
      5. Compute the infinity norm of the matrix using `np.linalg.norm(matrix, np.inf)`.
      6. Display all three calculated matrix norms formatted to two decimal places.
      7. Stop the program.
## Program:
```Python
# Register No:26017171
# Developed By:Arjun M
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import ast
import numpy as np
matrix_input=ast.literal_eval(input())
A=np.array(matrix_input)
norm_1=np.linalg.norm(A, ord=1)
print(f"{norm_1:.2f}")



# 2-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat =np.array(eval(input()))
ans =np.linalg.norm(mat,2)
print(round(ans, 2))




# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat =np.array(eval(input()))
ans =np.linalg.norm(mat, np.inf)
print(f"{ans:.2f}")




```
## Output:
### 1-Norm of a Matrix
<img width="828" height="755" alt="image" src="https://github.com/user-attachments/assets/48bba465-bee5-44e8-890d-7e1d6d8891b0" />


### 2-Norm of a Matrix
<img width="802" height="798" alt="image" src="https://github.com/user-attachments/assets/761bfea0-b801-4d8c-aebd-171f89606811" />


### Infinity Norm of a Matrix
<img width="745" height="748" alt="image" src="https://github.com/user-attachments/assets/37ef368d-8aee-4660-a825-60310c033fa8" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
