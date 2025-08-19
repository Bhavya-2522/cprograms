## 1.write a program to count sum of elements in an array.
```c
#include <stdio.h>
int main()
{
    int a[100],i,n,sum=0;
    printf("no.of elements are:");
    scanf("%d",&n);
    printf("the elements are:\n");
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    printf("the elements in an array:\n");
    for(i=0;i<n;i++)
    {
        printf("%d ",a[i]);
    }
    printf("\nsum of elements in an array are:");
    for(i=0;i<n;i++)
    {
        sum=sum+a[i];
    }
    printf("%d\n",sum);
}
```
## 2. Write a program in C to store elements in an array and print them.
```c
#include <stdio.h>
int main()
{
    int a[100],i,n;
    printf("no.of elements are: ");
    scanf("%d",&n);
    printf("the elements are: \n");
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    printf("the elements to be stored:\n");
    for(i=0;i<n;i++)
    {
        printf("%d ",a[i]);
    }
}
```

