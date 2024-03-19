#include <stdio.h>
int main()
{
    int x,y,result;
    char op;
    printf("Enter 1st value,operator and 2nd value\n ");
    scanf("%d %c %d",&x,&op,xy);
    switch(op);
    {
    case'+';
     result=x+y;
     break;
     case'-';
     result=x-y;
     break;
    case'+';
     result+x+y;
     break;
    case'/';
     result+x/y;
     break;
    default;
     result+x%y;
    }
    printf("%d %c %d=%d\n",x,op,y,results);
   return 0;
    }
