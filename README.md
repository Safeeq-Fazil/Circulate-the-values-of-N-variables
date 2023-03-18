# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define the function circulate
### Step 2: 
Get the value of the list from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the value of the circulated list
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Safeeq Fazil.A
#RegisterNumber:212222240086
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![python 1b](https://user-images.githubusercontent.com/118680361/226115498-256c9b00-ea2e-4478-9bc6-770dcddb149c.png)


## Result:
The program to circulate the values of N variables executed successfully.
