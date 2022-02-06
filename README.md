# Greatest-number-
Write a program in C to find greatest among three integers.
#include <stdio.h>

int main()
{
   int a,b,c;
   printf("Enter a first number:\n");
   scanf("%d",&a);
   printf("Enter a second number:\n");
   scanf("%d",&b);
   printf("Enter a third number:\n");
   scanf("%d",&c);
   
   if(a>b && a>c){
       printf("%d is greatest\n",a);
   }
   else if(b>a && b>c){
       printf("%d is greatest\n",b);
   }
   else if(c>a && c>b){
       printf("%d is greatest\n",c);
   }
   else{
       printf("Equal");
   }
    return 0;
}

output-
Enter a first number:
50
Enter a second number:
80
Enter a third number:
70
80 is greatest
