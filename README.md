# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1.Read the elements of augmented matrix into arrays a and b 
 
2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution 

## Program:

(i) To find the L and U matrix

Program to find the L and U matrix.

Developed by: mahalakshmi.k

RegisterNumber: 212222240057

import numpy as np

from scipy.linalg import lu

A = np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)


(ii) To find the LU Decomposition of a matrix
/*
Program to find the LU Decomposition of a matrix.

Developed by:mahalakshmi.k 

RegisterNumber:212222240057

import numpy as np

from scipy.linalg import lu_factor, lu_solve

A = eval(input())#np.array(eval(input())

b = eval(input())

lu, piv = lu_factor(A)

x = lu_solve((lu,piv), b)

print (x)


## Output:
![Screenshot (14)](https://github.com/maha712/LU-Decomposition/assets/121156360/101f3ac9-42c0-430b-859f-1d39b26199d7)

![Screenshot (15)](https://github.com/maha712/LU-Decomposition/assets/121156360/da21a2ea-7f30-4ed0-a59c-75935e90b76d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

