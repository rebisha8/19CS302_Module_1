# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE: 28/04/2025
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start.
2. Declare a variable value of type char.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Check eligible for marriage.
6. If age >= 21, print "Eligible".
7. If false, print " Not Eligible".
8. End.

## Program:
#include <stdio.h>

int main() {
    int age;
    scanf("%d", & age);

    if (age >= 21) {
        printf("You are eligible for marriage.\n");
    } else {
        printf("You are not eligible for marriage.\n");
    }

    return 0;
}

## Output:

![image](https://github.com/user-attachments/assets/45d00046-d00f-4a35-9d7f-d27c5c311f9c)



## Result:
Thus the program was executed and the output was verified successfully.
