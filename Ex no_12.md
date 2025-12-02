# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.

## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
Start

Declare the variable i.

Read the value given using scanf.

Check whether the given number is prime or not using if-else statement condition.

If true,print ("%d is a prime number.",i).

If false, print ("%d is not a prime number.",i).

End.

## Program:
```
#include <stdio.h>

void checkPrime(int n)
{
    int i, flag = 1;
    if (n <= 1)
        flag = 0;

    for (i = 2; i <= n / 2; i++)
    {
        if (n % i == 0)
        {
            flag = 0;
            break;
        }
    }

    if (flag == 1)
        printf("%d is a prime number.", n);
    else
        printf("%d is not a prime number.", n);
}

int main()
{
    int n;
    scanf("%d", &n);
    checkPrime(n);
    return 0;
}
```

## Output:

<img width="394" height="143" alt="image" src="https://github.com/user-attachments/assets/1eff49c9-d964-42e3-b19e-69eac99cb70b" />




## Result:
Thus the program was executed and the output was verified successfully.
