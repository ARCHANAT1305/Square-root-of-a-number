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
#Prgram to find the square root of a number
#Developed By : ARCHANA.T
#Register Number:212223240013
def square_root(number):
    x=number/2
    while True:
        new_x=0.5*(x+number/x)
        if new_x ==x:
            break
        x=new_x
    return x
def main():
    num = int(input())
    if num<0:
        print("x")
    else:
        result =square_root(num)
    print(f"Square root of the number: {result}")
if __name__=="__main__":
    main()
```

## Output:
![square root](https://github.com/ARCHANAT1305/Square-root-of-a-number/assets/145975189/5e761f8f-1c90-47d9-ba6e-9d39edf88a30)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
