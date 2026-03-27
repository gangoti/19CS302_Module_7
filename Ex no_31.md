# EX 31 C program to find the smallest among three numbers using Structure.
## DATE:
## AIM:
To write a C program to find the smallest among three numbers using Structure.

## Algorithm
Start. Define a variables a,b,c. Write program to find the smallest among the three numbers. Read the value using scanf. Ask the user to make an input. Print out the answer. End

## Program:
```
#include<stdio.h> 
int main()
{
int a,b,c; 
scanf("%d%d%d",&a,&b,&c); 
if(a<b && a<c)
{
printf("%d is the smallest number.",a);
}
else if(b<a && b<c)
{
printf("%d is the smallest number.",b);
}
else
{
printf("%d is the smallest number.",c);
}
}
*/
```

## Output:
<img width="1037" height="225" alt="image" src="https://github.com/user-attachments/assets/874348a6-c71d-4f93-9d02-addf6b068302" />

## Result:
Thus the program was executed and the output was verified successfully.
