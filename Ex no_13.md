# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1.Start the program and declare a 2D array with rows and columns.

2.Read the number of rows and columns from the user.

3.Input all elements of the 2D array using nested loops.

4.Traverse the array and check if an element is odd using modulus operator.

5.Print only the odd elements.

## Program:
```
/*
Program to read the elements and print only the odd elements in the 2D array.
Developed by: Santhosh kumar B
RegisterNumber: 212223060249 
*/
#include <stdio.h>

int main()
{
    int arr[10][10], rows, cols, i, j;

    printf("Enter number of rows: ");
    scanf("%d", &rows);

    printf("Enter number of columns: ");
    scanf("%d", &cols);

    printf("Enter elements of the array:\n");
    for(i = 0; i < rows; i++)
    {
        for(j = 0; j < cols; j++)
        {
            scanf("%d", &arr[i][j]);
        }
    }

    printf("Odd elements in the array are:\n");
    for(i = 0; i < rows; i++)
    {
        for(j = 0; j < cols; j++)
        {
            if(arr[i][j] % 2 != 0)
            {
                printf("%d ", arr[i][j]);
            }
        }
    }

    printf("\n");
    return 0;
}


```

## Output:
<img width="372" height="360" alt="image" src="https://github.com/user-attachments/assets/3eadca03-44a2-4843-af52-c85b5c55c90a" />




## Result:
Thus the program was executed and the output was verified successfully.
