---
title: "Compilation Errors"
date: 2024-06-26
categories:
---

# C Compilation Errors
## Hello.c
### *_Here are the list of Errors_*

### **First Error**
#### Removing `;` at the end
```C
#include <stdio.h>

int main(void)
{
    printf("Welcome to my notes\n")
}
```

##### Compiler error using help50:
```bash
hello.c:7:36: error: expected ';' after expression
    printf("Welcome to my notes\n")
                                   ^
                                   ;
1 error generated.
make: *** [<builtin>: hello] Error
Are you missing a semicolon at the end of line 7 of hello.c
```



### **Second Error**
#### Removing parenthesis`()` at end of *_int main_*
```C
#include <cs50.h>
#include <stdio.h>

int main(void
{

    printf("Welcome to my notes\n");
}
```

##### Compiler using help50:
```bash
hello.c:5:1: error: expected ')'
{
^
hello.c:4:9: note: to match this '('
int main(void
        ^
fatal error: too many errors emitted, stopping now [-ferror-limit=]
2 errors generated.
make: *** [<builtin>: hello] Error
In particular, check to see if you are missing a closing parenthesis on line 4 of hello.c.

```


### **Third Error**
#### Removing Flower bracket `}` at the end
```C
#include <cs50.h>
#include <stdio.h>

int main(void
{

    printf("Welcome to my notes\n");

```

##### Compiler using help50:
```bash
hello.c:8:1: error: expected '}'
^
hello.c:5:1: note: to match this '{'
{
^
1 error generated.
make: *** [<builtin>: hello] Error
Make sure that all opening brace symbols { are matched with a closing brace }.
```

