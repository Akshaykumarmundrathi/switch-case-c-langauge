#include<stdio.h>
main()
{
int x;
printf("Enter /'0/' or /'1 /' number\n");
scanf("%d",&x);
switch(x)
{
case 0:printf("you just entered 0");break;
case 1:printf("you just entered 1");break;
default:printf("invalid input");break;
}
}
