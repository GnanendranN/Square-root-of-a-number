# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Gnanendran N
RegisterNumber:  23006661
*/
def square_root(number):
    x=number/2.0
    iterations=100
    for i in range(iterations):
        x=0.5*(x+number/x)
    return x
a=int(input())
result=square_root(a)
print("Square root of the number:",result)
```

## Output:
![2b](https://github.com/GnanendranN/Square-root-of-a-number/assets/138955207/5189c134-ac89-4ea8-a375-393c414c8044)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
