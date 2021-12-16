# c-prog-2
alternative method to find length

#include<stdio.h>
void main()
{
    char St[100];
    int i=0;
    printf("Enter the String\n");
    scanf("%s",St);
    while(St[i]!=0)
    {
        i=i+1;
    }
    
    printf("Length of the string is :- %d",i);
}
