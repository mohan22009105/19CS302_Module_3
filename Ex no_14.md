# EX 14 C program to delete first element in an array.

## AIM:
To write a C program to delete first element in an array.

## Algorithm
Start.

Define a variables i,j,a.

Read the value using scanf.

Ask the user to make an input

Print out the answer

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

    for (i = 1; i < n; i++)
        printf("%d ", a[i]);

    return 0;
}

```

## Output:

<img width="358" height="103" alt="image" src="https://github.com/user-attachments/assets/1d34c192-8170-4531-89c8-d7b84706404d" />



## Result:
Thus the program was executed and the output was verified successfully.
