
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
#include <stdio.h>  
int main()  
{  
    int age;   
    printf("Enter your age?");   
    scanf("%d",&age);  
    if(age>=18)  
    {  
        printf(" eligible for  vote");   
    }  
    else   
    {  
        printf("not eligible for vote");   
    }  
}  