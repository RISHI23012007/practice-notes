---
title: "Product of Two Numbers"
date: 2024-06-28
categories:
---

# **Product Of Two Numbers**
## The related code is about product of two numbers:
```c
#include<cs50.h>
#include<stdio.h>

int main(void)
{
    int num1;
    int num2;
    int product;
    printf("To find out product of two numbers\n");
    num1 = get_int("Enter First number : ");
    num2 = get_int("Enter Second number : ");
    product = num1*num2;
    printf("The product of  %i and %i is %i",num1,num2,product);
}
```
## By this way we can calculate product of two numbers
# Output:
### "To find out product of two numbers"

Enter First number : 6

Enter Second number : 18

The product of  6 and 18 is 108