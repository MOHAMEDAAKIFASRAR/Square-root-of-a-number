# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step1:
Define a function.
## Step2:
Assign number_iters = 100 in the function to perform 100 iteratios.
## Step3:
Set i = 0.
## Step4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
## Step5:
Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: MOHAMED AAKIF ASRAR S
RegisterNumber:  23003613
num=int(input())
a=1e-6
max=100

guess=num/2.0
for _ in range(max):
    new=0.5*(guess+num/guess)
    if abs(new-guess)<a:
        break
    guess=new
print(f"Square root of the number: {new}")    
*/
```

## Output:
![gcd of two number](gcd.png)![Screenshot 2023-12-21 175001](https://github.com/MOHAMEDAAKIFASRAR/Square-root-of-a-number/assets/148514683/0c4c481a-bdb6-4b81-a0fb-5947054f9e27)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
