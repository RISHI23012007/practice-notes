---
title: "Positive or Negative"
date: 2024-07-01
categories:
---
# To check if a given number is *positive* or **negative*
```c
#include<cs50.h>
#include<stdio.h>
int main (void)
{
    int n1;
    printf("To check positive or negative\n");
    n1 = get_int ("Enter the number : ");
    if (n1<0)
{
    printf("The entered number %i is negative \n",n1);
    }
    else
    printf("The entered number %i is positive \n",n1);
}

```
## By this we way we can check

# OUTPUT :

To check positive or negative

Enter the number : -10

The entered number -10 is negative .