
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

