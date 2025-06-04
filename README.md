# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include <stdio.h>

int main() {
    float num1, num2, min;

    printf("Enter two fractional numbers: ");
    scanf("%f %f", &num1, &num2);

    min = (num1 < num2) ? num1 : num2;

    printf("Minimum of %.2f and %.2f is %.2f\n", num1, num2, min);

    return 0;
}
```


## OUTPUT:
![Screenshot 2025-04-27 090615](https://github.com/user-attachments/assets/fb6a2acb-37a3-4717-b9ab-08c96176aaf4)











## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.
