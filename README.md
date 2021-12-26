
# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. START THE PROGRAM
2. IMPORT numpy,scipy
3. USE lu_solve,lu_factor 
4. END THE PROGRAM

## Program:
```
/*

1.Use LU Decomposition to find L and U matrix.

'''Program to find L and U matrix using LU decomposition.
Developed by: PRANAVE B 
RegisterNumber: 21500582
'''

# To print L and U matrix
import numpy as np
import scipy 
from scipy.linalg import lu

A=eval(input())
P,L,U=lu(A)
print(L)
print(U)

2.Use LU Decomposition to solve a matrix.

'''Program to solve a matrix using LU decomposition.
Developed by: PRANAVE B
RegisterNumber: 21500582

# To print X matrix (solution to the equations)
import numpy as np
import scipy
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)

x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:
![](lU.png)
![](LU1.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

=======
# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. START THE PROGRAM
2. IMPORT numpy,scipy
3. USE lu_solve,lu_factor 
4. END THE PROGRAM

## Program:
```
/*

1.Use LU Decomposition to find L and U matrix.

'''Program to find L and U matrix using LU decomposition.
Developed by: PRANAVE B 
RegisterNumber: 21500582
'''

# To print L and U matrix
import numpy as np
import scipy 
from scipy.linalg import lu

A=eval(input())
P,L,U=lu(A)
print(L)
print(U)

2.Use LU Decomposition to solve a matrix.

'''Program to solve a matrix using LU decomposition.
Developed by: PRANAVE B
RegisterNumber: 21500582

# To print X matrix (solution to the equations)
import numpy as np
import scipy
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)

x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:
![](lU.png)
![](LU1.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

