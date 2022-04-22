/*# C-code
program to make simple calculator using switch*/

#include<stdio.h>
int main()
{
 int a,b,sum,sub,multi,divi;
 int operator;
 printf("enter any two values\n");
 scanf("%d \n %d",&a,&b);
 printf(" enter 1 for addition\n enter 2 for substraction\n enter 3 for multipication\n enter 4 for division\n");
 scanf("%d",&operator);
 
  switch(operator)
  {
      case 1:
      sum=a+b;
      printf("%d",sum);
      break;
      case 2:
      sub=a-b;
      printf("%d",sub);
      break;
      case 3:
      multi=a*b;
      printf("%d",multi);
      break;
      case 4:
      divi=a/b;
      printf("%d",divi);
      break;
      default:
      printf("enter valid operator");
      
  }
  return 0;
} 
 
