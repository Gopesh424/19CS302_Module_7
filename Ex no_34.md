# EX 34 C program to read a file name from user and create that file and insert student roll numbers in to that file.
## DATE:08/05/2025
## AIM:To write a C program to read a file name from user and create that file and insert student roll numbers in to that file.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a program to read a file name from user and create that file and insert student 
roll numbers in to that file. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.    

## Program:
```
#include <stdio.h> 
int main() 
{ 
FILE *p; 
char name[100]; 
int num; 
int id; 
char text[100]; 
float m; 
scanf("%s",name); 
scanf("%d",&num); 
p=fopen("name","w"); 
printf("%s Opened\n",name); 
{ 
scanf("%d %s %f",&id,text,&m); 
fprintf(p,"%d %s %f",id,text,m); 
} 
fclose(p); 
printf("Data added Successfully"); 
 
}
/*
C program to read a file name from user and create that file and insert student roll numbers in to that file.
Developed by: 
RegisterNumber:  
*/
```

## Output:
Sample.txt  2   90   80
Sample.txt Opened 
Data added Successfully


## Result:
Thus the program was executed and the output was verified successfully.
