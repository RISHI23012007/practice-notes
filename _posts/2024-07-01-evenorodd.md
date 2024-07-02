---
title: "Even or Odd"
date: 2024-07-01
categories:
---

# Even or odd
## To check a number if it is even or odd:
### Below code is used 
```c
#include<cs50.h>
#include<stdio.h>

int main(void)
{
   int n;
   n = get_int("Enter your number : ");

   if (n %2 ==0)
   {
     printf("The given number %i is even\n",n);

   }
   else
   {
    printf("The given number %i is odd ",n);
   }

}

```
## This way we can check and print odd or even

# OUTPUT :

Enter your number : 4

The given number 4 is even.




