# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import numpy module to use built-in functions
### Step 2:
Get lists from the linear equation and assign it to np.array
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Print the result
### Step 5: 
End the program
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: naveen s
#RegisterNumber: 212222110030
import math
list1=[4,2]
list2=[10,6]
distance=math.sqrt(((list2[0]-list1[0])**2+((list2[1]-list1[1])**2)))
print("{:.2f}".format(distance))
```

### OUTPUT:
![image](https://github.com/NaveenSivamalai/DISTANCE-BETWEEN-TWO-POINTS/assets/123792574/5491d3fc-16c8-4123-921f-3e4d3a21d20b)


### RESULT:
Thus the distance between the two points is successfully obtained.
