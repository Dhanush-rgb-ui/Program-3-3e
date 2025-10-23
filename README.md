# module-3 SEB
## AIM:
To Write a C Program to Print the sum of an Array.

## For example:
<img width="292" height="73" alt="image" src="https://github.com/user-attachments/assets/4576bbf9-2a2a-40fa-a66a-831efde53948" />

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
<img width="495" height="72" alt="image" src="https://github.com/user-attachments/assets/971b56e1-3c5d-448e-8ebe-38a5309f14f9" />

