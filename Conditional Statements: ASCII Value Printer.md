# Conditional Statements: ASCII Value Printer in C

## Aim
To write a C program that prints the ASCII value of the characters 'a', 'z', 'A', or 'Z' using a switch statement. If any other character is entered, the program prompts the user to enter a valid alphabet.

## Algorithm
1.Declare a variable ch of type char.

2.Read a character from the user.

3. Use a switch statement to check if ch is 'a', 'A', 'z', or 'Z'.

4. If ch matches any of these cases, print its ASCII value using the printf function with %d format specifier.

## Program
```
#include <stdio.h>

int main() {
    char ch;
    printf("Enter a character (a, z, A, or Z): ");
    scanf(" %c", &ch);  e
    switch (ch) {
        case 'a':
        case 'z':
        case 'A':
        case 'Z':
            printf("ASCII value of '%c' is %d\n", ch, ch);
            break;
        default:
            printf("Invalid input. Please enter a valid alphabet: a, z, A, or Z.\n");
    }
    return 0;
}
```


## Output
```
User Input:
Enter a character (a, z, A, or Z): a
Program Output:
ASCII value of 'a' is 97
```

## Result
programme was implemented and executed
