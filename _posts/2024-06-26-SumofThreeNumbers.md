---
title: "Sum of three numbers"
date: 2024-06-26
categories:
---


# Sum of **Three numbers**
## The related code for adding "three numbers" is shown below:
```C

#include<cs50.h>
#include<stdio.h>

int main(void)

{
    int num1 ;
    int num2 ;
    int num3 ;
    int sum ;
    printf("To add three numbers.\n");
    num1 =get_int ("Enter First number: ");
    num2 =get_int("Enter Second number: ");
    num3=get_int("Enter Third number: ");
    sum=num1 + num2 + num3;
    printf("The sum of %i and %i and %i is %i",num1,num2,num3,sum);

}
```

### By this way we can add three numbers
#### Task for 26-06-2024