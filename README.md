# Simple-Calculator
#include <stdio.h>
#include <math.h>
int main()
{
 float a,b,c,d,e,f,g,h;
 int i;
 printf("Enter 1 for addition\n\n");
 printf("Enter 2 for subtraction\n\n");
 printf("Enter 3 for multiplication\n\n");
 printf("Enter 4 for division\n\n");
 printf("Enter 5 for division's remainder\n\n");
 printf("Enter 6 for 2nd power of 1st\n\n");
 scanf("%d",&i);
 if(i==1)
 {
     
     printf("Enter the value of A and B");
     scanf("%f %f",&a,&b);
     printf("%f",a+b);
 }
 else if(i==2)
 {
     d=a-b;
     printf("Enter the value of A and B");
     scanf("%f %f",&a,&b);
     printf("%f",a-b);
 }
 else if(i==3)
 {
     e=a*b;
     printf("Enter the value of A and B");
     scanf("%f %f",&a,&b);
     printf("%f",a*b);
 }
 else if(i==4)
 {
     f=a/b;
     printf("Enter the value of A and B");
     scanf("%f %f",&a,&b);
     printf("%f",a/b);
 }
 else if(i==5)
 {
     int g,h;
     printf("Enter the value of A and B");
     scanf("%d %d",&g,&h);
     printf("%d",g%h);
 }
    
 else if(i==6)
 {
     
     printf("Enter the value of A and B");
     scanf("%f %f",&a,&b);
     printf("%f",pow(a,b));
 }
 else
 printf("Enter a number between 1 to 6 .....");
 

    return 0;
}

