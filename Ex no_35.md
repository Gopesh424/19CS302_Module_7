# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE:08/05/2025
## AIM:To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
1. Start
2. Declare a file pointer using FILE *p;.
3. Open a file named "Hospital.txt" in write mode using fopen().
4. Check if the file is successfully opened (optional in basic cases).
5. Display a message indicating that the file was created and opened successfully.
6. Close the file using fclose() and print a message confirming it was closed.
7. End
   

## Program:
```
#include <stdio.h>

int main() {
    FILE *p;
    p = fopen("Hospital.txt", "w");

    printf("Hospital.txt File Created Successfully\n");
    printf("Hospital.txt File Opened\n");

    fclose(p);
    printf("Hospital.txt File Closed\n");

    return 0;
}
/*
C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
Developed by: 
RegisterNumber:  
*/
```

## Output:
Hospital.txt File Created Successfully
Hospital.txt File Opened
Hospital.txt File Closed


## Result:
Thus the program was executed and the output was verified successfully.
