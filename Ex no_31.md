# EX 31 C program to find the smallest among three numbers using Structure.
## DATE:08/05/2025
## AIM:To write a C program to find the smallest among three numbers using Structure.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a program to find the smallest among three numbers using structure. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.
   
## Program:
```
#include<stdio.h> 
struct num 
{ 
int a,b,c; 
}; 
int main() 
{ 
struct num n; 
scanf("%d%d%d",&n.a,&n.b,&n.c); 
if(n.a<n.b&&n.a<n.c) 
{ 
printf("%d",n.a); 
} 
else if(n.b<n.a&&n.b<n.c) 
{ 
printf("%d",n.b); 
} 
else 
{printf("%d",n.c);}
} 
/*
C program to find the smallest among three numbers using Structure.
Developed by: 
RegisterNumber:  
*/
```

## Output:
-28  -30  30
-30


## Result:
Thus the program was executed and the output was verified successfully.
