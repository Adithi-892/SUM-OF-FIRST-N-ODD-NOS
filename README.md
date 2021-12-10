# SUM-OF-FIRST-N-ODD-NOS
Find the sum of squares of first N odd natural numbers

#include <stdio.h>
int main() {
   int n ;
   int sum = 0;
   printf("Enter the nos : ");
   scanf("%d",&n);
   for (int i = 1; i <= n; i++)
      sum += (2*i - 1) * (2*i - 1);
   printf("The sum of square of first %d odd numbers is %d",n, sum);
   return 0;
}

=========================================================================================

OUTPUT

--------------------------------------------

Enter the nos : 4
The sum of square of first 4 odd numbers is 84
