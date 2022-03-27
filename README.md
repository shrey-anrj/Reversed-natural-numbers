#include<stdio.h>
void main()
{
    int x,n;
    printf("Enter Number of natural no to be dispalayed\n");
    scanf("%d",&n);
    printf("N natural numbers in reversed order are:\n");
    for(x=n;x>=1;x--)
    {
        printf("%d\n",x);
    }
}
