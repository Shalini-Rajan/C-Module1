## Datatypes & Operators-Quotient Finder in C

## Aim
To write a C program to find the **quotient** of two integer numbers.

## Algorithm
1. Declare variables `a`, `b`, and `quotient`.
2. Read two integers `a` and `b` from the user.
3. Calculate the quotient by dividing `a` by `b` and store the result in the variable `quotient`.
4. Print the values of `a`, `b`, and `quotient` using the `printf` function.
5. Return 0 to indicate successful execution.

## Sample Code
```c
#include <stdio.h>

int main() {
    int a, b, quotient;

    // Read input values
    printf("Enter the value of a: ");
    scanf("%d", &a);
    printf("Enter the value of b: ");
    scanf("%d", &b);

    // Check for division by zero
    if (b == 0) {
        printf("Division by zero is not allowed.\n");
        return 1;
    }

    // Calculate quotient
    quotient = a / b;

    // Display the result
    printf("a = %d\n", a);
    printf("b = %d\n", b);
    printf("Quotient = %d\n", quotient);

    return 0;
}
