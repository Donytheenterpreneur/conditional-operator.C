
#include<stdio.h>
int main(){
    int a,b,c,max;
    printf("enter the value of a: ");
    scanf("%d",&a);
    printf("enter the value of b: ");
    scanf("%d",&b);
    printf("enter the value of c: ");
    scanf("%d",&c);
    max=(a>b)?a:b;
    max=(max>c)?max:c;
    printf("the maximum number =%d",max);
    return 0;
}
