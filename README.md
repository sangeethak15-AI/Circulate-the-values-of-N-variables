# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the function to circulate variables.
### Step 2: 
Assign the given values in a list.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Assign a variable for the new list after slicing and print the variable.
### Step 6: 
End of the program.
## Program:
```
#Program to circulate N values.
#Developed by: sangeetha.K
#RegisterNumber:21500118
def circulate():
    num1=[10,20,30,40,50,60]
    n=int(input())
    circ=num1[n:]+num1[:n]
    print("After circulating the values are:",circ)  
```    
## Output:
![output](./Output.png)
## Result:
Thus the circulate the n variables are successfully executed
