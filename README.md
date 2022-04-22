/*# C-code
program to make simple calculator using switch*/

#include<stdio.h>
int main();
{
 int a,b,sum,sub,multi,divi;
 char operator;
 scanf("%c",&operator);
 scanf("%d %d",&a,&b);
  switch(operator)
  {
      case '+':
      sum=a+b;
      cout<<sum;
      break;
      case '-':
      sub=a-b;
      cout<<sub;
      break;
      case '*':
      multi=a*b;
      cout<<multi;
      break;
      case '/':
      divi=a/b;
      cout<<divi;
      break;
      default:
      cout<<"enter valid operator";
      
  }
  return 0;
  } 
 
 
