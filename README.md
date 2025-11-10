#include<stdio.h>
int main()
{
int a,b,c;
printf("Enter the values of a,b,c");
scanf("%d%d%d",&a,&b,&c);
if(a>b&&b>c) {
printf("a is greatest");
}
else if(b>c&&c>a) {
printf("b is greatest");
}
else {
printf("c is greatest");
}
return 0;
}
