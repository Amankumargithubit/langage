#include<stdio.h>
#include<conio.h>
main()
{
int n,c,r,arm=0;
printf("enter any number");
scanf("%d",&n);
c=n;
while(n>0)
{
r=n%10;
arm=r*r*r+arm;
n=n%10;
}
if(c==arm)
printf("Armstrong number");
else
 printf("not  a arm strong number");
 }
  }
