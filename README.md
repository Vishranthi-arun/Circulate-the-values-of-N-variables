# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Enter the values
### Step 2: 
values range from 10-60
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the result
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Vishranthi A
#RegisterNumber:21003066
def circulate():
   a=[10,20,30,40,50,60]
   b=int(input())
   result=a[b:]+a[:b]
   print("After circulating the values are:",result)
```
## Output:
![OUTPUT](./Ex02.JPG)

## Result:
Thus the circulating of N variables are successfully executed.