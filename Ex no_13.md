# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.

## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
Start.

Define a variables i,j,n,a.

Write program to find n x n matrix.

Read the value using scanf.

Ask the user to make an input

Print out the answer.

End.

## Program:
```
#include <stdio.h>

int main()
{
    int n, i, j;
    scanf("%d", &n);

    int a[n][n];

    for (i = 0; i < n; i++)
        for (j = 0; j < n; j++)
            scanf("%d", &a[i][j]);

    for (i = 0; i < n; i++)
        for (j = 0; j < n; j++)
            if (a[i][j] % 2 != 0)
                printf("a[%d][%d] is %d\n", i, j, a[i][j]);

    return 0;
}
```

## Output:

<img width="432" height="299" alt="image" src="https://github.com/user-attachments/assets/2a36fcf3-fedc-4a5d-b0e6-313c831c3589" />




## Result:
Thus the program was executed and the output was verified successfully.
