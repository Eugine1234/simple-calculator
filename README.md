# simple-calculator
simplecalc
* C program to perfrom all arithmetic o
*/

#include  <stdio.h>

int main()
{
    int num1, num2;
    int sum, sub, mult, mod;
    float div;
    
    /*
     * input two numbers from user
     */
     printf("Enter any two numers: ");
     scanf("%d%d", &num1, &num2);
     
     /*
      * perform  all arithmetic operations
      */
      sum = num1 + num2;
      sub = num1 - num2;
      mult = num1 * num2;
      div =  (float) num1 / num2;
      mod = num1 % num2;
      
      /*
       * print result of all arithmetic op
       */
       printf("SUM = %d\n", sum );
       printf("DIFFERENCE = %d\n", sub);
       printf("PRODUCT = %d\n", mult);
       printf("QUOTIENT = %f\n", div);
       printf("MODULUS = %d\n", mod);
       
       return 0 ;
       }
   
