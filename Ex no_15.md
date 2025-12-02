# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
Start.

Declare a array size value of type int.

Prompt the user to enter a value.

Read the value using scanf.

Initialize array elements.

Replace all even elements to E

End.
## Program:
```
#include <stdio.h>

int main()
{
    int n, i;
    scanf("%d", &n);

    int a[n];
    for (i = 0; i < n; i++)
        scanf("%d", &a[i]);

    for (i = 0; i < n; i++)
    {
        if (a[i] % 2 == 0)
            printf("E ");
        else
            printf("%d ", a[i]);
    }

    return 0;
}
```

## Output:

<img width="450" height="154" alt="image" src="https://github.com/user-attachments/assets/528ef6c8-29df-43fa-bfc4-c4921666f75b" />



## Result:
Thus the program was executed and the output was verified successfully.
