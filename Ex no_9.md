# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:17/03/2026
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
Start
Read num
Convert num to positive if negative
Initialize sum = 0
do-while loop:
Get last digit
If odd, add to sum
Remove last digit
Repeat until num == 0
Print sum
End  

## Program:
```
/*
Program to find the sum of odd digits using do while loop.
#include <stdio.h>
int main() {
    int num, digit, sum = 0;
    scanf("%d", &num);
    if (num < 0) {
        num = -num;
    }
    do {
        digit = num % 10;
        if (digit % 2 != 0) { 
            sum += digit;
        }
        num = num / 10;
    } while (num != 0);
    printf("Sum of odd digits is: %d\n", sum);
    return 0;
}

Developed by: ARIGALA LAVANYA
RegisterNumber: 212222060019 
*/
```

## Output:

<img width="263" height="55" alt="image" src="https://github.com/user-attachments/assets/6a529855-627a-468b-80bc-50735a9ecac8" />


## Result:
Thus the program was executed and the output was verified successfully.
