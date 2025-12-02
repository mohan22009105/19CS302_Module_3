# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.

## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
Start.

Declare a integer variable

Define a function named dectobin.

Return the integer.

Read the value using scanf.

Convert decimal to binary value.

Print the dectobin

End.

## Program:
```
#include <stdio.h>

int convert(int n)
{
    int bin = 0, base = 1;
    while (n > 0)
    {
        int r = n % 2;
        bin = bin + r * base;
        base *= 10;
        n /= 2;
    }
    return bin;
}

int main()
{
    int n;
    scanf("%d", &n);
    int binary = convert(n);
    printf("%d in decimal = %d in binary", n, binary);
    return 0;
}
```

## Output:

<img width="731" height="230" alt="image" src="https://github.com/user-attachments/assets/f842f0e2-10a0-4ad5-bbc9-85b381732509" />




## Result:
Thus the program was executed and the output was verified successfully.
