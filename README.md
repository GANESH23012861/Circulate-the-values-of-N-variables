# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start program
### Step 2: 
Get input from the user 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the value
### Step 6: 
End program
## Program:
```
#Program to circulate N values.
#Developed by: selvaganesh R
#RegisterNumber: 23012861
def circulate(): 
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![output](/cir%20output.png)
## Result:
Thus given values are circulated using function concept