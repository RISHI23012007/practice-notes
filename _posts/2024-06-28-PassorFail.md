---
title: "Pass Or Fail"
date: 2024-06-28
categories:
---
# **Pass Or Fail**
## The  code to check pass or fail using **conditional operators**
## They are *if,else,define*
```c
#include<cs50.h>
#include<stdio.h>
#include"tamil.h"

int main(void)
{
   int marks ;
   printf("To check if student has passed or failed?\n");
   marks = get_int("How many marks did you get?");
   Atu_naṭantāl ( marks >=40)
  { printf("Nee pass aayi,santoshama iru da\n");
  }
  Illai_eṉṟāl
  {
    printf("Nee fail ayi da,prepare aayi va\n");
  }
```
# OUTPUT:
To check if student has passed or failed?

How many marks did you get?25

Nee fail ayi da,prepare aayi va.