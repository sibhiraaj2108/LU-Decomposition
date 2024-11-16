# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix

Program to find the L and U matrix.
Developed by: sibhiraaj R
RegisterNumber: 24010177

    import numpy as np
    import scipy
    from scipy.linalg import lu
    a=np.array(eval(input()))
    p,l,u=lu(a)
    print(l)
    print(u)3

(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
Developed by: sibhiraaj R
RegisterNumber: 24010177

    import numpy as np
    from scipy.linalg import lu_factor,lu_solve
    a=eval(input())
    b=eval(input())
    lu,piv=lu_factor(a)
    x=lu_solve((lu,piv),b)
    print(x)

## output:
![imagw 1](<Screenshot 2024-11-16 203707.png>)

![image 2](<Screenshot 2024-11-16 203716.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

