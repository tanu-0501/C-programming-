
#include <stdio.h>
int main()
{
    int a = 1, b = 5,c=5;
    if (a > b && a > c)
        printf("%d", a);
    else if (b > a && b > c)
        printf("%d", b);
    else
        printf("%d", c);

    return 0;
}
#include<stdio.h>    
int main()
{    
   int number;    
   printf("Enter a number:");    
   scanf("%d",&number);    
   if(number%2==0)
   {    
      printf("%d is even number",number);    
    }    
return 0;
}
