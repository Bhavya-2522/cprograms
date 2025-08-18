## 1. Write a c program to count words in a string.
```
#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main()
{
    char str[100];
    printf("enter string:");
    fgets(str,sizeof(str),stdin);
    str[strcspn(str,"\n")]='\0';
    int i,word=0;
    for(i=0;str[i]!='\0';i++)
    {
        if(str[i]==' ')
        {
            word++;
        }
    }
    printf("words=%d\n",word+1);
}
```
