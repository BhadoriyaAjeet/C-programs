#WAP to check whether a number is positive or negative or zero
#include<stdio.h>

int main() {
   int i=-63636;
   if(i>=1 && i<=100000)
   {
       printf("Number in Range");
   }
   else if(i>100000)
   {
       printf("Number out of bounds");
   }
   else if(i==0)
   {
	printf("Number is zero");
   }
   else
   {
       printf("Negative Number");
   }
}
