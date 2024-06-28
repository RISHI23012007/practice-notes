---
title: "Sum of Numbers"
date: 2024-06-27
categories:
---


# Sum of **Numbers**
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

##### Chatgpt has given me some suggestions to improve my code

Your code for adding three numbers and printing the sum looks good. However, here are a few improvements to make it more concise and properly formatted:

1. Remove unnecessary spaces before the semicolons.
2. Ensure consistent spacing around operators and parentheses for better readability.
3. Correct the format of the final `printf` statement for better readability.

Here's the improved version of your code:

```c
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int num1;
    int num2;
    int num3;
    int sum;

    printf("To add three numbers.\n");
    num1 = get_int("Enter First number: ");
    num2 = get_int("Enter Second number: ");
    num3 = get_int("Enter Third number: ");
    sum = num1 + num2 + num3;
    printf("The sum of %i, %i, and %i is %i\n", num1, num2, num3, sum);

    return 0;
}
```

Changes made:
1. Added spaces around assignment operators and after commas in `printf` for better readability.
2. Added a `return 0;` statement at the end of the `main` function for good practice.
3. Improved the final `printf` statement to be more readable by adding commas and proper spacing.
4. Added `\n` at the end of the `printf` statement to ensure the output ends with a new line.

### THE OUTPUT:

To add three numbers.

Enter First number: 2

Enter Second number: 3

Enter Third number: 4

The sum of 2 and 3 and 4 is 9

## The related code for adding **"Four numbers"**
```C
#include<cs50.h>
#include<stdio.h>

int main(void)

{
    int num1 ;
    int num2 ;
    int num3 ;
    int num4 ;
    int sum ;
    printf("To add four numbers.\n");
    num1 =get_int ("Enter First number: ");
    num2 =get_int("Enter Second number: ");
    num3=get_int("Enter Third number: ");
    num4=get_int("Enter fourth number: ");
    sum=num1 + num2 + num3 + num4;
    printf("The sum of %i and %i and %i and %i is %i",num1,num2,num3,num4,sum);

}
```
### By this way we can add four numbers
#### Chat Gpt has given me suggestion for improving my code

Your code for adding four numbers and printing the sum is almost correct. Here are a few improvements for better readability and consistency:

1. Remove unnecessary spaces before semicolons.
2. Ensure consistent spacing around operators and parentheses.
3. Correct the format of the final `printf` statement for better readability.
4. Add `\n` at the end of the `printf` statement for a new line.
5. Add `return 0;` at the end of the `main` function for good practice.

Here's the improved version of your code:

```c
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int num1;
    int num2;
    int num3;
    int num4;
    int sum;

    printf("To add four numbers.\n");
    num1 = get_int("Enter First number: ");
    num2 = get_int("Enter Second number: ");
    num3 = get_int("Enter Third number: ");
    num4 = get_int("Enter Fourth number: ");
    sum = num1 + num2 + num3 + num4;
    printf("The sum of %i, %i, %i, and %i is %i\n", num1, num2, num3, num4, sum);

    return 0;
}
```

Changes made:
1. Added spaces around assignment operators and after commas in `printf` for better readability.
2. Improved the final `printf` statement to be more readable by adding commas and proper spacing.
3. Added `\n` at the end of the `printf` statement to ensure the output ends with a new line.
4. Added `return 0;` statement at the end of the `main` function for good practice.

## The Output:

To add four numbers.

Enter First number: 5


Enter Second number: 7

Enter Third number: 8

Enter fourth number: 9

The sum of 5 and 7 and 8 and 9 is 29