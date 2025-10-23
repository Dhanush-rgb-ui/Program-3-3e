# module-3 SEB
## AIM:
To Write a C Program to Print the sum of an Array.

## For example:

## Program:
```c
#include<stdio.h>
int main(){
    int n=7,i,sum=0;
    int a[n];
    for(i=0;i<n;i++){
        scanf("%d",&a[i]);
    }
    for(i=0;i<n;i++){
        sum+=a[i];
    }
    printf("Total Sum: %d",sum);
    return 0;
}
```
## Result:

