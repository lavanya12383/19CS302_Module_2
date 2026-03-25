# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:17/03/2026
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
Start.
Declare the variables.
Prompt the user to enter a value.
Read the value using scanf.
Enter number for multiplication and division.
End.
## Program:
```
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
#include<stdio.h> 
void multiply(int a,int b); 
void div(int a,int b); 
int main () 
{ 
int a,b; 
scanf("%d%d",&a,&b); 
multiply(a,b); 
div(a,b); 
} 
void multiply(int a,int b) 
{ 
int product; 
product= a*b; 
printf("Multiplication: %d",product); 
} 
void div(int a,int b) 
{ 
int result; 
result=a/b; 
printf("\nDivision: %d",result); 
} 
Developed by: ARIGALA LAVANYA
RegisterNumber:  212222060019
*/
```

## Output:
<img width="622" height="239" alt="image" src="https://github.com/user-attachments/assets/3658965c-dab1-4aa7-bf60-3f138645956f" />



## Result:
Thus the program was executed and the output was verified successfully.
