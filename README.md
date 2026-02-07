# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212225220023
# Developed By:DHARSHAN BABU A
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2) 
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix) 


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input())) 
ans=np.linalg.norm(mat,np.inf) 
Norm_of_matrix="{:.2f}".format(ans) 
print(Norm_of_matrix)  




```
## Output:
### 1-Norm of a Matrix



<img width="1068" height="835" alt="image" src="https://github.com/user-attachments/assets/eab34a3d-d2ac-4e7a-8565-ff355cad5a5a" />


<img width="1234" height="344" alt="image" src="https://github.com/user-attachments/assets/93c5fdc7-34f1-4aee-b847-b5583aceccb1" />


### 2-Norm of a Matrix


<img width="835" height="822" alt="image" src="https://github.com/user-attachments/assets/421464b4-32cd-4e51-b852-d61c447523e4" />


<img width="1236" height="388" alt="image" src="https://github.com/user-attachments/assets/3a116108-1bb5-4ffe-a07f-927adf698faf" />


### Infinity Norm of a Matrix



<img width="1238" height="794" alt="image" src="https://github.com/user-attachments/assets/19941ea3-3ea3-4622-9fc3-44500548b33d" />


<img width="1227" height="336" alt="image" src="https://github.com/user-attachments/assets/0913618e-4995-4d4f-90e8-864f081a214a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
