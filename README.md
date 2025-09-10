# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n;

    printf("Enter how many random numbers to generate: ");
    scanf("%d", &n);

    srand(time(0)); // Seed the random number generator

    printf("Generated Random Numbers:\n");
    for (int i = 0; i < n; i++) {
        printf("%d ", rand());
    }

    printf("\n");
    return 0;
}
```
# OUTPUT:
<img width="1705" height="550" alt="image" src="https://github.com/user-attachments/assets/93f659b5-9fdc-4c70-84dc-b90b86e43f5b" />

# RESULT:
Thus the code is successfully executed
