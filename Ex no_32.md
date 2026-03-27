# EX 32 C program to display Hardware details such as price, product name and price using structure.
## DATE:
## AIM:
To write a C program to display Hardware details such as price, product name and price using structure.

## Algorithm
Start. Define a variables. Write a program to display hardware details such as price, product name and price using structure. Read the value using scanf. Ask the user to make an input. Print out the answer. End.
## Program:
```
#include<stdio.h> 
struct hardware
{
char qr[10];
char product[10]; 
int price;
}j[10];
int main()
{
int i; 
for(i=0;i<3;i++)
scanf("%s%s%d",j[i].qr,j[i].product,&j[i].price); 
for(i=0;i<3;i++)
printf("QRcode:%s\nproduct:%s\nprice :%d\n",j[i].qr,j[i].product,j[i].price);} 
*/
```
## Output:

<img width="1013" height="492" alt="image" src="https://github.com/user-attachments/assets/9908b5e5-6fb6-4c44-bf1a-1f285c1df3bc" />

## Result:
Thus the program was executed and the output was verified successfully.
