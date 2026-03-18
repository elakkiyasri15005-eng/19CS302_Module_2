# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Create a function to read a number and calculate its factorial.
2. Initialize factorial result to 1.
3. Use a loop to multiply numbers from 1 to the given number.
4. Return the factorial result from the function.
5. In main, call the function and print the result.
  

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: Sai Ranjani K
RegisterNumber: 212222060210
#include<stdio.h>
int factorial(int a)
{
    if(a==0)
    return 1;
    else
    return(a*factorial(a-1));
}
int main()
{
    int num;
    scanf("%d",&num);
    int fact=factorial(num);
    printf("Factorial value is: %d",fact);
    return 0;
    
}
*/
```

## Output:


![image](https://github.com/user-attachments/assets/15f4e401-81b6-4391-a3d3-8d49c86781ad)


## Result:
Thus the program was executed and the output was verified successfully.
