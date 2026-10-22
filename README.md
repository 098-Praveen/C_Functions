STAGE 1:
Definition:
A function is a block of code that performs particular code

#include<stdio.h>
int add(int a,int b)
{
  int sum=s+b;
  return sum;
}
int main()
{
  int result;
  result=add(10,29);
  printf("%d",result);
  return 0;
  }

  here int is return type of function 
  sum is function name 
  int a,int b are parameters or arguments
  add() is function invocation 
  add(int a,int b) is function definition which executes when function is invoked
  return values is 39

USAGE OF FUNCTIONS:
1.code reusability--- you can call the same function many times
2.modularity---you can divide the large prgm into smaller tasks; like sum and mul and like that different func's in one

STAGE 2:
TYPES OF FUNCTIONS
  1.NO ARGUMENTS AND NO RETURN VALUES
  2.ARGUMENTS WITHOUT RETURN VALUE
  3.NO ARGUMENTS WITH RETURN VALUE
  4.FUNCTION WITH ARGUMENTS AND WITH RETURN VALUE

1.NO ARGUMENTS AND NO RETURN VALUE:

#include<stdio.h>
void greet(void)
{
  printf("hello");
}
int main()
{
  greet();
  return 0;
}

first void in function definition is tells us that it returns nothing and second void tells that takes no arguments
greet is function call it executes the definition sand prints hello and returns to main function 

2.ARGUMENTS BUT NO RETURN VALUES:

#include<stdio.h>
void multiply(int a,int b)
{
    int result=a*b;
    printf("%d",result);
}
int main()
{
    multiply(4,5);
    return 0;
}

1.return type is void 
2 parameters it accepts
3.a and b receive 2 values
4.value of the result is 20
5.multiply returns nothing but prints 20

3.NO ARGUMENTS BUT A RETURN VALUE
int getnumber(void)
{
   return 100;
}
#include<stdio.h>
int main()
{
    int x=getnumber();
    printf("%d",x);
    return 0;
}

here getnumber accepts no arguments 
but return int value;

4.ARGUMENTS AND RETURN VALUES

int sum(int a,int b)
{
    int c;
    return c=a+b;
}
#include<stdio.h>
int main()
{
    sum(10,20);
    printf("%d",sum);
    return 0;
}

PRACTICE QUESTION
#include<stdio.h>
int calculate(int x,int y)
{
    int result=x*y;
    return result+5;
}
int main(void)
{
   int a=calculate(3,4);
   printf("%d",a);
   return 0;
}

1.what type of function is calculate is among 4? 4th.
2.what values do x and y receive ? 3,4.
3.what is the value of the result? 12
4.what value does the function return ? 17
5.what is the final output? 17.



    



