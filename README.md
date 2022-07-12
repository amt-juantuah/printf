### C - printf

printf is the C language function to do formatted printing. The same function is also available in PERL. This project designs and implements how printf works.

## How It Works

This requires the gcc compiler. Now consider the main function below. It include the main.h header file

```
#include "main.h"

int main(void)
{
    _printf('it works!!!');

    return (0);
}
```

Now compile all `.c` files in this repository and name it as test or any name you prefer.

```
$ gcc *.c -o test
```

Now output the results by running the test file

```
$ ./test
```
Output will be >>
```
it works!!!
```

## Description

* The prototypes of all your functions should be included in your header file called main.h
* Use the test/main.c file to test the functions
* No more than 5 functions per file
* To be compiled using the gcc compiler as `gcc -Wall -Wextra -Werror -pedantic -std=gnu89 -Wno-format *.c`
