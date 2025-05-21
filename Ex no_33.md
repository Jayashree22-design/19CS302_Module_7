# EX 33 C program to read a file name from user and create that file using fopen().
## DATE:
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
1. Start the program and declare a character array to store the file name.
2. Read the file name from the user using scanf().
3. Use fopen() in write mode ("w") to create the file.
4. Check if the file is created successfully and display a message.
5. Close the file using fclose().

## Program:
```
/*
C program to read a file name from user and create that file using fopen().
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include <stdio.h>

int main()
{
    char filename[100];
    FILE *fp;

    printf("Enter the file name to create: ");
    scanf("%s", filename);

    fp = fopen(filename, "w");

    if(fp == NULL)
    {
        printf("File creation failed.\n");
        return 1;
    }

    printf("File '%s' created successfully.\n", filename);
    fclose(fp);

    return 0;
}
*/
```

## Output:
![442491475-b7024c94-78a4-4ab5-9d95-d750cdf03682](https://github.com/user-attachments/assets/b8c5757a-95cb-4a6e-960d-cbf0cedd28b7)

## Result:
Thus the program was executed and the output was verified successfully.
