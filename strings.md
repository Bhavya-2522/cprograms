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
## 2. Write a c program to reverse a string.
```
#include<stdio.h>
#include<string.h>
int main()
{
    char a[50],temp;
    printf("enter a string:");
    fgets(a,sizeof(a),stdin);
    a[strcspn(a,"\n")]='\0';
    int l=strlen(a);
    for(int i=0;i<l/2;i++)
    {
        temp=a[i];
        a[i]=a[l-1-i];
        a[l-1-i]=temp;
    }
    printf("reversed string=%s",a);
}
```
