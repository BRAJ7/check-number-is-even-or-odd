# check-number-is-even-or-odd


/* Program to print whether the given number is even or 

odd*/
#include<stdio.h>
main()
{
int x;
clrscr();
printf("Enter a number: \n");
scanf("%d",&x);
if (x%2==0)//Comparision operator ==
printf("\nGiven number is even:\n");
else
printf("\nGiven number is odd:");
return 0;
}
