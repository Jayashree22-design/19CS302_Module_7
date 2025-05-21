# EX 32 C program to display Hardware details such as price, product name and price using structure.
## DATE:11/05/2025
## AIM:
To write a C program to display Hardware details such as price, product name and price using structure.

## Algorithm
1. Start the program and define a structure with fields for product name and price.
2. Declare a structure variable to store hardware details.
3. Read the product name and price from the user.
4. Store the values in the structure.
5. Display the hardware details using the structure fields.

## Program:
```
/*
C program to display Hardware details such as price, product name and price using structure.
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include <stdio.h>

struct Hardware
{
    char productName[100];
    float price;
};

int main()
{
    struct Hardware h;

    printf("Enter the product name: ");
    scanf("%s", h.productName);

    printf("Enter the price: ");
    scanf("%f", &h.price);

    printf("Hardware Details:\n");
    printf("Product Name: %s\n", h.productName);
    printf("Price: %.2f\n", h.price);

    return 0;
}
*/
```

## Output:

![442490648-75750861-d019-4c6b-9ebd-e64097004b6d](https://github.com/user-attachments/assets/252bceed-0d91-45a9-b6c9-5e3808e547d0)


## Result:
Thus the program was executed and the output was verified successfully.
