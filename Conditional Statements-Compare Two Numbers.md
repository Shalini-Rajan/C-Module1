## Conditional Statements-Compare Two Numbers
## Aim
Write a C program to read values of x and y and print whether x == y or x != y using an if-else statement.

## Algorithm
Declare variables x and y.

Read two integers x and y from the user.

Check if x is equal to y using the if statement.

If x is equal to y, print "X is equal to Y".

If x is not equal to y, print "X is NOT equal to Y".

## Program
```
#include <stdio.h>
int main() {
    int x, y;
    printf("Enter two integers (x and y): ");
    scanf("%d %d", &x, &y);
    if (x == y) {
        printf("X is equal to Y\n");
    } else {
        printf("X is NOT equal to Y\n");
    }
    return 0;
}
```
## Output
```
User Input:
Enter two integers (x and y): 5 5
Program Output:
X is equal to Y
```

## Result
Program to read values of x and y and print whether x == y or x != y using an if-else statement was implemented and executed successfully.
