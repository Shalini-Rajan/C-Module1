## Datatypes & Operators-Quotient Finder in C

## Aim
To write a C program to find the **quotient** of two integer numbers.

## Algorithm
1. Declare variables `a`, `b`, and `quotient`.
2. Read two integers `a` and `b` from the user.
3. Calculate the quotient by dividing `a` by `b` and store the result in the variable `quotient`.
4. Print the values of `a`, `b`, and `quotient` using the `printf` function.
5. Return 0 to indicate successful execution.

## Program
```
#include <stdio.h>

int main() {
    int a, b, quotient;
    printf("Enter the first number (a): ");
    scanf("%d", &a);
    printf("Enter the second number (b): ");
    scanf("%d", &b);
    if (b != 0) {
        quotient = a / b;
        printf("a = %d, b = %d, quotient = %d\n", a, b, quotient);
    } else {
        printf("Error: Division by zero is not allowed.\n");
    }

   return 0; 
}
```


## Output
```
User Input:
Enter the first number (a): 20
Enter the second number (b): 4
Program Output:
a = 20, b = 4, quotient = 5
```

## Result
programme was implemented and executed.
    
