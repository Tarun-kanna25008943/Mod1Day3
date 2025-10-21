# EX-03 Find Maximum of Two Numbers Using Conditional (Ternary) Operator

## AIM:
To write a C program to find the maximum number between two values using a conditional (ternary) operator.

## ALGORITHM:
1. Start
2. Declare two integer variables a and b.
3. Input the values of a and b.
4. Use the ternary operator max = (a > b) ? a : b; to find the largest number.
5. Display the maximum number.
6. Stop

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1,num2;
    printf("Enter the two numbers: ");
    scanf("%d %d",&num1,&num2);
    if(num1>num2)
    {
        printf("Maximum between %d and %d is %d",num1,num2,num1);
    }
    else
    {
        printf("Maximum between %d and %d is %d",num1,num2,num2);
    }
}
```

## OUTPUT:

<img width="666" height="129" alt="image" src="https://github.com/user-attachments/assets/8ed4ace1-8d66-44e2-8cea-147c8526cdcf" />

## RESULT:
The program successfully finds and displays the maximum number using the ternary operator.
